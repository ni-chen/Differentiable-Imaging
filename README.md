<h2 class="section-title">Differentiable Imaging: a new tool for computational optical imaging </h2>
<h5 class="pubname"> Advanced Physics Research, 2023 </h5>

<nav class="text-center" style="width: 100%">
  <a href="https://ni-chen.github.io/" class="author">Ni Chen</a><sup>1</sup>,
  <a href="http://www.holoddd.com/" class="author">Liangcai Cao</a><sup>2</sup>,
  <a href="https://sites.google.com/vt.edu/oshandholographiclab/" class="author">T.-C. Poon</a><sup>3</sup>,
  <a href="http://oeqelab.snu.ac.kr/PROF" class="author">Byoungho Lee</a><sup>4</sup>,
  <a href="https://www.eee.hku.hk/~elam/" class="author">Edmund Y. Lam</a><sup>5</sup>
</nav>

</br>

</br>

Computational imaging has made significant advancements in recent years, but faces limitations due to the restrictions imposed by traditional computational techniques. Differentiable programming offers a promising solution by combining the strengths of classical optimization and deep learning. By integrating physics into the modeling process, **differentiable imaging** [[2](https://github.com/ni-chen/Differentiable-Imaging/blob/master/code/tutorial.ipynb)] - which employs differentiable programming in computational imaging - has the potential to overcome challenges posed by sparse, incomplete, and noisy data. This could be a key factor in advancing the field of computational imaging and its various applications.

Modeling the physics accurately is of great importance in differentiable imaging. Since many computational imaging techniques rely on ray tracing and diffraction [[6](https://opg.optica.org/oe/fulltext.cfm?uri=oe-30-21-37727&id=507396)], we have developed both a **ray-tracing differentiable framework**  [[4](https://ieeexplore.ieee.org/abstract/document/9919421)] and a **diffraction-based differentiable framework** [[3](https://repository.kaust.edu.sa/handle/10754/679652)]. These frameworks have applications in self-calibration [[4](https://ieeexplore.ieee.org/abstract/document/9919421)], end-to-end lens design [[4](https://ieeexplore.ieee.org/abstract/document/9919421)], metrology [[5](https://opg.optica.org/oe/fulltext.cfm?uri=oe-29-19-30284&id=458455)], holography ($\partial {H}$) [[3](https://doi.org/10.1002/lpor.202200828), [13](https://doi.org/10.1364/DH.2023.HTh2C.2)], Phase Retrieval [[8](https://arxiv.org/abs/2404.18946),[9](https://preprints.opticaopen.org/articles/preprint/Adaptive_cascade_calibrated_multi-plane_phase_retrieval/25697982/1/)], Fourier Ptychographic Microscopy [[10](https://preprints.opticaopen.org/articles/preprint/Automatic_Differentiation-Assisted_Fourier_Ptychographic_Microscopy/25687317/1), [11](),[12](https://doi.org/10.1364/FIO.2023.FM1C.2)] and more. The differentiable ray-tracing framework has proven to be highly efficient and enables easy incorporation of neural networks, thereby promoting lens design [[7](https://arxiv.org/abs/2302.01089)].

Please refer to the paper to find how this **differentiable imaging** [[2](https://github.com/ni-chen/Differentiable-Imaging/blob/master/code/tutorial.ipynb)] enables more efficient and effective imaging, and our insights on its potential impact in the computational imaging field. Below is the supplementary code [[1](https://github.com/ni-chen/Differentiable-Imaging/blob/master/code/tutorial.ipynb)] of the paper[[2](https://github.com/ni-chen/Differentiable-Imaging/blob/master/code/tutorial.ipynb)]. 



## Reference and related publications

1. Tutorial code for developing differentiable optimization with PyTorch: [Jupyter notebook](https://github.com/ni-chen/Differentiable-Imaging/blob/master/code/tutorial.ipynb)
2. Ni Chen, Liangcai Cao, Ting-Chung Poon, Byoungho Lee, Edmund Y. Lam, “[Differentiable Imaging: A New Tool for Computational Optical Imaging](https://onlinelibrary.wiley.com/doi/full/10.1002/apxr.202200118), ” Advanced Physcics Research 2(2), 2023.
3. Ni Chen, Congli Wang and Wolfgang Heidrich, “[$\partial {H}$: Differentiable Holography](https://doi.org/10.1002/lpor.202200828)”, Laser & Photonics Reviews, 2023.
4. Congli Wang, Ni Chen and Wolfgang Heidrich, "[dO: A Differentiable Engine for Deep Lens Design of Computational Imaging Systems](https://ieeexplore.ieee.org/abstract/document/9919421)," IEEE Transactions on Computational Imaging, vol. 8, pp. 905-916, 2022.  [GitHub](https://github.com/vccimaging/DiffOptics)
5. Congli Wang, Ni Chen, and Wolfgang Heidrich, "[Towards self-calibrated lens metrology by differentiable refractive deflectometry](https://opg.optica.org/oe/fulltext.cfm?uri=oe-29-19-30284&id=458455)," Opt. Express **29**, 30284-30295 (2021). [Github](https://github.com/vccimaging/DiffDeflectometry)
6. Ni Chen, Congli Wang, and Wolfgang Heidrich, "[HTRSD: Hybrid Taylor Rayleigh-Sommerfeld diffraction](https://opg.optica.org/oe/fulltext.cfm?uri=oe-30-21-37727&id=507396)," Opt. Express **30**, 37727-37735 (2022)
7. Xinge Yang and Qiang Fu and Wolfgang Heidrich, “[Curriculum Learning for ab initio Deep Learned Refractive Optics](https://arxiv.org/abs/2302.01089),” ArXiv, 2023.
8. Jiabao Wang, Yang Wu, Jun Wang*, Ni Chen*, "[Adaptive cascade calibrated multi-plane phase retrieval](https://arxiv.org/abs/2404.18946)," In Computational Optical Sensing and Imaging (COSI), Toulouse, France, . 2024. 
9. Jiabao Wang, Yang Wu, Jun Wang*, Ni Chen*, "[Alignment-free multi-plane phase retrieval](https://preprints.opticaopen.org/articles/preprint/Adaptive_cascade_calibrated_multi-plane_phase_retrieval/25697982/1)," 2022
10. Yang Wu, Chao Tan, Jun Wang*, Ni Chen*, "[Automatic Differentiation-Assisted Fourier Ptychographic Microscopy](https://preprints.opticaopen.org/articles/preprint/Automatic_Differentiation-Assisted_Fourier_Ptychographic_Microscopy/25687317/1)," In Computational Optical Sensing and Imaging (COSI), Toulouse, France. 2024. 
11. Ni Chen, David J. Brady, "[Slimming Optical Systems and Boosting Performance with Differentiable Programming]()," In 14th International Conference on Optics-Photonics Design and Fabrication (ODF‘24), Tucson, AZ, USA, Jul. 2024. 
12. Ni Chen, Rongguang Liang, "[Revolutionizing Medical Imaging: Advancements through Differentiable Imaging Techniques](https://doi.org/10.1364/FIO.2023.FM1C.2)," In FiO LS Congress: Fabrication, Design and Instrumentation, Tacoma, WA, USA, Oct. 2023. Invited talk
13. Yang Wu, Jun Wang*, Ni Chen*, "[Volumetric particle imaging with differentiable holography](https://doi.org/10.1364/DH.2023.HTh2C.2)," In Digital Holography & 3D Imaging, Boston, USA, Oct. 2023.
