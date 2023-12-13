# CNN_Fashion-MNIST_Classifier

## Các bước làm
1. Load dữ liệu từ file `/data`.
2. Tách dữ liệu ra 2 tập train và validation.
3. Chuẩn hóa dữ liệu cho label của train và validation sang categorical.
4. Load backbone `EfficientNetV2M`.
5. Chuẩn hóa dữ liệu và tạo dataset tensor cho train và validation.
6. Thiết kế dựa trên basemodel là EfficientNetV2M.
7. Lưu epoch có val_accuracy tốt nhất.
8. Load epoch đã lưu.
9. Chuẩn hóa và chuyển tập test qua tensor để phù hợp với dữ liệu đầu vào của mô hình.
10. Dự đoán test dataset và xuất ra file `.csv`.

## Introduction
This is a package with EfficientNetV2 model variants adapted to Keras functional API.
I rewrote them this way so that the usage is similar to `keras.applications`.

The model's weights are converted from [original repository](https://github.com/google/automl/tree/master/efficientnetv2).

## Summary
![image](https://github.com/M1nhHoang/CNN_Fashion-MNIST_Classifier/assets/106025710/4dea9c05-e6ab-4e37-b79a-8e884ff8a8c5)


## Dataset
Total 42,000 different 28 x 28 grayscale images.  

![image](https://github.com/M1nhHoang/MLP_For_Classifier_Images/assets/106025710/45fff3a8-0774-46e4-8e9a-8dbc994bc15e)

## Result
![image](https://github.com/M1nhHoang/CNN_Fashion-MNIST_Classifier/assets/106025710/0fea5133-205c-4b61-8734-5a6c894408d6)

## Kaggle compertitions: My team - [123TGMT2002-7777](https://www.kaggle.com/competitions/cnn-competition-123/leaderboard)
[Final result](https://docs.google.com/spreadsheets/d/1q-2ltaBjoGufW0XxyljoMNXtRKogu-SZR0V123Up438)
