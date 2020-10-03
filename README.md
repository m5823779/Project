
<p align="center">
  <b> End to end motion planner using Deep Deterministic Policy Gradient (DDPG) </b>
</p>
<br>

With the progress of technology, more and more service robots appear in our daily lives. The key technologies of service robots involve many fields. Including: mobile navigation, system control, mechanism modules, vision modules, voice modules, artificial intelligence, and other related technical fields. In this research we will focus on developing indoor robot navigation.

In this project, we present a learning-based mapless motion planner by taking the sparse laser single and the target position in the robot frame (relative distance and relative angles) as input and the continuous steering commands as output. This saves us from using traditional methods such as "SLAM" to have maps and can also do the navigation. The trained motion planner can also be directly applied in environments which it never seen before.

<p align="center">
  <img width="640" height="360" src="https://github.com/m5823779/Project/blob/main/Doc/DeepReinforcementLearning.gif">
</p>

> Keywords : Deep Reinforcement Learning (DRL), Deep Deterministic Policy Gradient (DDPG), Motion Planner, Navigation,  ROS, Tensorflow  , Python

<p align="center">
  <b> AR Virtual Display </b>
</p>
<br> 

The flourishing development of Augmented reality (AR) in recent years, more and more companies are beginning to develop AR devices and applications. Such as Microsoft's Hololens. However, most of the current AR applications be used for entertainment. Have you ever wondered if AR can increase our productivity? We came up with a new idea. Getting more screens through AR glasses. In this way, users don’t have to spend a lot of money buying lots of physical monitors. And all this is base on "Vuforia or Aruco". Attach target image on physical monitors to track its pose. Then draw the virtual screen in AR glass.

<p align="center">
  <img width="640" height="360" src="https://github.com/m5823779/Project/blob/main/Doc/Vuforia.gif">
</p>

> Keywords : AR, OpenCV, Aruco, Vuforia, Unity, C#, C++

<p align="center">
  <b> Monitor Landmark Detection / Pose Estimation </b>
</p>
<br> 

As the augmented reality (AR) industry in recent years, the rapid development AR device such as smartphone and AR glasses for the growing demand. For AR technology, being able to track real-world objects stably is the most important and difficult part. And most of the current AR technologies are based on SLAM which is based on the point cloud (feature points). This reason leads to his zero awareness of real-world things. For convolutional neural networks, it has been proven many times to have excellent results in "Facial Landmark Detection" and "Human Pose Estimation". We combine this and AR. So that, let it not only can tracking things but also awareness real world easily.

<p align="center">
  <img width="640" height="360" src="https://github.com/m5823779/Project/blob/main/Doc/LandmarkDetection.gif">
</p>

> Keywords : Deep Learning, Convolutional Neural Networks, Landmark Detection, Pose Estimation, Tracking, Yolo v3, HRNet, OpenCV, Pytorch, Python

<p align="center">
  <b> Stereo (Side by Side) Image Generator from Single Image </b>
</p>
<br> 

Have you ever wondered why people and many animals have two eyes? By using two eyes we can have a perception of depth. If you could have two pictures of your both eyes and you try to overlap these pictures you will see that there are big displacements in the nearest objects to your eyes while the displacements in the objects that are far away will be very small. These observed displacements are translated to the depth of the objects.

So far, many deep learning algorithms have made a huge success in monocular depth estimation. Using a convolution neural network, we can predict the depth value of each pixel, given only a single RGB image as input. According to the previous introduction, for pixels with farther depth, we make a larger offset for the pixels corresponding to the original image. for pixels with closer depth, we make a smaller offset. Then using some image inpainting algorithms. So that we can get an image from different perspectives. Combine with the original input we can get a stereo image. Finally, through a special display, we can let this stereo (side by side) image produce a 3D effect.

<p align="center">
  <img width="640" height="360" src="https://github.com/m5823779/Project/blob/main/Doc/SBSGenerator.gif">
</p>

> Keywords : Deep Learning, Convolutional Neural Networks, Depth Estimation, Image Inpainting, Side by Side, 3D, MiDas, OpenCV, Pytorch, Python, Libtorch, C++

<p align="center">
  <b> A Convolutional Neural Network for Real Time robot pose estimation by RGB Image </b>
</p>
<br> 

Localization is an important issue for navigation. SLAM has a good performance in indoor localization. Commonly used sensors are mainly divided into lasers or cameras. The advantage of laser SLAM is its high localization accuracy. However, the lack of image information leads to restrictions on some applications. Visual SLAM relies on RGB image and depth map. It also has good localization performance. The disadvantage is that a large number of features extracting and matching, cause a large amount of computation. Therefore, this research will focus on the pose estimation only by RGB image, without features extracting and matching. The robot pose is directly regressing by RGB image to achieve the purpose of indoor navigation.

In recent years, convolutional neural network have achieved good results in many computer vision studies.  There have some studies shown that it is possible to use deep learning to estimate pose by RGB images, such as PoseNet and MapNet. In this study, we use laser SLAM to collect the data, including RGB images and robot pose which is used as the training pairs required by PoseNet and MapNet. Our target is to regress the robot pose based on the current RGB image. Finally, apply this system on the real robot and combined it with path planning and speed control system to achieve the goal of navigation.

<p align="center">
  <img width="640" height="360" src="https://github.com/m5823779/Project/blob/main/Doc/PoseEstimation.gif">
</p>

> Keywords : Deep Learning, Convolutional Neural Networks, Localization, Pose Estimation, ROS, PoseNet, MapNet, OpenCV, Pytorch, Python

<p align="center">
  <b> Tiger Lake Touch Panel Phone Detection </b>
</p>
<br> 

In recent years, more and more laptops with touch panels are constantly being invented. And we cannot do without smart devices in our lives. Such as smartphone and smartwatch. communication and data transmission between equipment and equipment are increasingly important. We came up with an idea, is to put your smart device on the touch panel. Using "segmentation" to detect where is the device and Identify the phone model. Then connect with it. In this way, we don’t have to go through a cumbersome connection process to connect your mobile phone or any smart device to our computer.

<p align="center">
  <img width="640" height="360" src="https://github.com/m5823779/Project/blob/main/Doc/Segmentation.png">
</p>

> Keywords : Deep Learning, Convolutional Neural Networks, Semantic Segmentation, Background Subtraction, AutoEncoder, Encoder-Decoder, OpenCV, Tensorflow, Python
