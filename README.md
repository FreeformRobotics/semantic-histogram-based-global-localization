# semantic-histogram-based-global-localization
The global localization system based on semantic information

paper link: https://arxiv.org/abs/2010.09297 or https://ieeexplore.ieee.org/document/9353207/

Results
-
![](https://github.com/gxytcrc/Semantic-Graph-based--global-Localization/blob/main/example/result1.png)
![](https://github.com/gxytcrc/Semantic-Graph-based--global-Localization/blob/main/example/result2.png)

# 1. Prerequisites #
* Ubuntu
* CMake
* Eigen
* Pangolin
* OpenCV
* PCL

# 2. Running #
Clone the repository and catkin_make:
```
    git clone https://https://github.com/gxytcrc/Semantic-Graph-based--global-Localization.git
    mkdir build
    cd build
    cmake ..
    catkin_make
```
Download the dataset that is created from Airsim, and save them into the Datset . Download link: https://drive.google.com/file/d/1PIuRyah6lKDTe_YJ6HSVRX4l7MQLwKq5/view?usp=sharing. 

Launch it as follows:
```
./mapAlignment robot1-foldername startFrameNumber endFrameNumber robot2-foldername startFrameNumber endFrameNumber
```
