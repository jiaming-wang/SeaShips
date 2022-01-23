# Seaships: A large-scale precisely annotated dataset for ship detection

We introduce a new large-scale dataset of ships, called SeaShips, which is designed for training and evaluating ship object detection algorithms. The dataset currently consists of 31 455 images and covers six common ship types (ore carrier, bulk cargo carrier, general cargo ship, container ship, fishing boat, and passenger ship). All of the images are from about 10 080 real-world video segments, which are acquired by the monitoring cameras in a deployed coastline video surveillance system. They are carefully selected to mostly cover all possible imaging variations, for example, different scales, hull parts, illumination, viewpoints, backgrounds, and occlusions. All images are annotated with ship-type labels and high-precision bounding boxes.

Sponsor: The State Key Laboratory of Information Engineering in Surveying, Mapping and Remote Sensing, Wuhan University

Contact: Jiaming Wang, Email: wjmecho@whu.edu.cn;  Zhenfeng Shao, Email: shaozhenfeng@whu.edu.cn;  

# Examples of Raw Samples


![image](/fig/fig1.png)

Image 1. Example images of six ship types.

----------


![image](/fig/fig2.png)

Image 2. Three different scales when the camera is looking side the sea.

----------

![image](/fig/fig3.png)

Image 3. Some backgrounds in the dataset.

----------

Table 1. Number of images of each ship category.  
|Categories|Images|Percentage|
|:---:|:---:|:---:|
|Ore carries| 5126 | 0.1630|
|Bulk cargo carries| 5067 | 0.1610|
|Container ship| 3657 | 0.1163|
|General cargo ship| 5342 | 0.1698|
|Fishing boat| 5652 | 0.1797|
|Passenger ship| 3171 | 0.1008|
|Mixed type| 3440 | 0.1094|
----------



# Download Datasets
Download link: [Baidu](https://pan.baidu.com/s/1p3cWGB-CrpExpdbMGxPs2g) Password: j3aq

Download link: [Url](http://www.lmars.whu.edu.cn/prof_web/shaozhenfeng/datasets/SeaShips(7000).zip)


# Reference

If you find this work useful, please consider citing it.
```
@article{shao2018seaships,
  title={Seaships: A large-scale precisely annotated dataset for ship detection},
  author={Shao, Zhenfeng and Wu, Wenjing and Wang, Zhongyuan and Du, Wan and Li, Chengyuan},
  journal={IEEE transactions on multimedia},
  volume={20},
  number={10},
  pages={2593--2604},
  year={2018},
  publisher={IEEE}
}

@article{shao2019saliency,
  title={Saliency-aware convolution neural network for ship detection in surveillance video},
  author={Shao, Zhenfeng and Wang, Linggang and Wang, Zhongyuan and Du, Wan and Wu, Wenjing},
  journal={IEEE Transactions on Circuits and Systems for Video Technology},
  volume={30},
  number={3},
  pages={781--794},
  year={2019},
  publisher={IEEE}
}
```
