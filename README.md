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
  [OIT](#oit) &nbsp;&nbsp;
  [Effect](#effect) &nbsp;&nbsp; [VFX](#vfx)    
  
>**Emulation**

  [Nature](#nature) &nbsp;&nbsp; [Environment](#environment) &nbsp;&nbsp; [Character](#character)
  
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
* Unity [Unity-Technologies](https://github.com/Unity-Technologies)  &nbsp;&nbsp; [unity3d-jp](https://github.com/unity3d-jp)  &nbsp;&nbsp;  [UnityLabs](https://github.com/UnityLabs)  &nbsp;&nbsp;  [UnityTech](https://github.com/unitytech)
* AMD  [GPUOpen-LibrariesAndSDKs](https://github.com/GPUOpen-LibrariesAndSDKs)  &nbsp;&nbsp; [GPUOpen-Tools](https://github.com/GPUOpen-Tools)  &nbsp;&nbsp;  [GPUOpen-Effects](https://github.com/GPUOpen-Effects)
* NVIDIA [NVIDIAGameWorks](https://github.com/NVIDIAGameWorks)  &nbsp;&nbsp; [nvpro-samples](https://github.com/nvpro-samples)  &nbsp;&nbsp; [NVIDIA](https://github.com/NVIDIA)  &nbsp;&nbsp;  [NVlabs](https://github.com/NVlabs)  
* Intel [Intel GameTechDev](https://github.com/GameTechDev) https://software.intel.com/gamedev
* ARM [ARM-software](https://github.com/ARM-software)
* SideEfects [sideeffects](https://github.com/sideeffects) Hodini
* [id-Software](https://github.com/id-Software)
* [InteractiveComputerGraphics](https://github.com/InteractiveComputerGraphics)

## Engine
* [UnrealEngine](https://github.com/EpicGames/UnrealEngine) :star: https://www.unrealengine.com/
* [CRYENGINE](https://github.com/CRYTEK/CRYENGINE) :star:  https://www.cryengine.com/
* [Lumberyard](https://github.com/aws/lumberyard) https://aws.amazon.com/lumberyard/
* [Urho3D](https://github.com/urho3d/Urho3D) lightweight, cross-platform 2D and 3D game engine,Greatly inspired by OGRE and Horde3D.
* [filament](https://github.com/google/filament):thumbsup: Filament is a physically based rendering engine for Android, Windows, Linux and macOS
* [Falcor](https://github.com/NVIDIAGameWorks/Falcor) Real-Time Rendering Framework, NVIDIA
* [Klayag](https://github.com/gongminmin/KlayGE) A cross-platform open source game engine with plugin-based architecture
* [G3D]( https://casual-effects.com/g3d) Graphics research and rapid prototyping in OpenGL and C++
* [Ogre](https://github.com/ogrecave) ogre github mirror
* [OpenSceneGraph](https://github.com/openscenegraph/OpenSceneGraph)  http://www.openscenegraph.org 
* [WickedEngine](https://github.com/turanszkij/WickedEngine) C++ game engine focusing on modern rendering techniques. With Bullet Physics, Lua scripting, and more.
* [xenko](https://github.com/xenko3d/xenko)  An open-source C# game engine for realistic rendering and VR
* [godot](https://github.com/godotengine/godot) Godot Engine – Multi-platform 2D and 3D game engine https://godotengine.org
* [anki-3d-engine](https://github.com/godlikepanos/anki-3d-engine) AnKi 3D Engine - OGL/Vulkan backends, modern renderer, scripting, physics and more  
* [bgfx](https://github.com/bkaradzic/bgfx) :star: -Cross-platform, graphics API agnostic, "Bring Your Own Engine/Framework" style rendering library 
* [The-Forge](https://github.com/ConfettiFX/The-Forge) The Forge Cross-Platform Rendering Framework PC, macOS / iOS, Android, XBOX, PS4
* [oryol](https://github.com/floooh/oryol) - A small, portable and extensible C++ 3D coding framework
* [bsf](https://github.com/GameFoundry/bsf) Modern C++14 library for the development of real-time graphical applications https://www.bsframework.io
* [DiligentEngine](https://github.com/DiligentGraphics/DiligentEngine) A modern cross-platform low-level 3D graphics library http://diligentgraphics.com/diligent-engine/ 
* [cesium](https://github.com/AnalyticalGraphicsInc/cesium) An open-source JavaScript library for world-class 3D globes and maps 
* [playcanvas](https://github.com/playcanvas/engine)  ast and lightweight WebGL game engine https://playcanvas.com/
#### ForMobile
* [Granite](https://github.com/Themaister/Granite)  personal Vulkan renderer

## Engine Plugin
* [armory](https://github.com/armory3d/armory)  -3D Game Engine for Blender
* [RenderPipeline](https://github.com/tobspr/RenderPipeline) -PBR and Deferred Rendering for the Panda3D game engine 
* [ray-mmd](https://github.com/ray-cast/ray-mmd) physically-based rendering at mikumikudance

## PBR RayTrace
* [embree](https://github.com/embree/embree)  A collection of high-performance ray tracing kernels, developed at Intel.
* [RadeonRays RadeonProRender](https://github.com/GPUOpen-LibrariesAndSDKs) ray intersection acceleration library for hardware and software multiplatforms using CPU and GPU
* [appleseed](https://github.com/appleseedhq/appleseed) A modern open source rendering engine for animation and visual effects https://appleseedhq.net/
* [pbrt](https://github.com/mmp/pbrt-v3) Source code for "Physically Based Rendering: From Theory To Implementation" 
* [mitsuba](https://github.com/mitsuba-renderer/mitsuba) http://mitsuba-renderer.org/
* [LuxCoreRender](https://github.com/LuxCoreRender) https://www.luxcorerender.org
* [ospray](https://github.com/ospray/ospray) A Ray Tracing Based Rendering Engine for High-Fidelity Visualization
* [taichi](https://github.com/yuanming-hu/taichi) Open Source Computer Graphics Library http://taichi.graphics
* [tungsten](https://github.com/tunabrain/tungsten) High performance physically based renderer in C++11
* [nori](https://github.com/wjakob/nori) Nori: an educational ray tracer https://wjakob.github.io/nori
* [nanort](https://github.com/lighttransport/nanort)  single header only modern ray tracing kernel.
* [SORT](https://github.com/JerryCao1985/SORT)  Simple Open-source Ray Tracer https://agraphicsguy.wordpress.com/

## Soft Renderer
* [OpenSWR](http://openswr.org/) A High Performance, Highly Scalable Software Rasterizer for OpenGL
* [miaow](https://github.com/VerticalResearchGroup/miaow) An open source GPU based off of the AMD Southern Islands ISA.
* [tinyrenderer](https://github.com/ssloy/tinyrenderer)  A brief computer graphics / rendering course
* [coco3d](http://coco3d.codeplex.com/) Coco3D is a real-time 3D software renderer for Windows PCs and mobile devices
* [muli3d](https://sourceforge.net/projects/muli3d/)  implements features of current graphics hardware in software. The focus is on ease of use and clear code
* [swiftshader](https://github.com/google/swiftshader) high-performance CPU-based implementation of the OpenGL ES and Direct3D 9 graphics APIs
* [Mesa3D](https://gitlab.freedesktop.org/mesa/mesa) https://www.mesa3d.org
* [SoftwareRenderer](https://github.com/Angelo1211/SoftwareRenderer) Software rendering engine with PBR. Built from scratch on C++.
* [Tyler](https://github.com/NotCamelCase/Tyler) Tile-based SW rasterizer 

## GI
### Collection
* [GITechDemo](https://github.com/iftodebogdan/GITechDemo)  A global illumination technical demo application.
* [dirtchamber](https://github.com/thefranke/dirtchamber) A mixed reality testing environment for real-time global illumination algorithms 
* [Cinder-Experiments](https://github.com/simongeilfus/Cinder-Experiments) A collection of experiments, samples and other bits of code.
* [IlluminationComparison](https://github.com/EKnapik/IlluminationComparison) A comparison of typical illumination methods. (SSAO, HBO, VXGI, and Ray Traced Global Illumination)
* [3D-Graphics-Engine](https://github.com/Gregjksmith/3D-Graphics-Engine) Capable of rendering online and offline global illumination using a number of different methods
* [RTGI](https://github.com/jazzboysc/RTGI)
#### SVO
* [SEGI](https://github.com/sonicether/SEGI) [NKLI](https://github.com/ninlilizi/SEGI)A fully-dynamic voxel-based global illumination system for Unity 
* [VCTRenderer](https://github.com/jose-villegas/VCTRenderer) Deferred Voxel Shading for Real Time Global Illumination
* [voxel-cone-tracing](https://github.com/Friduric/voxel-cone-tracing) A real-time global illumination implementation using voxel cone tracing.
* [VoxelConeTracing](https://github.com/domme/VoxelConeTracing) An implementation of the "Voxel Cone Tracing" global illumination technique proposed by Cyril Crassin
* [VCTGI](https://github.com/rdinse/VCTGI) GPU-based real-time global illumination renderer based on voxel cone tracing
* [Vulkan-VXGI-VR-FrameWork](https://github.com/byumjin/Vulkan-VXGI-VR-FrameWork) University of Pennsylvania, CIS 565: GPU Programming and Architecture, Final Project
* [HarshLight](https://github.com/MangoSister/HarshLight) Real-time global illumination based on voxel cone tracing
* [Voxel_Cone_Tracing](https://github.com/kbladin/Voxel_Cone_Tracing) easy to understand
* [Voxel-Cone-Tracing](https://github.com/Cigg/Voxel-Cone-Tracing) easy to understand
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
#### Deferred Irradiance Volumes
* [webgl-deferred-irradiance-volumes](https://github.com/pyalot/webgl-deferred-irradiance-volumes)  An implementation of deferred irradiance volumes in WebGL
#### Deferred Radiance Transfer Volumes
#### Radiosity
#### Instant Radiosity
* [instant_radiosity](https://github.com/cache-tlb/instant_radiosity)
* [simple-instant-radiosity](https://github.com/githole/simple-instant-radiosity)
* [GIGL](https://github.com/vgfx/GIGL) Tiny Global Illumination OpenGL Renderer
#### Ray tracing
#### Path tracing
* [minpt](https://github.com/hi2p-perim/minpt) A path tracer in 300 lines of C++
* [simple-bidirectional-pathtracer](https://github.com/githole/simple-bidirectional-pathtracer)
* [edubpt](https://github.com/githole/edubpt)
#### Metropolis light transport
#### PhotonMapping
* [CPMFIGIOTVVD](https://github.com/ResearchDaniel/Correlated-Photon-Mapping-for-Interactive-Global-Illumination-of-Time-Varying-Volumetric-Data) Correlated Photon Mapping for Interactive Global Illumination of Time-Varying Volumetric Data by Daniel Jönsson and Anders Ynnerman
* [SOPGI](https://github.com/alexnardini/SOPGI)  A VEX raytracer for SideFX Houdini with photon mapping global illumination and full recursive reflections and refractions
#### Ambient occlusion
* [KinoObscurance](https://github.com/keijiro/KinoObscurance) Alchemy Ambient Obscurance ---AlchemyHPG11
* [ScalableAmbientObscurance](https://research.nvidia.com/publication/scalable-ambient-obscurance) https://research.nvidia.com/publication/scalable-ambient-obscurance
* [ASSAO](https://github.com/GameTechDev/ASSAO) Adaptive Screen Space Ambient Occlusion
* [Robust Screen Space Ambient Occlusion](https://github.com/wolfgangfengel/GPUZen/tree/master/04_Screen%20Space/) Robust Screen Space Ambient Occlusion
* [HBAOPlus](https://github.com/NVIDIAGameWorks/HBAOPlus) HBAO+ is a SSAO algorithm designed to achieve high efficiency on DX11 GPUs. 
* [gl_ssao](https://github.com/nvpro-samples/gl_ssao) optimized screen-space ambient occlusion, cache-aware hbao  
* [VXAO](https://developer.nvidia.com/vxao-voxel-ambient-occlusion) Voxel Ambient Occlusion
* [MiniEngineAO](https://github.com/keijiro/MiniEngineAO) SSAO image effect from Microsoft MiniEngine, ported to Unity.
* [NNAO](https://github.com/simeonradivoev/NNAO) Neural Network Ambien Occlusion
* [dssdo](https://github.com/kayru/dssdo) Deferred Screen Space Directional Occlusion http://kayru.org/articles/dssdo/
* [ssgi](https://github.com/jdupuy/ssgi) Screen space global illumination demo: SSAO vs SSDO
* [Unity-Ground-Truth-Ambient-Occlusion](https://github.com/MaxwellGengYF/Unity-Ground-Truth-Ambient-Occlusion) A physically based screen space ambient occulsion post processing effect  
* [Unity-GeoAO](https://github.com/nezix/Unity-GeoAO) Fast ambien occlusion in Unity at runtime
* [ConeSphereOcclusionLUT](https://github.com/knarkowicz/ConeSphereOcclusionLUT) ConeSphereOcclusionLUT generates a cone sphere occlusion LUT to be used with TLoU style **capsule AO shadows**. For details "Lighting Technology Of "The Last Of Us".
#### Bent Normal
* [ssbn](https://github.com/KageKirin/ssbn) Screen Space Bent Normals
#### Radiosity Normal Mapping
* [GzRNM](https://github.com/Geenz/GzRNM) brings Radiosity Normal Mapping/Directional Light Mapping to Unity 3D!
* [SSbumpGenerator](https://sourceforge.net/projects/ssbumpgenerator/) A GUI interface to a tool for generating SSBumps (Self Shadowed Bump Maps).
#### LightMap
* [lightmapper](https://github.com/ands/lightmapper) A C/C++ single-file library for drop-in lightmap baking. Just use your existing OpenGL renderer to bounce light!
* [seamoptimizer](https://github.com/ands/seamoptimizer) A C/C++ single-file library that minimizes the hard transition errors of disjoint edges in lightmaps.
* [BakingLab](https://github.com/TheRealMJP/BakingLab) A D3D11 application for experimenting with Spherical Gaussian lightmaps
* [GPULightmass](https://github.com/AlanIWBFT/GPULightmass) Luoshuang's GPULightmass for UE4
* [trianglepacker](https://github.com/ray-cast/trianglepacker) Triangle packer for light map
#### Light Field
* [temporal-lightfield-reconstruction](https://github.com/jiawen/temporal-lightfield-reconstruction)   mplementation of "Temporal Light Field Reconstruction for Rendering Distribution Effects" (SIGGRAPH 2011)
* [indirect-light-field-reconstruction](https://github.com/jtlehtin/indirect-light-field-reconstruction)  mplementation of "Reconstructing the Indirect Light Field for Global Illumination" (SIGGRAPH 2012)  

### GI Simulation
#### Diffuse inter-reflection
#### Caustic
* [SC_Tracer](https://github.com/ningfengh/SC_Tracer) photon mapping for global illumination and caustic
#### Reflection
* [ComputeStochasticReflections](https://github.com/simeonradivoev/ComputeStochasticReflections) Compute Stochastic Screen Space Reflections for unity post processing  
* [kode80SSR](https://github.com/kode80/kode80SSR) An open source screen space reflections implementation for Unity3D 5.  
* [StochasticScreenSpaceReflection](https://github.com/cCharkes/StochasticScreenSpaceReflection)
* [Unity-Screen-Space-Reflection](https://github.com/MaxwellGengYF/Unity-Screen-Space-Reflection) Clearly Screen Space Reflection
* [UnitySSR](https://github.com/Xerxes1138/UnitySSR) Open source screen space reflection for Unity 5
* [synthese_image](https://github.com/theFrenchDutch/synthese_image) author's [blog](http://thomasdeliot.wixsite.com/blog/single-post/2018/04/26/Small-project-OpenGL-engine-and-PBR-deferred-pipeline-with-SSRSSAO)
* [Jin-Engine-2.1](https://github.com/byumjin/Jin-Engine-2.1) The implementation of Pixel-projected Screen Space Reflections 
#### Refraction
#### Shadow
* [Shadows](https://github.com/TheRealMJP/Shadows) A sample app that demonstrates several techniques for rendering real-time shadow maps
* [UnityPCSS](https://github.com/TheMasonX/UnityPCSS) Nvidia's PCSS soft shadow algorithm implemented in Unity
* [ContactShadows](https://github.com/keijiro/ContactShadows) Experimental implementation of contact shadows for Unity.
* [HFTS](https://developer.nvidia.com/Hybrid-Frustum-Traced-Shadows) NVIDIA Hybrid Frustum Traced Shadows in NVIDIA ShadowLib.
* [ShadowFX](https://github.com/GPUOpen-Effects/ShadowFX) DirectX 11 and 12 library that provides a scalable and GCN-optimized solution for deferred shadow filtering 
* [ofxShadowMap](https://github.com/arturoc/ofxShadowMap) Shadow map using PCF or gaussian disk sampling for soft borders
* [of-ESMShadowMapping](https://github.com/jacres/of-ESMShadowMapping) Exponential Shadow Mapping in openFrameworks
* [RayTracedShadows](https://github.com/kayru/RayTracedShadows) This demo implements BVH construction and GPU traversal for rendering hard shadows.
* [ShadowVolume](https://github.com/chengkehan/ShadowVolume) Shadow Volume for Static-Scene-Object of Unity
* [variance_shadow_mapping_vk](https://github.com/sydneyzh/variance_shadow_mapping_vk) Variance shadow mapping for omni lights with Vulkan
* [Precomputed-Shadow-Fields-for-Dynamic-Scenes](https://github.com/nblintao/Precomputed-Shadow-Fields-for-Dynamic-Scenes) A realization of computing soft shadow by shadow fields
* [many-lights-gi](https://github.com/karyon/many-lights-gi) Real-time global illumination following the many-lights approach and using Imperfect Shadow Maps
* [voxelized-shadows-improved](https://github.com/loinesg/voxelized-shadows-improved) Construction and sampling of precomputed shadows in a compressed voxel octree

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
* [Phone-wire AA](http://www.humus.name/index.php?page=3D&ID=89)
#### Denoising 
* [oidn](https://github.com/OpenImageDenoise/oidn) Intel(R) Open Image Denoise library http://www.openimagedenoise.org/
* [practicalDenoising](https://github.com/ImageEngine/practicalDenoising) Reference Implementation of Practical Denoising for VFX Production Using Temporal Blur
* [bcd](https://github.com/superboubek/bcd) Bayesian Collaborative Denoiser for Monte-Carlo Rendering
* [glslSmartDeNoise](https://github.com/BrutPitt/glslSmartDeNoise) :thumbsup: Fast glsl spatial deNoise filter
#### Bloom
* [HexBokehBlur](https://github.com/zigguratvertigo/HexBokehBlur)
* [SE-Natural-Bloom-Dirty-Lens](https://github.com/sonicether/SE-Natural-Bloom-Dirty-Lens) (Legacy) post-processing effect for Unity.
* [hdreffects](https://github.com/karimnaaji/hdreffects)
#### Tone Mapping
* [tonemapper](https://github.com/tizian/tonemapper)
* [aces-dev](https://github.com/ampas/aces-dev)  AMPAS Academy Color Encoding System Developer Resources http://www.oscars.org/aces
#### DOF
* [VVDoFDemo](http://graphics.cs.williams.edu/papers/DepthOfFieldGPUPro2013/VVDoFDemo.zip)
#### Lens
* [PhysicallyBasedLensFlare](https://github.com/greje656/PhysicallyBasedLensFlare)
* [LightLeaksUnity](https://github.com/danielzeller/LightLeaksUnity)
#### Other
* [UnityScreenSpaceBoolean](https://github.com/hecomi/UnityScreenSpaceBoolean)
* [OffScreenParticleRendering](https://github.com/slipster216/OffScreenParticleRendering)

## Character
#### Skin
* [pbrt-skin-bssrdf](https://github.com/damlaren/pbrt-skin-bssrdf) Implementation of Donner & Jensen's "A Spectral BSSRDF for Shading Human Skin" in PBRT
* [CP_SSSSS](https://github.com/CustomPhase/CP_SSSSS) Naive screen-space subsurface scattering solution for Unity 5.
* [separable-sss](https://github.com/iryoku/separable-sss) iryoku's SSSSS
* [skin-shader-unity](https://github.com/leonardo-domingues/skin-shader-unity) GPU Gems 3 - Chapter 14 using the Unity engine
* [Unity-Human-Skin-Shader-PC](https://github.com/MaxwellGengYF/Unity-Human-Skin-Shader-PC)
* [SubsurfaceScattering](https://github.com/vcrom/SubsurfaceScattering) An implementation of a set screen space physically-based subsurface scattering algorithms
* [FaceWorks](https://github.com/NVIDIAGameWorks/FaceWorks) A middleware library and sample application for high-quality skin and eye rendering
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
* [UnityFurShader](https://github.com/Sorumi/UnityFurShader)  Fur shader for Unity.
* [GIFT_PorterDoll](https://github.com/marza-realtime/GIFT_PorterDoll) PorterDoll Asset wtih "THE GIFT"

## Nature
#### Water
* [Ceto](https://github.com/Scrawk/Ceto) :thumbsup: Ceto: Ocean system for Unity  
* [WaterSurfaceWavelets](https://github.com/lecopivo/WaterSurfaceWavelets) Water Surface Wavelets (SIGGRAPH 2018) http://visualcomputing.ist.ac.at/publications/2018/WSW/
* [VaOcean](https://github.com/ufna/VaOcean) Ocean Surface Simulation Plugin for Unreal Engine 4
* [OceanProject](https://github.com/UE4-OceanProject/OceanProject) An Ocean Simulation project for Unreal Engine 4
* [Ocean Community Next Gen](https://github.com/eliasts/Ocean_Community_Next_Gen) Next gen iteration of the unity community ocean shader
* [crest-oceanrender](https://github.com/huwb/crest-oceanrender) Crest is a technically advanced ocean renderer implemented in Unity3D
* [whitecaps](https://github.com/jdupuy/whitecaps)  Real-time Animation and Rendering of Ocean Whitecaps
* [BoatAttack](https://github.com/Verasl/BoatAttack) com.verasl.water-system Gerstner waves water.
* [Ocean_mobile_with_boat_physic](https://github.com/laurentClave/Ocean_mobile_with_boat_physic) Ocean mobile with boat physic controller
* [Unity-WaterBuoyancy](https://github.com/dbrizov/Unity-WaterBuoyancy) Water Buoyancy Simulation for Unity
* [RealtimeWater](https://github.com/hpatjens/RealtimeWater) implemented based on "Fast Water Simulation for Games Using Height Fields".
* [fft-ocean](https://github.com/jbouny/fft-ocean) WebGL FFT (Fast Fourier transform) ocean rendering for Three.js 
* [GX-EncinoWaves](https://github.com/speps/GX-EncinoWaves) "Empirical Directional Wave Spectra for Computer Graphics"
* [UnityWaveEquation](https://github.com/AsehesL/UnityWaveEquation)
* [water-wave-packets](https://github.com/jeschke/water-wave-packets) Sandbox binary and source code for the Siggraph 2017 paper "Water Wave Packets" by Stefan Jeschke (NVIDIA) and Chris Wojtan (IST Austria)

* Jerry Tessendorf's paper "Simulating Ocean Water".  
[fftocean](https://github.com/deiss/fftocean)  [ocean-simulation](https://github.com/klantz81/ocean-simulation)  [Phillips-Ocean](https://github.com/Scrawk/Phillips-Ocean)
* Eric.Bruneton's paper "an improved version using an FFT method to synthesize the surface."
[Eric.Bruneton](http://evasion.inrialpes.fr/~Eric.Bruneton/)  [Brunetons-Ocean](https://github.com/Scrawk/Brunetons-Ocean)
#### Snow
* [Unity-IndentShader](https://github.com/wacki/Unity-IndentShader) http://wacki.me/blog/2017/01/dynamic-snow-sand-shader-for-unity/
* [SnowDeformation](https://github.com/vanish87/SnowDeformation) To create a snow accumulation and deformation effect along with physical based rendering
* [UnrealSnow](https://github.com/bneukom/UnrealSnow) Unreal Engine snow simulation for large terrains using Compute Shaders for GPU paralellization.
* [DeepSnowFootprint](https://github.com/ZGeng/DeepSnowFootprint) A unity shader solution to generate footprint on thick snow surfaces.
* [unity-deformablesnow](https://github.com/thnewlands/unity-deformablesnow) Repository for online PIGSquad workshop on deformable snow in Unity.
* [SnowSimulation](https://github.com/hubi037/SnowSimulation) GPU Snow Simulation for Unity and Direct3D 
* [snow](https://github.com/Azmisov/snow)  "A Material Point Method for Snow Simulation" (Stomakhin et al., 2013).
* [SnowSimulation](https://github.com/TheBeach54/SnowSimulation)
#### Sand
* [JourneySand](https://github.com/AtwoodDeng/JourneySand) An Unity project to reproduce the sand rendering in Journey's style
#### Grass
* [KvantGrass](https://github.com/keijiro/KvantGrass) Animating grass shader for Unity
* [UnityGrassGeometryShader](https://github.com/IronWarrior/UnityGrassGeometryShader) https://roystan.net/articles/grass-shader.html
* [Grass.DirectX](https://github.com/mreinfurt/Grass.DirectX) Realistic Grass Rendering using DirectX 11 and a geometry-shader based approach.
* [VulkanGrassRendering](https://github.com/moneimne/VulkanGrassRendering) Vulkan implementation of "Responsive Real-Time Grass Rendering for General 3D Scenes" by Jahrmann and Wimmer
* [Project6-Vulkan-Grass-Rendering](https://github.com/CIS565-Fall-2017/Project6-Vulkan-Grass-Rendering)
* [GooHairGrass](https://github.com/cabbibo/GooHairGrass)
* [GPUGrass](https://github.com/MidoriMeng/GPUGrass) real-time grass rendering based on GPU instancing
#### Tree
* [Vulkan-Forest-Rendering-Engine](https://github.com/Jiaww/Vulkan-Forest-Rendering-Engine)
#### Terrain
* [Terrain-Topology-Algorithms](https://github.com/Scrawk/Terrain-Topology-Algorithms) Terrain topology algorithms in Unity
* [tin-terrain](https://github.com/heremaps/tin-terrain) A command-line tool for converting heightmaps in GeoTIFF format into tiled optimized meshes.
#### Cloud
* [volsample](https://github.com/huwb/volsample) Research on sampling methods for real-time volume rendering
* [kode80CloudsUnity3D](https://github.com/kode80/kode80CloudsUnity3D) A realtime volumetric cloud rendering solution for Unity3D. 
* [VolumeCloud](https://github.com/yangrc1234/VolumeCloud) Volume cloud for Unity3D
* [Raymarch-Clouds](https://github.com/Flafla2/Raymarch-Clouds)
* [clouds](https://github.com/greje656/clouds) Volumetric Clouds plugin for Stingray
* [Marshmallow](https://github.com/mccannd/Project-Marshmallow) Vulkan-based implementation of clouds from Decima Engine
* [Meteoros](https://github.com/Aman-Sachan-asach/Meteoros) Real-time Cloudscape Rendering in Vulkan based on the implementation of clouds in the Decima Engine.
* [Mesh-Cloud-Rendering](https://github.com/maajor/Mesh-Cloud-Rendering) Reimplement Sea of Thieves's Cloud in Unity 
#### Sky
* [SkyboxPanoramicShader](https://github.com/Unity-Technologies/SkyboxPanoramicShader)
* [CSky-Dynamic-Sky-Unity](https://github.com/bmjoy/CSky-Dynamic-Sky-Unity)  Dynamic Sky Sphere System for Unity 3d.
* [GenUtahSky](https://github.com/markstock/GenUtahSky) Radiance implementation of Preetham, Shirley, Smits model for sky color, plus more  
* [SkyModels](https://github.com/diharaw/SkyModels) A collection of various Sky Models implemented with OpenGL compute shaders suitable for real-time rendering.
#### Rain
* [RainDropEffect](https://github.com/EdoFrank/RainDropEffect) Rain Drop Effect2: Effective, Fast and Flexible Rain Distortion Effect for Unity
* [LensRain](https://github.com/Kink3d/LensRain) A screen-space lens rain effect using Unity's V2 Post-processing framework.
* [RainFX](https://github.com/smkplus/RainFX) Natural Rain
#### Fire
* [fire](https://github.com/robertcupisz/fire) A fire effect for Unity.
#### Ice
#### Iridescent
* [Iridescence](https://github.com/Xerxes1138/Iridescence)
* [Iridescent Shader](https://github.com/smkplus/Iridescence) Iridescence shader
#### Glass
* [unity-frosted-glass](https://github.com/andydbc/unity-frosted-glass) Test of a frosted glass material in Unity.

## Environment
#### VolumetricLight
* [VolumetricLights](https://github.com/SlightlyMad/VolumetricLights) Volumetric Lights for Unity
* [LightShafts](https://github.com/robertcupisz/LightShafts) A light shafts (volumetric shadows) effect for Unity.
* [OutdoorLightScattering](https://github.com/GameTechDev/OutdoorLightScattering) Outdoor Light Scattering Sample
* [VolumetricLighting](https://github.com/NVIDIAGameWorks/VolumetricLighting) NVIDIA Gameworks Volumetric Lighting
* [VolumetricLighting](https://github.com/Unity-Technologies/VolumetricLighting) ighting effects implemented for the Adam demo: volumetric fog, area lights and tube lights
* [Aura](https://github.com/raphael-ernaelsten/Aura) Volumetric Lighting for Unity
* [Vapor](https://github.com/ArthurBrussee/Vapor) Volumetric Fog for Unity
#### Atmospheric
* [AtmosphericScattering](https://github.com/SlightlyMad/AtmosphericScattering) Atmospheric Scattering for Unity
* [Scatterer](https://github.com/LGhassen/Scatterer) Atmospheric scattering mod for KSP 
* [precomputed_atmospheric_scattering](https://github.com/ebruneton/precomputed_atmospheric_scattering) Eric Bruneton, 2017
* [Brunetons-Improved-Atmospheric-Scattering](https://github.com/Scrawk/Brunetons-Improved-Atmospheric-Scattering) Eric Bruneton for Unity, 2017
* [glsl-atmosphere](https://github.com/wwwtyro/glsl-atmosphere) Renders sky colors with Rayleigh and Mie scattering.
#### Fog
* [unity-volumetric-fo](https://github.com/SiiMeR/unity-volumetric-fog)
* [UEShaderBits-GDC-Pack](https://github.com/sp0lsh/UEShaderBits-GDC-Pack)  UE4 Volumetric Fog Techniques
## Render Path
* [VolumeTiledForwardShading](https://github.com/jpvanoosten/VolumeTiledForwardShading) :thumbsup: Volume Tiled Forward Shading. This technique is based on Tiled and Clustered Forward Shading (Olsson, 2012)
* [HybridRenderingEngine](https://github.com/Angelo1211/HybridRenderingEngine) Clustered Forward/Deferred renderer with Physically Based Shading, Image Based Lighting and a whole lot of OpenGL.  
* [ClusteredShadingAndroid](https://github.com/GameTechDev/ClusteredShadingAndroid) and [IntelForwardClusteredShading](https://software.intel.com/en-us/articles/forward-clustered-shading) Clustered shading on Android sample  
* [clustered_forward_demo](https://gitlab.com/efficient_shading/clustered_forward_demo) Ola Olsson. 
* [clustered_forward_demo_vk](https://github.com/sydneyzh/clustered_forward_demo_vk)  Clustered forward rendering demo with Vulkan
* [ClusteredShadingConservative](https://github.com/kevinortegren/ClusteredShadingConservative) DirectX 12 light culling technique featured in GPU Pro 7  
* [lightindexed-deferredrender](https://github.com/dtrebilco/lightindexed-deferredrender) Light Indexed Deferred Rendering - Before there was Forward+ and Clustered deferred rendering there was Light Indexed Deferred Rendering (ShaderX7)  
* [Vulkan-Forward-Plus-Renderer](https://github.com/WindyDarian/Vulkan-Forward-Plus-Renderer) Forward+ renderer in Vulkan using Compute Shader. An Upenn CIS565 final project. 
* [cute-deferred-shading](https://github.com/Erkaman/cute-deferred-shading) Cute little deferred shading implementation.
* [nTiled](https://github.com/BeardedPlatypus/nTiled) nTiled - forward and deferred openGL renderer with support for Tiled Shading, Clustered Shading and Hashed Shading
* [DeferredTexturing](https://github.com/TheRealMJP/DeferredTexturing) A rendering sample that demonstrates bindless deferred texturing using D3D12

## Physically Based Rendering
#### Camera
* [Physical-Camera](https://github.com/Unity-Technologies/Physical-Camera)
* [pbc](https://github.com/kiwaiii/pbc)
* [Cat-Physically-Based-Camera](https://github.com/JoachimCoenen/Cat-Physically-Based-Camera)
#### File Format
* [OpenShadingLanguage](https://github.com/imageworks/OpenShadingLanguage) Advanced shading language for production GI renderers
* [glTF-SDK](https://github.com/Microsoft/glTF-SDK) glTF-SDK is a Software Development Kit for glTF (GL Transmission Format -https://github.com/KhronosGroup/glTF).  
* [USD](https://github.com/PixarAnimationStudios/USD) Universal Scene Description http://www.openusd.org

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
* [MultipassTranslucency](https://github.com/Philipp-Seifried/MultipassTranslucency) fake subsurface-scattering shader, using multiple passes with different blend ops to calculate thickness without reading back the depth buffer.
#### IBL
* [IBLBaker](https://github.com/derkreature/IBLBaker)  Light probe generation and BRDF authoring for physically based shading.
* [cmftStudio](https://github.com/dariomanesku/cmftStudio)  cross-platform open-source cubemap filtering tool.
* [Probulator](https://github.com/kayru/Probulator) Experimentation framework for probe-based lighting
* [PBR](https://github.com/Nadrin/PBR) An implementation of physically based shading model & image based lighting in various graphics APIs.
* [IBLGGX](https://github.com/tuccio/IBLGGX) Sample implementation of UE4/Frostbite image based lighting method based on GGX convolution of HDR environment maps.
* [IntegrateDFG](https://github.com/knarkowicz/IntegrateDFG) DFG LUT generator
* [hyper3d-envmapgen](https://github.com/Hyper3D/hyper3d-envmapgen) Pre-filtered mipmapped radiance environment map generator that runs on WebAssembly.
#### AreaLight
* [LTC_BRDF_Fit](https://github.com/EvgeniiG/LTC_BRDF_Fit)  BRDF fitting code for LTC Area Lights by Heitz et al.
* [ltc_code](https://github.com/selfshadow/ltc_code) Code for "Real-Time Polygonal-Light Shading with Linearly Transformed Cosines"

## Stylize
#### NPR
* [NPR_Lab](https://github.com/candycat1992/NPR_Lab)
* [MNPR](https://github.com/semontesdeoca/MNPR) An expressive non-photorealistic rendering framework for real-time, filter-based stylization pipelines within Maya. http://mnpr.artineering.io     
* [Wind-Waker-Shader](https://github.com/albertomelladoc/Wind-Waker-Shader) Cel Shading of two thresholds with a blur/gradient between them
* [ToonShading](https://github.com/Kink3d/ToonShading) A collection of "Toon" shaders for Unity based on a stepped PBR approximation.
* [kamakura-shaders](https://github.com/kayac/kamakura-shaders) NPR for Unity with a bunch of features and adjustable parameters in a user-friendly interface.
* [UnityNPR](https://github.com/GlitchEnzo/UnityNPR)
* [NPR](https://github.com/laundsallyn/NPR) CS 354 Computer Graphics final project
* [ChinesePaintingDemo](https://github.com/AtwoodDeng/ChinesePaintingDemo) Demo of Chinese Painting Shader
* [UnityChanToonShaderVer2_Project](https://github.com/unity3d-jp/UnityChanToonShaderVer2_Project) UnityChanToonShaderVer2 Project / v.2.0.7 Release 
* [MToon](https://github.com/Santarh/MToon) Toon Shader with Unity Global Illumination
* [PoiyomiToonShader](https://github.com/poiyomi/PoiyomiToonShader) A feature rich toon shader for unity and VR Chat
#### Low Poly
* [LowpolyOcean](https://github.com/JiongXiaGu/LowpolyOcean) low polygon water effect working in Unity
* [Lowpoly-Water-Unity](https://github.com/danielzeller/Lowpoly-Water-Unity) Low poly water with edge/shore blend. Similar to the awesome water in Monument Valley.  
* [FlatShader](https://github.com/cjurjiu/FlatShader) A very simple shader which performs flatshading without the need for duplicating vertices when building the geometry.
#### Voxel
* [UE4VoxelTerrain](https://github.com/bw2012/UE4VoxelTerrain) Unreal Engine 4: Smooth voxel terrian 
* [VoxelPlugin](https://github.com/Phyronnaz/VoxelPlugin) Voxel plugin for Unreal Engine
* [voxelizer](https://github.com/karimnaaji/voxelizer)  Header only mesh voxelizer in c99 
* [gpu-physics-unity](https://github.com/jknightdoeswork/gpu-physics-unity)  A GPU Accelerated Voxel Physics Solver for Unity
* [Field3D](https://github.com/imageworks/Field3D) A library for storing voxel data on disk and in memory.  
* [magicavoxel-shaders](https://github.com/lachlanmcdonald/magicavoxel-shaders) Shaders for MagicaVoxel to simplify common and repetitive tasks.  
* [UnityVOXFileImport](https://github.com/ray-cast/UnityVOXFileImport) A tool to import a .vox file for Unity's GameObject and Prefab

## Volume Rendering
#### RayMarch
* [Texture3DPreview-for-Unity](https://github.com/raphael-ernaelsten/Texture3DPreview-for-Unity) This package enables interactive previews of Texture3D assets in Unity's Inspector window. 
* [unity-volume-rendering](https://github.com/mattatz/unity-volume-rendering) Volume rendering by object space raymarching for Unity. 
* [uRaymarching](https://github.com/hecomi/uRaymarching)  Raymarching Shader Generator in Unity  
* [unity-ray-marching](https://github.com/brianasu/unity-ray-marching)  Ray marching for rendering 3D noise and textures in Unity 3D
* [SpaceWarp](https://github.com/mzandvliet/SpaceWarp)  Playing with DistanceField Raymarching as Post Effect in Unity3d
* [UE4_VolumeRaymarching](https://github.com/TheHugeManatee/UE4_VolumeRaymarching) Plugin for UE4 to perform volume raycasting
#### Point Clouds
* [PCL](http://www.pointclouds.org/)  A standalone, large scale, open project for 2D/3D image and point cloud processing.
* [Pcx](https://github.com/keijiro/Pcx) Point cloud importer & renderer for Unity
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
* [rasterizer](https://github.com/rawrunprotected/rasterizer) This project is a state-of-the-art software occlusion culling system.
* [IndirectOcclusionCulling](https://github.com/JJoosten/IndirectOcclusionCulling)
* [vigilant-system](https://github.com/nlguillemot/vigilant-system)
#### Hardware Occlusion Queries
#### Hierarchical-Z Buffer
* [Hierarchical-Z-Buffer](https://github.com/nickdarnell/Hierarchical-Z-Buffer)
#### Hierarchical Occlusion Map
#### GPU-Driven
* [Indirect-Rendering-With-Compute-Shaders](https://github.com/ellioman/Indirect-Rendering-With-Compute-Shaders) Compute shader: Frustum culling,Occlusion culling with HierarchicalZBuffer
#### Imposter
* [IMP](https://github.com/xraxra/IMP) billboard imposter baking for Unity
* [ImpostorBaker](https://github.com/ictusbrucks/ImpostorBaker) UE4 Plugin for generating Impostors for static meshes  
#### LOD
#### HLOD

## SceneManage
* [UnityOctree](https://github.com/Nition/UnityOctree) A dynamic, loose octree implementation for Unity written in C#
* [KdTree](https://github.com/codeandcats/KdTree) A fast, generic, multi-dimensional Binary Search Tree written in C#
* [aabo](https://github.com/bryanmcnett/aabo) Axis Aligned Bounding Octahedron
* [bhh](https://github.com/bryanmcnett/bhh) Bounding Halfspace Hierarchy
* [Fast-BVH](https://github.com/brandonpelfrey/Fast-BVH) A Simple, Optimized Bounding Volume Hierarchy for Ray/Object Intersection Testing
* [bvh](https://github.com/shinjiogaki/bvh)

## SDF
* [Discregrid](https://github.com/InteractiveComputerGraphics/Discregrid) A static C++ library for the generation of discrete functions on a box-shaped domain. This is especially suited for the generation of signed distance fields.
* [MeshToSDF](https://github.com/aman-tiwari/MeshToSDF) Convert a mesh to an SDF for the Visual Effect Graph (Unity) in realtime
* [msdfgen](https://github.com/Chlumsky/msdfgen) Multi-channel signed distance field generator
* [Typogenic](https://github.com/Chman/Typogenic) Signed-distance field text rendering for Unity
* [SDF](https://github.com/memononen/SDF) Signed Distance Field Builder for Contour Texturing
* [SDFGen](https://github.com/christopherbatty/SDFGen) A simple commandline utility to generate grid-based signed distance field (level set) generator from triangle meshes
* [DeepSDF](https://github.com/facebookresearch/DeepSDF) Learning Continuous Signed Distance Functions for Shape Representation
* [sdfu](https://github.com/termhn/sdfu) Signed Distance Field Utilities https://crates.io/crates/sdfu

## OIT
* [Order-Independent-Trasparency](https://github.com/PixelClear/Order-Independent-Trasparency)
* [OIT_Lab](https://github.com/candycat1992/OIT_Lab)
* [oitDemo](https://github.com/turol/oitDemo) Order Independent Transparency In OpenGL 4.x
Other.....
* [TLVulkanRenderer](https://github.com/trungtle/TLVulkanRenderer)  Vulkan-based renderer on real-time transparency
* [PreMulAlpha](https://github.com/dtrebilco/PreMulAlpha)  Pre-Multiplied blend mode  

## Math
* [Eigen](https://github.com/eigenteam/eigen-git-mirror) :star: linear algebra: matrices, vectors, numerical solvers, and related algorithms. [Eigen](http://eigen.tuxfamily.org/)
* [MathGeoLib](https://github.com/juj/MathGeoLib) A C++ library for linear algebra and geometry manipulation for computer graphics
* [glm](https://github.com/g-truc/glm) OpenGL Mathematics (GLM) https://glm.g-truc.net
* [CGAL](https://github.com/CGAL/cgal) geometric algorithms in the form of a C++ library.
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
#### Computer Vision
* [OpenCV](https://github.com/opencv/opencv) Open Source Computer Vision Library. C# Wrapper [opencvsharp](https://github.com/shimat/opencvsharp)
#### Image
* [bimg](https://github.com/bkaradzic/bimg) :thumbsup:  Image library.
* [OpenImageIO](https://github.com/OpenImageIO/oiio) OpenImageIO http://www.openimageio.org
* [ImageSharp](https://github.com/SixLabors/ImageSharp) A cross-platform library for the processing of image files; written in C#
* [ImageMagick](https://github.com/ImageMagick/ImageMagick) create, edit, compose, or convert bitmap images. It can read and write images in a variety of formats (over 200) 
* [Dithering-Unity3d](https://github.com/mcraiha/Dithering-Unity3d)  Dithering algorithms for Unity3d

#### VectorGraphics
* [vg-renderer](https://github.com/jdryg/vg-renderer)  A vector graphics renderer for bgfx, based on ideas from NanoVG and ImDrawList (Dear ImGUI)

#### TextureCompressed
* [nv_dds](https://github.com/paroj/nv_dds) DDS image loader for OpenGL/ OpenGL ES2 http://paroj.github.io/nv_dds/
* [nvidia-texture-tools](https://github.com/castano/nvidia-texture-tools) Texture processing tools with support for Direct3D 10 and 11 formats. 
* [crunch](https://github.com/BinomialLLC/crunch)  Advanced DXTc texture compression and transcoding library http://binomial.info
* [unity-ycca-subsampling](https://github.com/n-yoda/unity-ycca-subsampling) [ChromaPack](https://github.com/keijiro/ChromaPack)   YCCA chroma subsampling technique
* [basis_universal](https://github.com/BinomialLLC/basis_universal)  :star:  Basis Universal GPU Texture and Texture Video Compression Codec

#### Color
* [OpenColorIO](https://github.com/imageworks/OpenColorIO) A color management framework for visual effects and animation http://opencolorio.org
* [GLSL-Color-Spaces](https://github.com/tobspr/GLSL-Color-Spaces) Utility functions to convert between various color spaces in GLSL
* [colour](https://github.com/colour-science/colour) Colour Science for Python https://www.colour-science.org
* [color](https://github.com/dmilos/color) ++ library thats implemets class color. Available models: RGB, HSL, HSV, CMY, CMYK, YIQ, YUV and growing.  
* [colormap-shaders](https://github.com/kbinani/colormap-shaders) A collection of shaders to draw color maps.

## Noise
* [TileableVolumeNoise](https://github.com/sebh/TileableVolumeNoise)
* [FastNoise](https://github.com/Auburns/FastNoise)
* [Turbulence-Library](https://github.com/jesta88/Turbulence-Library)
* [GPU-Noise-Lib](https://github.com/BrianSharpe/GPU-Noise-Lib)
* [webgl-noise](https://github.com/ashima/webgl-noise)
* [VisualNoiseDesigner](https://github.com/x0r04rg/VisualNoiseDesigner)

## Mesh
#### IO
* [assimp](https://github.com/assimp/assimp) A library to import and export various 3d-model-formats   
* [open3mod](https://github.com/acgessler/open3mod) Open 3D Model Viewer - A quick and powerful 3D model viewer  
* [DirectXMesh](https://github.com/Microsoft/DirectXMesh)   
* [OpenFBX](https://github.com/nem0/OpenFBX) Lightweight open source FBX importer
#### Subdivision
* [OpenSubdiv](https://github.com/PixarAnimationStudios/OpenSubdiv) An Open-Source subdivision surface library. http://graphics.pixar.com/opensubdiv
#### Simplification
* [Fast-Quadric-Mesh-Simplification](https://github.com/sp4cerat/Fast-Quadric-Mesh-Simplification) Mesh triangle reduction using quadrics
* [UnityMeshSimplifier](https://github.com/Whinarn/UnityMeshSimplifier) Mesh simplification for Unity.  
* [simplify](https://github.com/fogleman/simplify) Implementation of Surface Simplification Using Quadric Error Metrics, SIGGRAPH 97, written in Go.
* [SeamAwareDecimater](https://github.com/songrun/SeamAwareDecimater) Mesh simplification with UV's boundary preserved
#### Deform  
* [Deform](https://github.com/keenanwoodall/Deform) A framework for deforming meshes in the editor and at runtime in Unity.
#### Destruction Slicer
* [unity-delaunay](https://github.com/OskarSigvardsson/unity-delaunay) A Delaunay/Voronoi library for Unity, and a simple destruction effect
* [unity-destruction](https://github.com/williambl/unity-destruction) An open-source script to destroy objects realistically in Unity3D.
* [ezy-slice](https://github.com/DavidArayan/ezy-slice) An open source mesh slicer framework for Unity3D Game Engine. Written in C#.
#### Modeling
* [meshlab](https://github.com/cnr-isti-vclab/meshlab) MeshLab is mostly based on the mesh processing library VCGlib
* [Mesh-processing-library](https://github.com/Microsoft/Mesh-processing-library) mesh processing techniques in computer graphics published at ACM SIGGRAPH in 1992–1998   
* [PyMesh](https://github.com/qnzhou/PyMesh) a rapid prototyping platform focused on geometry processing https://pymesh.readthedocs.io
* [poly2tri](https://github.com/greenm01/poly2tri) Fast and Robust Simple Polygon Triangulation With/Without Holes   
* [libigl](https://github.com/libigl/libigl) Simple C++ geometry processing library. 
* [instant-meshes](https://github.com/wjakob/instant-meshes)  Interactive field-aligned mesh generator  
* [openmesh](https://www.openmesh.org/) A generic and efficient polygon mesh data structure  
* [openflipper](https://www.openflipper.org/)   programming framework designed for processing, modeling and rendering of geometric data.
* [cinolib](https://github.com/mlivesu/cinolib) A generic programming header only C++ library for processing polygonal and polyhedral meshes
#### Optimization
* [meshoptimizer](https://github.com/zeux/meshoptimizer) Mesh optimization library that makes indexed meshes more GPU-friendly
#### Compress
* [Compressonator](https://github.com/GPUOpen-Tools/Compressonator) Tool suite for Texture and 3D Model Compression, Optimization and Analysis using CPUs, GPUs and APUs  
* [draco](https://github.com/google/draco) compressing and decompressing 3D geometric meshes and point clouds. 
 #### Reconstruction
 * [meshroom](https://github.com/alicevision/meshroom) 3D Reconstruction Software based on the (AliceVision)[https://github.com/alicevision/AliceVision] framework.
 * [openMVG](https://github.com/openMVG/openMVG)  open Multiple View Geometry library. Basis for 3D computer vision and Structure from Motion.
## Platform
* [herebedragons](https://github.com/kosua20/herebedragons)
* [glfw](https://github.com/glfw/glfw)
* [MoltenVK](https://github.com/KhronosGroup/MoltenVK) Vulkan graphics and compute API, that runs on Apple's Metal graphics framework
* [dxvk](https://github.com/doitsujin/dxvk) Vulkan-based D3D11 implementation for Linux / Wine  

## UI
* [imgui](https://github.com/ocornut/imgui) :star: Dear ImGui: Bloat-free Immediate Mode Graphical User interface for C++ with minimal dependencies  
* [nanovg](https://github.com/memononen/nanovg) Antialiased 2D vector drawing library on top of OpenGL for UI and visualizations. 
* [nanogui](https://github.com/wjakob/nanogui) Minimalistic GUI library for OpenGL
* [nuklear](https://github.com/vurtun/nuklear) A single-header ANSI C gui library  
* [AnttWeakbar](https://sourceforge.net/projects/anttweakbar/)  a light and intuitive GUI into OpenGL or DirectX based programs to interactively tweak parameters on-screen.
* [UIEffect](https://github.com/mob-sakai/UIEffect) UIEffect is an effect component for uGUI element in Unity
* [SpriteDicing](https://github.com/Elringus/SpriteDicing) Extension for Unity game engine to work with diced sprites
* [PolyMesh](https://github.com/UnityPatterns/PolyMesh) Create 2D shapes in an instant with the PolyMesh editor! 
* [Unity-MeshMask](https://github.com/leoin2012/Unity-MeshMask)  effient,easy use Mask Component compare to Unity Mask, cost less drawcall and lower pixel fill rate.

## Util
* [stb](https://github.com/nothings/stb)
* [yocto-gl](https://github.com/xelatihy/yocto-gl) Yocto/GL: Tiny C++ Libraries for Physically-based Graphics
* [debug-draw](https://github.com/glampert/debug-draw)
#### Unity
* [UnityFBXExporter](https://github.com/KellanHiggins/UnityFBXExporter)  A tool to export any Unity GameObject into a FBX ASCII format
* [EncodeToTGA](https://github.com/phwitti/EncodeToTGA)  Texture2D.EncodeToTGA (Unity)

## Effect 
* [shader-graph-nodes](https://github.com/gilescoope/shader-graph-nodes) Custom Nodes for Unity Shader Graph  
#### Minecraft
* [Wisdom-Shaders](https://github.com/bobcao3/Wisdom-Shaders) A Minecraft shaderspack. Offers high performance with high quality at the same time. https://qionouu.cn/  
* [Ebin-Shaders](https://github.com/BruceKnowsHow/Ebin-Shaders) This is a Minecraft shaderpack for use with Optifine.
* [robobo1221Shaders](https://github.com/robobo1221/robobo1221Shaders)
#### Meta Blobs
* [MetaBlob](https://github.com/danielzeller/MetaBlob) Meta Blobs for Unity 3D.
#### Transitions
* [gl-transitions](https://github.com/gl-transitions/gl-transitions) :thumbsup:  The open collection of GL Transitions https://gl-transitions.com/ 
* [ScreenManager](https://github.com/Xerios/ScreenManager) Flexible way to manage screens with transitions for Unity
#### Mesh Cut
* [cross-section](https://assetstore.unity.com/packages/vfx/shaders/cross-section-66300) create a cross section through meshes
#### PageCurl
* [Unity3DBookPageCurl](https://github.com/Dandarawy/Unity3DBookPageCurl) Page curl effect for Unity3D using native UI tools
#### Decal
* [ProjectionSpray](https://github.com/sugi-cho/ProjectionSpray)
#### OutLine
* [PixelBaseOutlinePostProcessing](https://github.com/vux427/PixelBaseOutlinePostProcessing) use some unity graphic API to display outline post processing.  
* [Outline-Effect](https://github.com/cakeslice/Outline-Effect) Outline Image Effect for Unity
* [Outlined-Diffuse-Shader-Fixed](https://github.com/Shrimpey/Outlined-Diffuse-Shader-Fixed) This is a fixed version of diffused outline shader from http://wiki.unity3d.com/index.php/Outlined_Diffuse_3
* [UltimateOutline](https://github.com/Shrimpey/UltimateOutline) The easiest way to achieve outlines in unity.
#### Motion
* [AmplifyMotion](https://github.com/AmplifyCreations/AmplifyMotion) Amplify Motion was the first Full-scene Motion Blur extension for Unity
#### Portal
* [unity-portal-rendering](https://github.com/pr0g/unity-portal-rendering) Super small example of using offscreen render targets to achieve a portal effect in Unity
#### Fractal 
* [ElectricSheep_WebGL](https://github.com/richardassar/ElectricSheep_WebGL) WebGL Electric Sheep Renderer
#### InteriorMapping
* [Unity-InteriorMapping](https://github.com/Gaxil/Unity-InteriorMapping)  Interior mapping shader for Unity with a sample scene. 
#### Compute Shader Effect
* [FinalAudition](https://github.com/bonzajplc/FinalAudition) A complete remake of 2005 demo "Final Audition" by Plastic

## VFX
#### Houdini
* [qLib](https://github.com/qLab/qLib) A procedural asset library for SideFX Houdini. http://qlab.github.com/qLib
#### Alembic
* [alembic](https://github.com/alembic/alembic) Alembic is an open framework for storing and sharing scene data that includes a C++ library, a file format, and client plugins and applications. http://alembic.io/
* [AlembicImporter](https://github.com/unity3d-jp/AlembicImporter) Alembic importer and exporter plugin for Unity

## Tools
#### UE4
* [u4pak](https://github.com/panzi/u4pak)
* [UModel](https://github.com/gildor2/UModel)
* [UnrealEnginePython](https://github.com/20tab/UnrealEnginePython)
#### Unity
* [AssetStudio](https://github.com/Perfare/AssetStudio) A tool for exploring, extracting and exporting assets and assetbundles
* [unitysizeexplorer](https://github.com/aschearer/unitysizeexplorer) Visualize how much space each asset in your Unity game takes
* [UnityEngineAnalyzer](https://github.com/vad710/UnityEngineAnalyzer) Roslyn Analyzer for Unity3D  
* [UnityEventVisualizer](https://github.com/MephestoKhaan/UnityEventVisualizer)  A graph editor for viewing all UnityEvents at a glance
* [Unity-AssetDependencyGraph](https://github.com/Unity-Harry/Unity-AssetDependencyGraph)  An Asset Dependency Graph for Unity
* [NuGetForUnity](https://github.com/GlitchEnzo/NuGetForUnity)  A NuGet Package Manager for Unity
* [ShaderAccessor](https://github.com/JiongXiaGu/ShaderAccessor)  Define the structure, assign values to shader parameters using C# reflection,work in unity
#### Shader
* [shader-playground](https://github.com/tgjones/shader-playground) :thumbsup: Shader compilers http://shader-playground.timjones.io
* [glsl-optimizer](https://github.com/aras-p/glsl-optimizer) :star: GLSL optimizer based on Mesa's GLSL compiler.
* [glslang](https://github.com/KhronosGroup/glslang) Khronos reference front-end for GLSL and ESSL, and sample SPIR-V generator
* [shaderc](https://github.com/google/shaderc) A collection of tools, libraries and tests for shader compilation.
* [ShaderForge](https://github.com/FreyaHolmer/ShaderForge) unity shader node editor.
* Shader HighLighting: [HlslTools](https://github.com/tgjones/HlslTools) [nshader](https://github.com/samizzo/nshader) [ShaderlabVS](https://github.com/wudixiaop/ShaderlabVS) 
* [graphicsfuzz](https://github.com/google/graphicsfuzz) A testing framework for automatically finding and simplifying bugs in graphics shader compilers.
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
* [Fornos](https://github.com/caosdoar/Fornos) GPU Texture Baking Tool
* [AwesomeBump](https://github.com/kmkolasinski/AwesomeBump) generate normal, height, specular or ambient occlusion textures from a single image
* [NormalmapGenerator](https://github.com/Theverat/NormalmapGenerator)  A simple program that converts images into normal maps
* [Imogen](https://github.com/CedricGuillemet/Imogen) GPU Texture Generator
* [aobaker](https://github.com/prideout/aobaker) ambient occlusion baking tool
* [Luminance HDR](https://github.com/LuminanceHDR/LuminanceHDR) A complete workflow for HDR imaging.
* [TextureGenerator](https://github.com/mtwoodard/TextureGenerator) 3D and 2D Noise/Texture generation using the compute shaders within the Unity engine.
#### Painter
* [InkPainter](https://github.com/EsProgram/InkPainter) Texture-Paint on Unity. https://esprogram.github.io/InkPainterDocument/
* [WaterByBakeDepth](https://github.com/AsehesL/WaterByBakeDepth)
#### Atlas 
* [boundary-first-flattening](https://github.com/GeometryCollective/boundary-first-flattening) Boundary First Flattening (BFF) is a free and open source application for surface parameterization.
* [simpleuv](https://github.com/huxingyi/simpleuv)
* [xatlas](https://github.com/jpcy/xatlas):thumbsup: Mesh parameterization / UV unwrapping library. A cleaned up version of thekla_atlas
* [thekla_atlas](https://github.com/Thekla/thekla_atlas) Atlas Generation Tool
* [UVAtlas](https://github.com/Microsoft/UVAtlas) UVAtlas isochart texture atlas  
* [Cheetah-Texture-Packer](https://github.com/scriptum/Cheetah-Texture-Packer)  High efficient and fast 2D bin packing tool
* [Unity3D-TextureAtlasSlicer](https://github.com/toxicFork/Unity3D-TextureAtlasSlicer)
* [VaTexAtlas](https://github.com/ufna/VaTexAtlas)  plugin for Unreal Engine 4 that makes texture atlases simpler to use with UMG system.
#### GPU Debug
* [renderdoc](https://github.com/baldurk/renderdoc) A stand-alone graphics debugging tool. https://renderdoc.org
* [CodeXL](https://github.com/GPUOpen-Tools) a comprehensive tool suite that enables developers to harness the benefits of CPUs, GPUs and APUs.
* [LPGPU2-CodeXL](https://github.com/codeplaysoftware/LPGPU2-CodeXL) LPGPU2 CodeXL power performance analysis and feedback tool for GPUs
* [perfdoc](https://github.com/ARM-software/perfdoc) A cross-platform Vulkan layer which checks Vulkan applications for best practices on Arm Mali devices.
* [gapid](https://github.com/google/gapid) Graphics API Debugger by google
* [vogl](https://github.com/ValveSoftware/vogl) OpenGL capture / playback debugger by valve
* [apitrace](https://github.com/apitrace/apitrace) Tools for tracing OpenGL, Direct3D, and other graphics APIs
* [GPUVis](https://github.com/mikesart/gpuvis) GPU Trace Visualizer
* [Remotery](https://github.com/Celtoys/Remotery) Single C file, Realtime CPU/GPU Profiler with Remote Web Viewer
* [BuGLe](https://sourceforge.net/projects/bugle/) BuGLe combines a graphical OpenGL debugger with a selection of filters on the OpenGL command stream. 
* Other: **gDEBugger**, **NVIDIA Nsight**, **Microsoft PIX**

## SDK&Tutorial
#### API Samples
* [DirectX-Graphics-Samples](https://github.com/Microsoft/DirectX-Graphics-Samples) This repo contains the DirectX Graphics samples that demonstrate how to build graphics intensive applications on Windows.
* [directx-sdk-samples](https://github.com/walbourn/directx-sdk-samples) This repo contains C++ samples from the DirectX SDK updated to build using the Windows 8.x SDK or Windows 10 SDK
* [Zombie-Direct3D-Samples](https://github.com/marselas/Zombie-Direct3D-Samples) June 2010 SDK updated to build with the latest version of Windows and Visual Studio
* [IntroductionToVulkan](https://github.com/GameTechDev/IntroductionToVulkan) Source code examples for "API without Secrets: Introduction to Vulkan" tutorial 
* [VulkanTutorial](https://github.com/Overv/VulkanTutorial)
* [Vulkan](https://github.com/SaschaWillems/Vulkan)
* [vulkan-sdk for android](https://github.com/ARM-software/vulkan-sdk)
* [nvpro-samples](https://github.com/nvpro-samples) NVIDIA DesignWorks Samples
* [NVIDIA Direct3D SDK 11](https://developer.nvidia.com/dx11-samples)
* [NVIDIA Direct3D SDK 10](http://developer.download.nvidia.com/SDK/10/direct3d/samples.html) 
* [NVIDIA Direct3D SDK 9](https://www.nvidia.com/object/sdk-9.html)
#### Book Code
* [OpenGLInsightsCode](https://github.com/OpenGLInsights/OpenGLInsightsCode)
* [GraphicsGems](https://github.com/erich666/GraphicsGems)
* [GPUZen](https://github.com/wolfgangfengel/GPUZen)
* [ray-tracing-gems](https://github.com/Apress/ray-tracing-gems)
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
* [PositionBasedDynamics](https://github.com/InteractiveComputerGraphics/PositionBasedDynamics) physically-based simulation of rigid bodies, deformable solids and fluids.
* [SPlisHSPlasH](https://github.com/InteractiveComputerGraphics/SPlisHSPlasH) physically-based simulation of fluids.
* [GridFluidSim3D](https://github.com/rlguy/GridFluidSim3D) A PIC/FLIP fluid simulation based on the methods found in Robert Bridson's "Fluid Simulation for Computer Graphics"
* [SPHFluid](https://github.com/MangoSister/SPHFluid) Interactive 3D Fluid Simulation based on SPH
* [RealTimeFluidRendering](https://github.com/ttnghia/RealTimeFluidRendering) Implementation of the i3D2018 paper "A Narrow-Range Filter for Screen-Space Fluid Rendering". 
* [fluid-engine-dev](https://github.com/doyubkim/fluid-engine-dev)  Fluid simulation engine for computer graphics applications https://fluidenginedevelopment.org/
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
* [Render-Crowd-Of-Animated-Characters](https://github.com/chenjd/Render-Crowd-Of-Animated-Characters)   anim map for vertex shader to modify the vertex position of the mesh at runtime. use gpu instancing to reduce draw call.
* [skeleton-builder](https://github.com/alecjacobson/skeleton-builder)
* [hazumu](https://github.com/emily-vo/hazumu) Raytracing Skeletal Animation
* [ssds](https://github.com/TomohikoMukai/ssds) An implementation of Skinning Decomposition with Similarity Transformations (I3D2018)

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

## Visualization
* [VTK](https://www.vtk.org/) The Visualization Toolkit
