# Graphics  

Reference description of modern graphics technologies.

1. _Shading_
     1. The terms
         1. [Specular highlight](https://en.wikipedia.org/wiki/Specular_highlight)
         2. [Diffuse reflection](https://en.wikipedia.org/wiki/Diffuse_reflection)
         3. [Specular reflection](https://en.wikipedia.org/wiki/Specular_reflection)
         4. Ambient Lighting
     2. Interpolation techniques
         1. [Flat shading](https://en.wikipedia.org/wiki/Shading#Flat_shading)
         2. [Gouraud shading](https://en.wikipedia.org/wiki/Gouraud_shading)
         3. [Phong shading](https://en.wikipedia.org/wiki/Phong_shading)
     3. Shading models
         1. [Blinn–Phong shading model](https://en.wikipedia.org/wiki/Blinn%E2%80%93Phong_shading_model)
         2. [Cel shading](https://en.wikipedia.org/wiki/Cel_shading)
         3. [Cook–Torrance model](https://en.wikipedia.org/wiki/Specular_highlight#Cook.E2.80.93Torrance_model)
         4. [Lambertian reflectance](https://en.wikipedia.org/wiki/Lambertian_reflectance)
         5. [Minnaert function](https://en.wikipedia.org/wiki/Minnaert_function)
         6. [Oren–Nayar reflectance model](https://en.wikipedia.org/wiki/Oren%E2%80%93Nayar_reflectance_model)
         7. [Ward anisotropic distribution](https://en.wikipedia.org/wiki/Specular_highlight#Ward_anisotropic_distribution)
         8. [Phong reflection model](https://en.wikipedia.org/wiki/Phong_reflection_model)

2. _Buffers_
    1. [Z-buffer](https://en.wikipedia.org/wiki/Z-buffering)
    2. [Stencil buffer](https://en.wikipedia.org/wiki/Stencil_buffer)
    3. [Index Buffer](http://www.gamedev.ru/code/terms/IndexBuffer)

3. _Texture-based techniques_
    1. [Sprite (computer graphics)](https://en.wikipedia.org/wiki/Sprite_(computer_graphics))
    2. [Reflection mapping](https://en.wikipedia.org/wiki/Reflection_mapping)
    3. [Cube mapping](https://en.wikipedia.org/wiki/Cube_mapping)
    4. [Sphere mapping](https://en.wikipedia.org/wiki/Sphere_mapping)
    5. [Mipmap](https://en.wikipedia.org/wiki/Mipmap)
    6. [Displacement mapping](https://en.wikipedia.org/wiki/Displacement_mapping)
    7. [Bump mapping](https://en.wikipedia.org/wiki/Bump_mapping)
         1. [Diffuse bump mapping](https://www.opengl.org/archives/resources/code/samples/advanced/advanced97/notes/node73.html)
         2. [Specular bump mapping](https://www.opengl.org/archives/resources/code/samples/advanced/advanced97/notes/node73.html)
         3. [Displacement bump mapping](http://www.gamedev.ru/code/terms/BumpMapping)
         4. [Environment map bump mapping](http://developer.download.nvidia.com/assets/gamedev/docs/ReflectiveBumpMapping.pdf)
         5. [Parallax mapping](https://en.wikipedia.org/wiki/Parallax_mapping)
    8. [Heightmap](https://en.wikipedia.org/wiki/Heightmap)
    9. [Deffuse mapping](http://wiki.splashdamage.com/index.php/Basic_Texture_Overview#Diffuse_Maps)
    10. [Normal mapping](https://en.wikipedia.org/wiki/Normal_mapping)
    11. [Image-based lighting](https://en.wikipedia.org/wiki/Image-based_lighting) (Global Illumination algorithm)
    12. [Texture maps](https://en.wikipedia.org/wiki/Texture_mapping#Texture_maps)
    13. [Relief mapping](https://en.wikipedia.org/wiki/Relief_mapping_(computer_graphics)) [(GPU Gems)](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch18.html)
    14. [Parallax occlusion mapping](https://en.wikipedia.org/wiki/Parallax_occlusion_mapping)
    15. [Texture synthesis](https://en.wikipedia.org/wiki/Texture_synthesis)
    16. [Texture atlas](https://en.wikipedia.org/wiki/Texture_atlas)
    17. [UV mapping](https://en.wikipedia.org/wiki/UV_mapping)
    18. [Texture splatting](https://en.wikipedia.org/wiki/Texture_splatting)
    19. [Specular mapping](https://en.wikipedia.org/wiki/Specularity#specular_maps)
    20. [Texture filtering](https://en.wikipedia.org/wiki/Texture_filtering)
         1. [Anisotropic filtering](https://en.wikipedia.org/wiki/Anisotropic_filtering)
         2. [Bilinear filtering](https://en.wikipedia.org/wiki/Bilinear_filtering)
         3. [Trilinear filtering](https://en.wikipedia.org/wiki/Trilinear_filtering)
    21. [DuDv map](http://www.gamedev.ru/code/terms/DuDv)
    22. [Tangent Space](https://www.opengl.org/archives/resources/code/samples/advanced/advanced97/notes/node73.html#SECTION000103100000000000000)

4. _Optimisation_
    1. [Tessellation](https://en.wikipedia.org/wiki/Tessellation_(computer_graphics))
    2. [Level of detail](https://en.wikipedia.org/wiki/Level_of_detail)
         1. [Progressive meshes](https://en.wikipedia.org/wiki/Progressive_meshes)
    3. [Distance fog](https://en.wikipedia.org/wiki/Distance_fog)
    4. [Hidden surface determination](https://en.wikipedia.org/wiki/Hidden_surface_determination)
    5. [Clipping](https://en.wikipedia.org/wiki/Category:Clipping_(computer_graphics))
    6. [Geometry Instancing](https://en.wikipedia.org/wiki/Geometry_instancing) [(GPU Gems)](https://developer.nvidia.com/gpugems/GPUGems2/gpugems2_chapter03.html)
    7. [Impostor](http://www.gamedev.ru/terms/Impostor) [(GPU Gems)](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch21.html)
    8. [PVS: Potentially Visible Set](https://en.wikipedia.org/wiki/Potentially_visible_set)
    9. [Range Fog](http://www.gamedev.ru/code/terms/RangeFog)
    10. [Triangle Strips](http://www.gamedev.ru/code/terms/TriangleStrips)

5. _Shadow_
    1. [Self-shadowing](https://en.wikipedia.org/wiki/Self-shadowing)
    2. [Shadow volume](https://en.wikipedia.org/wiki/Shadow_volume)
         1. [Robust Shadow Volumes](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch11.html)
         2. [CC shadow volumes](https://pdfs.semanticscholar.org/f9b6/186fb8dffa35892af78bf6396123ba06a7d2.pdf)
    3. [Shadow mapping](https://en.wikipedia.org/wiki/Shadow_mapping)
         1. Simple
             1. [SSM &quot;Simple&quot;](http://www.opengl-tutorial.org/intermediate-tutorials/tutorial-16-shadow-mapping/)
         2. Splitting
             1. [PSSM &quot;Parallel Split&quot;](https://habrahabr.ru/post/226421/) [(GPU Gems)](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch10.html)
             2. [CSM &quot;Cascaded&quot;](http://ogldev.atspace.co.uk/www/tutorial49/tutorial49.html)
         3. Warping
             1. [LiSPSM &quot;Light Space Perspective&quot;](https://www.cg.tuwien.ac.at/research/vr/lispsm/#Source) [(3.2.3)](http://resources.mpi-inf.mpg.de/ShadowCourse/coursenotes.pdf) [(t3)](https://users.cg.tuwien.ac.at/scherzer/files/papers/LispSM_survey.pdf)
             2. [TSM &quot;Trapezoid&quot;](http://www.comp.nus.edu.sg/~tants/tsm.html)
             3. [PSM &quot;Perspective&quot;](http://www.comp.nus.edu.sg/~tants/tsm/psm.html)
             4. [CSSM &quot;Camera Space&quot;](http://free-zg.t-com.hr/cssm/)
         4. Smoothing
             1. [PCF &quot;Percentage Closer Filtering&quot;](http://ogldev.atspace.co.uk/www/tutorial42/tutorial42.html)
         5. Filtering
             1. [ESM &quot;Exponential&quot;](http://www.trentreed.net/blog/exponential-shadow-maps/)
                 1. [ESSM &quot;Exponential Soft&quot;](http://www.cad.zju.edu.cn/home/jqfeng/papers/Exponential%20Soft%20Shadow%20Mapping.pdf)
             2. [CSM &quot;Convolution&quot;](https://mericam.github.io/papers/csm.pdf)
             3. [VSM &quot;Variance&quot;](http://student.agh.edu.pl/~mradzisz/EGA/vsm_paper.pdf) [(Nvidia)](http://developer.download.nvidia.com/SDK/10/direct3d/Source/VarianceShadowMapping/Doc/VarianceShadowMapping.pdf)
             4. [SAVSM &quot;Summed Area Variance&quot;](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch08.html) [(Nvidia)](https://www.google.ru/url?sa=t&amp;rct=j&amp;q=&amp;esrc=s&amp;source=web&amp;cd=2&amp;cad=rja&amp;uact=8&amp;ved=0ahUKEwj_qpuW6sHSAhWEKJoKHW51D0oQFggpMAE&amp;url=http%3A%2F%2Fdeveloper.download.nvidia.com%2Fpresentations%2F2007%2Fsiggraph%2FSAVSM.ppt&amp;usg=AFQjCNH4A_n5YXB05Gy_-0K9SA9XL1_9kA&amp;sig2=bhqnwcg4sKRqnMLErJQW6g&amp;bvm=bv.148747831,d.bGs)
             5. [SMSR &quot;Shadow Map Silhouette Revectorization&quot;](http://bondarev.nl/?p=326)
             6. [MSM &quot;Moment&quot;](http://cg.cs.uni-bonn.de/aigaion2root/attachments/MomentShadowMapping.pdf)
         6. Soft Shadows
             1. [PCSS &quot;Percentage Closer&quot;](http://developer.download.nvidia.com/shaderlibrary/docs/shadow_PCSS.pdf)
             2. SSSS &quot;Screen space soft shadows&quot; (GPU Pro 1 p477)
                 1. [SSPCSS &quot;Screen-Space Percentage-Closer Soft Shadows&quot;](https://hal.inria.fr/inria-00536256/file/paper.pdf)
             3. [FIV &quot;Fullsphere Irradiance Vector&quot;](http://getlab.org/publications/FIV/) [(t2)](https://pdfs.semanticscholar.org/e587/1eb96422f220b175e6ebb8debecf52c68950.pdf)
         7. Assorted
             1. [ASM &quot;Adaptive&quot;](http://www.cs.cornell.edu/~kb/publications/ASM.pdf)
             2. [AVSM &quot;Adaptive Volumetric&quot;](http://visual-computing.intel-research.net/art/publications/avsm/)
             3. [CSSM &quot;Camera Space&quot;](http://free-zg.t-com.hr/cssm/)
             4. DASM &quot;Deep Adaptive&quot;
             5. [DPSM &quot;Dual Paraboloid&quot;](http://sites.google.com/site/osmanbrian2/dpsm.pdf)
             6. [DSM &quot;Deep&quot;](http://graphics.pixar.com/library/DeepShadows/paper.pdf)
             7. [FSM &quot;Forward&quot;](http://www.cs.unc.edu/~zhangh/technotes/shadow/shadow.ps)
             8. [LPSM &quot;Logarithmic&quot;](http://gamma.cs.unc.edu/LOGSM/)
             9. [MDSM &quot;Multiple Depth&quot;](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.59.3376&amp;rep=rep1&amp;type=pdf)
             10. [RTW &quot;Rectilinear&quot;](http://www.cspaul.com/wordpress/publications_rosen-2012-i3d/)
             11. [RMSM &quot;Resolution Matched&quot;](http://www.idav.ucdavis.edu/func/return_pdf?pub_id=919)
             12. [SDSM &quot;Sample Distribution&quot;](https://software.intel.com/en-us/articles/sample-distribution-shadow-maps)
             13. [SPPSM &quot;Separating Plane Perspective&quot;](http://image.diku.dk/projects/media/morten.mikkelsen.07.pdf)
             14. [SSSM &quot;Shadow Silhouette&quot;](http://graphics.stanford.edu/papers/silmap/silmap.pdf)

6. _Colour_
    1. [Tone mapping](https://en.wikipedia.org/wiki/Tone_mapping)
    2. [HDR render](https://en.wikipedia.org/wiki/High-dynamic-range_rendering)
    3. [Gamma correction](https://en.wikipedia.org/wiki/Gamma_correction)
        1. [The Importance of Being Linear](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch23.html)

7. _Postprocessing_
    1. [Aliasing](https://en.wikipedia.org/wiki/Aliasing)
        1. Texture filtering
        2. [Spatial anti-aliasing](https://en.wikipedia.org/wiki/Spatial_anti-aliasing)
        3. [Fast approximate anti-aliasing](https://en.wikipedia.org/wiki/Fast_approximate_anti-aliasing)
        4. [Multisample anti-aliasing](https://en.wikipedia.org/wiki/Multisample_anti-aliasing)
        5. [Supersampling](https://en.wikipedia.org/wiki/Supersampling)
        6. [Temporal anti-aliasing](https://en.wikipedia.org/wiki/Temporal_anti-aliasing)
        7. [Xiaolin Wu&#39;s line algorithm](https://en.wikipedia.org/wiki/Xiaolin_Wu%27s_line_algorithm)
    2. [Motion blur](https://en.wikipedia.org/wiki/Motion_blur) [(GPU Gems)](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch27.html)
    3. [Real-Time Glow](https://developer.nvidia.com/gpugems/GPUGems/gpugems_ch21.html)
    4. [Bloom (shader effect)](https://en.wikipedia.org/wiki/Bloom_(shader_effect))
    5. [Lens flare](https://en.wikipedia.org/wiki/Lens_flare)
    6. [Depth of field](https://en.wikipedia.org/wiki/Depth_of_field) [(GPU Gems)](https://developer.nvidia.com/gpugems/GPUGems/gpugems_ch23.html) [(GPU Gems)](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch28.html)
        1. [Accumulation-Buffer Depth of Field](https://pdfs.semanticscholar.org/599f/0ad2594e71738bb2eb40ea34d061e74f4475.pdf)
        2. [Forward-Mapped Z-Buffer Depth of Field](https://www.researchgate.net/publication/220184473_A_Lens_and_Aperture_Camera_Model_for_Synthetic_Image_Generation)
        3. [Layered Depth of Field](http://dl.acm.org/citation.cfm?id=130753) [(t2)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.302.3897&amp;rep=rep1&amp;type=pdf) [(t3)](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2007/EECS-2007-19.pdf)
        4. [Ray-Traced Depth of Field](http://artis.inrialpes.fr/Enseignement/TRSA/CookDistributed84.pdf)
        5. [Reverse-Mapped Z-Buffer Depth of Field](http://developer.download.nvidia.com/assets/gamedev/docs/GDC2002_InGameSpecialEffects.pdf) [(t2)](https://www.cg.tuwien.ac.at/research/publications/2011/Steiner_2011/Steiner_2011-Thesis.pdf)
    7. [Depth-based blur](http://www.gamedev.ru/code/terms/DepthBasedBlur)

8. _Text render_
    1. [Rendering Vector Art on the GPU](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch25.html)

9. [_Blending_](https://en.wikipedia.org/wiki/Blend_modes)
    1. [Alpha compositing](https://en.wikipedia.org/wiki/Alpha_compositing)

10. _Render techniques_
    1. [Tiled rendering](https://en.wikipedia.org/wiki/Tiled_rendering)
    2. [Transform, clipping, and lighting](https://en.wikipedia.org/wiki/Transform,_clipping,_and_lighting)
    3. [Unbiased rendering](https://en.wikipedia.org/wiki/Unbiased_rendering)
    4. [Physically based rendering](https://en.wikipedia.org/wiki/Physically_based_rendering)
    5. [Image-based modeling and rendering](https://en.wikipedia.org/wiki/Image-based_modeling_and_rendering)
    6. [Per-pixel lighting](https://en.wikipedia.org/wiki/Per-pixel_lighting)
    7. [Deferred Shading](https://en.wikipedia.org/wiki/Deferred_shading) [(GPU Gems)](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch17.html)

11. _Material_
    1. [Subsurface scattering](https://en.wikipedia.org/wiki/Subsurface_scattering)
        1. [Depth Map based SSS](https://developer.nvidia.com/gpugems/GPUGems/gpugems_ch16.html)
        2. [Texture space diffusion](http://www.scribblethink.org/Work/Pdfs/Face-s2003.pdf)
    2. [Bidirectional reflectance distribution function](https://en.wikipedia.org/wiki/Bidirectional_reflectance_distribution_function)
        1. [Spatial BRDFs](https://developer.nvidia.com/gpugems/GPUGems/gpugems_ch18.html)
    3. [Bidirectional scattering distribution function](https://en.wikipedia.org/wiki/Bidirectional_scattering_distribution_function)
    4. [Bidirectional scattering-surface reflectance distribution function](http://graphics.stanford.edu/courses/cs448-05-winter/papers/nicodemus-brdf-nist.pdf) [(t2)](http://graphics.ucsd.edu/~henrik/papers/bssrdf/)
    5. [Bidirectional transmittance distribution function](http://proceedings.spiedigitallibrary.org/proceeding.aspx?articleid=1230783)
    6. [The Fresnel coefficients](https://en.wikipedia.org/wiki/Fresnel_equations) [(Коэффициенты Френеля)](http://www.gamedev.ru/code/terms/Fresnel) [(на практике)](http://www.gamedev.ru/code/articles/Glass_modeling)

12. [_Global illumination_](https://en.wikipedia.org/wiki/Global_illumination)
    1. [Ray tracing (graphics)](https://en.wikipedia.org/wiki/Ray_tracing_(graphics))
        1. [Distributed ray tracing](https://en.wikipedia.org/wiki/Distributed_ray_tracing)
        2. [Beam tracing](https://en.wikipedia.org/wiki/Beam_tracing)
        3. [Cone tracing](https://en.wikipedia.org/wiki/Cone_tracing)
    2. [Path tracing](https://en.wikipedia.org/wiki/Path_tracing)
        1. [Volumetric path tracing](https://en.wikipedia.org/wiki/Volumetric_path_tracing)
        2. Bi-directional Path Tracing
        3. Energy Redistriution Path Tracing
    3. [Photon mapping](https://en.wikipedia.org/wiki/Photon_mapping)
        1. Progressive Photon Mapping
        2. Stochastic Progressive Photon Mapping
    4. Lightcuts
        1. Multidimensional Lightcuts
        2. Bidirectional Lightcuts
    5. Point Based Global Illumination
    6. [Radiosity (computer graphics)](https://en.wikipedia.org/wiki/Radiosity_(computer_graphics))
        1. [Hemicube (computer graphics)](https://en.wikipedia.org/wiki/Hemicube_(computer_graphics))
        2. Hierarchical radiosity
        3. Instant Radiosity
        4. Bidirectional Instant Radiosity
    7. [Metropolis light transport](https://en.wikipedia.org/wiki/Metropolis_light_transport)
    8. [Spherical harmonic lighting](https://en.wikipedia.org/wiki/Spherical_harmonic_lighting)
    9. [Ambient occlusion](https://en.wikipedia.org/wiki/Ambient_occlusion)
    10. [Screen space ambient occlusion](https://en.wikipedia.org/wiki/Screen_space_ambient_occlusion)
        1. Screen space directional occlusion
        2. High Definition Ambient Occlusion
        3. Horizon Based Ambient Occlusion+
        4. Alchemy Ambient Occlusion
        5. Angle Based Ambient Occlusion
        6. PBAO
        7. Voxel Accelerated Ambient Occlusion (WSAO)
        8. [(GPU Gems)](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch12.html)
    11. Voxel-based Global Illumination
        1. Voxel Cone Tracing Global Illumination
        2. Sparse Voxel Octree Global Illumination
        3. Voxel Global Illumination (VXGI)
    12. Light Propagation Volumes Global Illumination
    13. Deferred Radiance Transfer Global Illumination
    14. Deep G-Buffer based Global Illumination
    15. Image-based lighting

13. [_Light_](https://en.wikipedia.org/wiki/Shading)
    1. [Lightmap](https://en.wikipedia.org/wiki/Lightmap)
    2. [Rendering equation](https://en.wikipedia.org/wiki/Rendering_equation)
    3. [Directional lighting](https://en.wikipedia.org/wiki/Shading#Directional_lighting)
    4. [Precomputed Radiance Transfer](https://en.wikipedia.org/wiki/Precomputed_Radiance_Transfer)
    5. [Chromatic aberration](https://en.wikipedia.org/wiki/Chromatic_aberration)
    6. [Caustic](https://en.wikipedia.org/wiki/Caustic_(optics))
        1. [Water Caustics](https://developer.nvidia.com/gpugems/GPUGems/gpugems_ch02.html)
    7. Global illumination
    8. Irradiance Volume (Объём освещенности)
    9. LightShafts: Light shafts (световые лучи)
        1. [Volumetric Light Scattering as a Post-Process](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch13.html)
    10. [Simulating Diffraction](https://developer.nvidia.com/gpugems/GPUGems/gpugems_ch08.html)
    11. [Accurate Atmospheric Scattering](https://developer.nvidia.com/gpugems/GPUGems2/gpugems2_chapter16.html)

14. _Useful links_
    1. [Computer graphics data structures](https://en.wikipedia.org/wiki/Category:Computer_graphics_data_structures)
    2. [Mesh generation](https://en.wikipedia.org/wiki/Mesh_generation)
    3. [Glossary of computer graphics](https://en.wikipedia.org/wiki/Glossary_of_computer_graphics)
    4. [Computer graphics algorithms](https://en.wikipedia.org/wiki/Category:Computer_graphics_algorithms)
    5. [Computer graphics](https://en.wikipedia.org/wiki/Portal:Computer_graphics)
    6. [Graphics Pipeline Performance](https://developer.nvidia.com/gpugems/GPUGems/gpugems_ch28.html)

15. _GPU Gems_
    1. Plants
        1. [Next-Generation SpeedTree Rendering](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch04.html)
        2. [GPU-Generated Procedural Wind Animations for Trees](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch06.html)
        3. [Vegetation Procedural Animation and Shading in Crysis](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch16.html)
    2. [Point-Based Visualization of Metaballs on a GPU](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch06.html)
    3. [Advanced Techniques for Realistic Real-Time Skin Rendering](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch13.html)
    4. [Robust Multiple Specular Reflections and Refractions](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch17.html)
    5. [Baking Normal Maps on the GPU](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch17.html)
