CNNModel erroe : 10 (base_model)

CNNNewBaseModel Error : 11 (model2)

CNNNewModel1 Error : 11 (CnnNewModel1)
# model0 = Sequential([
#         Conv2D(64, (3,3), activation='relu', padding='same', input_shape=(img_size, img_size, 3)),
#         MaxPool2D(2),
#         Dropout(0.25),

#         Conv2D(128, (3,3), activation='relu', padding='same'),
#         MaxPool2D(2),
#         Dropout(0.25),

#         Conv2D(256, (3,3), activation='relu', padding='same'),
#         MaxPool2D(2),
#         Dropout(0.25),

#         Flatten(),
#         Dense(128, activation='relu'),
#         Dropout(0.5),
#         Dense(num_classes, activation='softmax')
# ])

#Model : https://drive.google.com/drive/folders/1jNi-uwkHv1QH-GDynp7yvVgr3e7dpt7G?usp=sharing