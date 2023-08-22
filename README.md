# EfficientNet_Deeptooth

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
![image](https://github.com/natthanich/EfficientNet_Deeptooth/assets/108257658/e464e53a-c2b7-4247-b55d-c40844fc2de8)
![image](https://github.com/natthanich/EfficientNet_Deeptooth/assets/108257658/7df02543-7f22-424c-8d43-21880e4eec2f)
#### [Train ของรุ่นพี่ (250 epochs, Freeze)](https://github.com/Wanita-8943/Main_Project/blob/main/A1_Train_Freeze.ipynb)
![image](https://github.com/natthanich/EfficientNet_Deeptooth/assets/108257658/abf034d7-b185-4a64-adff-5cd84312ff90)
![image](https://github.com/natthanich/EfficientNet_Deeptooth/assets/108257658/ddbb2be4-7659-46f9-85d4-9198bd158a02)

## Predict รอบที่ 1 (เผลอเอา code ที่ train รอบแรกไปใช้ต่อ)
#### ผลจากชุดข้อมูลใหม่
- classification accuracy: 5.09%
- MAE: 5.608695652173913
- MSE: 46.35949098621421
- RMSE: 6.808780433103583
- ![image](https://github.com/natthanich/EfficientNet_Deeptooth/assets/108257658/254c30c4-b096-4314-b8cc-dd37e072f321)

#### [ผลจากรุ่นพี่](https://github.com/Wanita-8943/Main_Project/blob/main/A1_Predict_Freeze.ipynb)
- classification accuracy: 5.26%
- MAE: 4.7894736842105265
- MSE: 31.0
- RMSE: 5.5677643628300215
- ![image](https://github.com/natthanich/EfficientNet_Deeptooth/assets/108257658/c0ff49c8-b56a-4627-a2d9-5c67a3f69d8f)

## [Train รอบที่ 2 (250 epochs, Freeze)](https://github.com/natthanich/EfficientNet_Deeptooth/blob/main/Regress1_Train_250Freez_2.ipynb)
#### Train จากชุดข้อมูลใหม่
![image](https://github.com/natthanich/EfficientNet_Deeptooth/assets/108257658/364c2adb-6d7e-415a-8400-3a79c544e4e2)
![image](https://github.com/natthanich/EfficientNet_Deeptooth/assets/108257658/70e9cfe7-5e7b-4795-9eff-c31009da653a)

#### [Train ของรุ่นพี่](https://github.com/Wanita-8943/Main_Project/blob/main/A2_Train_Freeze.ipynb) 
![image](https://github.com/natthanich/EfficientNet_Deeptooth/assets/108257658/3f103b80-8a95-4704-9ed6-362ef9bc80df)
![image](https://github.com/natthanich/EfficientNet_Deeptooth/assets/108257658/ee64b657-4d78-43bd-b43b-866d9003a7f8)

## [Predict รอบที่ 2]()
#### ผลจากชุดข้อมูลใหม่
- classification accuracy: 5.30% 
- MAE: 4.737009544008483
- MSE: 30.04559915164369
- RMSE: 5.481386608481807
- ![image](https://github.com/natthanich/EfficientNet_Deeptooth/assets/108257658/0e258bc2-6310-4b11-977b-c6966b5f423e)


#### [ผลจากรุ่นพี่](https://github.com/Wanita-8943/Main_Project/blob/main/A2_Predict_Freeze.ipynb)
- classification accuracy: 5.26%
- MAE: 4.7368421052631575
- MSE: 30.0
- RMSE: 5.477225575051661
- ![image](https://github.com/natthanich/EfficientNet_Deeptooth/assets/108257658/c50e3a61-147e-494c-b6d7-57b9ce1e798d)



