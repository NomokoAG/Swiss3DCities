# Swiss3DCities: Aerial Photogrammetric 3D Pointcloud Dataset with Semantic Labels

This is the official repository of the **Swiss3DCities** dataset. For technical details, please refer to:

**Semantic Segmentation on Swiss3DCities: A Benchmark Study on Aerial Photogrammetric 3D Pointcloud Dataset** <br/>
[Gülcan Can*](https://ch.linkedin.com/in/g%C3%BClcan-can-8496b219), 
[Dario Mantegazza](https://ch.linkedin.com/in/dario-mantegazza), 
[Gabriele Abbate](https://www.supsi.ch/home_en/strumenti/rubrica/dettaglio.26119.html), 
[Sébastien Chappuis](https://ch.linkedin.com/in/s%C3%A9bastien-chappuis-16926381) and 
[Alessandro Giusti](https://ch.linkedin.com/in/alessandrogiusti). <br/>

<div align="center"> 
	
[![Paper](http://img.shields.io/badge/paper-arxiv.2012.12996-B31B1B.svg)](https://arxiv.org/abs/2012.12996)
[![Dataset](http://img.shields.io/badge/dataset-zenodo.record.4390295-B31B1B.svg)](https://zenodo.org/record/4390295)
<!--
ARXIV   
[![Paper](http://img.shields.io/badge/arxiv-cs.CV:2012.12996-B31B1B.svg)](https://arxiv.org/abs/2012.12996)
-->
<!--
ZENODO   
[![Dataset](http://img.shields.io/badge/dataset-zenodo.record.4390295-B31B1B.svg)](https://zenodo.org/record/4390295)
-->
 
</div>


### (1) Dataset Overview

We introduce a new outdoor urban 3D pointcloud dataset, covering a total area of 2.7 km^2, 
sampled from three Swiss cities with different characteristics. 
The dataset is manually annotated for semantic segmentation with per-point labels, 
and is built using photogrammetry from images acquired by multirotors equipped with high-resolution cameras. 
In contrast to datasets acquired with ground LiDAR sensors, the resulting point clouds are uniformly dense and complete, 
and are useful to disparate applications, including autonomous driving, gaming, smart city planning, and robotics. <br/>


### (2) Benchmark: PointNet++
As a benchmark, we evaluate the performance of a well-established point-based deep semantic segmentation model, 
namely [PointNet++](https://arxiv.org/abs/1706.02413), on our dataset. 
We provide an analysis on the model generalization across cities and discuss the gains from model ensembling. 
Please refer to [our paper](https://arxiv.org/abs/2012.12996) for more details. <br/>


### Licence

This dataset is licensed under [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International 
(CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/). <br/>

For commercial use and further questions on our 3D urban models/pointclouds, please contact us at [info@nomoko.world](info@nomoko.world). <br/>

### Citation
Please cite our work as follows:

	@article{can2020semantic3dcities,
      title={Semantic Segmentation on Swiss3DCities: A Benchmark Study on Aerial Photogrammetric 3D Pointcloud Dataset}, 
      author={Gülcan Can and Dario Mantegazza and Gabriele Abbate and Sébastien Chappuis and Alessandro Giusti},
      journal={arXiv preprint arXiv:2012.12996},
      year={2020}
      }


### Updates
* 23/12/2020: Initial release!




