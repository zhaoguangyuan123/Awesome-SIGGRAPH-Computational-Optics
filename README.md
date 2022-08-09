# Awesome-SIGGRAPH-Computational-Imaging
A curated list of computational imaging related literature presented on SIGGRAPH.

## Author's Intention for This Collection
A good way to master the taste and progress of an area is to read its high-impact papers. 
As a high-profile venue, SIGGRAPH(ASIA) has been publishing top-tier computational imaging papers for decades. However, as computational imaging is a relatively minor and nascent area in SIGGRAPH, every year there are only very few (mostly less than 5) computational imaging papers published on SIGGRAPH while the topic and content of computational imaging related papers are a bit different from the rest of SIGGRAPH papers. As a consequence, it is not easy to keep track of the past computational imaging papers. The author gets inspiration from [Krita](https://github.com/tkuri) and many others who are creating awesome lists and creates this collection to help the community. The author thanks [Ken-sen](https://kesen.realtimerendering.com/) for sharing the SIGGRAPH collection, which facilites the creation of this list. If you have any suggestion for this list, pls do not hesitate to drop an email to the author or make a comment in the issues. 

## TODO
- [x] Get the alpha version of collection out.
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
**Computational Imaging** is a rapidly emerging field that co-designs the sensing hardware and the algorithms to indirectly form images from measurements with reconstructions.
Computational imaging systems enables system designers to overcome some hardware limitations of optics and sensors (resolution, noise etc.). It also has advantages to probe multi-dimensional light field (spectral, depth, polarization etc.). However, there does not exist any universal description for computational imaging right now. Besides the some research papers or talks that can be clearly regarded as computational imaging papers, the author, according to his own taste, also collects some works (such as computational displays) which are not absolute computational imaging but related to the field. 


## Contents
<!-- ## Illumination Estimation (DL) -->
|Year|Venue|Paper(w/ code)|Repo (if any)|Summary(if any)|
|---|---|---|---|---|
|2022|SIG|[NeAT: Neural Adaptive Tomography](https://vccimaging.org/Publications/Ruckert2022NeAT/)|&nbsp;||&nbsp;||
|&nbsp;|&nbsp;|[Face Deblurring using Dual Camera Fusion on Mobile Phones](https://www.wslai.net/publications/fusion_deblur/)||
<!-- |&nbsp;|&nbsp;|[Searching for Fast Demosaicking Algorithms]()|[code]()||| -->
|2021|SIG ASIA|[Neural 3D Holography: Learning Accurate Wave Propagation Models for 3D Holographic Virtual and Augmented Reality Displays](http://www.computationalimaging.org/publications/neuralholography3d/)|&nbsp;|<details><summary>Enabling 3D modelling of wave propation</summary><p> Enabling 3D modelling of wave propation in display. </p></details><p></p>|
|&nbsp;|&nbsp;|[Polarimetric Spatio-Temporal Light Transport Probing](https://arxiv.org/abs/2105.11609)||
|&nbsp;|SIG|[End-to-End Complex Lens Design with Differentiable Ray Tracing](https://vccimaging.org/Publications/Sun2021DiffLens/)||
|&nbsp;|&nbsp;|[Imaging with local speckle intensity correlations: theory and practice](https://webee.technion.ac.il/people/anat.levin/papers/AltermanTOG2021SeeThrough.pdf)|[code](https://webee.technion.ac.il/people/anat.levin/)|
|&nbsp;|&nbsp;|[Differentiable Compound Optics and Processing Pipeline Optimization for End-to-end Camera Design](https://light.princeton.edu/publication/deep_compound_optics/)||
|&nbsp;|&nbsp;|[Low-Cost SPAD Sensing for Non-Line-Of-Sight Tracking, Material Classification and Depth Imaging](https://light.princeton.edu/publication/cheapspad/)|[code](https://github.com/princeton-computational-imaging/CheapSPAD)|
|2020|SIG ASIA|[Neural Holography with Camera-in-the-loop Training](https://www.computationalimaging.org/publications/neuralholography/)|[code](https://github.com/computational-imaging/neural-holography)|
|&nbsp;|&nbsp;|[Design and Fabrication of Freeform Holographic Optical Elements](https://research.fb.com/publications/design-and-fabrication-of-freeform-holographic-optical-elements/)||
|&nbsp;|&nbsp;|[Learned Hardware-in-the-loop Phase Retrieval for Holographic Near-Eye Displays](https://light.princeton.edu/publication/hil-holography/#:~:text=Computing%20Imaging%20Lab-,Learned%20Hardware%2Din%2Dthe%2Dloop%20Phase%20Retrieval,for%20Holographic%20Near%2DEye%20Displays&text=Holographic%20displays%20often%20show%20poor,%E2%80%9Cideal%E2%80%9D%20light%20propagation%20model.)||
|&nbsp;|&nbsp;|[Rendering Near-Field Speckle Statistics in Scattering Media](https://imaging.cs.cmu.edu/publications/rendering-near-field-speckle-statistics-in-scattering-media/)||
|&nbsp;|SIG|[Local Fourier Slice Photography](https://dl.acm.org/doi/abs/10.1145/3339307)||
|&nbsp;|&nbsp;|[Quanta Burst Photography](https://dl.acm.org/doi/pdf/10.1145/3386569.3392470)||
|&nbsp;|&nbsp;|[One Shot 3D Photography]()|[code](https://github.com/facebookresearch/one_shot_3d_photography)|
|&nbsp;|&nbsp;|[Non-Line-of-Sight Reconstruction using Efficient Transient Rendering]()|[code]()|
|&nbsp;|&nbsp;|[Non-Line-of-Sight Reconstruction using Efficient Transient Rendering](https://dl.acm.org/doi/abs/10.1145/3368314)||
|&nbsp;|&nbsp;|[End-to-end Learned, Optically Coded Super-resolution SPAD Camera]()|[code]()|
|2019|SIG ASIA|[Learning Efficient Illumination Multiplexing for Joint Capture of Reflectance and Shape]()|[code]()|
|&nbsp;|&nbsp;|[Handheld Mobile Photography in Very Low Light]()|[code]()|
|&nbsp;|&nbsp;|[Learned Hardware-in-the-loop Phase Retrieval for Holographic Near-Eye Displays]()|[code]()|
|&nbsp;|&nbsp;|[Accelerating ADMM for efficient simulation and optimization]()|[code]()|
|&nbsp;|&nbsp;|[Learned Large Field-of-View Imaging With Thin-Plate Optics]()|[code]()|
|&nbsp;|SIG|[Local Fourier Slice Photography]()|[code]()|
|&nbsp;|&nbsp;|[Synthetic Defocus and Look-Ahead Autofocus for Casual Videography]()|[code]()|
|&nbsp;|&nbsp;|[Handheld Multi-Frame Super-Resolution]()|[code]()|
|&nbsp;|&nbsp;|[A Unified Framework for Compression and Compressed Sensing of Light Fields and Light Field Videos]()|[code]()|
|&nbsp;|&nbsp;|[Hyperparameter Optimization in Black-box Image Processing using Differentiable Proxies]()|[code]()|
|&nbsp;|&nbsp;|[Coding Optimization for Fast Fluorescence Lifetime Imaging]()|[code]()|
|&nbsp;|&nbsp;|[Non-line-of-sight Imaging with Partial Occluders and Surface Normals]()|[code]()|
|&nbsp;|&nbsp;|[Wave-based Non-line-of-sight Imaging using Fast fk-Migration](http://www.computationalimaging.org/publications/nlos-fk/)|[code]()|
|&nbsp;|&nbsp;|[Compact Snapshot Hyperspectral Imaging with Diffracted Rotation]()|[code]()|
|2018|SIGG ASIA|[A System for Acquiring, Processing, and Rendering Panoramic Light Field Stills for Virtual Reality]()|[code]()|
|&nbsp;|SIG|[What Are Optimal Coding Functions for Time-of-Flight Imaging?]()|[code]()|
|&nbsp;|&nbsp;|[Single-Photon 3D Imaging with Deep Sensor Fusion]()|[code]()|
|&nbsp;|&nbsp;|[End-to-end Optimization of Optics and Image Processing for Achromatic Extended Depth of Field and Super-resolution Imaging]()|[code]()|
|&nbsp;|&nbsp;|[Megapixel Adaptive Optics: Towards Correcting Large-scale Distortions in Computational Cameras]()|[code]()|
|2017|SIG ASIA|[A System for Acquiring, Processing, and Rendering Panoramic Light Field Stills for Virtual Reality]()|[code]()|
|&nbsp;|&nbsp;|[Single-Photon 3D Imaging with Deep Sensor Fusion]()|[code]()|
|&nbsp;|&nbsp;|[End-to-end Optimization of Optics and Image Processing for Achromatic Extended Depth of Field and Super-resolution Imaging]()|[code]()|
|&nbsp;|&nbsp;|[Megapixel Adaptive Optics: Towards Correcting Large-scale Distortions in Computational Cameras]()|[code]()|
|&nbsp;|SIG|[What Are Optimal Coding Functions for Time-of-Flight Imaging?]()|[code]()|

<!-- 

|2017|SIGGRAPH ASIA|[Learning to Predict Indoor Illumination from a Single Image](https://arxiv.org/abs/1704.00090)|[code](http://indoor.hdrdb.com/)|
|2018|3DV|[Learning to Estimate Indoor Lighting from 3D Objects](https://arxiv.org/abs/1806.03994)|[Code & code] -->
