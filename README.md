# KeypointNet

This is a re-implementation of the keypoint network proposed in "Discovery of Latent 3D Keypoints via End-to-end Geometric Reasoning [[pdf](https://arxiv.org/pdf/1807.03146.pdf)]". The keypointnet predicts a consistent set of keypoints on a single image. The predicted keypoints can then be used for various downstream tasks such as detection and 3D pose estimation.  

## Sample Results

### Planes

<p align="center">
  <img src="https://github.com/Kishaan/keypointnet-tf2.1/blob/master/output_images/plane_working.png">
</p>

### Planes deformed

![Planes_deformed](https://github.com/Kishaan/keypointnet-tf2.1/blob/master/output_images/plane_deformed.png)

### Cars

![Cars_deformed](https://github.com/Kishaan/keypointnet-tf2.1/blob/master/output_images/car_working.png)

As seen in the images, the network is able to consistently detect the keypoints even with out of plane rotations. 

## Team Members

[Kishaan Jeeveswaran](https://github.com/Kishaan), 
[Swaroop Bhandary K](https://github.com/swaroop1904), 
[Deepan Chakravarthi Padmanabhan](https://github.com/DeepanChakravarthiPadmanabhan)

## Reference

```
@inproceedings{suwajanakorn2018discovery,
  title={Discovery of latent 3d keypoints via end-to-end geometric reasoning},
  author={Suwajanakorn, Supasorn and Snavely, Noah and Tompson, Jonathan J and Norouzi, Mohammad},
  booktitle={Advances in Neural Information Processing Systems},
  pages={2059--2070},
  year={2018}
}
```
## License

The functions defined in this repository (Transformer class, blender render script and few of the loss functions) have been either adapted from or directly taken from https://github.com/tensorflow/models/tree/master/research/keypointnet following the license under the original repository. 
