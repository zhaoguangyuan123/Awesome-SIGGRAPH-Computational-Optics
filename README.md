# Awesome-SIGGRAPH-Computational-Optics
A curated list of computational Optics-related papers presented on SIGGRAPH.

**Update in Seq. 23, 2023: We changed the repo title from "Computational Imaging" to "Computational Optics," which covers a broader context. 
In the author's view, the updated term computational optics includes at least three scopes:**
- Computational Imaging (Cameras).
- Computational Display (Projector).
- Computational Lithography (Fabrication).


## Author's Intention for this Collection
A good way to master the taste and progress of an area is to read its high-impact papers. 
As a high-profile venue, SIGGRAPH(ASIA) has been publishing top-tier computational Optics papers for decades. However, as computational imaging is a relatively minor and nascent area in SIGGRAPH, only very few (mostly less than 10) computational imaging papers are published on SIGGRAPH every year. The topic and content of computational imaging-related papers are a bit different from the rest of SIGGRAPH papers. Consequently, keeping track of past computational Optics papers is not easy. 

The author gets inspiration from [Krita](https://github.com/tkuri) and many others who are creating awesome lists and this collection to help the community. The author thanks [Ken-sen](https://kesen.realtimerendering.com/) for sharing the SIGGRAPH collection, which facilitates the creation of this list. If you have any suggestions for this list, please do not hesitate to email the author or comment on the issues. 

## TODO
- [x] Get the alpha version of the collection out.
- [ ] Track available papers in the past years.  
- [ ] Finish summaries on papers.  
<!-- 
## Table of contents
- [Illumination Estimation (DL)](#illumination-estimation-dl)
- [Intrinsic Decomposition (non-DL)](#intrinsic-decomposition-non-dl)
- [Intrinsic Decomposition (DL)](#intrinsic-decomposition-dl)
- [code](#code)
 -->

## Terminology of Computational Imaging

<details><summary>Computational Imaging is ... </summary><p> a rapidly emerging field that co-designs the sensing hardware and the algorithms to form images from measurements with indirect reconstructions.
Computational imaging systems enable designers to overcome some hardware limitations of optics and sensors (resolution, noise, etc.). It also has the advantage of probing multi-dimensional light fields (spectral, depth, polarization, etc.). 
 
There is no universal description for computational imaging right now. According to his taste, the author also collects some work (such as computational displays) which are not absolute imaging work but related to the field. </p></details><p></p>


No universal definition for computational imaging exists right now. According to his taste, the author also collects some works (such as computational displays) which are not absolute imaging work but related to the field.  -->


## Contents
<!-- ## Illumination Estimation (DL) -->
|Year|Venue|Paper(w/ code)|Repo (if any)|Summary(if any)|
|---|---|---|---|---|
|2024|SIG|[Zero Grads: Learning Local Surrogate Losses for Non-Differentiable Graphics](https://mfischer-ucl.github.io/zerograds/)|[colab](https://colab.research.google.com/drive/1GNd6DdRGRHQjKyG3rIfJ9519lo9VuAq4?usp=sharing)
|&nbsp;|&nbsp;|[Deep Hybrid Camera Deblurring for Smartphone Cameras](https://cg.postech.ac.kr/research/HCDeblur/)|[code](https://github.com/rimchang/HCDeblur)
|&nbsp;|&nbsp;|[Spin-Weighted Spherical Harmonics for Polarized Light Transport](http://vclab.kaist.ac.kr/publications.html)|
|&nbsp;|&nbsp;|[A Free-Space Diffraction BSDF](https://ssteinberg.xyz/2024/04/05/free_space_diffractions_bsdf/)|
|&nbsp;|&nbsp;|[Target-Aware Image Denoising for Inverse Monte Carlo Rendering](https://cglab.gist.ac.kr/sig24target/)|
|2023|SIG|[Self-Calibrating, Fully Differentiable NLOS Inverse Rendering](http://vclab.kaist.ac.kr/siggraphasia2023/nlospaper23-7.pdf)|[code](https://github.com/KAIST-VCLAB/nlos-inverse-rendering)
|2022|SIG|[NeAT: Neural Adaptive Tomography](https://vccimaging.org/Publications/Ruckert2022NeAT/)|&nbsp;||&nbsp;||
|&nbsp;|&nbsp;|[Sparse Ellipsometry: Portable Acquisition of Polarimetric SVBRDF and Shape with Unstructured Flash Photography](http://vclab.kaist.ac.kr/siggraph2022p1/index.html)|[code](https://github.com/KAIST-VCLAB/SparseEllipsometry)||
|&nbsp;|&nbsp;|[Face Deblurring using Dual Camera Fusion on Mobile Phones](https://www.wslai.net/publications/fusion_deblur/)||
|&nbsp;|&nbsp;|[Blending Camera and 77 GHz Radar Sensing for Equitable, Robust Plethysmography](https://visual.ee.ucla.edu/equi_pleth_camera_rf.htm/)||
|&nbsp;|&nbsp;|[Seeing Through Obstructions with Diffractive Cloaking](https://dl.acm.org/doi/10.1145/3528223.3530185)||
|&nbsp;|&nbsp;|[Dark Stereo: Improving Depth Perception Under Low Luminance](https://dark-stereo.mpi-inf.mpg.de/)||
|&nbsp;|&nbsp;|[Comparison of single image HDR reconstruction methods — the caveats of quality assessment](https://dark-stereo.mpi-inf.mpg.de/)|[code](https://github.com/gfxdisp/pu21)|
|&nbsp;|&nbsp;|[High Dynamic Range and Super-Resolution From Raw Image Bursts](https://arxiv.org/abs/2207.14671)||
|&nbsp;|&nbsp;|[Holographic Glasses for Virtual Reality](https://research.nvidia.com/publication/2022-08_holographic-glasses-virtual-reality)||
|&nbsp;|&nbsp;|[Joint Neural Phase Retrieval and Compression for Energy- and Computation-Efficient Holography on the Edge](https://dl.acm.org/doi/abs/10.1145/3528223.3530070)||
|&nbsp;|&nbsp;|[Time-multiplexed Neural Holography: A flexible framework for holographic near-eye displays with fast heavily-quantized spatial light modulators](https://www.computationalimaging.org/publications/time-multiplexed-neural-holography/)||
|&nbsp;|&nbsp;|[Accommodative Holography: Improving Accommodation Response for Perceptually Realistic Holographic Displays](https://www.computationalimaging.org/publications/time-multiplexed-neural-holography/)||
|&nbsp;|&nbsp;|[Hogel-free Holography](https://dl.acm.org/doi/abs/10.1145/3516428)||
|2021|SIGA|[Neural 3D Holography: Learning Accurate Wave Propagation Models for 3D Holographic Virtual and Augmented Reality Displays](http://www.computationalimaging.org/publications/neuralholography3d/)|[code](https://github.com/computational-imaging/neural-3d-holography)|<details><summary>Enabling 3D modelling of wave propation</summary><p> Enabling 3D modelling of wave propation in display. </p></details><p></p>|
|&nbsp;|&nbsp;|[Polarimetric Spatio-Temporal Light Transport Probing](https://arxiv.org/abs/2105.11609)||
|&nbsp;|SIG|[End-to-End Complex Lens Design with Differentiable Ray Tracing](https://vccimaging.org/Publications/Sun2021DiffLens/)|
|&nbsp;|&nbsp;|[Imaging with local speckle intensity correlations: theory and practice](https://webee.technion.ac.il/people/anat.levin/papers/AltermanTOG2021SeeThrough.pdf)|[code](https://webee.technion.ac.il/people/anat.levin/)||
|&nbsp;|&nbsp;|[Differentiable Compound Optics and Processing Pipeline Optimization for End-to-end Camera Design](https://light.princeton.edu/publication/deep_compound_optics/)||
|&nbsp;|&nbsp;|[Low-Cost SPAD Sensing for Non-Line-Of-Sight Tracking, Material Classification and Depth Imaging](https://light.princeton.edu/publication/cheapspad/)|[code](https://github.com/princeton-computational-imaging/CheapSPAD)||
|2020|SIGA|[Neural Holography with Camera-in-the-loop Training](https://www.computationalimaging.org/publications/neuralholography/)|[code](https://github.com/computational-imaging/neural-holography)||
|&nbsp;|&nbsp;|[Design and Fabrication of Freeform Holographic Optical Elements](https://research.fb.com/publications/design-and-fabrication-of-freeform-holographic-optical-elements/)||
|&nbsp;|&nbsp;|[Learned Hardware-in-the-loop Phase Retrieval for Holographic Near-Eye Displays](https://light.princeton.edu/publication/hil-holography/)||
|&nbsp;|&nbsp;|[Rendering Near-Field Speckle Statistics in Scattering Media](https://imaging.cs.cmu.edu/publications/rendering-near-field-speckle-statistics-in-scattering-media/)||
|&nbsp;|SIG|[Local Fourier Slice Photography](https://dl.acm.org/doi/abs/10.1145/3339307)||
|&nbsp;|&nbsp;|[Quanta Burst Photography](https://dl.acm.org/doi/pdf/10.1145/3386569.3392470)||
|&nbsp;|&nbsp;|[One Shot 3D Photography](https://facebookresearch.github.io/one_shot_3d_photography/)|[code](https://github.com/facebookresearch/one_shot_3d_photography)|
|&nbsp;|&nbsp;|[Non-Line-of-Sight Reconstruction using Efficient Transient Rendering](https://light.informatik.uni-bonn.de/non-line-of-sight-reconstruction-using-efficient-transient-rendering/)||
|&nbsp;|&nbsp;|[End-to-end Learned, Optically Coded Super-resolution SPAD Camera](https://dl.acm.org/doi/abs/10.1145/3372261)||
|2019|SIGA|[Learning Efficient Illumination Multiplexing for Joint Capture of Reflectance and Shape](https://dl.acm.org/doi/10.1145/3355089.3356492)||
|&nbsp;|&nbsp;|[Handheld Mobile Photography in Very Low Light](http://graphics.stanford.edu/papers/night-sight-sigasia19/night-sight-sigasia19.pdf)||
|&nbsp;|&nbsp;|[Accelerating ADMM for efficient simulation and optimization](https://dl.acm.org/doi/10.1145/3355089.3356491)|[code](https://github.com/bldeng/AA-ADMM)|
|&nbsp;|&nbsp;|[Learned Large Field-of-View Imaging With Thin-Plate Optics](https://dl.acm.org/doi/abs/10.1145/3355089.3356526)|[code](https://github.com/qilinsun/LearnedLargeFOV)|
|&nbsp;|&nbsp;|[Synthetic Defocus and Look-Ahead Autofocus for Casual Videography](https://ceciliavision.github.io/vid-auto-focus/)||
|&nbsp;|&nbsp;|[Handheld Multi-Frame Super-Resolution](https://dl.acm.org/doi/10.1145/3306346.3323024)|[code](https://github.com/kunzmi/ImageStackAlignator)|
|&nbsp;|&nbsp;|[A Unified Framework for Compression and Compressed Sensing of Light Fields and Light Field Videos](https://dl.acm.org/doi/abs/10.1145/3269980)||
|&nbsp;|&nbsp;|[Hyperparameter Optimization in Black-box Image Processing using Differentiable Proxies](https://www.cs.princeton.edu/~fheide/proxyopt)||
|&nbsp;|&nbsp;|[Coding Optimization for Fast Fluorescence Lifetime Imaging](https://wisionlab.com/wp-content/uploads/2019/06/ToG19_FLIM_Jongho_Combined.pdf)||
|&nbsp;|&nbsp;|[Non-line-of-sight Imaging with Partial Occluders and Surface Normals](https://www.cs.princeton.edu/~fheide/papers/OcclusionNLOS.pdf)||
|&nbsp;|&nbsp;|[Wave-based Non-line-of-sight Imaging using Fast fk-Migration](http://www.computationalimaging.org/publications/nlos-fk/)|[code](https://github.com/computational-imaging/nlos-fk)|
|&nbsp;|&nbsp;|[Compact Snapshot Hyperspectral Imaging with Diffracted Rotation](https://dl.acm.org/doi/10.1145/3306346.3322946)|[code](http://vclab.kaist.ac.kr/siggraph2019/index.html)|
|2018|SIGA|[A System for Acquiring, Processing, and Rendering Panoramic Light Field Stills for Virtual Reality](https://dl.acm.org/doi/10.1145/3272127.3275031)||
|&nbsp;|SIG|[What Are Optimal Coding Functions for Time-of-Flight Imaging?](https://dl.acm.org/doi/10.1145/3152155)||
|&nbsp;|&nbsp;|[Single-Photon 3D Imaging with Deep Sensor Fusion](https://dl.acm.org/doi/10.1145/3197517.3201316)||
|&nbsp;|&nbsp;|[End-to-end Optimization of Optics and Image Processing for Achromatic Extended Depth of Field and Super-resolution Imaging](https://vccimaging.org/Publications/Sitzmann2018EndToEndOptics/Sitzmann2018EndToEndOptics.pdf)|[code](https://github.com/vsitzmann/deepoptics)|
|&nbsp;|&nbsp;|[Megapixel Adaptive Optics: Towards Correcting Large-scale Distortions in Computational Cameras](https://dl.acm.org/doi/10.1145/3197517.3201299)|[code](https://github.com/vccimaging/MegapixelAO)|
|2017|SIGA|[Compact Single-Shot Hyperspectral Imaging Using a Prism](http://vclab.kaist.ac.kr/siggraphasia2017p2/index.html)||
|&nbsp;|&nbsp;|[High-Quality Hyperspectral Reconstruction Using a Spectral Prior](http://vclab.kaist.ac.kr/siggraphasia2017p1/index.html)|[code](https://github.com/KAIST-VCLAB/deepcassi/)|
|&nbsp;|&nbsp;|[DeepToF: Off-the-Shelf Real-Time Correction of Multipath Interference in Time-of-Flight Imaging](http://giga.cps.unizar.es/~juliom/pubs/2017SIGA-DeepToF/)||
|&nbsp;|&nbsp;|[Snapshot Difference Imaging using Correlation Time-of-Flight Sensors](https://light.cs.uni-bonn.de/snapshot-difference-imaging-using-time-of-flight-sensors/)|[code](https://github.com/KAIST-VCLAB/deepcassi/)|
|&nbsp;|SIG|[CoLux: Multi-Object 3D Micro-Motion Analysis Using Speckle Imaging](https://wisionlab.com/project/colux/)||
|&nbsp;|&nbsp;|[4D Imaging through Spray-On Optics](/https://light.cs.uni-bonn.de/4d-imaging-through-spray-on-optics/)||
|&nbsp;|&nbsp;|[Rainbow Particle Imaging Velocimetry for Dense 3D Fluid Velocity Imaging]([/https://light.cs.uni-bonn.de/4d-imaging-through-spray-on-optics/](https://vccimaging.org/Publications/Xiong2017RainbowPIV/))|[code](https://github.com/vccimaging/RainbowPIV)|
|&nbsp;|&nbsp;|[Epipolar Time-of-Flight Imaging]([/https://light.cs.uni-bonn.de/4d-imaging-through-spray-on-optics/](https://www.cs.cmu.edu/~ILIM/epitof/html/index.html))||
|&nbsp;|&nbsp;|[Deep Bilateral Learning for Real-Time Image Enhancement ]([[/https://light.cs.uni-bonn.de/4d-imaging-through-spray-on-optics/](https://groups.csail.mit.edu/graphics/hdrnet/)](https://vccimaging.org/Publications/Xiong2017RainbowPIV/)](https://groups.csail.mit.edu/graphics/hdrnet/))||
|2016|SIGA|[Deep Joint Demosaicking and Denoising](https://www.computationalimaging.org/publications/neuralholography/)|[code](https://github.com/computational-imaging/neural-holography)||
|&nbsp;|&nbsp;|[Computational Bounce Flash for Indoor Portraits](http://lmurmann.net/bounceflash)||
|&nbsp;|&nbsp;|[Burst photography for high dynamic range and low-light imaging on mobile cameras (HDR+)](https://static.googleusercontent.com/media/hdrplusdata.org/en//hdrplus.pdf)|[code](https://github.com/martin-marek/hdr-plus-pytorch)|
|&nbsp;|&nbsp;|[Learning-Based View Synthesis for Light Field Cameras](https://cseweb.ucsd.edu/~viscomp/projects/LF/papers/SIGASIA16/)||
|&nbsp;|&nbsp;|[Birefractive Stereo Imaging for Single-Shot Depth Acquisition](http://lmurmann.net/bounceflash)||
|&nbsp;|&nbsp;|[Model-Based Teeth Reconstruction](https://vcai.mpi-inf.mpg.de/projects/MZ/Papers/SGASIA2016_TR/page.html)||
|&nbsp;|&nbsp;|[Recovering Shape and Spatially-Varying Surface Reflectance under Unknown Illumination](https://www.cs.wm.edu/~ppeers/showPublication.php?id=Xia:2016:RSS)||
|&nbsp;|&nbsp;|[Simultaneous Acquisition of Microscale Reflectance and Normals ](http://www.minhkim.org/siggraphasia2016p2/index.html)||
|&nbsp;|&nbsp;|[Motion Parallax in Stereo 3D: Model and Applications](https://resources.mpi-inf.mpg.de/StereoParallax/)||
|&nbsp;|SIG|[The Diffractive Achromat: Full-Spectrum Computational Imaging With Diffractive Optics ](http://www.cs.ubc.ca/labs/imager/tr/2016/DiffractiveAchromatImaging/)||
|&nbsp;|&nbsp;|[Practical Multispectral Lighting Reproduction](https://dl.acm.org/doi/10.1145/2897824.2925934)||
|&nbsp;|&nbsp;|[Computational Imaging With Multi-Camera Time-of-Flight Systems](http://www.computationalimaging.org/publications/multi-camera-time-of-flight-systems/)||
|&nbsp;|&nbsp;|[Occluded Imaging With Time-of-Flight Sensors](https://dl.acm.org/doi/10.1145/2836164)||
|&nbsp;|&nbsp;|[Additive Light-Field Displays: Realization of Augmented Reality With Holographic Optical Elements](http://oeqelab.snu.ac.kr/AdditiveLightFieldDisplays)||
|&nbsp;|&nbsp;|[Fairy Lights in Femtoseconds: Aerial and Volumetric Graphics Rendered by a Focused Femtosecond Laser Combined With Computational Holographic Fields](https://arxiv.org/abs/1506.06668)||
|&nbsp;|&nbsp;|[Image Perforation: Automatically Accelerating Image Pipelines by Intelligently Skipping Samples ](https://arxiv.org/abs/1506.06668)||
|&nbsp;|&nbsp;|[Automatically Scheduling Halide Image Processing Pipelines](http://graphics.cs.cmu.edu/projects/halidesched/)||
|&nbsp;|&nbsp;|[ProxImaL: Efficient Image Optimization using Proximal Algorithms](http://graphics.stanford.edu/~niessner/heide2016proximal.html)||
|&nbsp;|&nbsp;|[Rigel: Flexible Multi-Rate Image Processing Hardware](http://graphics.stanford.edu/papers/rigel/)||
|2015|SIGA|[Data-Driven Structural Priors for Shape Completion](https://dl.acm.org/doi/10.1145/2816795.2818094)||
|&nbsp;|&nbsp;|[Autoscanning for Coupled Scene Reconstruction and Proactive Object Analysis](http://kevinkaixu.net/projects/pr2scene.html)||
|&nbsp;|&nbsp;|[Unsynchronized structured light](http://mesh.brown.edu/unsync/)||
|&nbsp;|SIG|[Homogeneous Codes for Energy Efficient Illumination and Imaging](http://www.cs.cmu.edu/~motoole2/energyefficientimaging.html)||
|&nbsp;|&nbsp;|[Doppler Time-of-Flight Imaging](http://www.cs.ubc.ca/labs/imager/tr/2015/DopplerToF/)||
|&nbsp;|&nbsp;|[Phasor Imaging: A Generalization of Correlation-Based Time-of-Flight Imaging](https://cave.cs.columbia.edu/projects/categories/project?cid=Computational+Imaging&pid=Phasor+Imaging)||
|&nbsp;|&nbsp;|[Micron-scale Light Transport Decomposition Using Interferometry](http://vision.seas.harvard.edu/transient/)||
|&nbsp;|&nbsp;|[Linear volumetric focus for light field cameras ](https://roboticimaging.org/Papers/Dansereau2015volumetric.pdf)||
|&nbsp;|&nbsp;|[A Light Transport Framework for Lenslet Light Field Cameras](https://dl.acm.org/doi/10.1145/2665075)||
|&nbsp;|&nbsp;|[Improving Light Field Camera Sample Design With Irregularity and Aberration](https://www.liyiwei.org/papers/sample-sig15/)||
|&nbsp;|&nbsp;|[Light Field Reconstruction Using Sparsity in the Continuous Fourier Domain](https://groups.csail.mit.edu/netmit/LFSparseRecon/)||
|&nbsp;|&nbsp;|[Layered Light-Field Reconstruction for Defocus Blur](https://www.intel.com/content/www/us/en/developer/overview.html#gs.8snifj)||



<!-- 

|2017|SIGGRAPH ASIA|[Learning to Predict Indoor Illumination from a Single Image](https://arxiv.org/abs/1704.00090)|[code](http://indoor.hdrdb.com/)|
|2018|3DV|[Learning to Estimate Indoor Lighting from 3D Objects](https://arxiv.org/abs/1806.03994)|[Code & code] -->
