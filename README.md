# AWS-Rekognition

We integrated a face recognition feature into any platform application using **Amazon Rekognition**, eliminating the need to worry about implementing complex Machine Learning or Computer Vision algorithms. This solution utilizes **AWS S3** for secure image storage, **DynamoDB** for managing face metadata, **AWS Lambda** for real-time serverless processing, and **IAM** for secure access control. When an image is uploaded to S3, a Lambda function triggers Rekognition to analyze faces, store the data in DynamoDB, and perform efficient face matching. This architecture is scalable, secure, and cost-effective, ideal for authentication, surveillance, and personalized services.
<p align="center">
  <img src="\Steps Images\Screenshot 2024-12-02 175351.png" alt="Project Screenshot 1" >
  <img src="\Steps Images\Screenshot 2024-12-02 175411.png" alt="Project Screenshot 2" >
  <img src="\Steps Images\Screenshot 2024-12-02 175452.png" alt="Project Screenshot 3" >
  <img src="\Steps Images\Screenshot 2024-12-02 175524.png" alt="Project Screenshot 4" >
  <img src="\Steps Images\Screenshot 2024-12-02 175536.png" alt="Project Screenshot 5" >
  <img src="\Steps Images\Screenshot 2024-12-02 180141.png" alt="Project Screenshot 6" >
</p>

