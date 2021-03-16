# 3-D seismic interpretation with deep learning: a brief introduction

![alt text](https://github.com/thilowrona/seismic_deep_learning/blob/master/image.png)

Here we are sharing our code, tutorials and examples used to interpret geological structures (e.g. faults, salt bodies and horizones) in 2-D and/or 3-D seismic reflection data using deep learning. You can find a few visual examples on our [poster](https://www.thilowrona.com/posters) and more technical details in our [preprint](https://eartharxiv.org/repository/view/1683/).

To get started, you don't need any special hardware, software, data or experience - just a bit of time. 
Check out [tutorial-1/tutorial-1.ipyng](https://github.com/thilowrona/seismic_deep_learning/blob/master/tutorial-1/tutorial-1.ipynb).


## Tutorials

### [Tutorial 1](https://github.com/thilowrona/seismic_deep_learning/blob/master/tutorial-1/tutorial-1.ipynb)
- This tutorial shows you how to map salt in a 2-D seismic image using a 2-D convolutional neural network for pixel-wise classification.

### [Tutorial 2](https://github.com/thilowrona/seismic_deep_learning/blob/master/tutorial-2/tutorial-2.ipynb)
- This tutorial describes how to speed up our mapping using U-Net type convolutional neural networks.

### [Tutorial 3](https://github.com/thilowrona/seismic_deep_learning/blob/master/tutorial-3/tutorial-3.ipynb)
- This tutorial shows you how to map tectonic faults in a 3-D seismic volume.

### [Tutorial 4](https://github.com/thilowrona/seismic_deep_learning/blob/master/tutorial-4/tutorial-4.ipynb)
- This tutorial will explain how to translate our fault mapping workflow to 3-D.

### [Tutorial 5](https://github.com/thilowrona/seismic_deep_learning/blob/master/tutorial-5/tutorial-5.ipynb)
- This tutorial will hows you how to quantify uncertainty during fault mapping (not ready yet)

### [Tutorial 6](https://github.com/thilowrona/seismic_deep_learning/blob/master/tutorial-6/tutorial-6.ipynb)
- This tutorial introduces you to mapping horizons in a 3-D seismic volume.

### [Tutorial 7](https://github.com/thilowrona/seismic_deep_learning/blob/master/tutorial-7/tutorial-7.ipynb)
- This tutorial shows you how to improve horizon mapping using a 2-D CNN

### [Tutorial 8](https://github.com/thilowrona/seismic_deep_learning/blob/master/tutorial-8/tutorial-8.ipynb)
- This tutorial will explain how to translate our horizon mapping workflow to 3-D.

### [Tutorial 9](https://github.com/thilowrona/seismic_deep_learning/blob/master/tutorial-9/tutorial-9.ipynb)
- This tutorial will show how to invert synthetic seismic data for rock properties (not ready yet)



## Citation
If you use this project in your research or wish to refer to the results of the tutorials, please use the following BibTeX entry.
```
@misc{deepseis2020,
  author =       {Thilo Wrona, Indranil Pan, Rebecca E. Bell, Robert L. Gawthorpe, Haakon Fossen and Sascha Brune},
  title =        {{Deep learning of geological structures in seismic reflection data: Tutorials}},
  howpublished = {\url{https://github.com/thilowrona/seismic_deep_learning}},
  year =         {2020}
}
```
