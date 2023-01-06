# OpenGraphic
Graphic Engine &amp; Game Engine open source list！

## Contents

>**Official**

  [Official](#official)  
  
>**Engine**

  [Engine](#engine) &nbsp;&nbsp; [EnginePlugin](#engine-plugin) &nbsp;&nbsp; [OfflineEngine](#Offline-Engine) &nbsp;&nbsp; [SoftRenderer](#soft-renderer)  &nbsp;&nbsp; [RenderingDesign](#rendering-design) 
  
>**Rendering**

  [GI](#gi) &nbsp;&nbsp; [VolumeRendering](#volume-rendering) &nbsp;&nbsp; [PostProcessing](#postprocessing)  &nbsp;&nbsp;  [Stylize](#stylize)  &nbsp;&nbsp; [Transparency](#transparency) &nbsp;&nbsp;  [VFX](#vfx)   &nbsp;&nbsp; [Standard Format](#standard-format)  
  
>**Emulation**

  [Material](#material) &nbsp;&nbsp; [Environment](#environment) &nbsp;&nbsp; &nbsp;&nbsp; [Camera](#Camera)   
  
>**Optimization**

  [Acceleration](#acceleration)  &nbsp;&nbsp; [SpatialDataStructures](#spatial-data-structures) &nbsp;&nbsp; [RenderPath](#render-path)  
  
>**Util**

  [Util](#util) &nbsp;&nbsp; [SDF](#sdf) &nbsp;&nbsp; [Math](#math) &nbsp;&nbsp; [Image&Color](#imagecolor) &nbsp;&nbsp; [Noise](#noise)  &nbsp;&nbsp; [Mesh](#mesh) &nbsp;&nbsp; [Platform](#platform) &nbsp;&nbsp; [UI](#ui) 
  
>**Tools**

  [Tools](#tools) 
  
>**Tutorial**

  [SDK&Tutorial](#sdktutorial)
  
>**Other**

  [Physics](https://github.com/Gforcex/OpenGraphic/blob/master/Physics.md) &nbsp;&nbsp; [Animation](#animation) &nbsp;&nbsp; [Particle](#particle) &nbsp;&nbsp; 
  
---

## Official
* Unity [Unity-Technologies](https://github.com/Unity-Technologies)  &nbsp;&nbsp; [unity3d-jp](https://github.com/unity3d-jp)  &nbsp;&nbsp;  [UnityLabs](https://github.com/UnityLabs)  &nbsp;&nbsp;  [UnityTech](https://github.com/unitytech)
* AMD  [GPUOpen-LibrariesAndSDKs](https://github.com/GPUOpen-LibrariesAndSDKs)  &nbsp;&nbsp; [GPUOpen-Tools](https://github.com/GPUOpen-Tools)  &nbsp;&nbsp;  [GPUOpen-Effects](https://github.com/GPUOpen-Effects)  &nbsp;&nbsp;  [GPUOpen-Drivers](https://github.com/GPUOpen-Drivers)
* NVIDIA [NVIDIAGameWorks](https://github.com/NVIDIAGameWorks)  &nbsp;&nbsp; [nvpro-samples](https://github.com/nvpro-samples)  &nbsp;&nbsp; [NVIDIA](https://github.com/NVIDIA)  &nbsp;&nbsp;  [NVlabs](https://github.com/NVlabs)  
* Intel [Intel GameTechDev](https://github.com/GameTechDev) https://software.intel.com/gamedev
* ARM [ARM-software](https://github.com/ARM-software)
* PowerVR [powervr-graphics](https://github.com/powervr-graphics)
* [The Khronos Group](https://github.com/KhronosGroup) https://www.khronos.org/
* [Academy Software Foundation](https://github.com/AcademySoftwareFoundation) https://www.aswf.io/
* [Pixar Animation Studios](https://github.com/PixarAnimationStudios) http://graphics.pixar.com
* SideEfects [sideeffects](https://github.com/sideeffects) Hodini
* [id-Software](https://github.com/id-Software)
* [InteractiveComputerGraphics](https://github.com/InteractiveComputerGraphics)

## Engine
* [UnrealEngine](https://github.com/EpicGames/UnrealEngine) :star: https://www.unrealengine.com/
* [CRYENGINE](https://github.com/CRYTEK/CRYENGINE_Source) :star:  https://www.cryengine.com/
* [o3de](https://github.com/o3de/o3de) https://www.o3de.org/
* [Urho3D](https://github.com/urho3d/Urho3D) lightweight, cross-platform 2D and 3D game engine,Greatly inspired by OGRE and Horde3D.
* [filament](https://github.com/google/filament):thumbsup: Filament is a physically based rendering engine for Android, Windows, Linux and macOS
* [Falcor](https://github.com/NVIDIAGameWorks/Falcor) Real-Time Rendering Framework, NVIDIA
* [Klayag](https://github.com/gongminmin/KlayGE) A cross-platform open source game engine with plugin-based architecture
* [G3D]( https://casual-effects.com/g3d) Graphics research and rapid prototyping in OpenGL and C++
* [Ogre](https://github.com/ogrecave) ogre github mirror
* [OpenSceneGraph](https://github.com/openscenegraph/OpenSceneGraph)  http://www.openscenegraph.org 
* [WickedEngine](https://github.com/turanszkij/WickedEngine) C++ game engine focusing on modern rendering techniques and performance. https://wickedengine.net
* [stride](https://github.com/stride3d/stride)  Stride Game Engine (formerly Xenko)
* [godot](https://github.com/godotengine/godot) Godot Engine – Multi-platform 2D and 3D game engine https://godotengine.org
* [anki-3d-engine](https://github.com/godlikepanos/anki-3d-engine) AnKi 3D Engine - OGL/Vulkan backends, modern renderer, scripting, physics and more 
* [SpartanEngine](https://github.com/PanosK92/SpartanEngine) Game engine with an emphasis on architectual quality and performance
* [ETEngine](https://github.com/Illation/ETEngine) Realtime 3D Game-Engine with a focus on space sim. Written in C++ 14
* [Granite](https://github.com/Themaister/Granite)  personal Vulkan renderer
* [FlaxEngine](https://github.com/FlaxEngine/FlaxEngine) Flax Engine – multi-platform 3D game engine. https://flaxengine.com/
* [bgfx](https://github.com/bkaradzic/bgfx) :star: -Cross-platform, graphics API agnostic, "Bring Your Own Engine/Framework" style rendering library 
* [The-Forge](https://github.com/ConfettiFX/The-Forge) The Forge Cross-Platform Rendering Framework PC, macOS / iOS, Android, XBOX, PS4
* [island](https://github.com/tgfrerer/island) Project Island is an experimental, hot-reloading Vulkan renderer/proto-engine for Linux, written in C/C++.
* [DiligentEngine](https://github.com/DiligentGraphics/DiligentEngine) A modern cross-platform low-level 3D graphics library http://diligentgraphics.com/diligent-engine/ 
* [three.js](https://github.com/mrdoob/three.js) JavaScript 3D library. https://threejs.org/  
* [Babylon.js](https://github.com/BabylonJS/Babylon.js) A powerful, beautiful, simple, and open game and rendering engine packed into a friendly JavaScript framework.
* [cesium](https://github.com/AnalyticalGraphicsInc/cesium) An open-source JavaScript library for world-class 3D globes and maps 
* [playcanvas](https://github.com/playcanvas/engine)  ast and lightweight WebGL game engine https://playcanvas.com/

## Engine Plugin
* [Graphics](https://github.com/Unity-Technologies/Graphics) Unity Graphics - Including Scriptable Render Pipeline
* [armory](https://github.com/armory3d/armory)  -3D Game Engine for Blender
* [RenderPipeline](https://github.com/tobspr/RenderPipeline) -PBR and Deferred Rendering for the Panda3D game engine 
* [ray-mmd](https://github.com/ray-cast/ray-mmd) physically-based rendering at mikumikudance

## Offline Engine
* [embree](https://github.com/embree/embree)  A collection of high-performance ray tracing kernels, developed at Intel.
* [kajiya](https://github.com/EmbarkStudios/kajiya)  Experimental real-time global illumination renderer
* [RadeonRays RadeonProRender](https://github.com/GPUOpen-LibrariesAndSDKs) ray intersection acceleration library for hardware and software multiplatforms using CPU and GPU
* [mitsuba3](https://github.com/mitsuba-renderer/mitsuba3) :thumbsup:  Mitsuba 3: A Retargetable Forward and Inverse Renderer http://mitsuba-renderer.org/
* [appleseed](https://github.com/appleseedhq/appleseed) A modern open source rendering engine for animation and visual effects https://appleseedhq.net/
* [pbrt](https://github.com/mmp/pbrt-v3) Source code for "Physically Based Rendering: From Theory To Implementation" 
* [LuxCoreRender](https://github.com/LuxCoreRender) https://www.luxcorerender.org
* [ospray](https://github.com/ospray/ospray) A Ray Tracing Based Rendering Engine for High-Fidelity Visualization
* [tungsten](https://github.com/tunabrain/tungsten) High performance physically based renderer in C++11
* [lighthouse2](https://github.com/jbikker/lighthouse2)  Lighthouse 2 framework for real-time ray tracing
* [etx-tracer](https://github.com/serhii-rieznik/etx-tracer) Physically-based CPU and GPU ray-tracer
* [nori](https://github.com/wjakob/nori) Nori: an educational ray tracer https://wjakob.github.io/nori
* [nanort](https://github.com/lighttransport/nanort)  single header only modern ray tracing kernel.
* [yocto-gl](https://github.com/xelatihy/yocto-gl) Yocto/GL: Tiny C++ Libraries for Physically-based Graphics
* [SORT](https://github.com/JerryCao1985/SORT)  Simple Open-source Ray Tracer https://agraphicsguy.wordpress.com/
* [fermat](https://github.com/NVlabs/fermat) a high performance research oriented physically based rendering system, trying to produce beautiful pictures following the mathematician’s principle of least time

## Soft Renderer
* [OpenSWR](http://openswr.org/) A High Performance, Highly Scalable Software Rasterizer for OpenGL
* [miaow](https://github.com/VerticalResearchGroup/miaow) An open source GPU based off of the AMD Southern Islands ISA.
* [tinyrenderer](https://github.com/ssloy/tinyrenderer)  A brief computer graphics / rendering course
* [coco3d](http://coco3d.codeplex.com/) Coco3D is a real-time 3D software renderer for Windows PCs and mobile devices
* [muli3d](https://sourceforge.net/projects/muli3d/)  implements features of current graphics hardware in software. The focus is on ease of use and clear code
* [swiftshader](https://github.com/google/swiftshader) high-performance CPU-based implementation of the OpenGL ES and Direct3D 9 graphics APIs
* [mesa](https://gitlab.freedesktop.org/mesa/mesa) :thumbsup: https://www.mesa3d.org
* [renderer](https://github.com/zauonlok/renderer)  A shader-based software renderer written from scratch in C89 https://zauonlok.github.io/renderer/
* [SoftwareRenderer](https://github.com/Angelo1211/SoftwareRenderer) Software rendering engine with PBR. Built from scratch on C++.
* [Tyler](https://github.com/NotCamelCase/Tyler) Tile-based SW rasterizer 
* [RetroWarp](https://github.com/Themaister/RetroWarp) The GPU is implemented with "pure" software rendering
* [SoftRas](https://github.com/ShichenLiu/SoftRas)  Project page of paper "Soft Rasterizer: A Differentiable Renderer for Image-based 3D Reasoning"
* [grr](https://github.com/kecho/grr) Gpu Renderer and Rasterizer - for python
* [virglrenderer](https://gitlab.freedesktop.org/virgl/virglrenderer/) VirGL virtual OpenGL renderer
* [AMDVLK](https://github.com/GPUOpen-Drivers/AMDVLK) AMD Open Source Driver For Vulkan
* [open-gpu-kernel-modules](https://github.com/NVIDIA/open-gpu-kernel-modules) NVIDIA Linux open GPU kernel module source
* [EmberGL](https://github.com/EmberGL-org/EmberGL) A low-level open source graphics library, similar to OpenGL/DirectX/Vulkan, designed for real-time 2D/3D rendering on MCUs and other memory constrained non-GPU systems

## Rendering Design
* [DataDrivenRendering](https://github.com/JorenJoestar/DataDrivenRendering) Data Driven Rendering repository
* [fg](https://github.com/acdemiralp/fg) Rendering abstraction which describes a frame as a directed acyclic graph of render tasks and resources.
* [FrameGraph](https://github.com/azhirnov/FrameGraph) vulkan abstraction layer that represent frame as a task graph
* [graphene](https://github.com/ApoorvaJ/graphene) Vulkan render graph shenanigans

## GI
### Collection
* [IlluminationComparison](https://github.com/EKnapik/IlluminationComparison) A comparison of typical illumination methods. (SSAO, HBO, VXGI, and Ray Traced Global Illumination)
* [dirtchamber](https://github.com/thefranke/dirtchamber) A mixed reality testing environment for real-time global illumination algorithms 
* [DXR-Sandbox-GI](https://github.com/steaklive/DXR-Sandbox-GI) Simple DirectX 12 toy framework for testing Global Illumination: Reflective Shadow Mapping, Light Propagation Volume, Voxel Cone Tracing, DXR
#### PRT
* [SHTest](https://github.com/dwilliamson/SHTest) Spherical Harmonic Lighting (Direct/Shadowed/Indirect/Subsurface)
* [SphericalHarmonicLighting](https://github.com/jan-van-bergen/SphericalHarmonicLighting) Global Illumination using Spherical Harmonics
* [Urho3D-1.4-SphericalHarmonicLighting](https://github.com/Lumak/Urho3D-1.4-SphericalHarmonicLighting) Testing spherical harmonic lighting based on the spherical-harmonic-lighting.pdf
* [precomputed-radiance-transfer](https://github.com/pramanc/precomputed-radiance-transfer) undergraduate student course project in Zhejiang University
#### Irradiance Probes/Voxels
* [webgl-deferred-irradiance-volumes](https://github.com/pyalot/webgl-deferred-irradiance-volumes)  An implementation of deferred irradiance volumes in WebGL
* [RTXGI](https://github.com/NVIDIAGameWorks/RTXGI) RTX Global Illumination (RTXGI) SDK
#### VPL
#### VSGL
* [VSGL](https://github.com/yusuketokuyoshi/VSGL) Fast Indirect Illumination Using Two Virtual Spherical Gaussian Lights
#### RSM
#### Imperfect Shadow Maps
* [qt5-shadow-maps](https://github.com/tatsy/qt5-shadow-maps) Shadow mapping implementation with Qt5 and OpenGL
#### Instant Radiosity
#### LPV
* [Light-Propagation-Volumes](https://github.com/djbozkosz/Light-Propagation-Volumes)
* [GI-LPV](https://github.com/innovation-cat/GI-LPV) Implement global illumination with OCaml, using light propagation volumes
#### VCT
* [Nigiri](https://github.com/ninlilizi/Nigiri) A fully-dynamic voxel-based global illumination system for Unity.
* [SEGI](https://github.com/sonicether/SEGI) Almost real-time Global Illumination for Unity.
* [Unity-SRP-VXGI](https://github.com/Looooong/Unity-SRP-VXGI) Voxel-based Global Illumination using Unity Scriptable Render Pipeline.
* [VCTRenderer](https://github.com/jose-villegas/VCTRenderer) Deferred voxel shading for real-time global illumination. https://jose-villegas.github.io/post/deferred_voxel_shading/
* [voxel-cone-tracing](https://github.com/Friduric/voxel-cone-tracing) A real-time global illumination implementation using voxel cone tracing.
* [VoxelConeTracingGI](https://github.com/compix/VoxelConeTracingGI) Global illumination with Voxel Cone Tracing in fully dynamic scenes using a 3D clipmap to support huge areas around the camera while maintaining a low memory footprint.
* [Vulkan-VXGI-VR-FrameWork](https://github.com/byumjin/Vulkan-VXGI-VR-FrameWork) University of Pennsylvania, CIS 565: GPU Programming and Architecture, Final Project
* [MAGE](https://github.com/matt77hias/MAGE) Game and rendering engine featuring both forward and deferred PBR (physically-based rendering) pipelines with optional indirect illumination using Voxel Cone Tracing.
* [VoxelConeTracing](https://github.com/domme/VoxelConeTracing) An implementation of the "Voxel Cone Tracing" global illumination technique proposed by Cyril Crassin
* [VCTGI](https://github.com/rdinse/VCTGI) GPU-based real-time global illumination renderer based on voxel cone tracing
* [DXE](https://github.com/LanLou123/DXE) A voxel cone traced realtime Global Illumination rendering engine in dx12, wip
* [Voxel_Cone_Tracing](https://github.com/kbladin/Voxel_Cone_Tracing)  [Voxel-Cone-Tracing](https://github.com/Cigg/Voxel-Cone-Tracing)    easy to understand
#### SSGI
* [SSGI-URP](https://github.com/demonixis/SSGI-URP) Screen Space Global Illumination for Unity Universal Render Pipeline
* [FSSGI](https://github.com/bloc97/FSSGI) Fast Screen Space Global Illumination
#### DFGI
#### Lighting Grid 
* [LGHDemo](https://github.com/DQLin/LGHDemo)  Real-Time Rendering with Lighting Grid Hierarchy I3D 2019 Demo
#### Point Based GI
* [PBGI](https://github.com/XT95/PBGI) Point Based Global Illumination
#### Radiosity
* [instant_radiosity](https://github.com/cache-tlb/instant_radiosity) Some (simple) global illumination algorithms
* [simple-instant-radiosity](https://github.com/githole/simple-instant-radiosity)
* [GIGL](https://github.com/vgfx/GIGL) Tiny Global Illumination OpenGL Renderer
#### Ray tracing
#### Path tracing
* [minpt](https://github.com/hi2p-perim/minpt) A path tracer in 300 lines of C++
* [GLSL-PathTracer](https://github.com/knightcrawler25/GLSL-PathTracer) :thumbsup: A GLSL Path Tracer
* [PSRayTracing](https://github.com/define-private-public/PSRayTracing) A (modern) C++ implementation of the first two books of the Peter Shirley Ray Tracing mini-books
* [rayn](https://github.com/termhn/rayn) A small path tracing renderer written in Rust.

* [simple-bidirectional-pathtracer](https://github.com/githole/simple-bidirectional-pathtracer)
* [edubpt](https://github.com/githole/edubpt)
* [Volumetric-Path-Tracer](https://github.com/sergeneren/Volumetric-Path-Tracer) Volumetric path tracer using cuda
* [simple-spectral](https://github.com/imallett/simple-spectral) A Simple Spectral Renderer
#### RTX
* [Q2RTX](https://github.com/NVIDIA/Q2RTX)  NVIDIA’s implementation of RTX ray-tracing in Quake II [zyanidelab/Q2RTX](https://github.com/zyanidelab/Q2RTX)
* [Quartz](https://github.com/Nadrin/Quartz)  Physically based Vulkan RTX path tracer with a declarative ES7-like scene description language.
* [DXRPathTracer](https://github.com/TheRealMJP/DXRPathTracer)  A (very) simple path tracer implemented using DirectX Ray Tracing (DXR)
* [WispRenderer](https://github.com/TeamWisp/WispRenderer) RTX Ray Tracing Renderer, made by Y3 students at Breda University of Applied Science https://teamwisp.github.io
* [rtx-explore](https://github.com/rtx-on/rtx-explore) DirectX Raytracing Path Tracer
* [Kaguya](https://github.com/kcloudy0717/Kaguya) This is a hobby project using DirectX 12 and DirectX RayTracing (DXR)
* [RayTracingInVulkan](https://github.com/GPSnoopy/RayTracingInVulkan) Implementation of Peter Shirley's Ray Tracing In One Weekend book using Vulkan and NVIDIA's RTX extension.
* [PBRVulkan](https://github.com/Zielon/PBRVulkan) Vulkan Real-time Path Tracer Engine
* [Helios](https://github.com/diharaw/Helios) Real-time unidirectional GPU path tracer using the cross-vendor Vulkan ray-tracing extensions.
* [vk_mini_path_tracer](https://github.com/nvpro-samples/vk_mini_path_tracer) A beginner-friendly Vulkan path tracing tutorial in under 300 lines of C++.
#### ReSTIR
* [VolumetricReSTIRRelease](https://github.com/DQLin/VolumetricReSTIRRelease) SIGGRAPH Asia 2021 paper "Fast Volume Rendering with Spatiotemporal Reservoir Resampling"
#### Metropolis Light Transport
#### PhotonMapping
* [CPMFIGIOTVVD](https://github.com/ResearchDaniel/Correlated-Photon-Mapping-for-Interactive-Global-Illumination-of-Time-Varying-Volumetric-Data) Correlated Photon Mapping for Interactive Global Illumination of Time-Varying Volumetric Data by Daniel Jönsson and Anders Ynnerman
* [SOPGI](https://github.com/alexnardini/SOPGI)  A VEX raytracer for SideFX Houdini with photon mapping global illumination and full recursive reflections and refractions
* [DXR-PhotonMapper](https://github.com/ananthaks/DXR-PhotonMapper) An implementation of Photon Mapping using DXR
#### Ambient occlusion
* [KinoObscurance](https://github.com/keijiro/KinoObscurance) Alchemy Ambient Obscurance ---AlchemyHPG11
* [ScalableAmbientObscurance](https://research.nvidia.com/publication/scalable-ambient-obscurance) https://research.nvidia.com/publication/scalable-ambient-obscurance
* [XeGTAO](https://github.com/GameTechDev/XeGTAO) An implementation of [Jimenez et al., 2016] Ground Truth Ambient Occlusion, MIT license
* [ASSAO](https://github.com/GameTechDev/ASSAO) Adaptive Screen Space Ambient Occlusion
* [Robust Screen Space Ambient Occlusion](https://github.com/wolfgangfengel/GPUZen/tree/master/04_Screen%20Space/) Robust Screen Space Ambient Occlusion
* [HBAOPlus](https://github.com/NVIDIAGameWorks/HBAOPlus) HBAO+ is a SSAO algorithm designed to achieve high efficiency on DX11 GPUs. 
* [gl_ssao](https://github.com/nvpro-samples/gl_ssao) optimized screen-space ambient occlusion, cache-aware hbao  
* [VXAO](https://developer.nvidia.com/vxao-voxel-ambient-occlusion) Voxel Ambient Occlusion
* [MiniEngineAO](https://github.com/keijiro/MiniEngineAO) SSAO image effect from Microsoft MiniEngine, ported to Unity.
* [NNAO](https://github.com/simeonradivoev/NNAO) Neural Network Ambien Occlusion
* [dssdo](https://github.com/kayru/dssdo) Deferred Screen Space Directional Occlusion http://kayru.org/articles/dssdo/
* [ssgi](https://github.com/jdupuy/ssgi) Screen space global illumination demo: SSAO vs SSDO
* [SSRT](https://github.com/cdrinmatane/SSRT) Real-time indirect diffuse illuminaton using screen-space information for Unity.
* [AmplifyOcclusion](https://github.com/AmplifyCreations/AmplifyOcclusion) Full source-code for Amplify Occlusion plugin for Unity [AmplifyOcclusion-URP](https://github.com/neon-age/AmplifyOcclusion-URP)
* [Unity-Ground-Truth-Ambient-Occlusion](https://github.com/MaxwellGengYF/Unity-Ground-Truth-Ambient-Occlusion) A physically based screen space ambient occulsion post processing effect  
* [Unity-GeoAO](https://github.com/nezix/Unity-GeoAO) Fast ambien occlusion in Unity at runtime
* [ConeSphereOcclusionLUT](https://github.com/knarkowicz/ConeSphereOcclusionLUT) ConeSphereOcclusionLUT generates a cone sphere occlusion LUT to be used with TLoU style **capsule AO shadows**. For details "Lighting Technology Of "The Last Of Us".
* [RTAO](https://github.com/boksajak/RTAO) Ray Traced Ambient Occlusion (RTAO) implemented using DirectX Raytracing (DXR)
* [BNAO](https://github.com/Fewes/BNAO) A tiny, GPU-based Bent Normal and Ambient Occlusion baker for Unity.
* [dxr-ao-bake](https://github.com/Twinklebear/dxr-ao-bake) A demo of ambient occlusion map baking using DXR
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
* [HDR_Lightmapper](https://github.com/Naxela/HDR_Lightmapper)  Implements a cycles based lightmapper with denoiser
* [The_Lightmapper](https://github.com/Naxela/The_Lightmapper) Fast and easy baked GI Lightmaps for Blender and Cycles
* [LightmapperToy](https://github.com/candycat1992/LightmapperToy) This project is a hobby lightmapper completely based on Houdini geometry nodes. Basically it grew out of a re-implementation of Matt's The Baking Lab with some modification. 
#### MLGI
* [DeepIllumination](https://github.com/CreativeCodingLab/DeepIllumination) Code and examples from our paper "Deep Illumination: Approximating Dynamic Global Illumination with Generative Adversarial Networks," by Manu Mathew Thomas and Angus Forbes

### GI Simulation
#### Diffuse inter-reflection
#### Caustic
* [SC_Tracer](https://github.com/ningfengh/SC_Tracer) photon mapping for global illumination and caustic
* [Crystal-Caustics](https://github.com/CJT-Jackton/Crystal-Caustics) Approximated crystal caustics effect in Unity.
#### Reflection
* [ComputeStochasticReflections](https://github.com/simeonradivoev/ComputeStochasticReflections) Compute Stochastic Screen Space Reflections for unity post processing  
* [kode80SSR](https://github.com/kode80/kode80SSR) An open source screen space reflections implementation for Unity3D 5.  
* [StochasticScreenSpaceReflection](https://github.com/cCharkes/StochasticScreenSpaceReflection)
* [Unity-Screen-Space-Reflection](https://github.com/MaxwellGengYF/Unity-Screen-Space-Reflection) Clearly Screen Space Reflection
* [UnitySSR](https://github.com/Xerxes1138/UnitySSR) Open source screen space reflection for Unity 5
* [synthese_image](https://github.com/theFrenchDutch/synthese_image) author's [blog](http://thomasdeliot.wixsite.com/blog/single-post/2018/04/26/Small-project-OpenGL-engine-and-PBR-deferred-pipeline-with-SSRSSAO)
* [URP_ScreenSpacePlanarReflections](https://github.com/Steven-Cannavan/URP_ScreenSpacePlanarReflections) Simple example of implementing screen space planar reflections as a RenderFeature for URP
* [UnityURP-MobileScreenSpacePlanarReflection](https://github.com/ColinLeung-NiloCat/UnityURP-MobileScreenSpacePlanarReflection) A simple and fast ScreenSpacePlanarReflection(SSPR) as a standalone reusable RendererFeature in URP.
* [Jin-Engine-2.1](https://github.com/byumjin/Jin-Engine-2.1) The implementation of Pixel-projected Screen Space Reflections 
* [BakedReflectionsUnity](https://github.com/julhe/BakedReflectionsUnity) :thumbsup: Reflection Probe Atlas impl. for Unity
#### Refraction
* [SS-refraction-through-depth-peeling-in-threejs](https://github.com/Domenicobrz/SS-refraction-through-depth-peeling-in-threejs) Screen space refraction through depth peeling in threejs
#### Shadow
* [realtimeshadows](https://www.realtimeshadows.com/?q=node/12) <Realtime Shadows> codes
* [Shadows](https://github.com/TheRealMJP/Shadows) :thumbsup: A sample app that demonstrates several techniques for rendering real-time shadow maps
* [UnityPCSS](https://github.com/TheMasonX/UnityPCSS) Nvidia's PCSS soft shadow algorithm implemented in Unity
* [ContactShadows](https://github.com/keijiro/ContactShadows) Experimental implementation of contact shadows for Unity.
* [HFTS](https://developer.nvidia.com/Hybrid-Frustum-Traced-Shadows) NVIDIA Hybrid Frustum Traced Shadows in NVIDIA ShadowLib.
* [ShadowFX](https://github.com/GPUOpen-Effects/ShadowFX) DirectX 11 and 12 library that provides a scalable and GCN-optimized solution for deferred shadow filtering 
* [Cinder-Experiments](https://github.com/simongeilfus/Cinder-Experiments) A collection of experiments, samples and other bits of code.
* [of-ESMShadowMapping](https://github.com/jacres/of-ESMShadowMapping) Exponential Shadow Mapping in openFrameworks
* [RayTracedShadows](https://github.com/kayru/RayTracedShadows) This demo implements BVH construction and GPU traversal for rendering hard shadows.
* [RaytracedHardShadow](https://github.com/unity3d-jp/RaytracedHardShadow) DXR based raytraced hard shadow for Unity
* [ShadowVolume](https://github.com/chengkehan/ShadowVolume) Shadow Volume for Static-Scene-Object of Unity
* [variance_shadow_mapping_vk](https://github.com/sydneyzh/variance_shadow_mapping_vk) Variance shadow mapping for omni lights with Vulkan
* [Precomputed-Shadow-Fields-for-Dynamic-Scenes](https://github.com/nblintao/Precomputed-Shadow-Fields-for-Dynamic-Scenes) A realization of computing soft shadow by shadow fields
* [voxelized-shadows-improved](https://github.com/loinesg/voxelized-shadows-improved) Construction and sampling of precomputed shadows in a compressed voxel octree
* [DeepShadowMap](https://github.com/ecidevilin/DeepShadowMap) Real-Time Deep Shadow Maps for Unity3D
* [CachedShadowMaps](https://github.com/aivclab/CachedShadowMaps) Cached Shadow Map Solution for Unity

## PostProcessing 
#### Collection
* [PostProcessing](https://github.com/Unity-Technologies/PostProcessing) Post Processing Stack
* [reshade-shaders](https://github.com/crosire/reshade-shaders) A collection of post-processing shaders written for ReShade. https://reshade.me
* [Cat-PostProcessing](https://github.com/JoachimCoenen/Cat-PostProcessing) various post-processing effects for Unity
* [Unity5Effects](https://github.com/i-saint/Unity5Effects)
* [Unity_ScreenSpaceTechStack](https://github.com/haolange/Unity_ScreenSpaceTechStack)  This is a package which contains SSAO, SSDiffuse and SSReflection.
#### AA
* [CMAA2](https://github.com/GameTechDev/CMAA2)  Conservative Morphological Anti-Aliasing 2.0
* [MSAAFilter](https://github.com/TheRealMJP/MSAAFilter)  MSAA and Temporal AA Sample
* [temporal](https://github.com/playdeadgames/temporal) Temporal Reprojection Anti-Aliasing for Unity 5.0+
* [TAA_Unity_URP](https://github.com/sienaiwun/TAA_Unity_URP) Temporal Anti-Aliasing(TAA) for Unity’s Universal Render Pipeline
* [smaa](https://github.com/iryoku/smaa) SMAA: Subpixel Morphological Antialiasing, is a very efficient GPU-based MLAA implementation
* [smaaDemo](https://github.com/turol/smaaDemo) Subpixel Morphological AntiAliasing OpenGL/Vulkan demo
* [SMAA](https://github.com/Chman/SMAA) SMAA in unity3D
* [SpecularAA](https://github.com/TheRealMJP/SpecularAA) A demo of various normal map filtering techniques for reducing specular aliasing
* [glsl-fxaa](https://github.com/mattdesl/glsl-fxaa) FXAA implementation for glslify in WebGL
* [Phone-wire AA](http://www.humus.name/index.php?page=3D&ID=89)
* [DLAA](https://github.com/ForserX/DLAA) (DLAA) Directionally Localized antiAliasing
* [TAA-STAR](https://github.com/cg-tuwien/TAA-STAR) C++/Vulkan Implementations of State of the Art Temporal Anti-Aliasing Techniques
* [UE4 DLSS](https://github.com/NvRTX/UnrealEngine) DLSS Plugin for Unreal Engine
#### Denoising 
* [oidn](https://github.com/OpenImageDenoise/oidn) Intel(R) Open Image Denoise library http://www.openimagedenoise.org/
* [NvidiaAIDenoiser](https://github.com/DeclanRussell/NvidiaAIDenoiser) A simple implementation of Nvidia's AI denoiser
* [RealTimeDenoisingNeuralBilateralGrid](https://github.com/xmeng525/RealTimeDenoisingNeuralBilateralGrid) [EGSR2020] Real-time Monte Carlo Denoising with the Neural Bilateral Grid
* [practicalDenoising](https://github.com/ImageEngine/practicalDenoising) Reference Implementation of Practical Denoising for VFX Production Using Temporal Blur
* [bcd](https://github.com/superboubek/bcd) Bayesian Collaborative Denoiser for Monte-Carlo Rendering
* [glslSmartDeNoise](https://github.com/BrutPitt/glslSmartDeNoise) :thumbsup: Fast glsl spatial deNoise filter
#### Bloom
* [SE-Natural-Bloom-Dirty-Lens](https://github.com/sonicether/SE-Natural-Bloom-Dirty-Lens) (Legacy) post-processing effect for Unity.
* [Unity_StarGlow](https://github.com/XJINE/Unity_StarGlow)  This is an implementation of Kawase's light-streak.
#### Tone Mapping
* [tonemapper](https://github.com/tizian/tonemapper)
* [aces-dev](https://github.com/ampas/aces-dev)  AMPAS Academy Color Encoding System Developer Resources http://www.oscars.org/aces
#### ImageProcess
* [UnityImageEffects](https://github.com/hiroakioishi/UnityImageEffects)
* [NeuralNetworkPostProcessing](https://github.com/maajor/NeuralNetworkPostProcessing) Unity Post Processing with Convolution Neural Network
* [RunwayML-for-Unity](https://github.com/runwayml/RunwayML-for-Unity) RunwayML for Unity 🎯 https://runwayml.com/integrations
* [Procedural-painting](https://github.com/IRCSS/Procedural-painting) Procedural painting algorithms in Unity 3d with compute shaders based on genetic evolution algorithms
* [Waifu2xBarracuda](https://github.com/keijiro/Waifu2xBarracuda) Waifu2x Unity Barracuda implementation
* [barracuda-style-transfer](https://github.com/UnityLabs/barracuda-style-transfer) Companion code for the Unity Style Transfer blog post, showcasing realtime style transfer using Barracuda. 
* [triangle](https://github.com/esimov/triangle) Convert images to computer generated art using delaunay triangulation
* [android-gpuimage](https://github.com/cats-oss/android-gpuimage) Android filters based on OpenGL (idea from GPUImage for iOS)
#### Compression
* [JPEG-MP4-Compression-PostProcessing-Effect-for-Unity3D](https://github.com/JanMalitschek/JPEG-MP4-Compression-PostProcessing-Effect-for-Unity3D) This package aims to accurately recreate the effect of JPEG/MP4 compression as a PostProcessing Effect

## Material
### Shade Model
##### BSDF
* [libbsdf](https://github.com/KimuraRyo/libbsdf) Library for BSDF, BRDF, and BTDF
* [brdf](https://github.com/wdas/brdf) &nbsp;&nbsp; [brdfExplorer](https://github.com/sotnychenko/brdfExplorer)
* [BRDFExplorer](https://github.com/Corralx/BRDFExplorer) http://corralx.github.io/projects
* [Lux](https://github.com/larsbertram69) Lux – open source physically based shader framework for unity
* [Alloy](https://github.com/Josh015/Alloy) Alloy physical shader framework for Unity. https://alloy.rustltd.com/
* [AntonovSuit](https://github.com/cCharkes/AntonovSuit)
* [brdf](https://github.com/boksajak/brdf) Code sample accompanying the article "Crash Course in BRDF Implementation"
* [anisotropic_layered_material](https://github.com/tomoya5296/anisotropic_layered_material) Code for "Real-time Rendering of Layered Materials with Anisotropic Normal Distributions", SIGGRAPH ASIA 2019.
* [WaveOpticsBrdf](https://github.com/lingqi/WaveOpticsBrdf) This code implements the key ideas of the paper: Rendering Specular Microgeometry with Wave Optics, by Ling-Qi Yan, Miloš Hašan, Bruce Walter, Steve Marschner, Ravi Ramamoorthi.
##### SVBRDF
* [svbrdf-oculus](https://github.com/jknuuttila/svbrdf-oculus) materials from Two-Shot SVBRDF Capture for Stationary Materials by Aittala et al (2015).
* [Matmorpher](https://github.com/AlbanGauthier/Matmorpher) Code repository for the EGSR 2021 paper MatMorpher: A Morphing Operator for SVBRDFs
* [DeepInverseRendering](https://github.com/msraig/DeepInverseRendering) Deep Inverse Rendering for High-resolution SVBRDF Estimation from an Arbitrary Number of Images
#### BSSRDF
* [Subsurface-Light-Transport-Raytracer](https://github.com/curranmax/Subsurface-Light-Transport-Raytracer)
* [SingleScatteringEditing](https://github.com/ykcadcg/SingleScatteringEditing)
* [hitchhikersscatter](https://github.com/eugenedeon/hitchhikersscatter) A Hitchhiker’s Guide to Multiple Scattering
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
* [rtswplusd](https://github.com/BastianUrbach/rtswplusd) Real-Time Shading with Polyhedral Lights using Silhouette Detection
* [BezierLightLTC](https://github.com/Paul180297/BezierLightLTC) An official implementation of the paper "Real-Time Shading of Free-Form Area Lights using Linearly Transformed Cosines".

### Character
#### SSS
* [FastTranslucentShader](https://github.com/tatsy/FastTranslucentShader)
* [separable-sss](https://github.com/iryoku/separable-sss) iryoku's SSSSS
* [ScreenSpaceSubsurfaceScattering](https://github.com/Xerxes1138/ScreenSpaceSubsurfaceScattering)
* [SubsurfaceScattering](https://github.com/vcrom/SubsurfaceScattering) An implementation of a set screen space physically-based subsurface scattering algorithms
* [MultipassTranslucency](https://github.com/Philipp-Seifried/MultipassTranslucency) fake subsurface-scattering shader, using multiple passes with different blend ops to calculate thickness without reading back the depth buffer.
#### Skin
* [pbrt-skin-bssrdf](https://github.com/damlaren/pbrt-skin-bssrdf) Implementation of Donner & Jensen's "A Spectral BSSRDF for Shading Human Skin" in PBRT
* [skin-shader-unity](https://github.com/leonardo-domingues/skin-shader-unity) GPU Gems 3 - Chapter 14 using the Unity engine
* [Unity-Human-Skin-Shader-PC](https://github.com/MaxwellGengYF/Unity-Human-Skin-Shader-PC)
* [FaceWorks](https://github.com/NVIDIAGameWorks/FaceWorks) A middleware library and sample application for high-quality skin and eye rendering
#### Eye
#### Hair
* [TressFX](https://github.com/GPUOpen-Effects/TressFX) DirectX 11 library that provides convenient access to realistically rendered and simulated hair and fur
* [vkhr](https://github.com/CaffeineViking/vkhr) Real-Time Hybrid Hair Rendering using Vulkan™
* [WetaHair](https://github.com/zhoub/WetaHair) Implementation of "Importance Sampling for Physically-Based Hair Fiber Models"
* [libWetHair](https://github.com/nepluno/libWetHair) A Multi-Scale Model for Simulating Liquid-Hair Interactions http://libwethair.info
#### Colth
* [libwetcloth](https://github.com/nepluno/libwetcloth) A Multi-Scale Model for Simulating Liquid-Fabric Interactions
* [fabric-micro-detail-scattering](https://github.com/bradweiers/fabric-micro-detail-scattering) Micro Detail Fabric Shader
#### Silk
#### Fur
* [FurRendering](https://github.com/jose-villegas/FurRendering) Fur rendering in Unity with Shell Texturing
* [UnityFurShader](https://github.com/Sorumi/UnityFurShader)  Fur shader for Unity.
* [GIFT_PorterDoll](https://github.com/marza-realtime/GIFT_PorterDoll) PorterDoll Asset wtih "THE GIFT"
* [ShellFurGodot](https://github.com/Arnklit/ShellFurGodot) Add-on that adds a fur node to the Godot engine, using a shell based approach to imitate fur strands.
#### Glint 
* [specular-manifold-sampling](https://github.com/tizian/specular-manifold-sampling) Code for "Specular Manifold Sampling for Rendering High-Frequency Caustics and Glints" (SIGGRAPH 2020)
* [real_time_glint](https://github.com/ASTex-ICube/real_time_glint) [real_time_glint_dictgenerator](https://github.com/ASTex-ICube/real_time_glint_dictgenerator) Procedural Physically based BRDF for Real-Time Rendering of Glints.

### Nature
#### Water
* [Ceto](https://github.com/Scrawk/Ceto) :thumbsup: Ceto: Ocean system for Unity  
* [WaterSurfaceWavelets](https://github.com/lecopivo/WaterSurfaceWavelets) Water Surface Wavelets (SIGGRAPH 2018) http://visualcomputing.ist.ac.at/publications/2018/WSW/
* [FSWW](https://github.com/schreckc/FSWW) Fundamental Sources for Water Wave Animation
* [VaOcean](https://github.com/ufna/VaOcean) Ocean Surface Simulation Plugin for Unreal Engine 4
* [OceanProject](https://github.com/UE4-OceanProject/OceanProject) An Ocean Simulation project for Unreal Engine 4
* [Ocean Community Next Gen](https://github.com/eliasts/Ocean_Community_Next_Gen) Next gen iteration of the unity community ocean shader
* [UE4_Dynamic_Water_Project](https://github.com/marvelmaster/UE4_Dynamic_Water_Project) Unreal Engine 4 Dynamic Water Project by marvelmaster
* [WaveWorks](https://github.com/NvPhysX/UnrealEngine/tree/WaveWorks) WaveWorks is a library for simulating wind-driven waves on large bodies of water, in real time, using GPU acceleration.
* [crest-oceanrender](https://github.com/huwb/crest-oceanrender) :thumbsup: Crest is a technically advanced ocean renderer implemented in Unity3D
* [whitecaps](https://github.com/jdupuy/whitecaps)  Real-time Animation and Rendering of Ocean Whitecaps
* [BoatAttack](https://github.com/Verasl/BoatAttack) com.verasl.water-system Gerstner waves water.
* [RealtimeWater](https://github.com/hpatjens/RealtimeWater) implemented based on "Fast Water Simulation for Games Using Height Fields".
* [fft-ocean](https://github.com/jbouny/fft-ocean) WebGL FFT (Fast Fourier transform) ocean rendering for Three.js 
* [EncinoWaves](https://github.com/blackencino/EncinoWaves) Implementation of "Empirical Directional Wave Spectra for Computer Graphics" paper by Christopher Horvath
* [water-wave-packets](https://github.com/jeschke/water-wave-packets) Sandbox binary and source code for the Siggraph 2017 paper "Water Wave Packets" by Stefan Jeschke (NVIDIA) and Chris Wojtan (IST Austria)
* [WaveParticle](https://github.com/AtwoodDeng/WaveParticle) A project for testing the wave particle
* [Wave-Particles-with-Interactive-Vortices](https://github.com/ACskyline/Wave-Particles-with-Interactive-Vortices) A dx12 river renderer using wave particles with interactive vortices.
  
* [UnityWaveEquation](https://github.com/AsehesL/UnityWaveEquation) unity实现二维波方程交互水面与实时焦散
* [WaterCaustics](https://github.com/pabennett/WaterCaustics) Water caustic rendering experiments in OpenGL with Python
* [threejs-caustics](https://github.com/martinRenou/threejs-caustics) Caustics computation using ThreeJS
* [water-demo](https://github.com/shanecelis/water-demo) A port of Evan Wallace's "Water Demo" for WebGL to Unity.

* [Ocean_mobile_with_boat_physic](https://github.com/laurentClave/Ocean_mobile_with_boat_physic) Ocean mobile with boat physic controller
* [Unity-WaterBuoyancy](https://github.com/dbrizov/Unity-WaterBuoyancy) Water Buoyancy Simulation for Unity
* [UnityTerrainErosionGPU](https://github.com/bshishov/UnityTerrainErosionGPU) Hydraulic and thermal erosion with shallow water equations implemented in Unity using compute shaders.
* [DynamicWaterDemo](https://github.com/CaptainProton42/DynamicWaterDemo) A real-time dynamic water simulation with object interaction made entirely within the Godot Engine.

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
* [GLGrassRenderer](https://github.com/LesleyLai/GLGrassRenderer)  implementation of Responsive Real-Time Grass Rendering for General 3D Scenes
* [Grass.DirectX](https://github.com/mreinfurt/Grass.DirectX) Realistic Grass Rendering using DirectX 11 and a geometry-shader based approach.
* [VulkanGrassRendering](https://github.com/moneimne/VulkanGrassRendering) Vulkan implementation of "Responsive Real-Time Grass Rendering for General 3D Scenes" by Jahrmann and Wimmer
* [GPUGrass](https://github.com/MidoriMeng/GPUGrass) real-time grass rendering based on GPU instancing
* [MassiveGrass](https://github.com/mewlist/MassiveGrass) Unity Terrain spawns a large number of grasses along the edge of the tree (shader independent)
* [RheaGrass](https://github.com/Ryan-Gee/RheaGrass) Rhea is a geometry-shader based grass for Unity's Universal Render Pipeline (URP).
#### Tree
* [Vulkan-Forest-Rendering-Engine](https://github.com/Jiaww/Vulkan-Forest-Rendering-Engine) High-Performance Real-Time Forest Rendering Engine developed using Vulkan
#### Terrain
* [Terrain-Topology-Algorithms](https://github.com/Scrawk/Terrain-Topology-Algorithms) Terrain topology algorithms in Unity
* [tin-terrain](https://github.com/heremaps/tin-terrain) A command-line tool for converting heightmaps in GeoTIFF format into tiled optimized meshes.
* [TerrainPrettifier](https://github.com/Fewes/TerrainPrettifier) A small GPU-based component designed to aid in cleaning and refining satellite/DEM based terrains directly inside Unity.
* [PVTUT](https://github.com/ACskyline/PVTUT) Procedural Virtual Texture with Unity Terrain
* [terrain-erosion-3-ways](https://github.com/dandrino/terrain-erosion-3-ways) Three Ways of Generating Terrain with Erosion Features
* [Webgl-Erosion](https://github.com/LanLou123/Webgl-Erosion) Erosion simulation in Web Browser
* [TerraForge3D](https://github.com/Jaysmito101/TerraForge3D) Cross Platform Professional Procedural Terrain Generation & Texturing Tool
* [Terrain-Decorator](https://github.com/emrecancubukcu/Terrain-Decorator) lightweight terrain tool for unity3d
* [ProceduralTerrain](https://github.com/theSoenke/ProceduralTerrain) Procedural voxel terrain generation in Unity
#### Cloud
* [volsample](https://github.com/huwb/volsample) Research on sampling methods for real-time volume rendering
* [kode80CloudsUnity3D](https://github.com/kode80/kode80CloudsUnity3D) A realtime volumetric cloud rendering solution for Unity3D. 
* [clouds](https://github.com/greje656/clouds) Volumetric Clouds plugin for Stingray
* [Meteoros](https://github.com/Aman-Sachan-asach/Meteoros) Real-time Cloudscape Rendering in Vulkan based on the implementation of clouds in the Decima Engine.
* [Custom-Middleware](https://github.com/ConfettiFX/Custom-Middleware) Ephemeris 2 is a middleware solution for implementing a dynamic 24 hour Skydome System. 
* [VolumeCloud](https://github.com/yangrc1234/VolumeCloud) Volume cloud for Unity3D
* [Clouds](https://github.com/SebLague/Clouds) https://www.youtube.com/watch?v=4QOcCGI6xOU
* [TerrainEngine-OpenGL](https://github.com/fede-vaccaro/TerrainEngine-OpenGL)  renders an (almost) procedural scene, featuring a terrain with distance adaptive LOD, water surface simulation and volumetric clouds.
* [realtime_clouds](https://github.com/clayjohn/realtime_clouds) Experiment with generating clouds in real time on low end computer
* [Marshmallow](https://github.com/mccannd/Project-Marshmallow) Vulkan-based implementation of clouds from Decima Engine
* [volumetric-clouds](https://github.com/jaagupku/volumetric-clouds) Volumetric clouds in Unity
* [Raymarch-Clouds](https://github.com/Flafla2/Raymarch-Clouds) Unity Iq's Clouds.
* [droplet-render](https://github.com/jaelpark/droplet-render) Volumetric cloud modeling and rendering for Blender.
* [Mesh-Cloud-Rendering](https://github.com/maajor/Mesh-Cloud-Rendering) Reimplement Sea of Thieves's Cloud in Unity
* [UnlitClouds](https://github.com/AlexStrook/UnlitClouds) A unity cloud shader, using vertex colors and tessellation for a simple stylized look.
#### Sky
* [SkyboxPanoramicShader](https://github.com/Unity-Technologies/SkyboxPanoramicShader) 
* [SkyModels](https://github.com/diharaw/SkyModels) A collection of various Sky Models implemented with OpenGL compute shaders suitable for real-time rendering.
* [sun-sky](https://github.com/andrewwillmott/sun-sky) Various sun/sky models, convolution of theta/gamma-parameterised models
* [nvjob-sky-shader-simple-and-fast](https://github.com/nvjob/nvjob-sky-shader-simple-and-fast) #NVJOB Dynamic Sky. Sky Shaders. Free Unity Asset.
#### Rain
* [Unity-Raindrops](https://github.com/ya7gisa0/Unity-Raindrops) raindrops shader
* [RainDropEffect](https://github.com/EdoFrank/RainDropEffect) Rain Drop Effect2: Effective, Fast and Flexible Rain Distortion Effect for Unity
* [LensRain](https://github.com/Kink3d/LensRain) A screen-space lens rain effect using Unity's V2 Post-processing framework.
* [RainFX](https://github.com/smkplus/RainFX) Natural Rain
#### Fire
* [fire](https://github.com/robertcupisz/fire) A fire effect for Unity.
* [volumetric-fire](https://github.com/jaagupku/volumetric-fire) Project for Computer Graphics course by Jaagup Kuhi, Siim Raudsepp and Andri Poolakese
#### Ice
#### Iridescent
* [Iridescence](https://github.com/Xerxes1138/Iridescence)
* [Iridescent Shader](https://github.com/smkplus/Iridescence) Iridescence shader
* [SoapFlow](https://github.com/amandaghassaei/SoapFlow) a fluid simulation of a 2D soap film
#### Glass
* [unity-frosted-glass](https://github.com/andydbc/unity-frosted-glass) Test of a frosted glass material in Unity.
#### Gem
* [UnityRayTracingGem](https://github.com/Sorumi/UnityRayTracingGem)  Ray tracing gem shader for Unity

## Environment
#### VolumetricLight
* [VolumetricLights](https://github.com/SlightlyMad/VolumetricLights) Volumetric Lights for Unity
* [LightShafts](https://github.com/robertcupisz/LightShafts) A light shafts (volumetric shadows) effect for Unity.
* [VolumetricLighting](https://github.com/NVIDIAGameWorks/VolumetricLighting) NVIDIA Gameworks Volumetric Lighting
* [VolumetricLighting](https://github.com/Unity-Technologies/VolumetricLighting) ighting effects implemented for the Adam demo: volumetric fog, area lights and tube lights
* [Aura](https://github.com/raphael-ernaelsten/Aura) Volumetric Lighting for Unity
* [Vapor](https://github.com/ArthurBrussee/Vapor) Volumetric Fog for Unity
* [unity-volumetric-fo](https://github.com/SiiMeR/unity-volumetric-fog) A volumetric fog implementation in Unity
#### FakeVolumetricLight
* [VolumetricTracer](https://github.com/Fewes/VolumetricTracer) A simple way to render soft, volumetric bullet tracers in Unity. Only needs a unit cube and a material to render and supports instancing.
#### Atmospheric
* [UnrealEngineSkyAtmosphere](https://github.com/sebh/UnrealEngineSkyAtmosphere) A Scalable and Production Ready Sky and Atmosphere Rendering Technique
* [AtmosphericScattering](https://github.com/SlightlyMad/AtmosphericScattering) Atmospheric Scattering for Unity
* [precomputed_atmospheric_scattering](https://github.com/ebruneton/precomputed_atmospheric_scattering) Eric Bruneton, 2017
* [Brunetons-Improved-Atmospheric-Scattering](https://github.com/Scrawk/Brunetons-Improved-Atmospheric-Scattering) Eric Bruneton for Unity, 2017 [LWRP ver(greje656)](https://github.com/greje656/Brunetons-Improved-Atmospheric-Scattering)
* [clear-sky-models](https://github.com/ebruneton/clear-sky-models) This project implements 8 clear sky models in a common framework to compare them with each other and with a reference model and reference measurements.  
* [OutdoorLightScattering](https://github.com/GameTechDev/OutdoorLightScattering) Outdoor Light Scattering Sample
* [Scatterer](https://github.com/LGhassen/Scatterer) Atmospheric scattering mod for KSP 
* [tectonics.js](https://github.com/davidson16807/tectonics.js/tree/master/precompiled) 3d plate tectonics in your web browser
* [MinimalAtmosphere](https://github.com/Fewes/MinimalAtmosphere) A minimal atmospheric scattering implementation for Unity
* [glsl-atmosphere](https://github.com/wwwtyro/glsl-atmosphere) Renders sky colors with Rayleigh and Mie scattering.
#### Fog
* [UEShaderBits-GDC-Pack](https://github.com/sp0lsh/UEShaderBits-GDC-Pack)  UE4 Volumetric Fog Techniques
* [SSMS](https://github.com/OCASM/SSMS) Screen space multiple scattering for Unity.
* [GPU-Fog-Particles](https://github.com/MirzaBeig/GPU-Fog-Particles) Textureless fog particles using a highly customizable shader to attenuate noise values.
## Render Path
* [VolumeTiledForwardShading](https://github.com/jpvanoosten/VolumeTiledForwardShading) :thumbsup: Volume Tiled Forward Shading. This technique is based on Tiled and Clustered Forward Shading (Olsson, 2012)
* [HybridRenderingEngine](https://github.com/Angelo1211/HybridRenderingEngine) Clustered Forward/Deferred renderer with Physically Based Shading, Image Based Lighting and a whole lot of OpenGL.  
* [ClusteredShadingAndroid](https://github.com/GameTechDev/ClusteredShadingAndroid) and [IntelForwardClusteredShading](https://software.intel.com/en-us/articles/forward-clustered-shading) Clustered shading on Android sample  
* [clustered_forward_demo](https://gitlab.com/efficient_shading/clustered_forward_demo) Ola Olsson. 
* [Cluster](https://github.com/pezcode/Cluster) Clustered shading implementation with bgfx
* [ClusteredShadingConservative](https://github.com/kevinortegren/ClusteredShadingConservative) DirectX 12 light culling technique featured in GPU Pro 7  
* [lightindexed-deferredrender](https://github.com/dtrebilco/lightindexed-deferredrender) Light Indexed Deferred Rendering - Before there was Forward+ and Clustered deferred rendering there was Light Indexed Deferred Rendering (ShaderX7)  
* [Vulkan-Forward-Plus-Renderer](https://github.com/WindyDarian/Vulkan-Forward-Plus-Renderer) Forward+ renderer in Vulkan using Compute Shader. An Upenn CIS565 final project. 
* [nTiled](https://github.com/BeardedPlatypus/nTiled) nTiled - forward and deferred openGL renderer with support for Tiled Shading, Clustered Shading and Hashed Shading
* [DeferredTexturing](https://github.com/TheRealMJP/DeferredTexturing) A rendering sample that demonstrates bindless deferred texturing using D3D12
* [SweetTexelShading](https://github.com/julhe/SweetTexelShading) Texel-Shading (experimental!) with Unity's ScriptableRenderPipeline

## Camera 
#### Physically Based Camera
* [Physical-Camera](https://github.com/Unity-Technologies/Physical-Camera) Unity Component that can describes a physical camera's attributes.
* [pbc](https://github.com/kiwaiii/pbc) Physically based camera
* [Cat-Physically-Based-Camera](https://github.com/JoachimCoenen/Cat-Physically-Based-Camera) a physically based camera component for Unity
#### DOF
* [HexBokehBlur](https://github.com/zigguratvertigo/HexBokehBlur) Hexagonal Bokeh Blur
* [BokehDepthOfField](https://github.com/Erfan-Ahmadi/BokehDepthOfField) Implementing Different Algorithms to mimic Bokeh Depth Of Field: A Physical Camera Effect created due to Focal Length, Aperture size, shape
* [VVDoFDemo](http://graphics.cs.williams.edu/papers/DepthOfFieldGPUPro2013/VVDoFDemo.zip)
#### Lens
* [PhysicallyBasedLensFlare](https://github.com/greje656/PhysicallyBasedLensFlare) Lens flare
* [LightLeaksUnity](https://github.com/danielzeller/LightLeaksUnity) Light Leaks Image Effects for Unity
* [hdreffects](https://github.com/karimnaaji/hdreffects) High dynamic range rendering, with lens flare approximation and bloom 
* [LensFlares](https://github.com/dotsquid/LensFlares) Simple GPU Occlusion for Lens Flares
* [UnityOcclusionLensFlare](https://github.com/pschraut/UnityOcclusionLensFlare) A Lens Flare effect for Unity that doesn't require Physics.

## Standard Format
* [OpenShadingLanguage](https://github.com/imageworks/OpenShadingLanguage) Advanced shading language for production GI renderers
* [glTF-SDK](https://github.com/Microsoft/glTF-SDK) glTF-SDK is a Software Development Kit for glTF 
* [cgltf](https://github.com/jkuhlmann/cgltf) Single-file glTF 2.0 loader and writer written in C99
* [fx-gltf](https://github.com/jessey-git/fx-gltf) A C++14/C++17 header-only library for simple, efficient, and robust serialization/deserialization of glTF 2.0
* [gltf-pipeline](https://github.com/CesiumGS/gltf-pipeline) Content pipeline tools for optimizing glTF assets
* [glTFast](https://github.com/atteneder/glTFast) Efficient glTF 3D import / export package for Unity
* [fastgltf](https://github.com/spnda/fastgltf) A blazing fast C++17 glTF library powered by SIMD.
* [SharpGLTF](https://github.com/vpenades/SharpGLTF) glTF reader and writer for .NET Standard
* [USD](https://github.com/PixarAnimationStudios/USD) Universal Scene Description http://www.openusd.org
* [MaterialX](https://github.com/materialx/MaterialX) MaterialX is an open standard for transfer of rich material and look-development content between applications and renderers.
* [MDL](https://github.com/NVIDIA/MDL-SDK) NVIDIA Material Definition Language SDK
* [OpenMeshEffect](https://github.com/eliemichel/OpenMeshEffect) OpenFX Mesh Effect API - A plug-in API for cross-software procedural mesh effects

## Stylize
#### NPR
* [NPR_Lab](https://github.com/candycat1992/NPR_Lab) Test some NPR in Unity.
* [JasonMaToonRenderPipeline](https://github.com/Jason-Ma-233/JasonMaToonRenderPipeline) JTRP : Unity HDRP ToonShading Render Pipeline (Preview) 
* [UnityURPToonLitShaderExample](https://github.com/ColinLeung-NiloCat/UnityURPToonLitShaderExample) A very simple toon lit shader example, for you to learn writing custom lit shader in Unity URP
* [ToonShading](https://github.com/Kink3d/ToonShading) A collection of "Toon" shaders for Unity based on a stepped PBR approximation.
* [kamakura-shaders](https://github.com/kayac/kamakura-shaders) NPR for Unity with a bunch of features and adjustable parameters in a user-friendly interface.
* [UnityChanToonShaderVer2_Project](https://github.com/unity3d-jp/UnityChanToonShaderVer2_Project) UnityChanToonShaderVer2 Project / v.2.0.7 Release 
* [MToon](https://github.com/Santarh/MToon) Toon Shader with Unity Global Illumination
* [lilToon](https://github.com/lilxyzw/lilToon) Feature-rich shaders for avatars
* [PoiyomiToonShader](https://github.com/poiyomi/PoiyomiToonShader) A feature rich toon shader for unity and VR Chat
* [Xiexes-Unity-Shaders](https://github.com/Xiexe/Xiexes-Unity-Shaders) A re-write and restructure of XSToon.
* [MNPR](https://github.com/semontesdeoca/MNPR) An expressive non-photorealistic rendering framework for real-time, filter-based stylization pipelines within Maya. http://mnpr.artineering.io     
* [Wind-Waker-Shader](https://github.com/albertomelladoc/Wind-Waker-Shader) Cel Shading of two thresholds with a blur/gradient between them
* [ChinesePaintingDemo](https://github.com/AtwoodDeng/ChinesePaintingDemo) Demo of Chinese Painting Shader
* [WaterColorFilter](https://github.com/nobnak/WaterColorFilter) WaterColorFilter for Unity
* [ToonLandscape3](https://github.com/chrisloop/ToonLandscape3) ToonLandscape3
* [URP_StylizedLitShader](https://github.com/madumpa/URP_StylizedLitShader) Madumpa's URP Stylized Lit Shader Repository
* [Toon-Shader](https://github.com/SnutiHQ/Toon-Shader) A character focused Toon Shader for Unity using Shader Graph.
* [BotW-ToonShader](https://github.com/ciro-unity/BotW-ToonShader) A recreation of Zelda: Breath of the Wild's toon shader in Unity, using Shader Graph
* [LiliumToonGraph](https://github.com/you-ri/LiliumToonGraph) UniversalRP Toon Shader with ShaderGraph
* [UNITY-Arc-system-Works-Shader](https://github.com/Aerthas/UNITY-Arc-system-Works-Shader) Shader created to emulate the design style of Arc System Works games such as Guilty Gear and Dragon Ball FighterZ. Created using Amplify Shader Editor.
* [Blender-miHoYo-Shaders](https://github.com/Festivize/Blender-miHoYo-Shaders) Shaders for Blender attempting to replicate the shading of games developed by miHoYo. These shaders are especially for datamined assets, not custom-made ones nor the MMD variants.
#### Low Poly
* [LowpolyOcean](https://github.com/JiongXiaGu/LowpolyOcean) low polygon water effect working in Unity
* [Lowpoly-Water-Unity](https://github.com/danielzeller/Lowpoly-Water-Unity) Low poly water with edge/shore blend. Similar to the awesome water in Monument Valley.  
* [FlatShader](https://github.com/cjurjiu/FlatShader) A very simple shader which performs flatshading without the need for duplicating vertices when building the geometry.
#### Voxel
* [Magicavoxel](https://github.com/ephtracy/ephtracy.github.io/releases) http://ephtracy.github.io/
* [UE4VoxelTerrain](https://github.com/bw2012/UE4VoxelTerrain) Unreal Engine 4: Smooth voxel terrian 
* [VoxelPlugin](https://github.com/Phyronnaz/VoxelPlugin) Voxel plugin for Unreal Engine
* [voxelizer](https://github.com/karimnaaji/voxelizer)  Header only mesh voxelizer in c99 
* [gpu-physics-unity](https://github.com/jknightdoeswork/gpu-physics-unity)  A GPU Accelerated Voxel Physics Solver for Unity
* [Field3D](https://github.com/imageworks/Field3D) A library for storing voxel data on disk and in memory.  
* [magicavoxel-shaders](https://github.com/lachlanmcdonald/magicavoxel-shaders) Shaders for MagicaVoxel to simplify common and repetitive tasks.  
* [UnityVOXFileImport](https://github.com/ray-cast/UnityVOXFileImport) A tool to import a .vox file for Unity's GameObject and Prefab
* [Terasology](https://github.com/MovingBlocks/Terasology) open source voxel world http://terasology.org
* [VoxelSpace](https://github.com/s-macke/VoxelSpace) errain rendering algorithm in less than 20 lines of code 
* [unity-voxel](https://github.com/mattatz/unity-voxel) Mesh voxelization for Unity.
* [tsdf-fusion](https://github.com/andyzeng/tsdf-fusion) Fuse multiple depth frames into a TSDF voxel volume.
* [Marching-Cubes-Terrain](https://github.com/Eldemarkki/Marching-Cubes-Terrain) Marching Cubes terrain implementation in Unity using the Job System and the Burst compiler
* [smoothvoxels](https://github.com/jel-app/smoothvoxels) 

## Volume Rendering
#### RayMarch
* [uRaymarching](https://github.com/hecomi/uRaymarching)  Raymarching Shader Generator in Unity  
* [unity-ray-marching](https://github.com/TheAllenChou/unity-ray-marching) Ray Marching Sandbox
* [unity-volume-rendering](https://github.com/mattatz/unity-volume-rendering) Volume rendering by object space raymarching for Unity.
* [Texture3DPreview-for-Unity](https://github.com/raphael-ernaelsten/Texture3DPreview-for-Unity) This package enables interactive previews of Texture3D assets in Unity's Inspector window. 
* [UnityVolumeRendering](https://github.com/mlavik1/UnityVolumeRendering) A volume renderer, made in Unity3D. See slides from presentation here: https://speakerdeck.com/mlavik1/volume-rendering-in-unity3d
* [unity-ray-marching](https://github.com/brianasu/unity-ray-marching)  Ray marching for rendering 3D noise and textures in Unity 3D
* [UE4_VolumeRaymarching](https://github.com/TheHugeManatee/UE4_VolumeRaymarching) Plugin for UE4 to perform volume raycasting
#### Point Clouds
* [PCL](http://www.pointclouds.org/)  A standalone, large scale, open project for 2D/3D image and point cloud processing.
* [Pcx](https://github.com/keijiro/Pcx) Point cloud importer & renderer for Unity
* [compute_rasterizer](https://github.com/m-schuetz/compute_rasterizer) Rendering Point Clouds with Compute Shaders
* [potree](https://github.com/potree/potree) WebGL point cloud viewer for large datasets
* [point2mesh](https://github.com/ranahanocka/point2mesh) Reconstruct Watertight Meshes from Point Clouds [SIGGRAPH 2020]
#### Shear-warp
#### Other
* [OpenVDB](https://github.com/dreamworksanimation/openvdb) Sparse volume data structure and tools. [OpenVDBForUnity](https://github.com/karasusan/OpenVDBForUnity)
* [unreal-vdb](https://github.com/eidosmontreal/unreal-vdb) This repo is a non-official Unreal plugin that can read OpenVDB and NanoVDB files in Unreal.
* [openvkl](https://github.com/openvkl/openvkl) Intel® Open Volume Kernel Library (Intel® Open VKL) is a collection of high-performance volume computation kernels

## Acceleration
#### Frustum Culling
* [sseculling](https://github.com/nsf/sseculling)
#### PVS
* [kPortals](https://github.com/Kink3d/kPortals) A pre-calculated Portal visibility system for Unity.
* [CornerCulling](https://github.com/87andrewh/CornerCulling) Fast and Maximally Accurate Occlusion Culling
#### ..
* [pipeline](https://github.com/nvpro-pipeline/pipeline) nvpro-pipeline is a research rendering pipeline
* [IndirectOcclusionCulling](https://github.com/JJoosten/IndirectOcclusionCulling) Indirect Occlusion Culling
* [melt](https://github.com/karimnaaji/melt) Automatic conservative mesh occluder generation by box filling
#### Bounding
* [bounding-mesh](https://github.com/gaschler/bounding-mesh) Implementation of the bounding mesh and bounding convex decomposition algorithms for single-sided mesh approximation
#### Soft Occlusion Culling
* [intel_occlusion_cull](https://github.com/rygorous/intel_occlusion_cull)
* [Image-Space-Occlusion-Culling-Engine](https://github.com/lebarba/Image-Space-Occlusion-Culling-Engine) Image Space Occlusion Culling Engine optimized to perform occlusion culling in CPU.
* [Janua](https://github.com/gigc/Janua) Open Source occlusion culling engine for 3D Scenes
* [OcclusionCulling](https://github.com/GameTechDev/OcclusionCulling) software (CPU) based approach to occllusion culling using multi-threading and SIMD instructions to improve performance.
* [rasterizer](https://github.com/rawrunprotected/rasterizer) This project is a state-of-the-art software occlusion culling system.
* [vigilant-system](https://github.com/nlguillemot/vigilant-system)
* [Horus-Unity-Occlusion-Culling](https://github.com/FerzanK/Horus-Unity-Occlusion-Culling) Occlusion culling for Unity
#### Hardware Occlusion Queries
#### Hierarchical-Z Buffer
* [Hierarchical-Z-Buffer](https://github.com/nickdarnell/Hierarchical-Z-Buffer)
#### Hierarchical Occlusion Map
#### GPU-Driven
* [Indirect-Rendering-With-Compute-Shaders](https://github.com/ellioman/Indirect-Rendering-With-Compute-Shaders) Compute shader: Frustum culling,Occlusion culling with HierarchicalZBuffer
* [gpu_occlusion_culling_vk](https://github.com/sydneyzh/gpu_occlusion_culling_vk)  GPU occlusion culling using compute shader with Vulkan  
* [niagara](https://github.com/zeux/niagara) A Vulkan renderer written from scratch on stream
#### Imposter
* [IMP](https://github.com/xraxra/IMP) billboard imposter baking for Unity
* [ImpostorBaker](https://github.com/ictusbrucks/ImpostorBaker) UE4 Plugin for generating Impostors for static meshes  
#### LOD
* [Planet-LOD](https://github.com/sp4cerat/Planet-LOD) Planet Rendering: Adaptive Spherical Level of Detail based on Triangle Subdivision
#### HLOD
* [HLODSystem](https://github.com/Unity-Technologies/HLODSystem) HLOD system
#### Meshlets
* [meshlete](https://github.com/JarkkoPFC/meshlete) Chop 3D objects to meshlets
* [gl_vk_meshlet_cadscene](https://github.com/nvpro-samples/gl_vk_meshlet_cadscene) This OpenGL/Vulkan sample illustrates the use of "mesh shaders" for rendering CAD models.

## Spatial Data Structures
* [aardvark.algodat](https://github.com/aardvark-platform/aardvark.algodat) Aardvark.Algodat is part of the open-source Aardvark platform for visual computing, real-time graphics and visualization
* [Unity_GPUNearestNeighbor](https://github.com/kodai100/Unity_GPUNearestNeighbor) Spatial Hashing Algorithm with GPU Acceleration
* [HashDAG](https://github.com/Phyronnaz/HashDAG) Interactively Modifying Compressed Sparse Voxel Representations
* [aabo](https://github.com/bryanmcnett/aabo) Axis Aligned Bounding Octahedron
* [Transvoxel-XNA](https://github.com/BinaryConstruct/Transvoxel-XNA) Transvoxel implementation in C# for XNA
#### Octree&Quadtree
* [UnityOctree](https://github.com/Nition/UnityOctree) A dynamic, loose octree implementation for Unity written in C#
* [NativeTrees](https://github.com/bartofzo/NativeTrees) Burst compatible Octree and Quadtree for Unity
* [NativeQuadtree](https://github.com/marijnz/NativeQuadtree) A Quadtree Native Collection for Unity DOTS
* [ECS-Octree](https://github.com/Antypodish/ECS-Octree) Unity ECS based octree.
* [ooc_svo_builder](https://github.com/Forceflow/ooc_svo_builder) Out-Of-Core Construction of Sparse Voxel Octrees - reference implementation
* [SparseVoxelOctree](https://github.com/AdamYuan/SparseVoxelOctree) A GPU SVO Builder using rasterization pipeline, a efficient SVO ray marcher and a simple SVO path tracer.
#### KDTree
* [KDTree](https://github.com/viliwonka/KDTree) Fast KDTree for Unity, with thread-safe querying.
* [KdTree](https://github.com/codeandcats/KdTree) A fast, generic, multi-dimensional Binary Search Tree written in C#
* [KNN](https://github.com/ArthurBrussee/KNN) Fast K-Nearest Neighbour Library for Unity DOTS
#### BVH
* [three-mesh-bvh](https://github.com/gkjohnson/three-mesh-bvh) A BVH implementation to speed up raycasting and enable spatial queries against three.js meshes.
* [bhh](https://github.com/bryanmcnett/bhh) Bounding Halfspace Hierarchy
* [Fast-BVH](https://github.com/brandonpelfrey/Fast-BVH) A Simple, Optimized Bounding Volume Hierarchy for Ray/Object Intersection Testing
* [bvh](https://github.com/madmann91/bvh) A modern C++ BVH construction and traversal library
* [bvh](https://github.com/shinjiogaki/bvh) BVH STAR in Japanese
* [bvh_article](https://github.com/jbikker/bvh_article) Code accompanying the blog post on bvh construction.
* [ComputeShaderBVHMeshHit](https://github.com/fuqunaga/ComputeShaderBVHMeshHit) Unity ComputeShader implementation of BVH(Bounding Volume Hierarchy) based mesh hit checking.
#### SDF
* [Discregrid](https://github.com/InteractiveComputerGraphics/Discregrid) A static C++ library for the generation of discrete functions on a box-shaped domain. This is especially suited for the generation of signed distance fields.
* [IsoMesh](https://github.com/EmmetOT/IsoMesh) A group of related tools for Unity for converting meshes into signed distance field data, raymarching signed distance fields, and extracting signed distance field data back to meshes via surface nets or dual contouring.
* [SDFr](https://github.com/xraxra/SDFr) Unity. ECS. Many rays intersect in triangles 
* [MeshToSDF](https://github.com/aman-tiwari/MeshToSDF) Unity. Computer Shader. JFD Generate SDF in realtime
* [Signed-Distance-Field-Generator](https://github.com/danielshervheim/Signed-Distance-Field-Generator) Unity. Computer Shader. Find the nearest distance of the triangle
* [msdfgen](https://github.com/Chlumsky/msdfgen) Multi-channel signed distance field generator
* [Typogenic](https://github.com/Chman/Typogenic) Signed-distance field text rendering for Unity
* [SDF](https://github.com/memononen/SDF) Signed Distance Field Builder for Contour Texturing
* [SDFGen](https://github.com/christopherbatty/SDFGen) A simple commandline utility to generate grid-based signed distance field (level set) generator from triangle meshes
* [DeepSDF](https://github.com/facebookresearch/DeepSDF) Learning Continuous Signed Distance Functions for Shape Representation
* [sdfu](https://github.com/termhn/sdfu) Signed Distance Field Utilities https://crates.io/crates/sdfu
* [mTec](https://github.com/xx3000/mTec)   Rendering the World Using a Single Triangle:Efficient Distance Field Rendering
* [distance-occlusion](https://github.com/andrewwillmott/distance-occlusion) A library of distance and occlusion generation routines
* [pb_CSG](https://github.com/karl-/pb_CSG) Constructive Solid Geometry (CSG) [csg.js](https://evanw.github.io/csg.js/)
* [rust_test](https://github.com/sebbbi/rust_test) :thumbsup: 
* [snelly](https://github.com/portsmouth/snelly) A system for physically-based SDF (signed distance field) pathtracing in WebGL
* [Signed](https://github.com/markusmoenig/Signed) Signed will be an GPL licensed editor and renderer for procedural Signed Distance Functions (SDFs). 
* [sdf-explorer](https://github.com/tovacinni/sdf-explorer)  JCGT / I3D paper, "A Dataset and Explorer for 3D Signed Distance Functions".

## Transparency
* [unity-dithered-transparency-shader](https://github.com/gkjohnson/unity-dithered-transparency-shader) Unity material and shader for applying clipped, dithered transparency
* [Dithering-Unity3d](https://github.com/mcraiha/Dithering-Unity3d)  Dithering algorithms for Unity3d
* [PreMulAlpha](https://github.com/dtrebilco/PreMulAlpha)  Pre-Multiplied blend mode  
#### OIT
* [Order-Independent-Trasparency](https://github.com/PixelClear/Order-Independent-Trasparency)
* [OIT_Lab](https://github.com/candycat1992/OIT_Lab)
* [oitDemo](https://github.com/turol/oitDemo) Order Independent Transparency In OpenGL 4.x
* [vk_order_independent_transparency](https://github.com/nvpro-samples/vk_order_independent_transparency) Demonstrates seven different techniques for order-independent transparency in Vulkan.
* [PixelSyncOIT](https://github.com/chrismile/PixelSyncOIT) A demo for order independent transparency using pixel synchronization (GL_ARB_fragment_shader_interlock)
#### Optimization
* [OffScreenParticleRendering](https://github.com/slipster216/OffScreenParticleRendering) Off Screen Particle Rendering system for Unity
Other.....
* [TLVulkanRenderer](https://github.com/trungtle/TLVulkanRenderer)  Vulkan-based renderer on real-time transparency

## Differentiable
* [redner](https://github.com/BachiLi/redner) Differentiable rendering without approximation.
* [nvdiffrast](https://github.com/NVlabs/nvdiffrast) Nvdiffrast - Modular Primitives for High-Performance Differentiable Rendering.
* [jrender](https://github.com/Jittor/jrender) Jrender 2.0 (Jittor渲染库)
  
## Math
* [Eigen](https://github.com/eigenteam/eigen-git-mirror) :star: linear algebra: matrices, vectors, numerical solvers, and related algorithms. [Eigen](http://eigen.tuxfamily.org/)
* [MathGeoLib](https://github.com/juj/MathGeoLib) :thumbsup: A C++ library for linear algebra and geometry manipulation for computer graphics
* [GeometricTools](https://github.com/davideberly/GeometricTools) :thumbsup: A collection of source code for computing in the fields of mathematics, geometry, graphics, image analysis and physics.
* [CGAL](https://github.com/CGAL/cgal) geometric algorithms in the form of a C++ library.
* [Mathfs](https://github.com/FreyaHolmer/Mathfs) :thumbsup:  Expanded Math Functionality for Unity
* [glm](https://github.com/g-truc/glm) OpenGL Mathematics (GLM) https://glm.g-truc.net
* [cglm](https://github.com/recp/cglm)  Highly Optimized Graphics Math (glm) for C
* [GEOS](http://trac.osgeo.org/geos) Geometry Engine
* [klein](https://github.com/jeremyong/klein) :thumbsup:  P(R*_{3, 0, 1}) specialized SIMD Geometric Algebra Library https://jeremyong.com/klein
* [MTL](https://svn.simunova.com/svn/mtl4/trunk) Matrix Template Library,  a linear algebra library for C++ programs.
* [DirectXMath](https://github.com/Microsoft/DirectXMath) DirectXMath is an all inline SIMD C++ linear algebra library for use in games and graphics apps
* [polyscope](https://github.com/nmwsharp/polyscope) A prototyping-oriented UI for geometric algorithms https://polyscope.run
* [geogram](https://github.com/BrunoLevy/geogram) a programming library with geometric algorithms
* [geomc](https://github.com/trbabb/geomc) A c++ linear algebra template library  
* [geometry3Sharp](https://github.com/gradientspace/geometry3Sharp) C# library for 2D/3D geometric computation, mesh algorithms, and so on
* [fastapprox](https://github.com/romeric/fastapprox) Approximate and vectorized versions of common mathematical functions
* [hlslpp](https://github.com/redorav/hlslpp) Math library using hlsl syntax with SSE/NEON support 
* [vml](https://github.com/valentingalea/vml)  C++17 GLSL-like vector and matrix math lib
* [mathfu](https://github.com/google/mathfu) C++ math library developed primarily for games focused on simplicity and efficiency. http://google.github.io/mathfu 
* [mathnet-numerics](https://github.com/mathnet/mathnet-numerics) Math.NET Numerics numerics.mathdotnet.com
* [Terathon-Math-Library](https://github.com/EricLengyel/Terathon-Math-Library) C++ math library for 2D/3D/4D vector, matrix, quaternion, and geometric algebra.
* [MathUtilities](https://github.com/zalo/MathUtilities) :thumbsup: A collection of some of the neat math and physics tricks that I've collected over the last few years. 
* [just_math](https://github.com/ramakarl/just_math) Just Math - A collection of pure math demos for computer graphics.
#### MathInShader
* [ShaderFastLibs](https://github.com/michaldrobot/ShaderFastLibs) Shader libraries for fast shader opetations.
#### SH
* [sh-lib](https://github.com/andrewwillmott/sh-lib)  Spherical/zonal harmonics library
* [spherical-harmonics](https://github.com/google/spherical-harmonics)  Spherical harmonics library
* [IntegralSH](https://github.com/belcour/IntegralSH)  Integrating Clipped Spherical Harmonics Expansions
* [HLSL-Spherical-Harmonics](https://github.com/sebh/HLSL-Spherical-Harmonics)  A collection of HLSL functions one can include to use spherical harmonics in shaders.
* [SHTOOLS](https://github.com/SHTOOLS/SHTOOLS) SHTOOLS - Spherical Harmonic Tools https://shtools.github.io/SHTOOLS/
#### Curve
* [tinyspline](https://github.com/msteinbeck/tinyspline) ANSI C library for NURBS, B-Splines, and Bézier curves with interfaces for C++, C#, D, Go, Java, Javascript, Lua, Octave, PHP, Python, R, and Ruby.
* [nurbs](https://github.com/StandardCyborg/nurbs) Non-Uniform Rational B-Splines (NURBS) of any dimensionality 
* [BezierInfo-2](https://github.com/Pomax/BezierInfo-2) The development repo for the Primer on Bézier curves, https://pomax.github.io/bezierinfo
#### FFT
* [benchmarking-fft](https://github.com/project-gemmi/benchmarking-fft)  choosing FFT library
* [VkFFT](https://github.com/DTolm/VkFFT) Vulkan Fast Fourier Transform library
* [GLFFT](https://github.com/Themaister/GLFFT) A C++11/OpenGL library for the Fast Fourier Transform
* [dj_fft](https://github.com/jdupuy/dj_fft) Header only FFT library
#### Sampling
* [SampleZoo](https://github.com/Atrix256/SampleZoo) Simple implementations of sampling patterns, with objective tests to compare them
#### Random
* [pcg-cpp](https://github.com/imneme/pcg-cpp) PCG Random Number Generation

## Image&Color
#### Noise
* [procedural-tileable-shaders](https://github.com/tuxalin/procedural-tileable-shaders) Collection of tileable procedural textures such as: cellular noise, fbm, voronoi, perlin and other.
* [FastNoiseLite](https://github.com/Auburn/FastNoiseLite) Fast Portable Noise Library - C# C++ C Java(Script) HLSL GLSL
* [FastNoise2](https://github.com/Auburn/FastNoise2) Modular node graph based noise generation library using SIMD, C++17 and templates
* [LibNoise.Unity](https://github.com/ricardojmendez/LibNoise.Unity) [libnoise](http://libnoise.sourceforge.net/index.html) Coherent noise library for Unity, a port of LibNoise
* [webgl-noise](https://github.com/stegu/webgl-noise) :star: Procedural Noise Shader Routines compatible with WebGL
* [Wombat](https://github.com/BrianSharpe/Wombat) An efficient texture-free GLSL procedural noise library
* [GPU-Noise-Lib](https://github.com/BrianSharpe/GPU-Noise-Lib) Optimized GPU noise functions and utilities http://briansharpe.wordpress.com/
* [NoiseShader](https://github.com/keijiro/NoiseShader) Noise shader library for Unity
* [OpenSimplex2](https://github.com/KdotJPG/OpenSimplex2) Successors to OpenSimplex Noise, plus updated OpenSimplex.
* [Accidental Noise Library](http://accidentalnoise.sourceforge.net/) generating Perlin noise and other forms of noise in a modular fashion.
* [VisualNoiseDesigner](https://github.com/x0r04rg/VisualNoiseDesigner) Visual Noise Designer for Unity
* [TileableVolumeNoise](https://github.com/sebh/TileableVolumeNoise) Collection of functions that can be used to generate tileable volume/3d noise. An exemple of volume noise functions that can be specifically used for clouds is also presented.
* [CloudNoiseGen](https://github.com/Fewes/CloudNoiseGen)  A static utility class for Unity which handles generating and loading periodic, cloud-like (perlin-worley) 3D noise textures on the GPU.
* [BlueNoiseGenerator](https://github.com/bartwronski/BlueNoiseGenerator) an implementation of a Siggraph 2016 paper "Blue-noise Dithered Sampling" by Iliyan Georgiev and Marcos Fajardo from Solid Angle
* [LowDiscBlueNoise](https://github.com/dcoeurjo/LowDiscBlueNoise) generate 2D point sets which have both low discrepancy and Blue-Noise properties. 
* [glsl-curl-noise](https://github.com/cabbibo/glsl-curl-noise) [CurlNoise](https://github.com/rajabala/CurlNoise)
* [Noice](https://github.com/kecho/Noice) Noise generator utility.
* [psrdnoise](https://github.com/stegu/psrdnoise) Tiling simplex flow noise in 2-D and 3-D compatible with GLSL 1.20 (WebGL 1.0) and above.
#### Computer Vision
* [OpenCV](https://github.com/opencv/opencv) Open Source Computer Vision Library. C# Wrapper [opencvsharp](https://github.com/shimat/opencvsharp)
* [unrealcv](https://github.com/unrealcv/unrealcv) UnrealCV: Connecting Computer Vision to Unreal Engine
#### Image
* [bimg](https://github.com/bkaradzic/bimg) :thumbsup:  Image library.
* [OpenImageIO](https://github.com/OpenImageIO/oiio) OpenImageIO http://www.openimageio.org
* [ImageSharp](https://github.com/SixLabors/ImageSharp) A cross-platform library for the processing of image files; written in C#
* [ImageMagick](https://github.com/ImageMagick/ImageMagick) create, edit, compose, or convert bitmap images. It can read and write images in a variety of formats (over 200) 
* [ImageViewer](https://github.com/kopaka1822/ImageViewer) HDR, PFM, DDS, KTX, EXR, PNG, JPG, BMP image viewer and manipulator
* [GIMP](https://github.com/GNOME/gimp) The GNU Image Manipulation Program
* [psd_sdk](https://github.com/MolecularMatters/psd_sdk) A C++ library that directly reads Photoshop PSD files. 
* [hdrview](https://github.com/wkjarosz/hdrview) High-dynamic range image viewer with an emphasis on examining and comparing images, and including minimalistic tonemapping capabilities.
* [Luminance HDR](https://github.com/LuminanceHDR/LuminanceHDR) A complete workflow for HDR imaging.
#### VectorGraphics
* [vg-renderer](https://github.com/jdryg/vg-renderer)  A vector graphics renderer for bgfx, based on ideas from NanoVG and ImDrawList (Dear ImGUI)
  
#### TextureCompressed
* [nv_dds](https://github.com/paroj/nv_dds) DDS image loader for OpenGL/ OpenGL ES2 http://paroj.github.io/nv_dds/
* [nvidia-texture-tools](https://github.com/castano/nvidia-texture-tools) Texture processing tools with support for Direct3D 10 and 11 formats. 
* [crunch](https://github.com/BinomialLLC/crunch)  Advanced DXTc texture compression and transcoding library http://binomial.info
* [unity-ycca-subsampling](https://github.com/n-yoda/unity-ycca-subsampling) [ChromaPack](https://github.com/keijiro/ChromaPack)   YCCA chroma subsampling technique
* [basis_universal](https://github.com/BinomialLLC/basis_universal)  :star:  Basis Universal GPU Texture and Texture Video Compression Codec
* [bc7enc](https://github.com/richgel999/bc7enc) Single source file BC1-5 and BC7 encoders and BC1-5/7 decoders with MIT or Public Domain licenses
* [bcdec](https://github.com/iOrange/bcdec) Small header-only C library to decompress any BC compressed image
* [astc-encoder](https://github.com/ARM-software/astc-encoder) This is the official repository for the Arm ASTC Encoder, a texture compressor for the Adaptive Scalable Texture Compression data format.
* [brotli_g_sdk](https://github.com/GPUOpen-LibrariesAndSDKs/brotli_g_sdk) Brotli-G SDK provides an improved lossless compression ratio with GPU decompression support than the standard Brotli compression algorithm maintained by the IETF (also known as RFC7932)
* [betsy](https://github.com/darksylinc/betsy) Betsy aims to be a GPU compressor for various modern GPU compression formats such as BC6H, purposedly written in GLSL so that it can be easily incorporated into OpenGL and Vulkan projects.
* [Goofy](https://github.com/SergeyMakeev/Goofy) Goofy - Realtime DXT1/ETC1 encoder
* [GPURealTimeBC6H](https://github.com/knarkowicz/GPURealTimeBC6H) Real-time BC6H compression on GPU
* [ISPCTextureCompressor](https://github.com/GameTechDev/ISPCTextureCompressor) ISPC Texture Compressor
* [tev](https://github.com/Tom94/tev) High dynamic range (HDR) image comparison tool for graphics people with an emphasis on OpenEXR images.
* [KtxUnity](https://github.com/atteneder/KtxUnity) :thumbsup: Load KTX and Basis Universal textures at runtime
* [qoi](https://github.com/phoboslab/qoi) The “Quite OK Image” format for fast, lossless image compression
* [libspng](https://github.com/randy408/libspng) Simple, modern libpng alternative  https://libspng.org/
* [fpng](https://github.com/richgel999/fpng) Super fast C++ .PNG writer/reader
  
#### Color
* [OpenColorIO](https://github.com/imageworks/OpenColorIO) A color management framework for visual effects and animation http://opencolorio.org
* [GLSL-Color-Spaces](https://github.com/tobspr/GLSL-Color-Spaces) Utility functions to convert between various color spaces in GLSL
* [colour](https://github.com/colour-science/colour) Colour Science for Python https://www.colour-science.org  [colour-unity](https://github.com/colour-science/colour-unity)   
* [color](https://github.com/dmilos/color) ++ library thats implemets class color. Available models: RGB, HSL, HSV, CMY, CMYK, YIQ, YUV and growing.  
* [colormap-shaders](https://github.com/kbinani/colormap-shaders) A collection of shaders to draw color maps.

## Mesh
#### IO
* [assimp](https://github.com/assimp/assimp) A library to import and export various 3d-model-formats   
* [open3mod](https://github.com/acgessler/open3mod) Open 3D Model Viewer - A quick and powerful 3D model viewer  
* [DirectXMesh](https://github.com/Microsoft/DirectXMesh)   DirectXMesh geometry processing library
* [OpenFBX](https://github.com/nem0/OpenFBX) Lightweight open source FBX importer
* [fast_obj](https://github.com/thisistherk/fast_obj) Fast C OBJ parser
#### Subdivision
* [OpenSubdiv](https://github.com/PixarAnimationStudios/OpenSubdiv) An Open-Source subdivision surface library. http://graphics.pixar.com/opensubdiv
#### Simplification
* [Fast-Quadric-Mesh-Simplification](https://github.com/sp4cerat/Fast-Quadric-Mesh-Simplification) Mesh triangle reduction using quadrics
* [UnityMeshSimplifier](https://github.com/Whinarn/UnityMeshSimplifier) Mesh simplification for Unity.  
* [simplify](https://github.com/fogleman/simplify) Implementation of Surface Simplification Using Quadric Error Metrics, SIGGRAPH 97, written in Go.
* [SeamAwareDecimater](https://github.com/songrun/SeamAwareDecimater) Mesh simplification with UV's boundary preserved
* [BunnyLOD](https://github.com/dougbinks/BunnyLOD) Cross platform GLFW based port of Stan Melax's BunnyLOD Easy Mesh Simplification
#### Deform  
* [Deform](https://github.com/keenanwoodall/Deform) A framework for deforming meshes in the editor and at runtime in Unity.
#### DelaunayTriangulation
* [Triangle.NET](https://github.com/wo80/Triangle.NET)  :thumbsup:  C# / .NET version of Jonathan Shewchuk's Triangle mesh generator. [Triangle.Net-for-Unity](https://github.com/Nox7atra/Triangle.Net-for-Unity)   
* [voronoi](https://github.com/JCash/voronoi) A C implementation for creating 2D voronoi diagrams
* [poly2tri](https://github.com/greenm01/poly2tri) Fast and Robust Simple Polygon Triangulation With/Without Holes  [poly2tri-cs](https://github.com/MaulingMonkey/poly2tri-cs)  
* [CDT](https://github.com/artem-ogre/CDT) C++ library for constrained Delaunay triangulation (CDT)
* [delaunator](https://github.com/mapbox/delaunator) An incredibly fast JavaScript library for Delaunay triangulation of 2D points
* [unity-triangulation2D](https://github.com/mattatz/unity-triangulation2D) Ruppert's Delaunay Refinement Algorithm in Unity
* [unity-delaunay-triangulation](https://github.com/komietty/unity-voronoi) Voronoi mesh generator
* [Constrained_Delaunay_Triangulation](https://github.com/Samson-Mano/Constrained_Delaunay_Triangulation) Constrained Delaunay Triangulation (CDT) of a random surface domain.
* [Hull-Delaunay-Voronoi](https://github.com/Scrawk/Hull-Delaunay-Voronoi) Hull, Delaunay and Voronoi algorithms in Unity
* [BurstTriangulator](https://github.com/andywiecko/BurstTriangulator) 2d Delaunay triangulation with mesh refinement for Unity with Burst compiler
#### Hull
* [3d-quickhull](https://github.com/karimnaaji/3d-quickhull) Header only 3d quickhull in c99 http://www.karim.naaji.fr/projects/quickhull
* [qhull](https://github.com/qhull/qhull) Qhull development for www.qhull.org
* [unity-convexhull](https://github.com/komietty/unity-convexhull) Realtime convexhull generator
#### Delaunay&Destruction
* [unity-delaunay](https://github.com/OskarSigvardsson/unity-delaunay) A Delaunay/Voronoi library for Unity, and a simple destruction effect
* [Boom.unity](https://github.com/OskarSigvardsson/Boom.unity) Destruction effect in unity
* [ScamScatter](https://github.com/danbystrom/ScamScatter) Open Source Real time procedural mesh destruction for Unity3D
* [unity-destruction](https://github.com/williambl/unity-destruction) An open-source script to destroy objects realistically in Unity3D.
* [OpenFracture](https://github.com/dgreenheck/OpenFracture) Open source mesh slicing/fracturing utility for Unity
#### Slicer
* [ezy-slice](https://github.com/DavidArayan/ezy-slice) An open source mesh slicer framework for Unity3D Game Engine. Written in C#.
#### Modeling
* [Dust3D](https://github.com/huxingyi/dust3d) :thumbsup: a cross-platform 3D modeling software. Auto UV unwrapping, auto rigging with PBR Material support, pose and motion authoring all in one. https://dust3d.org/  
* [meshlab](https://github.com/cnr-isti-vclab/meshlab) MeshLab is mostly based on the mesh processing library VCGlib
* [Mesh-processing-library](https://github.com/Microsoft/Mesh-processing-library) mesh processing techniques in computer graphics published at ACM SIGGRAPH in 1992–1998  
* [pmp-library](https://github.com/pmp-library/pmp-library) The Polygon Mesh Processing Library
* [PyMesh](https://github.com/qnzhou/PyMesh) a rapid prototyping platform focused on geometry processing https://pymesh.readthedocs.io
* [trimesh](https://github.com/mikedh/trimesh) Python library for loading and using triangular meshes.  
* [libigl](https://github.com/libigl/libigl) Simple C++ geometry processing library. 
* [instant-meshes](https://github.com/wjakob/instant-meshes)  Interactive field-aligned mesh generator  
* [openmesh](https://www.openmesh.org/) A generic and efficient polygon mesh data structure  
* [openflipper](https://www.openflipper.org/)   programming framework designed for processing, modeling and rendering of geometric data.
* [cinolib](https://github.com/mlivesu/cinolib) A generic programming header only C++ library for processing polygonal and polyhedral meshes
* [mmg](https://github.com/MmgTools/mmg) open source software for bidimensional and tridimensional remeshing http://www.mmgtools.org
* [Directional](https://github.com/avaxman/Directional) Directional is a C++ library for creating, manipulating and visualizing directional fields on 3D meshes
* [Easy3D](https://github.com/LiangliangNan/Easy3D) A lightweight, easy-to-use, and efficient C++ library for processing and rendering 3D data
#### Sketch
* [monster-mash](https://github.com/google/monster-mash) A new sketch-based modeling and animation tool that allows you to quickly sketch a character, inflate it into 3D, and promptly animate it. 
#### Optimization
* [meshoptimizer](https://github.com/zeux/meshoptimizer) Mesh optimization library that makes indexed meshes more GPU-friendly
#### Compress
* [Compressonator](https://github.com/GPUOpen-Tools/Compressonator) Tool suite for Texture and 3D Model Compression, Optimization and Analysis using CPUs, GPUs and APUs  
* [draco](https://github.com/google/draco) compressing and decompressing 3D geometric meshes and point clouds. 
 #### Reconstruction
 * [meshroom](https://github.com/alicevision/meshroom) 3D Reconstruction Software based on the (AliceVision)[https://github.com/alicevision/AliceVision] framework.
 * [openMVG](https://github.com/openMVG/openMVG)  open Multiple View Geometry library. Basis for 3D computer vision and Structure from Motion.
#### Direction fields 
* [fieldgen](https://github.com/GeometryCollective/fieldgen) Generates high-quality, optimally smooth tangent direction fields on triangle meshes.

## Platform
* [herebedragons](https://github.com/kosua20/herebedragons) A basic 3D scene implemented with various engines, frameworks or APIs.
* [glfw](https://github.com/glfw/glfw) A multi-platform library for OpenGL, OpenGL ES, Vulkan, window and input
* [MoltenVK](https://github.com/KhronosGroup/MoltenVK) Vulkan graphics and compute API, that runs on Apple's Metal graphics framework
* [dxvk](https://github.com/doitsujin/dxvk) Vulkan-based D3D11 implementation for Linux / Wine  

## UI
* [imgui](https://github.com/ocornut/imgui) :star: Dear ImGui: Bloat-free Immediate Mode Graphical User interface for C++ with minimal dependencies  
* [ImGuizmo](https://github.com/CedricGuillemet/ImGuizmo) Immediate mode 3D gizmo for scene editing and other controls based on Dear Imgui
* [nanovg](https://github.com/memononen/nanovg) Antialiased 2D vector drawing library on top of OpenGL for UI and visualizations. 
* [nanogui](https://github.com/wjakob/nanogui) Minimalistic GUI library for OpenGL
* [nuklear](https://github.com/vurtun/nuklear) A single-header ANSI C gui library  
* [AnttWeakbar](https://sourceforge.net/projects/anttweakbar/)  a light and intuitive GUI into OpenGL or DirectX based programs to interactively tweak parameters on-screen.

## Util
* [stb](https://github.com/nothings/stb)
* [debug-draw](https://github.com/glampert/debug-draw)
#### GPGPU
* [arrayfire](https://github.com/arrayfire/arrayfire) ArrayFire: a general purpose GPU library.
* [hipSYCL](https://github.com/illuhad/hipSYCL) Implementation of SYCL for CPUs, AMD GPUs, NVIDIA GPUs
* [Amplifier.NET](https://github.com/tech-quantum/Amplifier.NET) Amplifier allows .NET developers to easily run complex applications with intensive mathematical computation on Intel CPU/GPU, NVIDIA, AMD without writing any additional C kernel code.
* [moderngpu](https://github.com/moderngpu/moderngpu) Patterns and behaviors for GPU computing
* [ILGPU](https://github.com/m4rs-mt/ILGPU) ILGPU JIT Compiler for high-performance .Net GPU programs   www.ilgpu.net
#### JIT
* [taichi](https://github.com/taichi-dev/taichi)  Productive & portable high-performance programming in Python.  taichi-lang.org
* [Halide](https://github.com/halide/Halide) a language for fast, portable data-parallel computation  halide-lang.org
* [warp](https://github.com/NVIDIA/warp) A Python framework for high performance GPU simulation and graphics
* [drjit](https://github.com/mitsuba-renderer/drjit) Dr.Jit — A Just-In-Time-Compiler for Differentiable Rendering

## VFX
* [UnityExperiments](https://github.com/MaxSigma/UnityExperiments) Collection of experimental Unity Projects
* [ShadersForFun](https://github.com/cinight/ShadersForFun) ShadersForFun
* [smo-shaders](https://github.com/daniel-ilett/smo-shaders) A collection of shaders to replicate those used in Super Mario Odyssey's Snapshot Mode.
* [shader-graph-nodes](https://github.com/gilescoope/shader-graph-nodes) Custom Nodes for Unity Shader Graph  
#### Minecraft
* [Wisdom-Shaders](https://github.com/bobcao3/Wisdom-Shaders) A Minecraft shaderspack. Offers high performance with high quality at the same time. https://qionouu.cn/  
* [Ebin-Shaders](https://github.com/BruceKnowsHow/Ebin-Shaders) This is a Minecraft shaderpack for use with Optifine.
* [robobo1221Shaders](https://github.com/robobo1221/robobo1221Shaders)
#### MetaBlobs
* [MetaBlob](https://github.com/danielzeller/MetaBlob) Meta Blobs for Unity 3D.
* [unity-metaball](https://github.com/qine/unity-metaball) unity-metaball
#### Transitions
* [gl-transitions](https://github.com/gl-transitions/gl-transitions) :thumbsup:  The open collection of GL Transitions https://gl-transitions.com/ 
* [ScreenManager](https://github.com/Xerios/ScreenManager) Flexible way to manage screens with transitions for Unity
#### Mesh Cut
* [cross-section](https://assetstore.unity.com/packages/vfx/shaders/cross-section-66300) create a cross section through meshes
* [UnityScreenSpaceBoolean](https://github.com/hecomi/UnityScreenSpaceBoolean) Screen Space Boolean Implementation for Unity. 
* [3DXRayShader_Unity](https://github.com/MdIqubal/3DXRayShader_Unity)  Surface shader. Clips a Model with given plane , applies fresnel on clipped part and highlights the cross section.
#### PageCurl
* [Unity3DBookPageCurl](https://github.com/Dandarawy/Unity3DBookPageCurl) Page curl effect for Unity3D using native UI tools
#### Projector
* [ProjectorForLWRP](https://github.com/nyahoon-games/ProjectorForLWRP)  Projector component
* [DynamicShadowProjectorExtensionForLWRP](https://github.com/nyahoon-games/DynamicShadowProjectorExtensionForLWRP)
#### Decal
* [driven-decals](https://github.com/Anatta336/driven-decals) A mesh-based PBR decal system for Unity's universal render pipeline.
* [ProjectionSpray](https://github.com/sugi-cho/ProjectionSpray) Draw spray to 3D model with Unity.
* [Splatoonity](https://github.com/SquirrelyJones/Splatoonity) Splatoon like painting in Unity 3D
* [DMDecalBuffer](https://github.com/DMeville/DMDecalBuffer) Rendering decals to an offscreen buffer in URP for shader effects
* [SkinnedMeshDecals](https://github.com/naelstrof/SkinnedMeshDecals) An example of rendering decals on SkinnedMesh Renderers in Unity.
#### OutLine
* [UnityFx.Outline](https://github.com/Arvtesh/UnityFx.Outline) Screen-space outlines for Unity3d.  
* [Outline-Effect](https://github.com/cakeslice/Outline-Effect) Outline Image Effect for Unity
* [PixelBaseOutlinePostProcessing](https://github.com/vux427/PixelBaseOutlinePostProcessing) use some unity graphic API to display outline post processing.
* [Outlined-Diffuse-Shader-Fixed](https://github.com/Shrimpey/Outlined-Diffuse-Shader-Fixed) This is a fixed version of diffused outline shader from http://wiki.unity3d.com/index.php/Outlined_Diffuse_3
* [UltimateOutline](https://github.com/Shrimpey/UltimateOutline) The easiest way to achieve outlines in unity.
* [UnityOutlineShader](https://github.com/IronWarrior/UnityOutlineShader) Source code for Outline Shader tutorial for Unity. Detects edges in a scene using the depth and normals buffers.
#### Motion
* [AmplifyMotion](https://github.com/AmplifyCreations/AmplifyMotion) Amplify Motion was the first Full-scene Motion Blur extension for Unity
* [ProceduralMotion](https://github.com/keijiro/ProceduralMotion) A collection of procedural motion scripts for Unity
#### Portal
* [unity-portal-rendering](https://github.com/pr0g/unity-portal-rendering) Super small example of using offscreen render targets to achieve a portal effect in Unity
* [shaders-portal](https://github.com/daniel-ilett/shaders-portal) A showcase of shader effects to replicate portals in videogames.
#### Fractal 
* [ElectricSheep_WebGL](https://github.com/richardassar/ElectricSheep_WebGL) WebGL Electric Sheep Renderer
#### InteriorMapping
* [Unity-InteriorMapping](https://github.com/Gaxil/Unity-InteriorMapping)  Interior mapping shader for Unity with a sample scene. 
#### Dissolve
* [VerticalDissolve](https://github.com/AdultLink/VerticalDissolve)  Procedural vertical dissolve shader. Highly customizable. Tweak edge color, noisiness & waviness, rim light, emission scrolling and more.
#### HoloShield
* [HoloShield](https://github.com/AdultLink/HoloShield) Highly customizable sci-fi shield / force field shader for Unity3D.
#### Glitch
* [CyberPunkEffect](https://github.com/smkplus/CyberPunkEffect) Cyberpunk 2077 Scanning Effect
#### SmearFrame
* [SmearFrame](https://github.com/LuggLD/SmearFrame) Unreal Engine 4 smear frame material effect
* [SmokeBlur](https://github.com/nobnak/SmokeBlur)
#### Matcap 
* [matcaps](https://github.com/nidorx/matcaps) Huge library of matcap PNG textures organized by color
* [spherical-environment-mapping](https://github.com/spite/spherical-environment-mapping) Spherical Environment Mapping GLSL Shader
* [matcap-studio](https://github.com/kchapelier/matcap-studio) An utility to tweak matcaps, with realtime visual feedback.
* [UnityMatCapShader](https://github.com/inoook/UnityMatCapShader) Unity MatCap shader
#### EchoFX
* [unity_echofx](https://github.com/joscanper/unity_echofx) The Division ECHO fx implemented in Unity3D
#### Scan
* [Post-Processing-Scan](https://github.com/MirzaBeig/Post-Processing-Scan)  A 3D scan/sonar-like post-processing effect for Unity. Essentially a visualization of a spherical signed distance field (SDF).
#### Cubism
* [Cubism-Shader](https://github.com/IRCSS/Cubism-Shader) A shader that creates a cubism effect based on voronoi segmentation in Unity 3d
#### Wireframe
* [unity-solidwire-shader](https://github.com/Milun/unity-solidwire-shader) A simple shader which renders stylized wireframes while staying true (within reason) to the visual style of the Vectrex
#### Growth
* [hedera](https://github.com/radiatoryang/hedera) paint 3D ivy in the Unity Editor, watch procedurally generated meshes simulate growth and clinging in real-time
#### BleedingEdge
* [BleedingEdgeEffects_GDC_2020](https://github.com/asaia/BleedingEdgeEffects_GDC_2020) Demo Project for Bleeding Edge Effects on Mobile 2020 GDC talk
#### Cone Light
* [GPU-Line-of-Sight](https://github.com/EntroPi-Games/GPU-Line-of-Sight) GPU Line of Sight / Field of View visualization for Unity
* [unity_coneofsightfx](https://github.com/joscanper/unity_coneofsightfx) This project shows how to implement Commandos cone of sight fx in Unity3D.
* [VisionConeDemo](https://github.com/phanshaw/VisionConeDemo) A demo of using URP RenderFeatures to add a vision cone rendering pass
#### VFXGraph
* [HDRP-Fluvio](https://github.com/miketucker/HDRP-Fluvio) Some early tests of FluvioFX with VFX Graph and HDRP
#### Compute Shader Effect
* [FinalAudition](https://github.com/bonzajplc/FinalAudition) A complete remake of 2005 demo "Final Audition" by Plastic
#### Others
* [Anime-Speed-Lines](https://github.com/MirzaBeig/Anime-Speed-Lines) Post-processing effect to procedurally generate a anime/manga-style vignette of lines typically used to portray speed or surprise.

## Tools
#### UE4
* [UnrealEngine](https://github.com/Gforcex/OpenGraphic/blob/master/UnrealEngine.md)
#### Unity
* [Unity](https://github.com/Gforcex/OpenGraphic/blob/master/Unity.md) 
#### DataExchange
* [Unity-AlembicToVAT](https://github.com/Gaxil/Unity-AlembicToVAT) Alembic to VAT (Vertex Animation Texture) mini tool
* [Unity3D-VATUtils](https://github.com/Bonjour-Interactive-Lab/Unity3D-VATUtils) Extension of VAT shader form sideFX houdini with various utils for Unity
* [VFXGraphSandbox](https://github.com/fuqunaga/VFXGraphSandbox) Unity VFX Graph technical experiment.
* [alembic](https://github.com/alembic/alembic) Alembic is an open framework for storing and sharing scene data that includes a C++ library, a file format, and client plugins and applications. http://alembic.io/
* [AlembicImporter](https://github.com/unity3d-jp/AlembicImporter) Alembic importer and exporter plugin for Unity
#### Shader
* [Pyramid](https://github.com/jbarczak/Pyramid) :thumbsup: Pyramid Shader Analyzer
* [shader-playground](https://github.com/tgjones/shader-playground) :thumbsup: Shader compilers http://shader-playground.timjones.io
* [glsl-optimizer](https://github.com/aras-p/glsl-optimizer) :star: GLSL optimizer based on Mesa's GLSL compiler.
* [glslang](https://github.com/KhronosGroup/glslang) Khronos reference front-end for GLSL and ESSL, and sample SPIR-V generator
* [naga](https://github.com/gfx-rs/naga) Universal shader translation in Rust
* [shaderc](https://github.com/google/shaderc) A collection of tools, libraries and tests for shader compilation.
* [ShaderConductor](https://github.com/microsoft/ShaderConductor) ShaderConductor is a tool designed for cross-compiling HLSL to other shading languages
* [graphicsfuzz](https://github.com/google/graphicsfuzz) A testing framework for automatically finding and simplifying bugs in graphics shader compilers.
* [ComputeSharp](https://github.com/Sergio0694/ComputeSharp) A .NET Standard 2.1 library to run C# code in parallel on the GPU through DX12 and dynamically generated HLSL compute shaders
* [SPIRV-VM](https://github.com/dfranx/SPIRV-VM) Virtual machine for executing SPIR-V
* Shader HighLighting: [HlslTools](https://github.com/tgjones/HlslTools) [nshader](https://github.com/samizzo/nshader) [ShaderlabVS](https://github.com/wudixiaop/ShaderlabVS) 
#### ShaderToy
* [glslViewer](https://github.com/patriciogonzalezvivo/glslViewer) Console-based GLSL Sandbox for 2D/3D shaders shaders
* [SHADERed](https://github.com/dfranx/SHADERed) :star: Lightweight, cross-platform & full-featured shader IDE
* [shader-toy](https://github.com/stevensona/shader-toy) Shadertoy-like live preview for GLSL shaders in Visual Studio Code 
* [ShaderMan](https://github.com/smkplus/ShaderMan) Convert ShaderToy to Unity HLSL/CG https://smkplus.github.io/ShaderMan.io
#### Visual Effects
* [gaffer](https://github.com/GafferHQ/gaffer)  A open source application framework designed specifically for creating tools for use in visual effects production.
* [cortex](https://github.com/ImageEngine/cortex) Libraries for visual effects software development
#### Procedural Texture
* [armorpaint](https://github.com/armory3d/armorpaint) :thumbsup:  3D PBR Texture Painting Software https://armorpaint.org
* [Mixture](https://github.com/alelievr/Mixture) :thumbsup: Mixture is a powerful node-based tool crafted in unity to generate all kinds of textures in realtime
* [material-maker](https://github.com/RodZill4/material-maker) A procedural textures authoring and 3D model painting tool based on the Godot game engine
* [FilterJS](https://github.com/CosmoMyzrailGorynych/FilterJS) A node-based procedural texture generator, written in node.js and powered by WebGL
* [texturelab](https://github.com/njbrown/texturelab) Free, Cross-Platform, GPU-Accelerated Procedural Texture Generator
* [Materialize](https://github.com/maikramer/Materialize) Materialize is a program for converting images to materials for use in video games and similars. 
* [xNormal](http://www.xnormal.net/) A free tool to bake texture maps ( like normal maps and ambient occlusion )
* [FlowmapPainter](http://teckartist.com/?page_id=107)
* [Fornos](https://github.com/caosdoar/Fornos) GPU Texture Baking Tool
* [AwesomeBump](https://github.com/kmkolasinski/AwesomeBump) generate normal, height, specular or ambient occlusion textures from a single image
* [NormalmapGenerator](https://github.com/Theverat/NormalmapGenerator)  A simple program that converts images into normal maps
* [Imogen](https://github.com/CedricGuillemet/Imogen) GPU Texture Generator
* [aobaker](https://github.com/prideout/aobaker) ambient occlusion baking tool
* [TextureGenerator](https://github.com/mtwoodard/TextureGenerator) 3D and 2D Noise/Texture generation using the compute shaders within the Unity engine.
#### Atlas 
* [boundary-first-flattening](https://github.com/GeometryCollective/boundary-first-flattening) Boundary First Flattening (BFF) is a free and open source application for surface parameterization.
* [OptCuts](https://github.com/liminchen/OptCuts) a new parameterization algorithm, jointly optimizes arbitrary embeddings for seam quality and distortion
* [simpleuv](https://github.com/huxingyi/simpleuv) Automatic UV Unwrapping Library for Dust3D
* [xatlas](https://github.com/jpcy/xatlas):thumbsup: Mesh parameterization / UV unwrapping library. A cleaned up version of thekla_atlas
* [thekla_atlas](https://github.com/Thekla/thekla_atlas) Atlas Generation Tool
* [UVAtlas](https://github.com/Microsoft/UVAtlas) UVAtlas isochart texture atlas  
* [Cheetah-Texture-Packer](https://github.com/scriptum/Cheetah-Texture-Packer)  High efficient and fast 2D bin packing tool
* [Unity3D-TextureAtlasSlicer](https://github.com/toxicFork/Unity3D-TextureAtlasSlicer)
* [VaTexAtlas](https://github.com/ufna/VaTexAtlas)  plugin for Unreal Engine 4 that makes texture atlases simpler to use with UMG system.
* [RectangleBinPack](https://github.com/juj/RectangleBinPack) Source code for performing 2d rectangular bin packing. 
* [UnityRuntimeSpriteSheetsGenerator](https://github.com/DaVikingCode/UnityRuntimeSpriteSheetsGenerator) Unity – generate SpriteSheets at runtime!
* [pack-spheres](https://github.com/mattdesl/pack-spheres)  Brute force circle/sphere packing in 2D or 3D
* [texture-defrag](https://github.com/maggio-a/texture-defrag) Texture Defragmentation for Photo-Reconstructed 3D Models 
#### GPU Debug
* [renderdoc](https://github.com/baldurk/renderdoc) A stand-alone graphics debugging tool. https://renderdoc.org
* [tracy](https://github.com/wolfpld/tracy) A real time, nanosecond resolution, remote telemetry, hybrid frame and sampling profiler for games and other applications.
* [CodeXL](https://github.com/GPUOpen-Tools) a comprehensive tool suite that enables developers to harness the benefits of CPUs, GPUs and APUs.
* [LPGPU2-CodeXL](https://github.com/codeplaysoftware/LPGPU2-CodeXL) LPGPU2 CodeXL power performance analysis and feedback tool for GPUs
* [perfdoc](https://github.com/ARM-software/perfdoc) A cross-platform Vulkan layer which checks Vulkan applications for best practices on Arm Mali devices.
* [agi](https://github.com/google/agi) Android GPU Inspector
* [gapid](https://github.com/google/gapid) Graphics API Debugger by google
* [microprofile](https://github.com/zeux/microprofile) embeddable CPU/GPU profiler
* [vogl](https://github.com/ValveSoftware/vogl) OpenGL capture / playback debugger by valve
* [apitrace](https://github.com/apitrace/apitrace) Tools for tracing OpenGL, Direct3D, and other graphics APIs
* [GPUVis](https://github.com/mikesart/gpuvis) GPU Trace Visualizer
* [Remotery](https://github.com/Celtoys/Remotery) Single C file, Realtime CPU/GPU Profiler with Remote Web Viewer
* [BuGLe](https://sourceforge.net/projects/bugle/) BuGLe combines a graphical OpenGL debugger with a selection of filters on the OpenGL command stream. 
* Other: **gDEBugger**, **NVIDIA Nsight**, **Microsoft PIX**

#### ML Modeling
* [GET3D](https://github.com/nv-tlabs/GET3D) A Generative Model of High Quality 3D Textured Shapes Learned from Images (NeurIPS 2022)
* [MeshCNN](https://github.com/ranahanocka/MeshCNN) Convolutional Neural Network for 3D meshes in PyTorch
* [points2surf](https://github.com/ErlerPhilipp/points2surf) Learning Implicit Surfaces from Point Clouds (ECCV 2020)
#### ML Texture
* [Text2Light](https://github.com/FrozenBurning/Text2Light) [SIGGRAPH Asia 2022] Text2Light: Zero-Shot Text-Driven HDR Panorama Generation
* [texturize](https://github.com/texturedesign/texturize) Generate photo-realistic textures based on source images. Remix, remake, mashup! Useful if you want to create variations on a theme or elaborate on an existing texture.
* [Exposure_Correction](https://github.com/mahmoudnafifi/Exposure_Correction) Project page of the paper "Learning Multi-Scale Photo Exposure Correction" (CVPR 2021).
* [Deep_White_Balance](https://github.com/mahmoudnafifi/Deep_White_Balance) Reference code for the paper: Deep White-Balance Editing (CVPR 2020). Our method is a deep learning multi-task framework for white-balance editing.
* [HiDT](https://github.com/saic-mdal/HiDT) Official repository for the paper "High-Resolution Daytime Translation Without Domain Labels" (CVPR2020, Oral)
* [MODNet](https://github.com/ZHKKKe/MODNet) A Trimap-Free Portrait Matting Solution in Real Time [AAAI 2022]
* [segmentation_models.pytorch](https://github.com/qubvel/segmentation_models.pytorch) Segmentation models with pretrained backbones. PyTorch.
* [stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) Stable Diffusion web UI
* [dream-textures](https://github.com/carson-katri/dream-textures) Stable Diffusion built-in to the Blender shader editor
* [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) Real-ESRGAN aims at developing Practical Algorithms for General Image/Video Restoration.
* [TecoGAN](https://github.com/thunil/TecoGAN) a TEmporally COherent GAN for video super-resolution.
* [lama-cleaner](https://github.com/Sanster/lama-cleaner) Image inpainting tool powered by SOTA AI Model. Remove any unwanted object, defect, people from your pictures or erase and replace(powered by stable diffusion) any thing on your pictures.

## SDK&Tutorial
#### SDK Samples
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
* [NVIDIA Direct3D SDK 9](https://developer.download.nvidia.com/SDK/9.5/Samples/samples.html) [download all](https://www.nvidia.com/de-de/drivers/sdk-9/)
* [NVIDIA GameWorks Graphics Samples](https://github.com/lyntel/GraphicsSamples) GameWorks cross-platform graphics API samples
* [GPUOpen-LibrariesAndSDKs](https://github.com/GPUOpen-LibrariesAndSDKs)
* [GPUOpen-Effects](https://github.com/GPUOpen-Effects)
* [NVIDIAGameWorks](https://github.com/NVIDIAGameWorks)
* [opengl-es-sdk-for-android](https://github.com/ARM-software/opengl-es-sdk-for-android)
* [powervr-graphics](https://github.com/powervr-graphics)
* [GodComplex](https://github.com/Patapom/GodComplex)
#### Book Code
* [d3d12book](https://github.com/d3dcoder/d3d12book) Sample code for the book "Introduction to 3D Game Programming with DirectX 12"
* [OpenGLInsightsCode](https://github.com/OpenGLInsights/OpenGLInsightsCode)
* [GraphicsGems](https://github.com/erich666/GraphicsGems)
* [GPUZen](https://github.com/wolfgangfengel/GPUZen)
* [ray-tracing-gems](https://github.com/Apress/ray-tracing-gems)
* [jgt-code](https://github.com/erich666/jgt-code) Code developed for articles in the "Journal of Graphics Tools"
#### Graphics Awesome
* [graphics-resources](https://github.com/mattdesl/graphics-resources) a list of graphic programming resources  
* [awesome-graphics](https://github.com/ericjang/awesome-graphics) Curated list of computer graphics tutorials and resources  
* [awesome-vulkan](https://vinjn.github.io/awesome-vulkan/) A curated list of awesome Vulkan libraries
* [awesome-opengl](https://github.com/eug/awesome-opengl) A curated list of awesome OpenGL libraries, debuggers and resources.
#### Book&Tutorial
* [thebookofshaders](https://github.com/patriciogonzalezvivo/thebookofshaders)
* [ShaderTutorials](https://github.com/Xibanya/ShaderTutorials) Shaders For People Who Don't Know How To Shader, a tutorial series for beginners!
* [ekzhang/graphics-workshop](https://github.com/ekzhang/graphics-workshop) Learn computer graphics by writing GPU shaders!

## Animation
* [ozz-animation](https://github.com/guillaumeblanc/ozz-animation) open source c++ 3d skeletal animation library and toolset
* [DMotion](https://github.com/gamedev-pro/dmotion) DMotion - A high level Animation Framework for Unity DOTS
* [Mesh-Animation](https://github.com/codewriter-packages/Mesh-Animation) Mesh Animation is lightweight library for rendering hundreds of meshes in one draw call with GPU instancing.
* [acl](https://github.com/nfrechette/acl) Animation Compression Library
* [cal3d](https://sourceforge.net/projects/cal3d/) Askeletal based 3d character animation library written in C++ in a platform-/graphic API-independent way.
* [GPUSkinning](https://github.com/chengkehan/GPUSkinning)
* [Animation-Texture-Baker](https://github.com/sugi-cho/Animation-Texture-Baker) Animation Texture Baker for Unity
* [UE4_MotionMatching-](https://github.com/Hethger/UE4_MotionMatching-) Early Implementation of Motion Matching tech
* [skeleton-builder](https://github.com/alecjacobson/skeleton-builder)
* [hazumu](https://github.com/emily-vo/hazumu) Raytracing Skeletal Animation
* [ssds](https://github.com/TomohikoMukai/ssds) An implementation of Skinning Decomposition with Similarity Transformations (I3D2018)
#### ML
* [AI4Animation](https://github.com/sebastianstarke/AI4Animation) Character Animation in Unity3D using Deep Learning and Artificial Intelligence
#### Bone
* [uSpringBone](https://github.com/EsProgram/uSpringBone) High performance SpringBone using ECS and JobSystem in Unity.
* [UnityChanSpringBone](https://github.com/unity3d-jp/UnityChanSpringBone) UnityChan Sping Bone System for lightweight secondary animations
* [SPCRJointDynamics](https://github.com/SPARK-inc/SPCRJointDynamics) 布風骨物理エンジン
* [EZSoftBone](https://github.com/EZhex1991/EZSoftBone) A simple kinetic simulator for Unity, you can use it to simulate hair/tail/breast/skirt and other soft objects
* [dem-bones](https://github.com/electronicarts/dem-bones) An automated algorithm to extract the linear blend skinning (LBS) from a set of example poses
* [KawaiiPhysics](https://github.com/pafuhana1213/KawaiiPhysics) Simple fake Physics for UnrealEngine4 & 5
#### IK
* [SimpleIK](https://github.com/ditzel/SimpleIK) Unity Inverse Kinematics made easy
#### Skin
* [DQ-skinning-for-Unity](https://github.com/ConstantineRudenko/DQ-skinning-for-Unity) DQ-skinning
* [dem-bones](https://github.com/electronicarts/dem-bones) An automated algorithm to extract the linear blend skinning (LBS) from a set of example poses

## Particle
* [XParticle](https://github.com/antoinefournier/XParticle)
* [Effekseer](https://github.com/effekseer/Effekseer) This software is a particle effect editing tool. 
* [VolumetricParticles](https://github.com/DaSutt/VolumetricParticles)
* [gpu-particles](https://github.com/Robert-K/gpu-particles) A GPU Particle System for Unity
* [CurlNoiseParticleSystem](https://github.com/edom18/CurlNoiseParticleSystem) Particle system using Curl Noise for Unity.

## Visualization
* [VTK](https://www.vtk.org/) The Visualization Toolkit
