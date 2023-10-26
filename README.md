# JiaolongDSMS_datasets

## Jiaolong Deep-Sea Manned Submersible datasets (Life Support System)

The data used in this paper was collected and provided from the National Deep Sea Center in Qingdao, Shandong, China. The initial data is collected in the exploration task for the JiaoLong DSMS on March $19^{th}$, 2017. 
The form of data is the multi-variate time series with around 11 features. The sub-system of JiaoLong DSMS such as life support system is selected to analyze. Our purpose is to assess the safety level, such as safe level and unsafe level, for the tested data stream. 

The seven variables of the life support system represent the real-time monitoring indicators, including oxygen ($O_2$) concentration in the cabin, carbon dioxide ($CO_2$) concentration in the cabin, cabin pressure (Pa), cabin humidity, and cabin temperature ($^\circ$C). In addition, backup 2 and backup 3 are also considered, representing the oxygen concentration of another set of oxygen sensors and the carbon dioxide concentration of another set of carbon dioxide sensors, respectively. Two settings of oxygen and carbon dioxide sensors are set up in the cabin as a backup to monitor the oxygen and carbon dioxide concentration at any time.  Hence, the monitoring data of backup 2 and backup 3 are the values of another set of oxygen and carbon dioxide sensors. Moreover, four settings of other external monitoring variables containing salinity, temperature, depth, and speed are selected. The monitoring data is sourced from the value of the conductivity temperature depth (CTD) sensor installed outside the JiaoLong DSMS, which monitors the real-time seawater salinity, temperature, depth, and the speed of ascending and descending.

During the experiment, the JiaoLong DSMS gradually descended from the shore to around 3000 meters. It is worth noting that the used labels are derived from the records of real voyage logs obtained in JiaoLong DSMS. The total number of samples is $64138$. 


## Citation

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
