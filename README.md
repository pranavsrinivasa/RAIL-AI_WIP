# RAIL-AI [WIP]:
## Problem statement:
- Using existing CCTV network for crowd management, crime prevention, and work monitoring using AI ML 
## Proposed solution:
- Computer vision is incorporated with CCTV in the railway stations to accumulated in datasets
- Time Series Anomaly detection GAN network is planned to use analyze the incoming image as a whole to generate a optimal image from the time series data and compare it with the actual iamge to analyze anamolies in crowd control
- Any deviation from the optimal image can be used to optimize the crowd control system and inform the respective authorities to ensure smooth crowd flow by using appropriate measures such as increase queues when it is predicted to have large crowds
- A crime detection model is create to analyze each image to acertain any abnormal behavior in people or any crimes that are being commited, helping the authorities to act faster.
- Time series GAN or Stable diffusion models are used for crowd controll since they are better at analyzing image as a whole 
- A seperate crime detection model is used since small subsets of the images need to be analyzed for which GAN and Stable diffusion would not be efficient.
