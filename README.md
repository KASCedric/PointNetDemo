# PointNetDemo

See the [official](https://github.com/KASCedric/PointNet/blob/main/README.md#Usage) repository for usage.

This repository contains:

- A model based on [PointNet](https://arxiv.org/abs/1612.00593) and pre-trained on [semantic-kitti](http://www.semantic-kitti.org/) dataset `sample-model.pth` 

- A sample data `raw-data.bin`, from the kitti odometry velodyne dataset (sequence=01, pointclous=000000.bin).

- The same sample data downsampled with PCL using a voxelgrid with a leaf_size=0.1 (=10 cm): `ds-data.ply`
Note: The model was trained using downsampled data of same distribution as `ds-data.ply`

### Model Evaluation:
Under construction
