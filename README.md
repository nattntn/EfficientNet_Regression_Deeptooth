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

## Train รอบที่ 2 
#### [Train จากชุดข้อมูลใหม่ (250 epochs, Freeze)](Regress1_Train_250Freez_2.ipynb)
#### [Train ของรุ่นพี่ (250 epochs, Freeze)](https://github.com/Wanita-8943/Main_Project/blob/main/A2_Train_Freeze.ipynb)

## Predict รอบที่ 2
#### [ผลจากชุดข้อมูลใหม่](Regress1_Predict_Freeze_2.ipynb)
- classification accuracy: 5.30% 
- MAE: 4.737009544008483
- MSE: 30.04559915164369
- RMSE: 5.481386608481807

#### [ผลจากรุ่นพี่](https://github.com/Wanita-8943/Main_Project/blob/main/A2_Predict_Freeze.ipynb)
- classification accuracy: 5.26%
- MAE: 4.7368421052631575
- MSE: 30.0
- RMSE: 5.477225575051661

## Train รอบที่ 3 
#### [Train จากชุดข้อมูลใหม่ (250 epochs, Freeze)](Regress1_Train_250Freez_3.ipynb)
#### [Train ของรุ่นพี่ (250 epochs, Freeze)](https://github.com/Wanita-8943/Main_Project/blob/main/A3_Train_Freeze.ipynb)

## Predict รอบที่ 3
#### [ผลจากชุดข้อมูลใหม่](Regress1_Predict_Freeze_3.ipynb)
- classification accuracy: 12.41% 
- MAE: 2.535524920466596
- MSE: 10.389183457051962
- RMSE: 3.223225629249675

#### [ผลจากรุ่นพี่](https://github.com/Wanita-8943/Main_Project/blob/main/A3_Predict_Freeze.ipynb)
- classification accuracy: 5.26%
- MAE: 4.7368421052631575
- MSE: 30.0
- RMSE: 5.477225575051661

## Train รอบที่ 4 
#### [Train จากชุดข้อมูลใหม่ (250 epochs, Freeze)](Regress1_Train_250Freez_4.ipynb)
#### [Train ของรุ่นพี่ (250 epochs, Unfreeze)](https://github.com/Wanita-8943/Main_Project/blob/main/A4_Train_Unfreez.ipynb)

## Predict รอบที่ 4
#### [ผลจากชุดข้อมูลใหม่](Regress1_Predict_Freeze_4.ipynb)
- classification accuracy: 11.66% 
- MAE: 2.4464475079533403
- MSE: 9.632025450689289
- RMSE: 3.103550458859867

#### [ผลจากรุ่นพี่](https://github.com/Wanita-8943/Main_Project/blob/main/A4_Predict_Unfreeze.ipynb)
- classification accuracy: 19.89%
- MAE: 1.7968421052631578
- MSE: 5.893684210526316
- RMSE: 2.427691127496724

## Train รอบที่ 5 
#### [Train จากชุดข้อมูลใหม่ (250 epochs, Freeze)](Regress1_Train_250Freez_5.ipynb)
#### [Train ของรุ่นพี่ (250 epochs, Unfreeze)](https://github.com/Wanita-8943/Main_Project/blob/main/A5_Train_Unfreez.ipynb)

## Predict รอบที่ 5
#### [ผลจากชุดข้อมูลใหม่](Regress1_Predict_Freeze_5.ipynb)
- classification accuracy: 13.79% 
- MAE: 2.503711558854719
- MSE: 10.255567338282079
- RMSE: 3.2024314728471674

#### [ผลจากรุ่นพี่](https://github.com/Wanita-8943/Main_Project/blob/main/A5_Predict_Unfreeze.ipynb)
- classification accuracy: 23.10%
- MAE: 1.6189473684210527
- MSE: 5.096842105263158
- RMSE: 2.257618680216648

## Train รอบที่ 6 
#### [Train จากชุดข้อมูลใหม่ (500 epochs, Freeze)](Regress1_Train_500Freez_6.ipynb)

## Predict รอบที่ 6
#### [ผลจากชุดข้อมูลใหม่](Regress1_Predict_500Freeze_6.ipynb)
- classification accuracy: 14.95% 
- MAE: 2.3213149522799577
- MSE: 9.366914103923648
- RMSE: 3.060541472341724

## Train รอบที่ 7 
#### [Train จากชุดข้อมูลใหม่ (250 epochs, Unfreeze)](Regress1_Train_250Unfreez_7.ipynb)

## Predict รอบที่ 7
#### [ผลจากชุดข้อมูลใหม่](Regress1_Predict_250Unfreeze_7.ipynb)
- classification accuracy: 18.98% 
- MAE: 1.616118769883351
- MSE: 4.685047720042418
- RMSE: 2.1644971055749687

## Train รอบที่ 8 
#### [Train จากชุดข้อมูลใหม่ (250 epochs, Unfreeze)](Regress1_Train_250Unfreez_8.ipynb)

## Predict รอบที่ 8
#### [ผลจากชุดข้อมูลใหม่](Regress1_Predict_250Unfreeze_8.ipynb)
- classification accuracy: 26.62% 
- MAE: 1.4146341463414633
- MSE: 3.9660657476139978
- RMSE: 1.9914983674645574

## Train รอบที่ 9 
#### [Train จากชุดข้อมูลใหม่ (250 epochs, Unfreeze)](Regress1_Train_250Unfreez_9.ipynb)

## Predict รอบที่ 9
#### [ผลจากชุดข้อมูลใหม่](Regress1_Predict_250Unfreeze_9.ipynb)
- classification accuracy: 25.87% 
- MAE: 1.4878048780487805
- MSE: 4.327677624602333
- RMSE: 2.0803070986280687


## Train รอบที่ 10 
#### [Train จากชุดข้อมูลใหม่ (250 epochs, Unfreeze)](Regress1_Train_250Unfreez_10.ipynb)

## Predict รอบที่ 10
#### [ผลจากชุดข้อมูลใหม่](Regress1_Predict_250Unfreeze_10.ipynb)
- classification accuracy: 32.45% 
- MAE: 1.4019088016967127
- MSE: 4.373276776246024
- RMSE: 2.0912380964983455


