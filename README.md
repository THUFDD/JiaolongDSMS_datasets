<div align="center">
    <img src="https://github.com/songqiaohu/pictureandgif/blob/main/jiaolong-1.png?raw=true" width="50%">
</div>

### Background：
The data was collected and provided by the National Deep Sea Center in Qingdao, Shandong, China. The initial data is collected in the exploration task for the JiaoLong Deep-sea Manned Submersible on March 19-th, 2017. The form of data is the multi-variate time series with around 24 features. We hide the measurement units of all the variables. We aim to provide a benchmark dataset of real-time safety assessment (RTSA) methods for dynamic systems, enabling researchers to conduct their research effectively.

### Variable Description: 


| Monitored Variable                             | Explanations in Chinese            |
|:-------------------------------:|:----:|
| Roll Angle of Motion Sensor      | 运动传感器横倾角          |
| Pitch Angle of Motion Sensor     | 运动传感器纵倾角          |
| Yaw Angle of Motion Sensor       | 运动传感器航向角          |
| Velocity in Bow Direction        | 运动传感器艏向速度        |
| Roll Velocity of Motion Sensor   | 运动传感器横摇速度        |
| Pitch Velocity of Motion Sensor  | 运动传感器纵倾速度        |
| Salinity                         | 盐度                       |
| Temperature                      | 温度                       |
| Depth                            | 深度                       |
| Velocity                         | 速度                       |
| Thrust in X-axis                 | x轴向推力                 |
| Thrust in Y-axis                 | y轴向推力                 |
| Thrust in Z-axis                 | z轴向推力                 |
| Moment about X-axis              | 绕X轴力矩                 |
| Moment about Y-axis              | 绕Y轴力矩                 |
| Moment about Z-axis              | 绕Z轴力矩                 |
| Oxygen Concentration             | 氧气浓度                   |
| Carbon Dioxide Concentration     | 二氧化碳浓度               |
| Cabin Pressure                   | 舱内压力                   |
| Cabin Temperature                | 舱内温度                   |
| Cabin Humidity                   | 舱内湿度                   |
| Emergency Hydraulic Source Pressure | 应急液压源压力           |
| Backup 2                         | 备份2                     |
| Backup 3                         | 备份3                     |


### Label Description:
  | Safety Level                            | Descriptions            |
|:-------------------------------:|:----:|
|  **Level I**     | DSMS is currently in *safety* state. There are no safety risks from the external environment and the system is in a healthy state internally.          |
|  **Level II**     | DSMS is currently operating in a *mildly unsafe* state. There may be safety risks in the external environment or controllable abnormalities within the system.      |
|  **Level III**       | DSMS is currently operating in an *unsafe* state. There are certain safety risks in the external environment or dangerous abnormalities inside the system.        |
  
### Dataset Description:
| Number of monitored variables  | 24     |
|:-------------------------------:|:----:|
| Number of safety levels         | 3      |
| Number of time points          | 30000 |
| Imbalance ratio (I: II: III)   | 10512 : 10985 : 8503 |


### Visualization:

<div align="center">
    <img src="https://github.com/songqiaohu/pictureandgif/blob/main/variable-1.png?raw=true" width="50%">
</div>

<div align="center">
    <img src="https://github.com/songqiaohu/pictureandgif/blob/main/Jiaolong_dataset-1.png?raw=true" width="50%">
</div>

### Citation
```
Z. Liu, Y. Zhang, Z. Ding, and X. He, “An Online Active Broad Learning Approach for Real-Time Safety Assessment of Dynamic Systems in Nonstationary Environments,” IEEE Transactions on Neural Networks and Learning Systems, 2022, doi: 10.1109/TNNLS.2022.3222265.
```

```
@article{liu2022OABL,
  title={An Online Active Broad Learning Approach for Real-Time Safety Assessment of Dynamic Systems in Nonstationary Environments},
  author={Liu, Zeyi and Zhang, Yi and Ding, Zhongjun and He, Xiao},
  journal={IEEE Transactions on Neural Networks and Learning Systems},
  year={2022},
  doi={10.1109/TNNLS.2022.3222265},
  publisher={IEEE}
}
```

### Notes: 
- We are from the research group of THU-FDD, Department of Automation, Tsinghua University. For more information, please feel free to contact us! Emails: liuzy21@mails.tsinghua.edu.cn, hsq23@mails.tsinghua.edu.cn.

- We have updated a newer version of the dataset (Version 2) on October 27, 2023. Compared with the previous version (Version 1), it contains more monitoring variables and more detailed descriptions.
