# Code and Software

## [DeLTA Toolbox](https://github.com/delta-onera/delta_tb)

The [**DeLTA Toolbox**](https://github.com/delta-onera/delta_tb) is a toolbox for easy deep learning using the [PyTorch](pytorch.org) framework.
It will include part of the code developed in this project.

The sub-packages of the toolbox is presented in the following subsections.

#### Semantic segmentation

* [SegNet](http://mi.eng.cam.ac.uk/projects/segnet/) is a deep network for image segmentation.
* UNet is a second architecture for image segmentation.

#### Samples
Tutorial and/or code samples for deep learning applications can be found [here](https://github.com/delta-onera/samples). They are to be included in the toolbox.

## Image classification

#### [ShaResNet](https://github.com/aboulch/sharesnet)

ShaResNet is a deep residual neural architecture.
Compared to usual ResNets, the ShaResNets are lighter (between 20% and 45% less parameters) and offer similar performances.

Current implementation using Lua-Torch.

## 3D processing

#### SnapNet and derivative for point cloud labeling

[SnapNet](https://sites.google.com/view/boulch/publications/2017_3dor_pointclouds) is framework for unstructured point cloud labeling. By taking snapshots of the point set, the 3D labeling problem becomes a 2D semantic segmentation problem, that is solved using deep segmentation networks. The code is available [here](https://github.com/aboulch/sharesnet).
