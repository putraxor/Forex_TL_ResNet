# Forex_TL_ResNet
### Complete 37 Forex Instruments Pretrained ResNet Transfer Learning for Price Movement Classification

## What is this repo?
- This repo try to predict 60s horizon price movements from features derived from 600s close price window. 
- The price movement is categorized from 0 - 10 levels. Each category describes the level of movement from maximum down to maximum up.
-  You can use this repo to automatically extract features to be used for robust classifier like XGBoost or another NN model
- This model trained on 37 instruments, each instruments consist 7_000_000 seconds of close price 
- Using ResNet model adapted to time-series data
