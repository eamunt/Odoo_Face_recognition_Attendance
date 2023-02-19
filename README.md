# Odoo_Face_recognition_Attendance


Each person will have their own facial features and we can use classification or search methods to recognize that face, deep learning models are used to extract those features, from that can apply a search method to be able to recognize a person by comparing with the images already in the database. Therefore, in this topic will use Autofaiss, a method similar to the nearest neighbor search method, to search for faces detected from the DNN of OpenCV based ResNet SSD model and extract features using the model developed by Google is Facenet. Research and apply pre-processing techniques, compare face detection models as well as feature extraction models from face images to choose the best model, then build up Odoo a face time attendance system from Manual time attendance module is available on Odoo 13.

The Facenet feature extraction model gives an accuracy of 84.51% on the VN-Celeb dataset. Specially apply Autofaiss, an Approximate nearest neighbor (ANN) algorithm that is 5 times faster than traditional KNN algorithm for face recognition.

3 Giai đoạn của bài toán nhận diện khuôn mặt
<img width="1059" alt="Screen Shot 2023-02-19 at 23 55 07" src="https://user-images.githubusercontent.com/93971378/219962829-fe2d5700-4c33-4745-bd32-10ea00d68759.png">

Face detection:
<img width="824" alt="Screen Shot 2023-02-19 at 23 55 26" src="https://user-images.githubusercontent.com/93971378/219962961-c3ce1a72-0a82-4e48-a181-3223f0791b57.png">

Preprocessing
<img width="755" alt="Screen Shot 2023-02-19 at 23 55 42" src="https://user-images.githubusercontent.com/93971378/219962970-4a72d683-efd0-461e-8423-05dc97f83605.png">

Detect and crop
<img width="375" alt="Screen Shot 2023-02-19 at 23 56 16" src="https://user-images.githubusercontent.com/93971378/219963020-e265fecd-dd4b-47eb-a6ee-9368836dfed0.png">

Single shot multibox detector (SSD) model:
<img width="995" alt="Screen Shot 2023-02-19 at 23 56 44" src="https://user-images.githubusercontent.com/93971378/219963064-d0907a94-d5df-4c84-9d33-a7046736ba96.png">

Odoo:
<img width="654" alt="Screen Shot 2023-02-19 at 23 57 35" src="https://user-images.githubusercontent.com/93971378/219963082-9d388d05-0788-44cb-8397-d447469a57b4.png">

Chưa tới giờ chấm công:
<img width="746" alt="Screen Shot 2023-02-19 at 23 57 50" src="https://user-images.githubusercontent.com/93971378/219963118-41ebc14c-4db1-4651-a290-fe70047583be.png">

unknow(stranger):
<img width="723" alt="Screen Shot 2023-02-19 at 23 57 59" src="https://user-images.githubusercontent.com/93971378/219963147-b0120a41-c684-4c3a-b4cf-1bc5381bc240.png">

Checkin, checkout
<img width="973" alt="Screen Shot 2023-02-19 at 23 58 07" src="https://user-images.githubusercontent.com/93971378/219963176-4a7ae7d8-c3c0-4e98-a7f2-1022fe74bfc0.png">
<img width="1080" alt="Screen Shot 2023-02-19 at 23 58 17" src="https://user-images.githubusercontent.com/93971378/219963191-c5e6ce43-32a8-428a-a1b4-6c3b26bc163a.png">
