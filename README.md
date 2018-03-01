# OpenGraphic
Graphic Engine &amp; Game Engine open source list！

> ### Contents
- [Official](#official)  
- [Engine](#engine)  
- [Engine Plugin](#engine-plugin)  
- [Physically Based Rendering](#physically-based-rendering)  
- [PBR RayTrace](#pbr-raytrace)  
- [GI](#gi)  
- [PostProcessing](#postprocessing)  
- [Nature](#nature)  
- [Environment](#environment)  
- [Human](#human)  
- [Soft Renderer](#soft-renderer)  
- [Render Path](#render-path)  
- [Shade Model](#shade-model)  
- [NPL](#npl)  
- [Voxel](#voxel)  
- [RayMarch](#raymarch)  
- [SDF](#sdf)  
- [OIT](#oit)  
- [Math](#math)  
- [Image&Color](#imagecolor)  
- [Noise](#noise)  
- [SceneManage](#scenemanage)  
- [Point Clouds](#point-clouds)  
- [Mesh](#mesh)  
- [Platform](#platform)  
- [UI](#ui)  
- [Util](#util)  
- [Tools](#tools)  
- [Sample](#sample)  
- [Effect](#effect)  
- [Physics](#physics)  
- [Animation](#animation)  
- [VR&AR](#vrar)  

## Official
* [Unity-Technologies](https://github.com/Unity-Technologies)
* [GPUOpen-LibrariesAndSDKs](https://github.com/GPUOpen-LibrariesAndSDKs)
* [GPUOpen-Tools](https://github.com/GPUOpen-Tools)

## Engine
* [UnrealEngine](https://github.com/EpicGames/UnrealEngine)
* [CRYENGINE](https://github.com/CRYTEK/CRYENGINE)
* [Lumberyard](https://github.com/aws/lumberyard)
* [Klayag](https://github.com/gongminmin/KlayGE)
* [Urho3D](https://github.com/urho3d/Urho3D)
* [OpenSceneGraph](https://github.com/openscenegraph/OpenSceneGraph)
* [Ogre](https://github.com/ogrecave) ogre github mirror
* [WickedEngine](https://github.com/turanszkij/WickedEngine) with Voxel-based Global Illumination
* [xenko](https://github.com/SiliconStudio/xenko) -Enlighten's company
* [bgfx](https://github.com/bkaradzic/bgfx) -Orthodox C++ coding style and like OpenGL APIs 
* [The-Forge](https://github.com/ConfettiFX/The-Forge) The Forge Cross-Platform Rendering Framework PC, macOS / iOS, Android, XBOX, PS4
* [oryol](https://github.com/floooh/oryol) - A small, portable and extensible C++ 3D coding framework,Orthodox C++ coding style and APIs
* [cesium](https://github.com/AnalyticalGraphicsInc/cesium) An open-source JavaScript library for world-class 3D globes and maps
* [Anvil](https://github.com/GPUOpen-LibrariesAndSDKs/Anvil) Anvil is a cross-platform framework for Vulkan, AMD
* [Falcor](https://github.com/NVIDIAGameWorks/Falcor) Real-Time Rendering Framework, NVIDIA
* [XLE](https://github.com/xlgames-inc/XLE) the engine's blog is good about  Spherical Harmonics
* [BRE12](https://github.com/nbertoa/BRE12) a rendering framework [Blog](https://nbertoa.wordpress.com/)

## Engine Plugin
* [armory](https://github.com/armory3d/armory)  -3D Game Engine for Blender
* [RenderPipeline](https://github.com/tobspr/RenderPipeline) -PBR and Deferred Rendering for the Panda3D game engine 
* [ray-mmd](https://github.com/ray-cast/ray-mmd) physically-based rendering at mikumikudance

## Physically Based Rendering
#### Camera
* [Physical-Camera](https://github.com/Unity-Technologies/Physical-Camera)
* [pbc](https://github.com/kiwaiii/pbc)
* [Cat-Physically-Based-Camera](https://github.com/JoachimCoenen/Cat-Physically-Based-Camera)
#### File Format
* [yocto-gl](https://github.com/xelatihy/yocto-gl)

## PBR RayTrace
* [embree](https://github.com/embree/embree)
* [RadeonRays RadeonProRender](https://github.com/GPUOpen-LibrariesAndSDKs)
* [nori](https://github.com/wjakob/nori)
* [nanort](https://github.com/lighttransport/nanort)
* [appleseed](https://github.com/appleseedhq/appleseed)
* [mitsuba](https://github.com/mitsuba-renderer/mitsuba)
* [taichi](https://github.com/yuanming-hu/taichi)
* [ospray](https://github.com/ospray/ospray)
* [gotham](https://github.com/jaredhoberock/gotham) Photorealistic Renderer based on Unbiased Rendering Algorithms
* [tungsten](https://github.com/tunabrain/tungsten)

## GI
### GI Algorithms
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
#### Ray tracing
#### Path tracing
* [asst5_bidirectional_pathtracer](https://github.com/sohilshah2/asst5_bidirectional_pathtracer)
#### Metropolis light transport
#### PhotonMapping
* [CPMFIGIOTVVD](https://github.com/ResearchDaniel/Correlated-Photon-Mapping-for-Interactive-Global-Illumination-of-Time-Varying-Volumetric-Data)
#### Ambient occlusion
#### AO 
* [NNAO](https://github.com/simeonradivoev/NNAO)
* [dssdo](https://github.com/kayru/dssdo) Deferred Screen Space Directional Occlusion http://kayru.org/articles/dssdo/
* [ssgi](https://github.com/jdupuy/ssgi) Screen space global illumination demo: SSAO vs SSDO
#### Bent Normal
* [ssbn](https://github.com/KageKirin/ssbn) Screen Space Bent Normals
#### LightMap
* [lightmapper](https://github.com/ands/lightmapper)
* [seamoptimizer](https://github.com/ands/seamoptimizer)
* [BakingLab](https://github.com/TheRealMJP/BakingLab)
### GI Simulation
#### Diffuse inter-reflection
#### Caustic
* [SC_Tracer](https://github.com/ningfengh/SC_Tracer) photon mapping for global illumination and caustic
#### Reflection
* [kode80SSR](https://github.com/kode80/kode80SSR)
* [StochasticScreenSpaceReflection](https://github.com/cCharkes/StochasticScreenSpaceReflection)
* [UnitySSR](https://github.com/cCharkes/UnitySSR)
#### Refraction
#### Shadow
* [Shadows](https://github.com/TheRealMJP/Shadows)
* [UnityPCSS](https://github.com/TheMasonX/UnityPCSS)

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
#### Bloom
* [HexBokehBlur](https://github.com/zigguratvertigo/HexBokehBlur)
* [hdreffects](https://github.com/karimnaaji/hdreffects)
#### Tone Mapping
* [tonemapper](https://github.com/tizian/tonemapper)
#### Lens
* [PhysicallyBasedLensFlare](https://github.com/greje656/PhysicallyBasedLensFlare)
* [LightLeaksUnity](https://github.com/danielzeller/LightLeaksUnity)
#### Other
* [UnityScreenSpaceBoolean](https://github.com/hecomi/UnityScreenSpaceBoolean)
* [OffScreenParticleRendering](https://github.com/slipster216/OffScreenParticleRendering)

## Human
#### Skin
* [pbrt-skin-bssrdf](https://github.com/damlaren/pbrt-skin-bssrdf)
* [skinparam](https://github.com/patwonder/skinparam)
* [CP_SSSSS](https://github.com/CustomPhase/CP_SSSSS)
* [separable-sss](https://github.com/iryoku/separable-sss)
* [skin-shader-unity](https://github.com/leonardo-domingues/skin-shader-unity) GPU Gems 3 - Chapter 14 using the Unity engine
#### Eye
#### Hair
* [TressFX](https://github.com/GPUOpen-Effects/TressFX)
* [WetaHair](https://github.com/zhoub/WetaHair)
* [libWetHair](https://github.com/nepluno/libWetHair)
#### Colth
#### Fur
* [FurRendering](https://github.com/jose-villegas/FurRendering)

## Nature
#### Water
* [Ocean Community Next Gen](https://github.com/eliasts/Ocean_Community_Next_Gen)
* [OceanProject](https://github.com/UE4-OceanProject/OceanProject)
* [VaOcean](https://github.com/ufna/VaOcean)
* [fft-ocean](https://github.com/jbouny/fft-ocean)
* [Unity-WaterBuoyancy](https://github.com/dbrizov/Unity-WaterBuoyancy)
* [Ocean_Community_Next_Gen](https://github.com/eliasts/Ocean_Community_Next_Gen)
* [crest-oceanrender](https://github.com/huwb/crest-oceanrender) Novel ocean rendering techniques (Unity3D)
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
#### Grass
* [Grass.DirectX](https://github.com/mreinfurt/Grass.DirectX)
* [VulkanGrassRendering](https://github.com/moneimne/VulkanGrassRendering)
* [GooHairGrass](https://github.com/cabbibo/GooHairGrass)
* [Project6-Vulkan-Grass-Rendering](https://github.com/CIS565-Fall-2017/Project6-Vulkan-Grass-Rendering)
#### Tree
* [Vulkan-Forest-Rendering-Engine](https://github.com/Jiaww/Vulkan-Forest-Rendering-Engine)
#### Terrain
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
#### Fire
* [fire](https://github.com/robertcupisz/fire)

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

## Soft Renderer
* [openswr-mesa](https://github.com/OpenSWR/openswr-mesa) [OpenSWR](http://openswr.org/)
* [miaow](https://github.com/VerticalResearchGroup/miaow)
* [tinyrenderer](https://github.com/ssloy/tinyrenderer)
* [coco3d](http://coco3d.codeplex.com/)
* [muli3d](https://sourceforge.net/projects/muli3d/)

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

## Shade Model
#### BRDF
* [brdf](https://github.com/wdas/brdf)
* [brdfExplorer](https://github.com/sotnychenko/brdfExplorer)
* [BRDFExplorer](https://github.com/Corralx/BRDFExplorer)
* [Lux](https://github.com/larsbertram69)
* [Alloy](https://github.com/Josh015/Alloy)
* [AntonovSuit](https://github.com/cCharkes/AntonovSuit)
* [AnisotropicStandardShader](https://github.com/Kink3d/AnisotropicStandardShader)
#### IBL
* [IBLBaker](https://github.com/derkreature/IBLBaker)
* [cmftStudio](https://github.com/dariomanesku/cmftStudio)
* [Probulator](https://github.com/kayru/Probulator)
* [IBLGGX](https://github.com/tuccio/IBLGGX)
* [IntegrateDFG](https://github.com/knarkowicz/IntegrateDFG)
#### BSSRDF
* [Subsurface-Light-Transport-Raytracer](https://github.com/curranmax/Subsurface-Light-Transport-Raytracer)
* [SingleScatteringEditing](https://github.com/ykcadcg/SingleScatteringEditing)
* [pbrt-importance-sampling](https://github.com/dnx4015/pbrt-importance-sampling)
* [hitchhikersscatter](https://github.com/eugenedeon/hitchhikersscatter)
#### SSS
* [FastTranslucentShader](https://github.com/tatsy/FastTranslucentShader)

## NPR
* [NPR_Lab](https://github.com/candycat1992/NPR_Lab)
* [Wind-Waker-Shader](https://github.com/albertomelladoc/Wind-Waker-Shader) Cel Shading of two thresholds with a blur/gradient between them
* [ToonShading](https://github.com/Kink3d/ToonShading) A collection of "Toon" shaders for Unity based on a stepped PBR approximation.

## Voxel
* [UE4VoxelTerrain](https://github.com/bw2012/UE4VoxelTerrain)
* [voxelizer](https://github.com/karimnaaji/voxelizer)
* [gpu-physics-unity](https://github.com/jknightdoeswork/gpu-physics-unity)

## RayMarch
* [ray-march](https://github.com/lightbits/ray-march)
* [uRaymarching](https://github.com/hecomi/uRaymarching)
* [unity-ray-marching](https://github.com/brianasu/unity-ray-marching)
* [dli](https://github.com/dli)

## SDF
* [distancefield-unity](https://github.com/kvantetore/distancefield-unity)
* [Typogenic](https://github.com/Chman/Typogenic)
* [SDF](https://github.com/memononen/SDF)

## OIT
* [Order-Independent-Trasparency](https://github.com/PixelClear/Order-Independent-Trasparency)
* [OIT_Lab](https://github.com/candycat1992/OIT_Lab)
* [oitDemo](https://github.com/turol/oitDemo) Order Independent Transparency In OpenGL 4.x

## Math
* [MathGeoLib](https://github.com/juj/MathGeoLib)
* [sh-lib](https://github.com/andrewwillmott/sh-lib)
* [spherical-harmonics](https://github.com/google/spherical-harmonics)
* [Urho3D-1.4-SphericalHarmonicLighting](https://github.com/Lumak/Urho3D-1.4-SphericalHarmonicLighting)
* [DirectXMath](https://github.com/Microsoft/DirectXMath)
* [geomc](https://github.com/trbabb/geomc)
* [geometry3Sharp](https://github.com/gradientspace/geometry3Sharp)
* [ShaderFastLibs](https://github.com/michaldrobot/ShaderFastLibs) Shader Math lib

## Image&Color
* [GLSL-Color-Spaces](https://github.com/tobspr/GLSL-Color-Spaces)
* [ImageSharp](https://github.com/SixLabors/ImageSharp) A cross-platform library for the processing of image files; written in C#
* [Dithering-Unity3d](https://github.com/mcraiha/Dithering-Unity3d)
* [glsl-colormap](https://github.com/kbinani/glsl-colormap)

## Noise
* [TileableVolumeNoise](https://github.com/sebh/TileableVolumeNoise)
* [FastNoise](https://github.com/Auburns/FastNoise)
* [Turbulence-Library](https://github.com/jesta88/Turbulence-Library)
* [GPU-Noise-Lib](https://github.com/BrianSharpe/GPU-Noise-Lib)
* [webgl-noise](https://github.com/ashima/webgl-noise)

## SceneManage
* [UnityOctree](https://github.com/Nition/UnityOctree)
* [intel_occlusion_cull](https://github.com/rygorous/intel_occlusion_cull)
* [Image-Space-Occlusion-Culling-Engine](https://github.com/lebarba/Image-Space-Occlusion-Culling-Engine) SOCE is an Image Space Occlusion Culling Engine optimized to perform occlusion culling in CPU. If you have a densely occluded scene (e.g. urban, indoor scene) you can use this module in you 3D project to speed up the rendering.
* [Janua](https://github.com/gigc/Janua) Open Source occlusion culling engine for 3D Scenes

## Point Clouds
* [PCL](http://www.pointclouds.org/)

## Mesh
* [assimp](https://github.com/assimp/assimp) A library to import and export various 3d-model-formats
* [OpenSubdiv](https://github.com/PixarAnimationStudios/OpenSubdiv) An Open-Source subdivision surface library. http://graphics.pixar.com/opensubdiv
* [Fast-Quadric-Mesh-Simplification](https://github.com/sp4cerat/Fast-Quadric-Mesh-Simplification) Mesh triangle reduction using quadrics
* [MeshDecimator](https://github.com/Whinarn/MeshDecimator), [UnityMeshSimplifier](https://github.com/Whinarn/UnityMeshSimplifier)
* [meshlab](https://github.com/cnr-isti-vclab/meshlab) MeshLab is mostly based on the mesh processing library VCGlib
* [Mesh-processing-library](https://github.com/Microsoft/Mesh-processing-library) mesh processing techniques in computer graphics published at ACM SIGGRAPH in 1992–1998  
* [libigl](https://github.com/libigl/libigl)
* [DirectXMesh](https://github.com/Microsoft/DirectXMesh)
 
## Platform
* [glfw](https://github.com/glfw/glfw)
* [MoltenVK](https://github.com/KhronosGroup/MoltenVK) Vulkan graphics and compute API, that runs on Apple's Metal graphics framework

## UI
* [imgui](https://github.com/ocornut/imgui)
* [nanovg](https://github.com/memononen/nanovg)
* [nanogui](https://github.com/wjakob/nanogui)
* [nuklear](https://github.com/vurtun/nuklear)
* [unity-vertex-effects](https://github.com/n-yoda/unity-vertex-effects) Beautiful Text Outline for Unity UI

## Util
* [stb](https://github.com/nothings/stb)
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
* [nshader](https://github.com/samizzo/nshader) **Visual Studio 2013/2015/2017 syntax highlighting extension for shader languages**
#### ShaderToy
* [shader-toy](https://github.com/stevensona/shader-toy)
* [ofxShadertoy](https://github.com/tiagosr/ofxShadertoy)
* [ShaderMan](https://github.com/smkplus/ShaderMan)
#### Visual Effects
* [gaffer](https://github.com/GafferHQ/gaffer)
* [cortex](https://github.com/ImageEngine/cortex) Libraries for visual effects software development
#### GPU Debug
* [renderdoc](https://github.com/baldurk/renderdoc)
* [UE4RenderDocPlugin](https://github.com/Temaran/UE4RenderDocPlugin)
* [CodeXL](https://github.com/GPUOpen-Tools) a comprehensive tool suite that enables developers to harness the benefits of CPUs, GPUs and APUs.
* [perfdoc](https://github.com/ARM-software/perfdoc) A cross-platform Vulkan layer which checks Vulkan applications for best practices on Arm Mali devices.
* [gapid](https://github.com/google/gapid)
 
## Sample
### API Samples
* [DirectX-Graphics-Samples](https://github.com/Microsoft/DirectX-Graphics-Samples)
* [directx-sdk-samples](https://github.com/walbourn/directx-sdk-samples)
* [OpenGLInsightsCode](https://github.com/OpenGLInsights/OpenGLInsightsCode)
* [Vulkan](https://github.com/SaschaWillems/Vulkan)
* [vulkan-sdk for android](https://github.com/ARM-software/vulkan-sdk)
* [opengl-es-sdk-for-android](https://github.com/ARM-software/opengl-es-sdk-for-android)
* [IntroductionToVulkan](https://github.com/GameTechDev/IntroductionToVulkan)
* [GraphicsGems](https://github.com/erich666/GraphicsGems)
* [GPUZen](https://github.com/wolfgangfengel/GPUZen)
* [nvpro-samples](https://github.com/nvpro-samples) NVIDIA DesignWorks Samples
### Graphic SDK & Samples
* [GodComplex](https://github.com/Patapom/GodComplex)
* [GPUOpen-LibrariesAndSDKs](https://github.com/GPUOpen-LibrariesAndSDKs)
* [GPUOpen-Effects](https://github.com/GPUOpen-Effects)
* [NVIDIAGameWorks](https://github.com/NVIDIAGameWorks)
* [powervr-graphics](https://github.com/powervr-graphics)
* [directx-sdk-samples](https://github.com/walbourn/directx-sdk-samples)

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
* [GPUSkinning](https://github.com/chengkehan/GPUSkinning)
* [Animation-Texture-Baker](https://github.com/sugi-cho/Animation-Texture-Baker)

## Particle
* [XParticle](https://github.com/antoinefournier/XParticle)

## VR&AR
* [AugmentedUnreality](https://github.com/adynathos/AugmentedUnreality)
* [unrealcv](https://github.com/unrealcv/unrealcv)
