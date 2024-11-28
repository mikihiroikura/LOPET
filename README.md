This repository provides a simplified MATLAB code for our event-based object pose tracking method.

Firstly, extract the "event.zip" file to the current directory, and then execute the "main_demo.m".

Due to file size limitations, only a portion of the testing events are uploaded for demonstration purposes.

Details of the method can be found in our paper:

Line-based 6-DoF Object Pose Estimation and Tracking With an Event Camera

## Cite

@ARTICLE{10645740,  
  author={Liu, Zibin and Guan, Banglei and Shang, Yang and Yu, Qifeng and Kneip, Laurent},  
  journal={IEEE Transactions on Image Processing},   
  title={Line-based 6-DoF Object Pose Estimation and Tracking With an Event Camera},  
  year={2024},  
  volume={33},  
  pages={4765-4780},  
  doi={10.1109/TIP.2024.3445736}}  


## Contact
Please contact Zibin Liu <liuzibin19@nudt.edu.cn> to obtain the dataset for academic purposes. 
Please contact Banglei Guan <guanbanglei12@nudt.edu.cn> or any of the other authors for any inquiries or requests.

## Build docker environment
```
docker build  -t lopet:R2024b .
```
If you would like to modify Toolboxes, you can follow this [procedure](https://github.com/mathworks-ref-arch/matlab-dockerfile/tree/main/alternates/building-on-matlab-docker-image#build-an-image-with-license-server-information)

## Run docker container with docker-compose
```
docker compose up -d
```

## How to run `main_demo.m`
1. Run docker container
2. You can open browser and open this [Localhost URL](http://localhost:8888/index.html)
3. Go to LOPET directory
4. Unzip `events.zip`
5. Run `main_demo.m`
