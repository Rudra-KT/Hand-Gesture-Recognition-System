# Hand Gesture Recognition System
Hand Gesture Recognition System using google mediapipe and DL

# Model Architecture 
```
model = tf.keras.models.Sequential([
    tf.keras.layers.Input((21 * 2, )),
    tf.keras.layers.Dropout(0.2),
    tf.keras.layers.Dense(20, activation='relu'),
    tf.keras.layers.Dropout(0.4),
    tf.keras.layers.Dense(10, activation='relu'),
    tf.keras.layers.Dense(NUM_CLASSES, activation='softmax')
])
```

# Classification Report

The performance metrics for the model are as follows:

              precision    recall  f1-score   support

           0       0.92      0.99      0.95       411
           1       0.90      0.91      0.90       370
           2       0.85      0.99      0.92       305
           3       0.98      0.92      0.95        87
           4       0.81      0.64      0.71        39
           5       0.99      0.91      0.95        86
           6       0.94      0.68      0.79        87
           7       1.00      0.16      0.27        51

    accuracy                           0.90      1436
```
 macro avg       0.92      0.77      0.80      1436 
 weighted avg    0.91      0.90      0.89      1436 
```

# DEMO RUN
![image](https://github.com/Rudra-KT/Hand-Gesture-Recognition-System/assets/96310018/dc2651d9-2e57-4bea-84ba-fa6a87beb9d8)




