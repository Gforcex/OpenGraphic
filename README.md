# OpenGraphic
Graphic Engine &amp; Game Engine open source list！

## Contents

>**Official**

  [Official](#official)  
  
>**Engine**

  [Engine](#engine) &nbsp;&nbsp; [EnginePlugin](#engine-plugin) &nbsp;&nbsp; [PBRRayTrace](#pbr-raytrace) &nbsp;&nbsp; [SoftRenderer](#soft-renderer) 
  
>**Rendering**

  [GI](#gi) &nbsp;&nbsp; [VolumeRendering](#volume-rendering) &nbsp;&nbsp; [PostProcessing](#postprocessing)           
  [ShadeModel](#shade-model) &nbsp;&nbsp; [PhysicallyBasedRendering](#physically-based-rendering)   
  [Stylize](#stylize)    
  [Effect](#effect) &nbsp;&nbsp; [VFX](#vfx) 
  
>**Beyond Polygons**

  [OIT](#oit) &nbsp;&nbsp; [Decal](#decal)  
  
>**Emulation**

  [Nature](#nature) &nbsp;&nbsp; [Environment](#environment) &nbsp;&nbsp; [Human](#human)
  
>**Optimization**

  [Acceleration](#acceleration)  &nbsp;&nbsp; [SceneManage](#scenemanage) &nbsp;&nbsp; [RenderPath](#render-path)  
  
>**Util**

  [Util](#util) &nbsp;&nbsp; [SDF](#sdf) &nbsp;&nbsp; [Math](#math) &nbsp;&nbsp; [Image&Color](#imagecolor) &nbsp;&nbsp; [Noise](#noise)  &nbsp;&nbsp; [Mesh](#mesh) &nbsp;&nbsp; [Platform](#platform) &nbsp;&nbsp; [UI](#ui) &nbsp;&nbsp; [CG](#cg)
  
>**Tools**

  [Tools](#tools) 
  
>**Tutorial**

  [SDK&Tutorial](#sdktutorial)
  
>**Other**

  [Physics](#physics) &nbsp;&nbsp; [Animation](#animation) &nbsp;&nbsp; [Particle](#particle) &nbsp;&nbsp; [Machine Learning](#ml)  &nbsp;&nbsp;  [VR&AR](#vrar) &nbsp;&nbsp;
  
---

## Official
* Unity [Unity-Technologies](https://github.com/Unity-Technologies)  &nbsp;&nbsp; [unity3d-jp](https://github.com/unity3d-jp)
* AMD  [GPUOpen-LibrariesAndSDKs](https://github.com/GPUOpen-LibrariesAndSDKs)  &nbsp;&nbsp; [GPUOpen-Tools](https://github.com/GPUOpen-Tools)  &nbsp;&nbsp;  [GPUOpen-Effects](https://github.com/GPUOpen-Effects)
* NVIDIA [NVIDIAGameWorks](https://github.com/NVIDIAGameWorks)  &nbsp;&nbsp; [nvpro-samples](https://github.com/nvpro-samples)  &nbsp;&nbsp; [NVIDIA](https://github.com/NVIDIA)
* Intel [Intel GameTechDev](https://github.com/GameTechDev) https://software.intel.com/gamedev
* ARM [ARM-software](https://github.com/ARM-software)
* SideEfects [sideeffects](https://github.com/sideeffects) Hodini
* [id-Software](https://github.com/id-Software)
* [InteractiveComputerGraphics](https://github.com/InteractiveComputerGraphics)

## Engine
* [UnrealEngine](https://github.com/EpicGames/UnrealEngine) :star:
* [CRYENGINE](https://github.com/CRYTEK/CRYENGINE) :star:
* [Lumberyard](https://github.com/aws/lumberyard) :star:
* [Urho3D](https://github.com/urho3d/Urho3D):thumbsup: lightweight, cross-platform 2D and 3D game engine,Greatly inspired by OGRE and Horde3D.
* [filament](https://github.com/google/filament):thumbsup: Filament is a physically based rendering engine for Android, Windows, Linux and macOS
* [Falcor](https://github.com/NVIDIAGameWorks/Falcor):thumbsup: Real-Time Rendering Framework, NVIDIA
* [Klayag](https://github.com/gongminmin/KlayGE) A cross-platform open source game engine with plugin-based architecture
* [G3D]( https://casual-effects.com/g3d) Graphics research and rapid prototyping in OpenGL and C++
* [bsf](https://github.com/GameFoundry/bsf) Modern C++14 library for the development of real-time graphical applications https://www.bsframework.io
* [OpenSceneGraph](https://github.com/openscenegraph/OpenSceneGraph)
* [Ogre](https://github.com/ogrecave) ogre github mirror
* [WickedEngine](https://github.com/turanszkij/WickedEngine) with Voxel-based Global Illumination
* [xenko](https://github.com/xenko3d/xenko) -old address https://github.com/SiliconStudio/xenko
* [bgfx](https://github.com/bkaradzic/bgfx) -Orthodox C++ coding style and like OpenGL APIs 
* [The-Forge](https://github.com/ConfettiFX/The-Forge) The Forge Cross-Platform Rendering Framework PC, macOS / iOS, Android, XBOX, PS4
* [oryol](https://github.com/floooh/oryol) - A small, portable and extensible C++ 3D coding framework,Orthodox C++ coding style and APIs
* [cesium](https://github.com/AnalyticalGraphicsInc/cesium) An open-source JavaScript library for world-class 3D globes and maps
* [BRE12](https://github.com/nbertoa/BRE12) a rendering framework [Blog](https://nbertoa.wordpress.com/)

## Engine Plugin
* [armory](https://github.com/armory3d/armory)  -3D Game Engine for Blender
* [RenderPipeline](https://github.com/tobspr/RenderPipeline) -PBR and Deferred Rendering for the Panda3D game engine 
* [ray-mmd](https://github.com/ray-cast/ray-mmd) physically-based rendering at mikumikudance

## PBR RayTrace
* [embree](https://github.com/embree/embree)
* [RadeonRays RadeonProRender](https://github.com/GPUOpen-LibrariesAndSDKs)
* [appleseed](https://github.com/appleseedhq/appleseed)
* [pbrt](https://github.com/mmp/pbrt-v3) Source code for "Physically Based Rendering: From Theory To Implementation" 
* [mitsuba](https://github.com/mitsuba-renderer/mitsuba)
* [LuxCoreRender](https://github.com/LuxCoreRender)
* [ospray](https://github.com/ospray/ospray) A Ray Tracing Based Rendering Engine for High-Fidelity Visualization
* [taichi](https://github.com/yuanming-hu/taichi)
* [tungsten](https://github.com/tunabrain/tungsten) High performance physically based renderer in C++11
* [nori](https://github.com/wjakob/nori)
* [nanort](https://github.com/lighttransport/nanort)  single header only modern ray tracing kernel.
* [SORT](https://github.com/JerryCao1985/SORT)  Simple Open-source Ray Tracer https://agraphicsguy.wordpress.com/

## Soft Renderer
* [openswr-mesa](https://github.com/OpenSWR/openswr-mesa) [OpenSWR](http://openswr.org/) A High Performance, Highly Scalable Software Rasterizer for OpenGL
* [miaow](https://github.com/VerticalResearchGroup/miaow)
* [tinyrenderer](https://github.com/ssloy/tinyrenderer)
* [coco3d](http://coco3d.codeplex.com/)
* [muli3d](https://sourceforge.net/projects/muli3d/)
* [swiftshader](https://github.com/google/swiftshader) high-performance CPU-based implementation of the OpenGL ES and Direct3D 9 graphics APIs
* [Mesa3D](https://gitlab.freedesktop.org/mesa/mesa) https://www.mesa3d.org
* [SoftwareRenderer](https://github.com/Angelo1211/SoftwareRenderer) Software rendering engine with PBR. Built from scratch on C++.

## GI
### Collection
* [GITechDemo](https://github.com/iftodebogdan/GITechDemo)
* [DynamicRadianceVolume](https://github.com/Wumpf/DynamicRadianceVolume)
* [dirtchamber](https://github.com/thefranke/dirtchamber)
* [RTGI](https://github.com/jazzboysc/RTGI)
* [Cinder-Experiments](https://github.com/simongeilfus/Cinder-Experiments) A collection of experiments, samples and other bits of code.
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
#### Spherica lHarmonic Lighting
* [Urho3D-1.4-SphericalHarmonicLighting](https://github.com/Lumak/Urho3D-1.4-SphericalHarmonicLighting)
#### PRT
* [precomputed-radiance-transfer](https://github.com/pramanc/precomputed-radiance-transfer)
* [SHTest](https://github.com/dwilliamson/SHTest)
* [SphericalHarmonicLighting](https://github.com/Lumak/Urho3D-1.4-SphericalHarmonicLighting)
#### Radiosity
#### Instant Radiosity
* [instant_radiosity](https://github.com/cache-tlb/instant_radiosity)
* [simple-instant-radiosity](https://github.com/githole/simple-instant-radiosity)
* [GIGL](https://github.com/vgfx/GIGL)
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
* [Unity-GeoAO](https://github.com/nezix/Unity-GeoAO) Fast ambien occlusion in Unity at runtime
* [ConeSphereOcclusionLUT](https://github.com/knarkowicz/ConeSphereOcclusionLUT) ConeSphereOcclusionLUT generates a cone sphere occlusion LUT to be used with TLoU style **capsule AO shadows**. For details "Lighting Technology Of "The Last Of Us".
#### Bent Normal
* [ssbn](https://github.com/KageKirin/ssbn) Screen Space Bent Normals
#### Radiosity Normal Mapping
* [GzRNM](https://github.com/Geenz/GzRNM) brings Radiosity Normal Mapping/Directional Light Mapping to Unity 3D!
* [SSbumpGenerator](https://sourceforge.net/projects/ssbumpgenerator/) A GUI interface to a tool for generating SSBumps (Self Shadowed Bump Maps).
#### LightMap
* [lightmapper](https://github.com/ands/lightmapper)
* [seamoptimizer](https://github.com/ands/seamoptimizer)
* [BakingLab](https://github.com/TheRealMJP/BakingLab)
* [BocsLightmapper](https://github.com/sasa42/BocsLightmapper)
* [trianglepacker](https://github.com/ray-cast/trianglepacker) Triangle packer for light map
#### Light Field
* [temporal-lightfield-reconstruction](https://github.com/jiawen/temporal-lightfield-reconstruction)   mplementation of "Temporal Light Field Reconstruction for Rendering Distribution Effects" (SIGGRAPH 2011)
* [indirect-light-field-reconstruction](https://github.com/jtlehtin/indirect-light-field-reconstruction)  mplementation of "Reconstructing the Indirect Light Field for Global Illumination" (SIGGRAPH 2012)  

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
* [variance_shadow_mapping_vk](https://github.com/sydneyzh/variance_shadow_mapping_vk) Variance shadow mapping for omni lights with Vulkan
* [Precomputed-Shadow-Fields-for-Dynamic-Scenes](https://github.com/nblintao/Precomputed-Shadow-Fields-for-Dynamic-Scenes)

## PostProcessing 
#### Collection
* [PostProcessing](https://github.com/Unity-Technologies/PostProcessing)
* [reshade-shaders](https://github.com/crosire/reshade-shaders) A collection of post-processing shaders written for ReShade. https://reshade.me
* [Cat-PostProcessing](https://github.com/JoachimCoenen/Cat-PostProcessing)
* [Unity5Effects](https://github.com/i-saint/Unity5Effects)
* [UnityImageEffects](https://github.com/hiroakioishi/UnityImageEffects)
#### AA
* [CMAA2](https://github.com/GameTechDev/CMAA2)  Conservative Morphological Anti-Aliasing 2.0
* [MSAAFilter](https://github.com/TheRealMJP/MSAAFilter)  MSAA and Temporal AA Sample
* [temporal](https://github.com/playdeadgames/temporal) Temporal Reprojection Anti-Aliasing for Unity 5.0+
* [smaa](https://github.com/iryoku/smaa) SMAA: Subpixel Morphological Antialiasing, is a very efficient GPU-based MLAA implementation
* [smaaDemo](https://github.com/turol/smaaDemo) Subpixel Morphological AntiAliasing OpenGL/Vulkan demo
* [SMAA](https://github.com/Chman/SMAA) SMAA in unity3D
* [SpecularAA](https://github.com/TheRealMJP/SpecularAA) A demo of various normal map filtering techniques for reducing specular aliasing
* [glsl-fxaa](https://github.com/mattdesl/glsl-fxaa) FXAA implementation for glslify in WebGL
#### Denoising 
* [practicalDenoising](https://github.com/ImageEngine/practicalDenoising) Reference Implementation of Practical Denoising for VFX Production Using Temporal Blur
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
* [fabric-micro-detail-scattering](https://github.com/bradweiers/fabric-micro-detail-scattering)
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
#### Atmospheric
* [AtmosphericScattering](https://github.com/SlightlyMad/AtmosphericScattering)
* [AtmosphericScattering](https://github.com/yangzhengxing/AtmosphericScattering)
* [Scatterer](https://github.com/LGhassen/Scatterer)
* [precomputed_atmospheric_scattering](https://github.com/ebruneton/precomputed_atmospheric_scattering) Eric Bruneton, 2017
* [Brunetons-Improved-Atmospheric-Scattering](https://github.com/Scrawk/Brunetons-Improved-Atmospheric-Scattering) Eric Bruneton for Unity, 2017
* [glsl-atmosphere](https://github.com/wwwtyro/glsl-atmosphere)
#### Fog
* [Vapor](https://github.com/ArthurBrussee/Vapor) Volumetric Fog for Unity
* [unity-volumetric-fo](https://github.com/SiiMeR/unity-volumetric-fog)

## Render Path
* [ClusteredShadingAndroid](https://github.com/GameTechDev/ClusteredShadingAndroid)
* [VulkanClusteredShader](https://github.com/xnieamo/VulkanClusteredShader)
* [clustered_forward_demo_vk](https://github.com/sydneyzh/clustered_forward_demo_vk)  Clustered forward rendering demo with Vulkan
* [forward-clustered-shading](https://software.intel.com/en-us/articles/forward-clustered-shading)
* [ClusteredShadingConservative](https://github.com/kevinortegren/ClusteredShadingConservative) DirectX 12 light culling technique implementation of Clustered Deferred Shading

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
* [glTF-SDK](https://github.com/Microsoft/glTF-SDK) glTF-SDK is a Software Development Kit for glTF (GL Transmission Format -https://github.com/KhronosGroup/glTF).  

## Shade Model
### BSDF
* [libbsdf](https://github.com/KimuraRyo/libbsdf) Library for BSDF, BRDF, and BTDF
##### BRDF
* [brdf](https://github.com/wdas/brdf) &nbsp;&nbsp; [brdfExplorer](https://github.com/sotnychenko/brdfExplorer)
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
* [hyper3d-envmapgen](https://github.com/Hyper3D/hyper3d-envmapgen) Pre-filtered mipmapped radiance environment map generator that runs on WebAssembly.
* [LTC_BRDF_Fit](https://github.com/EvgeniiG/LTC_BRDF_Fit)  BRDF fitting code for LTC Area Lights by Heitz et al.

## Stylize
#### NPR
* [NPR_Lab](https://github.com/candycat1992/NPR_Lab)
* [MNPR](https://github.com/semontesdeoca/MNPR) An expressive non-photorealistic rendering framework for real-time, filter-based stylization pipelines within Maya. http://mnpr.artineering.io     
* [Wind-Waker-Shader](https://github.com/albertomelladoc/Wind-Waker-Shader) Cel Shading of two thresholds with a blur/gradient between them
* [ToonShading](https://github.com/Kink3d/ToonShading) A collection of "Toon" shaders for Unity based on a stepped PBR approximation.
* [kamakura-shaders](https://github.com/kayac/kamakura-shaders) NPR for Unity with a bunch of features and adjustable parameters in a user-friendly interface.
* [UnityNPR](https://github.com/GlitchEnzo/UnityNPR)
* [NPR](https://github.com/laundsallyn/NPR)
* [ChinesePaintingDemo](https://github.com/AtwoodDeng/ChinesePaintingDemo)
#### Low Poly
* [Lowpoly-Water-Unity](https://github.com/danielzeller/Lowpoly-Water-Unity) Low poly water with edge/shore blend. Similar to the awesome water in Monument Valley.  
* [FlatShader](https://github.com/cjurjiu/FlatShader) A very simple shader which performs flatshading without the need for duplicating vertices when building the geometry.
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
* [SpaceWarp](https://github.com/mzandvliet/SpaceWarp)  Playing with DistanceField Raymarching as Post Effect in Unity3d
#### Point Clouds
* [PCL](http://www.pointclouds.org/)
#### Shear-warp
#### Other
* [OpenVDB](https://github.com/dreamworksanimation/openvdb) Sparse volume data structure and tools
* [OpenVDBForUnity](https://github.com/karasusan/OpenVDBForUnity)

## Acceleration
#### Frustum Culling
* [sseculling](https://github.com/nsf/sseculling)
#### Soft Occlusion Culling
* [intel_occlusion_cull](https://github.com/rygorous/intel_occlusion_cull)
* [Image-Space-Occlusion-Culling-Engine](https://github.com/lebarba/Image-Space-Occlusion-Culling-Engine) Image Space Occlusion Culling Engine optimized to perform occlusion culling in CPU.
* [Janua](https://github.com/gigc/Janua) Open Source occlusion culling engine for 3D Scenes
* [OcclusionCulling](https://github.com/GameTechDev/OcclusionCulling) software (CPU) based approach to occllusion culling using multi-threading and SIMD instructions to improve performance.
* [rasterizer](https://github.com/rawrunprotected/rasterizer) faster in single-threaded AVX mode when rendering the full set of occluders (no minimum size).
* [IndirectOcclusionCulling](https://github.com/JJoosten/IndirectOcclusionCulling)
* [vigilant-system](https://github.com/nlguillemot/vigilant-system)
#### Hardware Occlusion Queries
#### Hierarchical-Z Buffer
#### Hierarchical Occlusion Map
#### Imposter
* [IMP](https://github.com/xraxra/IMP) billboard imposter baking for Unity
* [ImpostorBaker](https://github.com/ictusbrucks/ImpostorBaker) UE4 Plugin for generating Impostors for static meshes  
#### LOD
#### HLOD

## SceneManage
* [UnityOctree](https://github.com/Nition/UnityOctree)

## SDF
* [distancefield-unity](https://github.com/kvantetore/distancefield-unity)
* [Typogenic](https://github.com/Chman/Typogenic)
* [SDF](https://github.com/memononen/SDF)

## OIT
* [Order-Independent-Trasparency](https://github.com/PixelClear/Order-Independent-Trasparency)
* [OIT_Lab](https://github.com/candycat1992/OIT_Lab)
* [oitDemo](https://github.com/turol/oitDemo) Order Independent Transparency In OpenGL 4.x

## Math
* [Eigen](https://github.com/eigenteam/eigen-git-mirror) :star: linear algebra: matrices, vectors, numerical solvers, and related algorithms. [Eigen](http://eigen.tuxfamily.org/)
* [MathGeoLib](https://github.com/juj/MathGeoLib) A C++ library for linear algebra and geometry manipulation for computer graphics
* [CGAL](https://www.cgal.org/) geometric algorithms in the form of a C++ library.
* [GEOS](http://trac.osgeo.org/geos) Geometry Engine
* [MTL]() Matrix Template Library,  a linear algebra library for C++ programs.
* [sh-lib](https://github.com/andrewwillmott/sh-lib)  Spherical/zonal harmonics library
* [spherical-harmonics](https://github.com/google/spherical-harmonics)  Spherical harmonics library
* [DirectXMath](https://github.com/Microsoft/DirectXMath) DirectXMath is an all inline SIMD C++ linear algebra library for use in games and graphics apps
* [geomc](https://github.com/trbabb/geomc) A c++ linear algebra template library  
* [geometry3Sharp](https://github.com/gradientspace/geometry3Sharp) C# library for 2D/3D geometric computation, mesh algorithms, and so on
* [ShaderFastLibs](https://github.com/michaldrobot/ShaderFastLibs) Shader libraries for fast shader opetations.
* [hlslpp](https://github.com/redorav/hlslpp) Math library using hlsl syntax with SSE/NEON support  

## Image&Color
* [OpenCV](https://github.com/opencv/opencv) Open Source Computer Vision Library. C# Wrapper [opencvsharp](https://github.com/shimat/opencvsharp)
* [bimg](https://github.com/bkaradzic/bimg) Image library.
* [OpenColorIO](https://github.com/imageworks/OpenColorIO) A color management framework for visual effects and animation http://opencolorio.org
* [OpenImageIO](https://github.com/OpenImageIO/oiio) OpenImageIO http://www.openimageio.org
* [GLSL-Color-Spaces](https://github.com/tobspr/GLSL-Color-Spaces) Utility functions to convert between various color spaces in GLSL
* [ImageSharp](https://github.com/SixLabors/ImageSharp) A cross-platform library for the processing of image files; written in C#
* [Dithering-Unity3d](https://github.com/mcraiha/Dithering-Unity3d) 
* [colormap-shaders](https://github.com/kbinani/colormap-shaders) A collection of shaders to draw color maps.
* [colour](https://github.com/colour-science/colour) Colour Science for Python https://www.colour-science.org
* [NormalmapGenerator](https://github.com/Theverat/NormalmapGenerator)  A simple program that converts images into normal maps
* [vg-renderer](https://github.com/jdryg/vg-renderer)  A vector graphics renderer for bgfx, based on ideas from NanoVG and ImDrawList (Dear ImGUI)

#### TextureCompressed
* [nv_dds](https://github.com/paroj/nv_dds) DDS image loader for OpenGL/ OpenGL ES2 http://paroj.github.io/nv_dds/
* [nvidia-texture-tools](https://github.com/castano/nvidia-texture-tools) Texture processing tools with support for Direct3D 10 and 11 formats. 
* [crunch](https://github.com/BinomialLLC/crunch)  Advanced DXTc texture compression and transcoding library http://binomial.info
* [unity-ycca-subsampling](https://github.com/n-yoda/unity-ycca-subsampling) [ChromaPack](https://github.com/keijiro/ChromaPack)   YCCA chroma subsampling technique

## Noise
* [TileableVolumeNoise](https://github.com/sebh/TileableVolumeNoise)
* [FastNoise](https://github.com/Auburns/FastNoise)
* [Turbulence-Library](https://github.com/jesta88/Turbulence-Library)
* [GPU-Noise-Lib](https://github.com/BrianSharpe/GPU-Noise-Lib)
* [webgl-noise](https://github.com/ashima/webgl-noise)
* [VisualNoiseDesigner](https://github.com/x0r04rg/VisualNoiseDesigner)

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

* [Compressonator](https://github.com/GPUOpen-Tools/Compressonator) Tool suite for Texture and 3D Model Compression, Optimization and Analysis using CPUs, GPUs and APUs  
* [draco](https://github.com/google/draco) compressing and decompressing 3D geometric meshes and point clouds.   

* [meshlab](https://github.com/cnr-isti-vclab/meshlab) MeshLab is mostly based on the mesh processing library VCGlib
* [Mesh-processing-library](https://github.com/Microsoft/Mesh-processing-library) mesh processing techniques in computer graphics published at ACM SIGGRAPH in 1992–1998  
* [PyMesh](https://github.com/qnzhou/PyMesh) a rapid prototyping platform focused on geometry processing https://pymesh.readthedocs.io
* [poly2tri](https://github.com/greenm01/poly2tri) Fast and Robust Simple Polygon Triangulation With/Without Holes   
* [libigl](https://github.com/libigl/libigl)
* [openmesh](https://www.openmesh.org/)
* [openflipper](https://www.openflipper.org/)
 
## Platform
* [herebedragons](https://github.com/kosua20/herebedragons)
* [glfw](https://github.com/glfw/glfw)
* [MoltenVK](https://github.com/KhronosGroup/MoltenVK) Vulkan graphics and compute API, that runs on Apple's Metal graphics framework
* [dxvk](https://github.com/doitsujin/dxvk) Vulkan-based D3D11 implementation for Linux / Wine  

## UI
* [imgui](https://github.com/ocornut/imgui)
* [nanovg](https://github.com/memononen/nanovg)
* [nanogui](https://github.com/wjakob/nanogui)
* [nuklear](https://github.com/vurtun/nuklear)
* [AnttWeakbar](https://sourceforge.net/projects/anttweakbar/)
* [UIEffect](https://github.com/mob-sakai/UIEffect) UIEffect is an effect component for uGUI element in Unity
* [SpriteDicing](https://github.com/Elringus/SpriteDicing) Extension for Unity game engine to work with diced sprites
* [PolyMesh](https://github.com/UnityPatterns/PolyMesh) Create 2D shapes in an instant with the PolyMesh editor! 

## Util
* [stb](https://github.com/nothings/stb)
* [yocto-gl](https://github.com/xelatihy/yocto-gl) Yocto/GL: Tiny C++ Libraries for Physically-based Graphics
* [debug-draw](https://github.com/glampert/debug-draw)

## Effect 
#### Minecraft
* [Wisdom-Shaders](https://github.com/bobcao3/Wisdom-Shaders) A Minecraft shaderspack. Offers high performance with high quality at the same time. https://qionouu.cn/  
* [Ebin-Shaders](https://github.com/BruceKnowsHow/Ebin-Shaders) This is a Minecraft shaderpack for use with Optifine.
* [robobo1221Shaders](https://github.com/robobo1221/robobo1221Shaders)
#### Meta Blobs
* [MetaBlob](https://github.com/danielzeller/MetaBlob) Meta Blobs for Unity 3D.
#### Transitions
* [gl-transitions](https://github.com/gl-transitions/gl-transitions) :thumbsup:  The open collection of GL Transitions https://gl-transitions.com/ 
#### Mesh Cut
* [cross-section](https://assetstore.unity.com/packages/vfx/shaders/cross-section-66300) create a cross section through meshes
#### PageCurl
* [Unity3DBookPageCurl](https://github.com/Dandarawy/Unity3DBookPageCurl) Page curl effect for Unity3D using native UI tools
#### Decal
* [ProjectionSpray](https://github.com/sugi-cho/ProjectionSpray)
#### OutLine
* [Outline-Effect](https://github.com/cakeslice/Outline-Effect) Outline Image Effect for Unity
#### Motion
* [AmplifyMotion](https://github.com/AmplifyCreations/AmplifyMotion) Amplify Motion was the first Full-scene Motion Blur extension for Unity
#### Fractal
* [ElectricSheep_WebGL](https://github.com/richardassar/ElectricSheep_WebGL) WebGL Electric Sheep Renderer
#### Compute Shader Effect
* [FinalAudition](https://github.com/bonzajplc/FinalAudition) A complete remake of 2005 demo "Final Audition" by Plastic

## VFX
#### Houdini
* [qLib](https://github.com/qLab/qLib) A procedural asset library for SideFX Houdini. http://qlab.github.com/qLib

## Tools
#### UE4
* [u4pak](https://github.com/panzi/u4pak)
* [UModel](https://github.com/gildor2/UModel)
* [UnrealEnginePython](https://github.com/20tab/UnrealEnginePython)
#### Unity
* [AssetStudio](https://github.com/Perfare/AssetStudio) A tool for exploring, extracting and exporting assets and assetbundles
* [unitysizeexplorer](https://github.com/aschearer/unitysizeexplorer) Visualize how much space each asset in your Unity game takes
#### Shader
* [shader-playground](https://github.com/tgjones/shader-playground) :thumbsup: Shader compilers http://shader-playground.timjones.io
* [glsl-optimizer](https://github.com/aras-p/glsl-optimizer) :star: GLSL optimizer based on Mesa's GLSL compiler.
* [glslang](https://github.com/KhronosGroup/glslang) Khronos reference front-end for GLSL and ESSL, and sample SPIR-V generator
* [ShaderForge](https://github.com/FreyaHolmer/ShaderForge)

* [HlslTools](https://github.com/tgjones/HlslTools) A Visual Studio extension that provides enhanced support for editing High Level Shading Language (HLSL) files
* [nshader](https://github.com/samizzo/nshader) Visual Studio 2013/2015/2017 syntax highlighting extension for shader languages
* [ShaderlabVS](https://github.com/wudixiaop/ShaderlabVS) ShaderlabVS is a Visual Studio Plugin for Unity Shaderlab programming
#### ShaderToy
* [shader-toy](https://github.com/stevensona/shader-toy)
* [ofxShadertoy](https://github.com/tiagosr/ofxShadertoy)
* [ShaderMan](https://github.com/smkplus/ShaderMan)
#### Visual Effects
* [gaffer](https://github.com/GafferHQ/gaffer)  A open source application framework designed specifically for creating tools for use in visual effects production.
* [cortex](https://github.com/ImageEngine/cortex) Libraries for visual effects software development
#### Texture
* [xNormal](http://www.xnormal.net/) A free tool to bake texture maps ( like normal maps and ambient occlusion )
* [FlowmapPainter](http://teckartist.com/?page_id=107)
#### GPU Debug
* [renderdoc](https://github.com/baldurk/renderdoc) A stand-alone graphics debugging tool. https://renderdoc.org
* [CodeXL](https://github.com/GPUOpen-Tools) a comprehensive tool suite that enables developers to harness the benefits of CPUs, GPUs and APUs.
* [perfdoc](https://github.com/ARM-software/perfdoc) A cross-platform Vulkan layer which checks Vulkan applications for best practices on Arm Mali devices.
* [gapid](https://github.com/google/gapid) Graphics API Debugger by google
* [vogl](https://github.com/ValveSoftware/vogl) OpenGL capture / playback debugger by valve
* [apitrace](https://github.com/apitrace/apitrace) Tools for tracing OpenGL, Direct3D, and other graphics APIs
* [GPUVis](https://github.com/mikesart/gpuvis) GPU Trace Visualizer
* [Remotery](https://github.com/Celtoys/Remotery) Single C file, Realtime CPU/GPU Profiler with Remote Web Viewer
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
#### Graphics Awesome
* [graphics-resources](https://github.com/mattdesl/graphics-resources) a list of graphic programming resources  
* [awesome-graphics](https://github.com/ericjang/awesome-graphics) Curated list of computer graphics tutorials and resources  
* [awesome-vulkan](https://vinjn.github.io/awesome-vulkan/) A curated list of awesome Vulkan libraries
* [awesome-opengl](https://github.com/eug/awesome-opengl) A curated list of awesome OpenGL libraries, debuggers and resources.
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
* [ozz-animation](https://github.com/guillaumeblanc/ozz-animation) open source c++ 3d skeletal animation library and toolset
* [acl](https://github.com/nfrechette/acl) Animation Compression Library
* [cal3d](https://sourceforge.net/projects/cal3d/) Askeletal based 3d character animation library written in C++ in a platform-/graphic API-independent way.
* [GPUSkinning](https://github.com/chengkehan/GPUSkinning)
* [Animation-Texture-Baker](https://github.com/sugi-cho/Animation-Texture-Baker)
* [UE4_MotionMatching-](https://github.com/Hethger/UE4_MotionMatching-) Early Implementation of Motion Matching tech

## Particle
* [XParticle](https://github.com/antoinefournier/XParticle)
* [VolumetricParticles](https://github.com/DaSutt/VolumetricParticles)
* [gpu-particles](https://github.com/Robert-K/gpu-particles) A GPU Particle System for Unity

## VR&AR
* [AugmentedUnreality](https://github.com/adynathos/AugmentedUnreality)
* [unrealcv](https://github.com/unrealcv/unrealcv)

## ML
* [AI4Animation](https://github.com/sebastianstarke/AI4Animation) Character Animation in Unity3D using Deep Learning and Artificial Intelligence
* [NvidiaAIDenoiser](https://github.com/DeclanRussell/NvidiaAIDenoiser) A simple implementation of Nvidia's AI denoiser

## CG
* [VTK](https://www.vtk.org/) The Visualization Toolkit
