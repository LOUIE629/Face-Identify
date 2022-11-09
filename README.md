#图像与视频的人脸识别和聚类

##1.使用opencv自带的Haar cascade

##2.使用google 的FaceNet 模型+MTCNN

python src/align/detect_face_images.py data/test1.jpg #图片人脸识别

python src/align/detect_face_camera.py#摄像头识别

python src/cluster.py weight data/images src/cluster_result#聚类

