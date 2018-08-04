# OpenGraphic
Graphic Engine &amp; Game Engine open source list！

## Contents

>**Official**

  [Official](#official)  
  
>**Engine**

  [Engine](#engine) &nbsp;&nbsp; [EnginePlugin](#engine-plugin) &nbsp;&nbsp; [PBRRayTrace](#pbr-raytrace) &nbsp;&nbsp; [SoftRenderer](#soft-renderer) 
  
>**Rendering**

  [GI](#gi) &nbsp;&nbsp; [VolumeRendering](#volume-rendering) &nbsp;&nbsp; [PostProcessing](#postprocessing)        
  [RenderPath](#render-path) &nbsp;&nbsp;  [OIT](#oit)   
  [ShadeModel](#shade-model) &nbsp;&nbsp; [PhysicallyBasedRendering](#physically-based-rendering)   
  [Stylize](#stylize)
  
>**Emulation**

  [Nature](#nature) &nbsp;&nbsp; [Environment](#environment) &nbsp;&nbsp; [Human](#human)
  
>**Optimization**

  [Optimization](#optimization)
  
>**Util**

  [Util](#util) &nbsp;&nbsp; [SDF](#sdf) &nbsp;&nbsp; [Math](#math) &nbsp;&nbsp; [Image&Color](#imagecolor) &nbsp;&nbsp; [Noise](#noise)  &nbsp;&nbsp; [Mesh](#mesh) &nbsp;&nbsp; [Platform](#platform) &nbsp;&nbsp; [UI](#ui) &nbsp;&nbsp; [SceneManage](#scenemanage) &nbsp;&nbsp; [CG](#cg)
  
>**Tools**

  [Tools](#tools) 
  
>**Tutorial**

  [SDK&Tutorial](#sdktutorial) &nbsp;&nbsp; [Effect](#effect) 
  
>**Other**

  [Physics](#physics) &nbsp;&nbsp; [VR&AR](#vrar)   
  [Animation](#animation) &nbsp;&nbsp; [Particle](#particle)  
  
---

## Official
* Unity [Unity-Technologies](https://github.com/Unity-Technologies)  &nbsp;&nbsp; [unity3d-jp](https://github.com/unity3d-jp)
* AMD  [GPUOpen-LibrariesAndSDKs](https://github.com/GPUOpen-LibrariesAndSDKs)  &nbsp;&nbsp; [GPUOpen-Tools](https://github.com/GPUOpen-Tools)  &nbsp;&nbsp;  [GPUOpen-Effects](https://github.com/GPUOpen-Effects)
* NVIDIA 
* Intel [Intel GameTechDev](https://github.com/GameTechDev) https://software.intel.com/gamedev
* SideEfects [sideeffects](https://github.com/sideeffects) Hodini
* [id-Software](https://github.com/id-Software)
* [InteractiveComputerGraphics](https://github.com/InteractiveComputerGraphics)

## Engine
* [UnrealEngine](https://github.com/EpicGames/UnrealEngine)
* [CRYENGINE](https://github.com/CRYTEK/CRYENGINE)
* [Lumberyard](https://github.com/aws/lumberyard)
* [Klayag](https://github.com/gongminmin/KlayGE)
* [Urho3D](https://github.com/urho3d/Urho3D)
* [Falcor](https://github.com/NVIDIAGameWorks/Falcor) Real-Time Rendering Framework, NVIDIA
* [bsf](https://github.com/GameFoundry/bsf) Modern C++14 library for the development of real-time graphical applications https://www.bsframework.io
* [OpenSceneGraph](https://github.com/openscenegraph/OpenSceneGraph)
* [Ogre](https://github.com/ogrecave) ogre github mirror
* [WickedEngine](https://github.com/turanszkij/WickedEngine) with Voxel-based Global Illumination
* [xenko](https://github.com/SiliconStudio/xenko) -Enlighten's company
* [bgfx](https://github.com/bkaradzic/bgfx) -Orthodox C++ coding style and like OpenGL APIs 
* [The-Forge](https://github.com/ConfettiFX/The-Forge) The Forge Cross-Platform Rendering Framework PC, macOS / iOS, Android, XBOX, PS4
* [oryol](https://github.com/floooh/oryol) - A small, portable and extensible C++ 3D coding framework,Orthodox C++ coding style and APIs
* [cesium](https://github.com/AnalyticalGraphicsInc/cesium) An open-source JavaScript library for world-class 3D globes and maps
* [filament](https://github.com/google/filament) Filament is a physically based rendering engine for Android, Windows, Linux and macOS
* [BRE12](https://github.com/nbertoa/BRE12) a rendering framework [Blog](https://nbertoa.wordpress.com/)

## Engine Plugin
* [armory](https://github.com/armory3d/armory)  -3D Game Engine for Blender
* [RenderPipeline](https://github.com/tobspr/RenderPipeline) -PBR and Deferred Rendering for the Panda3D game engine 
* [ray-mmd](https://github.com/ray-cast/ray-mmd) physically-based rendering at mikumikudance

## PBR RayTrace
* [embree](https://github.com/embree/embree)
* [RadeonRays RadeonProRender](https://github.com/GPUOpen-LibrariesAndSDKs)
* [appleseed](https://github.com/appleseedhq/appleseed)
* [LuxCoreRender](https://github.com/LuxCoreRender)
* [mitsuba](https://github.com/mitsuba-renderer/mitsuba)
* [ospray](https://github.com/ospray/ospray)
* [taichi](https://github.com/yuanming-hu/taichi)
* [tungsten](https://github.com/tunabrain/tungsten) High performance physically based renderer in C++11
* [nori](https://github.com/wjakob/nori)
* [nanort](https://github.com/lighttransport/nanort)  single header only modern ray tracing kernel.
* [SORT](https://github.com/JerryCao1985/SORT)  Simple Open-source Ray Tracer https://agraphicsguy.wordpress.com/

## Soft Renderer
* [openswr-mesa](https://github.com/OpenSWR/openswr-mesa) [OpenSWR](http://openswr.org/)
* [miaow](https://github.com/VerticalResearchGroup/miaow)
* [tinyrenderer](https://github.com/ssloy/tinyrenderer)
* [coco3d](http://coco3d.codeplex.com/)
* [muli3d](https://sourceforge.net/projects/muli3d/)
* [swiftshader](https://github.com/google/swiftshader) high-performance CPU-based implementation of the OpenGL ES and Direct3D 9 graphics APIs

## GI
### Collection
* [GITechDemo](https://github.com/iftodebogdan/GITechDemo)
* [DynamicRadianceVolume](https://github.com/Wumpf/DynamicRadianceVolume)
* [dirtchamber](https://github.com/thefranke/dirtchamber)
* [RTGI](https://github.com/jazzboysc/RTGI)
* [Cinder-Experiments](https://github.com/simongeilfus/Cinder-Experiments) A collection of experiments, samples and other bits of code.
* [CSharpRenderer](https://github.com/bartwronski/CSharpRenderer) C#/.NET DirectX11 based graphics framework for rapid visual effects and algorithms prototyping
* [IlluminationComparison](https://github.com/EKnapik/IlluminationComparison) A comparison of typical illumination methods. (SSAO, HBO, VXGI, and Ray Traced Global Illumination)
* [VCTRenderer](https://github.com/jose-villegas/VCTRenderer)
* [3D-Graphics-Engine](https://github.com/Gregjksmith/3D-Graphics-Engine) Capable of rendering online and offline global illumination using a number of different methods. Written in c++ with OpenGL/GLSL.  
#### SVO
* [SEGI](https://github.com/sonicether/SEGI)
* [Voxel_Cone_Tracing](https://github.com/kbladin/Voxel_Cone_Tracing)
* [Voxel-Cone-Tracing](https://github.com/Cigg/Voxel-Cone-Tracing)
* [VoxelConeTracing](https://github.com/domme/VoxelConeTracing)
* [VCTGI](https://github.com/rdinse/VCTGI)
* [Vulkan-VXGI-VR-FrameWork](https://github.com/byumjin/Vulkan-VXGI-VR-FrameWork)
* [HarshLight](https://github.com/MangoSister/HarshLight) Real-time global illumination based on voxel cone tracing
#### LPV
* [Light-Propagation-Volumes](https://github.com/djbozkosz/Light-Propagation-Volumes)
* [GI-LPV](https://github.com/innovation-cat/GI-LPV) Implement global illumination with OCaml, using light propagation volumes
#### Point Based GI
* [PBGI](https://github.com/XT95/PBGI) Point Based Global Illumination
#### PRT
* [precomputed-radiance-transfer](https://github.com/pramanc/precomputed-radiance-transfer)
* [SHTest](https://github.com/dwilliamson/SHTest)
* [SphericalHarmonicLighting](https://github.com/Lumak/Urho3D-1.4-SphericalHarmonicLighting)
#### Radiosity
#### Instant Radiosity
* [instant_radiosity](https://github.com/cache-tlb/instant_radiosity)
* [simple-instant-radiosity](https://github.com/githole/simple-instant-radiosity)
#### Ray tracing
#### Path tracing
* [simple-bidirectional-pathtracer](https://github.com/githole/simple-bidirectional-pathtracer)
* [edubpt](https://github.com/githole/edubpt)
#### Metropolis light transport
#### PhotonMapping
* [CPMFIGIOTVVD](https://github.com/ResearchDaniel/Correlated-Photon-Mapping-for-Interactive-Global-Illumination-of-Time-Varying-Volumetric-Data)
#### Ambient occlusion
* [NNAO](https://github.com/simeonradivoev/NNAO) Neural Network Ambien Occlusion
* [dssdo](https://github.com/kayru/dssdo) Deferred Screen Space Directional Occlusion http://kayru.org/articles/dssdo/
* [ASSAO](https://github.com/GameTechDev/ASSAO) Adaptive Screen Space Ambient Occlusion
* [ssgi](https://github.com/jdupuy/ssgi) Screen space global illumination demo: SSAO vs SSDO
#### Bent Normal
* [ssbn](https://github.com/KageKirin/ssbn) Screen Space Bent Normals
#### LightMap
* [lightmapper](https://github.com/ands/lightmapper)
* [seamoptimizer](https://github.com/ands/seamoptimizer)
* [BakingLab](https://github.com/TheRealMJP/BakingLab)
* [BocsLightmapper](https://github.com/sasa42/BocsLightmapper)
* [trianglepacker](https://github.com/ray-cast/trianglepacker) Triangle packer for light map
### GI Simulation
#### Diffuse inter-reflection
#### Caustic
* [SC_Tracer](https://github.com/ningfengh/SC_Tracer) photon mapping for global illumination and caustic
#### Reflection
* [kode80SSR](https://github.com/kode80/kode80SSR)
* [StochasticScreenSpaceReflection](https://github.com/cCharkes/StochasticScreenSpaceReflection)
* [Unity-Screen-Space-Reflection](https://github.com/MaxwellGengYF/Unity-Screen-Space-Reflection)
* [UnitySSR](https://github.com/cCharkes/UnitySSR)
* [synthese_image](https://github.com/theFrenchDutch/synthese_image) author's [blog](http://thomasdeliot.wixsite.com/blog/single-post/2018/04/26/Small-project-OpenGL-engine-and-PBR-deferred-pipeline-with-SSRSSAO)
* [Jin-Engine-2.1](https://github.com/byumjin/Jin-Engine-2.1)
#### Refraction
#### Shadow
* [Shadows](https://github.com/TheRealMJP/Shadows)
* [UnityPCSS](https://github.com/TheMasonX/UnityPCSS)
* [RayTracedShadows](https://github.com/kayru/RayTracedShadows)

## PostProcessing 
#### Collection
* [PostProcessing](https://github.com/Unity-Technologies/PostProcessing)
* [Reshade](https://github.com/crosire/reshade-shaders) An advanced, generic post-processing injector for games and video software. https://reshade.me
* [reshade-shaders](https://github.com/crosire/reshade-shaders) A collection of post-processing shaders written for ReShade.
* [Cat-PostProcessing](https://github.com/JoachimCoenen/Cat-PostProcessing)
* [Unity5Effects](https://github.com/i-saint/Unity5Effects)
* [UnityImageEffects](https://github.com/hiroakioishi/UnityImageEffects)
#### AA
* [MSAAFilter](https://github.com/TheRealMJP/MSAAFilter)
* [temporal](https://github.com/playdeadgames/temporal)
* [smaa](https://github.com/iryoku/smaa)
* [smaaDemo](https://github.com/turol/smaaDemo) Subpixel Morphological AntiAliasing OpenGL/Vulkan demo
* [SMAA](https://github.com/Chman/SMAA) SMAA in unity3D
* [SpecularAA](https://github.com/TheRealMJP/SpecularAA) A demo of various normal map filtering techniques for reducing specular aliasing
#### Bloom
* [HexBokehBlur](https://github.com/zigguratvertigo/HexBokehBlur)
* [hdreffects](https://github.com/karimnaaji/hdreffects)
#### Tone Mapping
* [tonemapper](https://github.com/tizian/tonemapper)
#### DOF
* [VVDoFDemo](http://graphics.cs.williams.edu/papers/DepthOfFieldGPUPro2013/VVDoFDemo.zip)
#### Lens
* [PhysicallyBasedLensFlare](https://github.com/greje656/PhysicallyBasedLensFlare)
* [LightLeaksUnity](https://github.com/danielzeller/LightLeaksUnity)
#### Other
* [UnityScreenSpaceBoolean](https://github.com/hecomi/UnityScreenSpaceBoolean)
* [OffScreenParticleRendering](https://github.com/slipster216/OffScreenParticleRendering)

## Human
#### Skin
* [pbrt-skin-bssrdf](https://github.com/damlaren/pbrt-skin-bssrdf) Implementation of Donner & Jensen's "A Spectral BSSRDF for Shading Human Skin" in PBRT
* [skinparam](https://github.com/patwonder/skinparam) Real-time skin renderer with adjustable skin parameters
* [CP_SSSSS](https://github.com/CustomPhase/CP_SSSSS) Naive screen-space subsurface scattering solution for Unity 5.
* [separable-sss](https://github.com/iryoku/separable-sss) iryoku's SSSSS
* [skin-shader-unity](https://github.com/leonardo-domingues/skin-shader-unity) GPU Gems 3 - Chapter 14 using the Unity engine
* [UnityCharacterRender_SeparableSubsurfaceScatter](https://github.com/haolange/UnityCharacterRender_SeparableSubsurfaceScatter)
* [SubsurfaceScattering](https://github.com/vcrom/SubsurfaceScattering) An implementation of a set screen space physically-based subsurface scattering algorithms

#### Eye
#### Hair
* [TressFX](https://github.com/GPUOpen-Effects/TressFX)
* [WetaHair](https://github.com/zhoub/WetaHair)
* [libWetHair](https://github.com/nepluno/libWetHair)
#### Colth
* [libwetcloth](https://github.com/nepluno/libwetcloth)
#### Silk
#### Fur
* [FurRendering](https://github.com/jose-villegas/FurRendering)
* [NeoFur](https://github.com/TsPersonalOrganization/neo-fur-for-unity)

## Nature
#### Water
* [VaOcean](https://github.com/ufna/VaOcean)
* [Ocean Community Next Gen](https://github.com/eliasts/Ocean_Community_Next_Gen) Next gen iteration of the unity community ocean shader
* [Ocean_mobile_with_boat_physic](https://github.com/laurentClave/Ocean_mobile_with_boat_physic) Ocean mobile with boat physic controller
* [OceanProject](https://github.com/UE4-OceanProject/OceanProject)
* [fft-ocean](https://github.com/jbouny/fft-ocean)
* [Unity-WaterBuoyancy](https://github.com/dbrizov/Unity-WaterBuoyancy)
* [crest-oceanrender](https://github.com/huwb/crest-oceanrender) Novel ocean rendering techniques (Unity3D)
* [Mistral-Water](https://github.com/AlphaMistral/Mistral-Water)
* [RealtimeWater](https://github.com/hpatjens/RealtimeWater) implemented based on "Fast Water Simulation for Games Using Height Fields".

* Jerry Tessendorf's paper "Simulating Ocean Water".  
[fftocean](https://github.com/deiss/fftocean)  [ocean-simulation](https://github.com/klantz81/ocean-simulation)  [Phillips-Ocean](https://github.com/Scrawk/Phillips-Ocean)
* Eric.Bruneton's paper "an improved version using an FFT method to synthesize the surface."
[Eric.Bruneton](http://evasion.inrialpes.fr/~Eric.Bruneton/)  [Brunetons-Ocean](https://github.com/Scrawk/Brunetons-Ocean)

#### Snow
* [SnowSimulation](https://github.com/hubi037/SnowSimulation)
* [SnowDeformation](https://github.com/vanish87/SnowDeformation)
* [UnrealSnow](https://github.com/bneukom/UnrealSnow)
* [Snowshader](https://github.com/RenV123/Snowshader)
* [snow](https://github.com/Azmisov/snow)
* [DeformationGPU](https://github.com/hsdk/DeformationGPU)
* [DeepSnowFootprint](https://github.com/ZGeng/DeepSnowFootprint)
* [unity-deformablesnow](https://github.com/thnewlands/unity-deformablesnow)
#### Sand
* [JourneySand](https://github.com/AtwoodDeng/JourneySand)
#### Grass
* [Grass.DirectX](https://github.com/mreinfurt/Grass.DirectX)
* [VulkanGrassRendering](https://github.com/moneimne/VulkanGrassRendering)
* [GooHairGrass](https://github.com/cabbibo/GooHairGrass)
* [Project6-Vulkan-Grass-Rendering](https://github.com/CIS565-Fall-2017/Project6-Vulkan-Grass-Rendering)
#### Tree
* [Vulkan-Forest-Rendering-Engine](https://github.com/Jiaww/Vulkan-Forest-Rendering-Engine)
#### Terrain
* [Terrain-Topology-Algorithms](https://github.com/Scrawk/Terrain-Topology-Algorithms)
#### Cloud
* [volsample](https://github.com/huwb/volsample)
* [kode80CloudsUnity3D](https://github.com/kode80/kode80CloudsUnity3D)
* [Raymarch-Clouds](https://github.com/Flafla2/Raymarch-Clouds)
* [clouds](https://github.com/greje656/clouds) Volumetric Clouds plugin for Stingray
* [Marshmallow](https://github.com/mccannd/Project-Marshmallow) Vulkan-based implementation of clouds from Decima Engine
* [Meteoros](https://github.com/Aman-Sachan-asach/Meteoros) Real-time Cloudscape Rendering in Vulkan based on the implementation of clouds in the Decima Engine.
#### Sky
* [SkyboxPanoramicShader](https://github.com/Unity-Technologies/SkyboxPanoramicShader)
#### Rain
* [RainDropEffect](https://github.com/EdoFrank/RainDropEffect)
* [LensRain](https://github.com/Kink3d/LensRain) A screen-space lens rain effect using Unity's V2 Post-processing framework.
* [RainFX](https://github.com/smkplus/RainFX)
#### Fire
* [fire](https://github.com/robertcupisz/fire)
#### Ice
#### Iridescent
* [Iridescence](https://github.com/Xerxes1138/Iridescence)
* [Iridescent Shader](https://www.patreon.com/posts/iridescent-18699278)

## Environment
#### VolumetricLight
* [VolumetricLights](https://github.com/SlightlyMad/VolumetricLights)
* [LightShafts](https://github.com/robertcupisz/LightShafts)
* [OutdoorLightScattering](https://github.com/GameTechDev/OutdoorLightScattering)
* [Scattering_Demos](https://github.com/yoyonel/Scattering_Demos)
* [Volumetric_Dynamic_Lights](https://github.com/yoyonel/Volumetric_Dynamic_Lights)
* [VolumetricLighting](https://github.com/Unity-Technologies/VolumetricLighting)
* [Aura](https://github.com/raphael-ernaelsten/Aura) Volumetric Lighting for Unity
* [Vapor](https://github.com/ArthurBrussee/Vapor) Volumetric Fog for Unity
#### Atmospheric
* [AtmosphericScattering](https://github.com/SlightlyMad/AtmosphericScattering)
* [AtmosphericScattering](https://github.com/yangzhengxing/AtmosphericScattering)
* [Scatterer](https://github.com/LGhassen/Scatterer)
* [precomputed_atmospheric_scattering](https://github.com/ebruneton/precomputed_atmospheric_scattering) Eric Bruneton, 2017
* [Brunetons-Improved-Atmospheric-Scattering](https://github.com/Scrawk/Brunetons-Improved-Atmospheric-Scattering) Eric Bruneton for Unity, 2017
* [glsl-atmosphere](https://github.com/wwwtyro/glsl-atmosphere)
#### Fog

## Render Path
* [ClusteredShadingAndroid](https://github.com/GameTechDev/ClusteredShadingAndroid)
* [VulkanClusteredShader](https://github.com/xnieamo/VulkanClusteredShader)
* [forward-clustered-shading](https://software.intel.com/en-us/articles/forward-clustered-shading)
* [light-indexed](https://github.com/wibbe/light-indexed)
* [lightindexed-deferredrender](https://github.com/dtrebilco/lightindexed-deferredrender)
* [Vulkan-Forward-Plus-Renderer](https://github.com/WindyDarian/Vulkan-Forward-Plus-Renderer)
* [cute-deferred-shading](https://github.com/Erkaman/cute-deferred-shading)
* [Makma](https://github.com/janhsimon/Makma) Makma is a deferred Vulkan renderer written in C++.
* [nTiled](https://github.com/BeardedPlatypus/nTiled)
* [DeferredTexturing](https://github.com/TheRealMJP/DeferredTexturing)

## Physically Based Rendering
#### Camera
* [Physical-Camera](https://github.com/Unity-Technologies/Physical-Camera)
* [pbc](https://github.com/kiwaiii/pbc)
* [Cat-Physically-Based-Camera](https://github.com/JoachimCoenen/Cat-Physically-Based-Camera)
#### File Format


## Shade Model
### BSDF
* [libbsdf](https://github.com/KimuraRyo/libbsdf) Library for BSDF, BRDF, and BTDF
##### BRDF
* [brdf](https://github.com/wdas/brdf)
* [brdfExplorer](https://github.com/sotnychenko/brdfExplorer)
* [BRDFExplorer](https://github.com/Corralx/BRDFExplorer)
* [Lux](https://github.com/larsbertram69)
* [Alloy](https://github.com/Josh015/Alloy)
* [AntonovSuit](https://github.com/cCharkes/AntonovSuit)
* [AnisotropicStandardShader](https://github.com/Kink3d/AnisotropicStandardShader)
##### SVBRDF
* [svbrdf-oculus](https://github.com/jknuuttila/svbrdf-oculus) materials from Two-Shot SVBRDF Capture for Stationary Materials by Aittala et al (2015).
##### BTDF
#### BSSRDF
* [Subsurface-Light-Transport-Raytracer](https://github.com/curranmax/Subsurface-Light-Transport-Raytracer)
* [SingleScatteringEditing](https://github.com/ykcadcg/SingleScatteringEditing)
* [pbrt-importance-sampling](https://github.com/dnx4015/pbrt-importance-sampling)
* [hitchhikersscatter](https://github.com/eugenedeon/hitchhikersscatter)
#### SSS
* [FastTranslucentShader](https://github.com/tatsy/FastTranslucentShader)
* [ScreenSpaceSubsurfaceScattering](https://github.com/Xerxes1138/ScreenSpaceSubsurfaceScattering)
#### IBL
* [IBLBaker](https://github.com/derkreature/IBLBaker)
* [cmftStudio](https://github.com/dariomanesku/cmftStudio)
* [Probulator](https://github.com/kayru/Probulator)
* [IBLGGX](https://github.com/tuccio/IBLGGX)
* [IntegrateDFG](https://github.com/knarkowicz/IntegrateDFG)
* [BRDFGenerator](https://github.com/HectorMF/BRDFGenerator)

## Stylize
#### NPR
* [NPR_Lab](https://github.com/candycat1992/NPR_Lab)
* [Wind-Waker-Shader](https://github.com/albertomelladoc/Wind-Waker-Shader) Cel Shading of two thresholds with a blur/gradient between them
* [ToonShading](https://github.com/Kink3d/ToonShading) A collection of "Toon" shaders for Unity based on a stepped PBR approximation.
* [kamakura-shaders](https://github.com/kayac/kamakura-shaders) NPR for Unity with a bunch of features and adjustable parameters in a user-friendly interface.
* [UnityNPR](https://github.com/GlitchEnzo/UnityNPR)
* [NPR](https://github.com/laundsallyn/NPR)
* [ChinesePaintingDemo](https://github.com/AtwoodDeng/ChinesePaintingDemo)
#### Low Poly
* [Lowpoly-Water-Unity](https://github.com/danielzeller/Lowpoly-Water-Unity)
#### Voxel
* [UE4VoxelTerrain](https://github.com/bw2012/UE4VoxelTerrain)
* [voxelizer](https://github.com/karimnaaji/voxelizer)
* [gpu-physics-unity](https://github.com/jknightdoeswork/gpu-physics-unity)
* [Field3D](https://github.com/imageworks/Field3D) A library for storing voxel data on disk and in memory.  

## Volume Rendering
#### RayMarch
* [ray-march](https://github.com/lightbits/ray-march)   
* [uRaymarching](https://github.com/hecomi/uRaymarching)   
* [unity-ray-marching](https://github.com/brianasu/unity-ray-marching)  
* [dli](https://github.com/dli)  
#### Point Clouds
* [PCL](http://www.pointclouds.org/)
#### Other
* [OpenVDB](https://github.com/dreamworksanimation/openvdb) Sparse volume data structure and tools
* [OpenVDBForUnity](https://github.com/karasusan/OpenVDBForUnity)

## Optimization
#### Frustum Culling
* [sseculling](https://github.com/nsf/sseculling)
#### Occlusion Culling
* [intel_occlusion_cull](https://github.com/rygorous/intel_occlusion_cull)
* [Image-Space-Occlusion-Culling-Engine](https://github.com/lebarba/Image-Space-Occlusion-Culling-Engine) Image Space Occlusion Culling Engine optimized to perform occlusion culling in CPU.
* [Janua](https://github.com/gigc/Janua) Open Source occlusion culling engine for 3D Scenes
* [OcclusionCulling](https://github.com/GameTechDev/OcclusionCulling) software (CPU) based approach to occllusion culling using multi-threading and SIMD instructions to improve performance.
* [rasterizer](https://github.com/rawrunprotected/rasterizer) faster in single-threaded AVX mode when rendering the full set of occluders (no minimum size).
* [IndirectOcclusionCulling](https://github.com/JJoosten/IndirectOcclusionCulling)
* [vigilant-system](https://github.com/nlguillemot/vigilant-system)
#### Hardware Occlusion Queries
#### Imposter
* [IMP](https://github.com/xraxra/IMP) billboard imposter baking for Unity
#### LOD
#### HLOD

## SDF
* [distancefield-unity](https://github.com/kvantetore/distancefield-unity)
* [Typogenic](https://github.com/Chman/Typogenic)
* [SDF](https://github.com/memononen/SDF)

## OIT
* [Order-Independent-Trasparency](https://github.com/PixelClear/Order-Independent-Trasparency)
* [OIT_Lab](https://github.com/candycat1992/OIT_Lab)
* [oitDemo](https://github.com/turol/oitDemo) Order Independent Transparency In OpenGL 4.x

## Math
* [Eigen](https://github.com/eigenteam/eigen-git-mirror)   **[Eigen](http://eigen.tuxfamily.org/) is a C++ template library for linear algebra: matrices, vectors, numerical solvers, and related algorithms**
* [MathGeoLib](https://github.com/juj/MathGeoLib)
* [CGAL](https://www.cgal.org/) geometric algorithms in the form of a C++ library.
* [GEOS](http://trac.osgeo.org/geos) Geometry Engine
* [MTL]() Matrix Template Library,  a linear algebra library for C++ programs.
* [sh-lib](https://github.com/andrewwillmott/sh-lib)
* [spherical-harmonics](https://github.com/google/spherical-harmonics)
* [Urho3D-1.4-SphericalHarmonicLighting](https://github.com/Lumak/Urho3D-1.4-SphericalHarmonicLighting)
* [DirectXMath](https://github.com/Microsoft/DirectXMath)
* [geomc](https://github.com/trbabb/geomc)
* [geometry3Sharp](https://github.com/gradientspace/geometry3Sharp)
* [ShaderFastLibs](https://github.com/michaldrobot/ShaderFastLibs) Shader Math lib

## Image&Color
* [bimg](https://github.com/bkaradzic/bimg)
* [OpenColorIO](https://github.com/imageworks/OpenColorIO)
* [OpenImageIO](https://github.com/OpenImageIO/oiio)
* [GLSL-Color-Spaces](https://github.com/tobspr/GLSL-Color-Spaces)
* [ImageSharp](https://github.com/SixLabors/ImageSharp) A cross-platform library for the processing of image files; written in C#
* [Dithering-Unity3d](https://github.com/mcraiha/Dithering-Unity3d)
* [glsl-colormap](https://github.com/kbinani/glsl-colormap)
* [nv_dds](https://github.com/paroj/nv_dds)
* [nvidia-texture-tools](https://github.com/castano/nvidia-texture-tools)
* [crunch](https://github.com/BinomialLLC/crunch)

## Noise
* [TileableVolumeNoise](https://github.com/sebh/TileableVolumeNoise)
* [FastNoise](https://github.com/Auburns/FastNoise)
* [Turbulence-Library](https://github.com/jesta88/Turbulence-Library)
* [GPU-Noise-Lib](https://github.com/BrianSharpe/GPU-Noise-Lib)
* [webgl-noise](https://github.com/ashima/webgl-noise)
* [VisualNoiseDesigner](https://github.com/x0r04rg/VisualNoiseDesigner)

## SceneManage
* [UnityOctree](https://github.com/Nition/UnityOctree)

## Mesh
*IO Subdivision Simplification Deform Destruction Optimization*  

* [assimp](https://github.com/assimp/assimp) A library to import and export various 3d-model-formats   
* [open3mod](https://github.com/acgessler/open3mod) Open 3D Model Viewer - A quick and powerful 3D model viewer  
* [DirectXMesh](https://github.com/Microsoft/DirectXMesh)    

* [OpenSubdiv](https://github.com/PixarAnimationStudios/OpenSubdiv) An Open-Source subdivision surface library. http://graphics.pixar.com/opensubdiv

* [Fast-Quadric-Mesh-Simplification](https://github.com/sp4cerat/Fast-Quadric-Mesh-Simplification) Mesh triangle reduction using quadrics
* [MeshDecimator](https://github.com/Whinarn/MeshDecimator), [UnityMeshSimplifier](https://github.com/Whinarn/UnityMeshSimplifier) Mesh simplification for Unity.  
* [SeamAwareDecimater](https://github.com/songrun/SeamAwareDecimater) Mesh simplification with UV's boundary preserved

* [MeshDGP](https://github.com/meshdgp/MeshDGP) a simple C# geometry processing library. demonstrates the dozens of keystone mesh processing algorithms
* [Deform](https://github.com/keenanwoodall/Deform) A framework for deforming meshes in the editor and at runtime in Unity.
 
* [meshoptimizer](https://github.com/zeux/meshoptimizer) Mesh optimization library that makes indexed meshes more GPU-friendly

* [meshlab](https://github.com/cnr-isti-vclab/meshlab) MeshLab is mostly based on the mesh processing library VCGlib
* [Mesh-processing-library](https://github.com/Microsoft/Mesh-processing-library) mesh processing techniques in computer graphics published at ACM SIGGRAPH in 1992–1998  
* [poly2tri](https://github.com/greenm01/poly2tri) Fast and Robust Simple Polygon Triangulation With/Without Holes   
* [libigl](https://github.com/libigl/libigl)
* [openmesh](https://www.openmesh.org/)
* [openflipper](https://www.openflipper.org/)
 
## Platform
* [glfw](https://github.com/glfw/glfw)
* [MoltenVK](https://github.com/KhronosGroup/MoltenVK) Vulkan graphics and compute API, that runs on Apple's Metal graphics framework

## UI
* [imgui](https://github.com/ocornut/imgui)
* [nanovg](https://github.com/memononen/nanovg)
* [nanogui](https://github.com/wjakob/nanogui)
* [nuklear](https://github.com/vurtun/nuklear)
* [AnttWeakbar](https://sourceforge.net/projects/anttweakbar/)
* [unity-vertex-effects](https://github.com/n-yoda/unity-vertex-effects) Beautiful Text Outline for Unity UI
* [PolyMesh](https://github.com/UnityPatterns/PolyMesh) Create 2D shapes in an instant with the PolyMesh editor! 

## Util
* [stb](https://github.com/nothings/stb)
* [yocto-gl](https://github.com/xelatihy/yocto-gl) Yocto/GL: Tiny C++ Libraries for Physically-based Graphics
* [debug-draw](https://github.com/glampert/debug-draw)

## Tools
#### UE4
* [u4pak](https://github.com/panzi/u4pak)
* [UModel](https://github.com/gildor2/UModel)
#### Unity
* [UnityStudio](https://github.com/Perfare/UnityStudio)
* [unitysizeexplorer](https://github.com/aschearer/unitysizeexplorer)
#### Shader
* [glsl-optimizer](https://github.com/aras-p/glsl-optimizer)
* [glslang](https://github.com/KhronosGroup/glslang)
* [HlslTools](https://github.com/tgjones/HlslTools) A Visual Studio extension that provides enhanced support for editing High Level Shading Language (HLSL) files
* [ShaderForge](https://github.com/FreyaHolmer/ShaderForge)
* [nshader](https://github.com/samizzo/nshader) Visual Studio 2013/2015/2017 syntax highlighting extension for shader languages
* [ShaderlabVS](https://github.com/wudixiaop/ShaderlabVS) ShaderlabVS is a Visual Studio Plugin for Unity Shaderlab programming
#### ShaderToy
* [shader-toy](https://github.com/stevensona/shader-toy)
* [ofxShadertoy](https://github.com/tiagosr/ofxShadertoy)
* [ShaderMan](https://github.com/smkplus/ShaderMan)
#### Visual Effects
* [gaffer](https://github.com/GafferHQ/gaffer)
* [cortex](https://github.com/ImageEngine/cortex) Libraries for visual effects software development
#### GPU Debug
* [renderdoc](https://github.com/baldurk/renderdoc)
* [CodeXL](https://github.com/GPUOpen-Tools) a comprehensive tool suite that enables developers to harness the benefits of CPUs, GPUs and APUs.
* [perfdoc](https://github.com/ARM-software/perfdoc) A cross-platform Vulkan layer which checks Vulkan applications for best practices on Arm Mali devices.
* [gapid](https://github.com/google/gapid) Graphics API Debugger by google
* [vogl](https://github.com/ValveSoftware/vogl) OpenGL capture / playback debugger by valve
* [apitrace](https://github.com/apitrace/apitrace) Tools for tracing OpenGL, Direct3D, and other graphics APIs
* [Remotery](https://github.com/Celtoys/Remotery)
* [BuGLe](https://sourceforge.net/projects/bugle/) BuGLe combines a graphical OpenGL debugger with a selection of filters on the OpenGL command stream. The debugger allows viewing of state, textures, framebuffers and shaders, while the filters allow for logging, error checking, video capture and more.
* Other: **gDEBugger**, **NVIDIA Nsight**, **Microsoft PIX**

## SDK&Tutorial
#### API Samples
* [DirectX-Graphics-Samples](https://github.com/Microsoft/DirectX-Graphics-Samples)
* [directx-sdk-samples](https://github.com/walbourn/directx-sdk-samples)
* [IntroductionToVulkan](https://github.com/GameTechDev/IntroductionToVulkan)
* [VulkanTutorial](https://github.com/Overv/VulkanTutorial)
* [Vulkan](https://github.com/SaschaWillems/Vulkan)
* [vulkan-sdk for android](https://github.com/ARM-software/vulkan-sdk)
* [nvpro-samples](https://github.com/nvpro-samples) NVIDIA DesignWorks Samples
#### Book Code
* [OpenGLInsightsCode](https://github.com/OpenGLInsights/OpenGLInsightsCode)
* [GraphicsGems](https://github.com/erich666/GraphicsGems)
* [GPUZen](https://github.com/wolfgangfengel/GPUZen)
#### Graphic SDK
* [GodComplex](https://github.com/Patapom/GodComplex)
* [GPUOpen-LibrariesAndSDKs](https://github.com/GPUOpen-LibrariesAndSDKs)
* [GPUOpen-Effects](https://github.com/GPUOpen-Effects)
* [NVIDIAGameWorks](https://github.com/NVIDIAGameWorks)
* [opengl-es-sdk-for-android](https://github.com/ARM-software/opengl-es-sdk-for-android)
* [powervr-graphics](https://github.com/powervr-graphics)

## Effect
#### Graphics Awesome
* [graphics-resources](https://github.com/mattdesl/graphics-resources)
* [awesome-graphics](https://github.com/ericjang/awesome-graphics)
* [awesome-vulkan](https://vinjn.github.io/awesome-vulkan/)
* [awesome-opengl](https://github.com/eug/awesome-opengl)
#### Shader Collection
* [Wisdom-Shaders](https://github.com/bobcao3/Wisdom-Shaders)
* [Depth3D](https://github.com/BlueSkyDefender/Depth3D) Depth Map Based 3D post-process shader for Reshade
* [robobo1221Shaders](https://github.com/robobo1221/robobo1221Shaders)
* [herebedragons](https://github.com/kosua20/herebedragons)
#### Some Effect
* [MetaBlob](https://github.com/danielzeller/MetaBlob)
* [gl-transitions](https://github.com/gl-transitions/gl-transitions)
* [FlatShader](https://github.com/cjurjiu/FlatShader)
* [Unity3DBookPageCurl](https://github.com/Dandarawy/Unity3DBookPageCurl) Page curl effect for Unity3D using native UI tools
* [cross-section](https://assetstore.unity.com/packages/vfx/shaders/cross-section-66300) create a cross section through meshes
#### Decal
* [ProjectionSpray](https://github.com/sugi-cho/ProjectionSpray)
#### Compute Shader Effect
* [FinalAudition](https://github.com/bonzajplc/FinalAudition) A complete remake of 2005 demo "Final Audition" by Plastic
#### Book
* [thebookofshaders](https://github.com/patriciogonzalezvivo/thebookofshaders)

## Physics
#### Library
* [bullet](https://github.com/bulletphysics/bullet3)
* [OPCODE](https://github.com/nitrocaster/OPCODE)
* [fcl](https://github.com/flexible-collision-library/fcl)
* [gjk.c](https://github.com/kroitor/gjk.c)
* [dyn4j](https://github.com/wnbittle/dyn4j) Java Collision Detection and Physics Engine
#### Fluid
* [tbb_liquid_amgpcg](https://github.com/zhxx1987/tbb_liquid_amgpcg)
* [PositionBasedDynamics](https://github.com/InteractiveComputerGraphics/PositionBasedDynamics) physically-based simulation of rigid bodies, deformable solids and fluids.
* [AlembicImporter](https://github.com/unity3d-jp/AlembicImporter)
* [GridFluidSim3D](https://github.com/rlguy/GridFluidSim3D)
* [SPHFluid](https://github.com/MangoSister/SPHFluid) Interactive 3D Fluid Simulation based on SPH
#### Demo
* [GamePhysicsCookbook](https://github.com/gszauer/GamePhysicsCookbook) 《Game Physics Cookbook》for Unity
* [SimplePhysicsDemo](https://github.com/LotteMakesStuff/SimplePhysicsDemo) A simple lil demo showing a jobified physics system

## Animation
* [cal3d](https://sourceforge.net/projects/cal3d/)
* [GPUSkinning](https://github.com/chengkehan/GPUSkinning)
* [Animation-Texture-Baker](https://github.com/sugi-cho/Animation-Texture-Baker)
* [UE4_MotionMatching-](https://github.com/Hethger/UE4_MotionMatching-)

## Particle
* [XParticle](https://github.com/antoinefournier/XParticle)
* [VolumetricParticles](https://github.com/DaSutt/VolumetricParticles)

## VR&AR
* [AugmentedUnreality](https://github.com/adynathos/AugmentedUnreality)
* [unrealcv](https://github.com/unrealcv/unrealcv)

## ML
* [AI4Animation](https://github.com/sebastianstarke/AI4Animation) Character Animation in Unity3D using Deep Learning and Artificial Intelligence
* [NvidiaAIDenoiser](https://github.com/DeclanRussell/NvidiaAIDenoiser) A simple implementation of Nvidia's AI denoiser

## CG
* [VTK](https://www.vtk.org/) The Visualization Toolkit

  
