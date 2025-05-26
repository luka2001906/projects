# Bike Image Classifier – City vs. Race
This project classifies bike images into:
- City Bikes
- Race Bikes
  
Built with TensorFlow & MobileNetV2.

https://colab.research.google.com/drive/1yFsYErV8RpxNq9jw4hegaZQwMZOt0izS#scrollTo=yIF09xzIjTax

##  Dataset Format
training:
bike_images/

├── city/

├── race/

testing:

test/

├── city/

├── race/

model info

- MobileNetV2 + Transfer Learning
- Accuracy ~80% on validation data
- Supports image prediction and evaluation

output:

- Confusion Matrix
- Classification Report
- Prediction Function

