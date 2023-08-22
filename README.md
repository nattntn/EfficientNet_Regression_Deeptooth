# EfficientNet_Deeptooth

# แบบที่ 1
batch_size = 16
width = 150
height = 150 
epochs = 250 ยกเว้น รอบที่ 6 500 epochs
dropout_rate = 0.2 
input_shape = (height, width, 3)
activation='softmax' ใน layer ชั้นรองสุดท้าย
loss='mse',
optimizer=Adam 
learning_rate=1e-4
metrics=['mae']

