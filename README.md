# 图像与视频的人脸识别和聚类

## 1.使用opencv自带的Haar cascade

![image](https://user-images.githubusercontent.com/74084385/200887066-2aedb266-8715-48df-86e2-587b8e7b50e0.png)

## 2.使用google 的FaceNet 模型+MTCNN

![image](https://user-images.githubusercontent.com/74084385/200886824-aae2ba97-b31d-426a-bd2e-69266dc25f0d.png)

## 3.使用说明

python src/align/detect_face_images.py data/test1.jpg #图片人脸识别

python src/align/detect_face_camera.py #摄像头识别

python src/cluster.py weight data/images src/cluster_result #聚类

