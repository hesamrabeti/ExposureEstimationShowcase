# Implementing Exposure Estimation on Google Tango

Digital cameras often automatically adjust frame exposure time and white balance across time to adapt to varying lighting conditions. This causes the color and intensity of surfaces viewed to vary. Such differences in exposure and white balance can cause severe visual artifacts or color variation on textures of 3D reconstructions. 

In this project, we developed an algorithm to reverse automatic exposure time and white balance adjustments. Once corrected, the images were fed into the pipeline of [Google Tango](https://get.google.com/tango/) to produce a better represenation of the real colors of the scene. A sample exposure correction can be seen below:

![Animation showing the original and exposure corrected versions of a mesh](https://raw.githubusercontent.com/hesamrabeti/ExposureEstimationShowcase/master/spencer_room.gif)

![Image comparing the original and exposure corrected versions of a mesh](https://raw.githubusercontent.com/hesamrabeti/ExposureEstimationShowcase/master/spencer_room_comparison.png)


Special thanks to [Yvain Quéau](https://sites.google.com/view/yvainqueau) at [TUM CVPR](http://vision.in.tum.de/) and [Jürgen Sturm](http://jsturm.de/wp/) of Google Munich.
