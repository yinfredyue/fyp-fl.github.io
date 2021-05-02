Supervisor: Professor C.L. Wang. Project member: Yue Yin, Ruijie Li. 



## Poster

![Poster](./poster.jpg)

Video explanation: [Google Drive link](https://drive.google.com/file/d/1ovrO3CFNfnRV6PtwZc02XMLbqdsoWx5G/view?usp=sharing)



## Abstract

Mobile devices have access to unprecedented amount of data for machine learning, and federated learning (FL) trains model using such data, without compromsing user privacy. The synchronization scheme crucial affects the performance of FL. Three schemes, ASP, BSP, and SSP are most widely used, where SSP is a generalized case. In this project we focus on SSP.

The value of staleness bound *s* is the key factor in SSP. In this project, we analyzed the relationship between *s*, convergence time, and model accuracy. Based on the observation, we proposed a strategy *Adaptive-SSP* that changes the value of *s* throughout training, to achieve high accuracy and fast convergence at the same time. We implemented Addaptive-SSP based on an open-source FL framework, and evaluated the performance of Adaptive-SSP on different FL applications.

See the [final report](./Final_report.pdf) for details. The source code is available at [here](https://github.com/yinfredyue/flower).