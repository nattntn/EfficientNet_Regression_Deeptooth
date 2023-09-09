# EfficientNet_Regression_Deeptooth

# แบบที่ 1
- batch_size = 16
- width = 150
- height = 150 
- epochs = 250 ยกเว้น รอบที่ 6 500 epochs
- dropout_rate = 0.2 
- input_shape = (height, width, 3)
- activation='softmax' ใน layer ชั้นรองสุดท้าย
- loss='mse',
- optimizer=Adam 
- learning_rate=1e-4
- metrics=['mae']
- 10-fold-crossvalidation
- 
## Train รอบที่ 1 (250 epochs, Freeze)(เผลอเอา code ที่ train รอบแรกไปใช้ต่อ) 	:smiling_face_with_tear:
#### Train จากชุดข้อมูลใหม่
#### [Train ของรุ่นพี่ (250 epochs, Freeze)](https://github.com/Wanita-8943/Main_Project/blob/main/A1_Train_Freeze.ipynb)
## Predict รอบที่ 1 (เผลอเอา code ที่ train รอบแรกไปใช้ต่อ)
#### ผลจากชุดข้อมูลใหม่
- classification accuracy: 5.09%
- MAE: 5.608695652173913
- MSE: 46.35949098621421
- RMSE: 6.808780433103583
  
#### [ผลจากรุ่นพี่](https://github.com/Wanita-8943/Main_Project/blob/main/A1_Predict_Freeze.ipynb)
- classification accuracy: 5.26%
- MAE: 4.7894736842105265
- MSE: 31.0
- RMSE: 5.5677643628300215

## [Train รอบที่ 2 (250 epochs, Freeze)](https://github.com/natthanich/EfficientNet_Deeptooth/blob/main/Regress1_Train_250Freez_2.ipynb)
#### Train จากชุดข้อมูลใหม่
#### [Train ของรุ่นพี่](https://github.com/Wanita-8943/Main_Project/blob/main/A2_Train_Freeze.ipynb) 

## [Predict รอบที่ 2]()
#### ผลจากชุดข้อมูลใหม่
- classification accuracy: 5.30% 
- MAE: 4.737009544008483
- MSE: 30.04559915164369
- RMSE: 5.481386608481807

#### [ผลจากรุ่นพี่](https://github.com/Wanita-8943/Main_Project/blob/main/A2_Predict_Freeze.ipynb)
- classification accuracy: 5.26%
- MAE: 4.7368421052631575
- MSE: 30.0
- RMSE: 5.477225575051661




