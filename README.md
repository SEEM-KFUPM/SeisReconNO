# SeisReconNO: Leveraging a U-Net-Enhanced Fourier Neural Operator for 3D Seismic Reconstruction
<div align="center">
  <a href="https://github.com/traversa942" target="_blank">Alessandro Traversa<sup>1</sup></a> &emsp;
  <a href="https://github.com/cuiyang512" target="_blank">Yang Cui<sup>1</sup></a> &emsp;
  <a href="https://cpg.kfupm.edu.sa/bio/dr-umair-bin-waheed/" target="_blank">Umair bin Waheed<sup>1</sup></sup></a> &emsp;
  <a href="https://www.jsg.utexas.edu/researcher/yangkang_chen" target="_blank">Yangkang Chen<sup>2</sup></a>
</div>
<div align="center">
  <sup>1</sup> College of Petroleum Engineering & Geosciences, King Fahd University of Petroleum & Minerals <br>
  <sup>2</sup> Jackson School of Geosciences, University of Texas at Austin
</div>


## Abstrac
Missing traces in 3D seismic data are a recurring challenge caused by receiver malfunctions, acquisition limitations, and geological or environmental constraints. These gaps hinder accurate interpretation and further processing. Although numerous model-driven approaches have been developed in recent decades, they often struggle with reconstructing the data with complex geological structures and high missing ratios. To address these limitations, we proposed a U\textendash Net-enhanced Fourier Neural Operator (UFNO) 3D seismic reconstruction framework to achieve a mesh-invariant seismic reconstruction across different missing scenarios. The UFNO model leverages both spectral and spatial representations to learn a generalized reconstruction operator. We train the model on field 3D seismic cubes featuring three key missing-data patterns: random, trace-wise,  and regular. Experimental results demonstrate the superior reconstruction capability of UFNO across varying missing ratios. Moreover, the model exhibits strong generalization to unseen data with different resolutions, confirming its potential as a robust and adaptable tool for seismic data enhancement in real-world applications.
