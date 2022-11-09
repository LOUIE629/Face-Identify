# 图像与视频的人脸识别和聚类

## 1.使用opencv自带的Haar cascade
![1](https://user-images.githubusercontent.com/74084385/179125092-193c4687-c4d5-4907-b8db-38919c9dee98.png)

## 2.使用google 的FaceNet 模型+MTCNN
![image](https://user-images.githubusercontent.com/74084385/200886824-aae2ba97-b31d-426a-bd2e-69266dc25f0d.png)

python src/align/detect_face_images.py data/test1.jpg #图片人脸识别

python src/align/detect_face_camera.py#摄像头识别

python src/cluster.py weight data/images src/cluster_result#聚类

