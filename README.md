# Image-based Obstacle Avoidance using 3DConv Network for Rocky Environment
To accomblish obstacle avoidace task, we used a 3DConv network to produse a steering direction based on sequantioal RGB images input. The results shows the ability of the nework to avoide rocks with different shapes and sizes. Traning and testing data was based on AirSim simulator. We considered 5 different inputs to the network and we tested to see which tyype of inpute yeilds the best performance. The different models included :
- Gray image
- Depth map
- Gray image + Depth map
- RGB image
- RGB image + Depth map

![network_2-1](https://user-images.githubusercontent.com/118448679/202459200-632b3990-b23f-4bde-acb4-276aed4a642f.png)
> Netwrok considaring gray sequance input
