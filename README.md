# Technoverse 2023 
# i-Help : Diabetic Retinopathy Detection To Protect Your Vision.

## Introduction
India is often referred to as the ‘Diabetes Capital of the World' as it accounts for a whopping 17% of the total diabetes patients in the world. There are currently close to 80 million people with diabetes in India and this number is set to rise to 135 million by 2045.

With the rise of diabetes, the risks associated with diabetes has also been leading to complications like Diabetic Retinopathy.

Diabetic retinopathy is an eye condition that can cause vision loss and blindness in people who have diabetes. It affects blood vessels in the retina (the light-sensitive layer of tissue in the back of the eye). For patients with diabetes, it is important to get a comprehensive dilated eye exam at least once a year. 

Diabetic retinopathy is best diagnosed with a comprehensive dilated eye exam. Exams like Optical Coherence Tomography (OCT) are taken for this purpose. However, this requies expensive OCT machines and expertise to provide the required diagnosis, both of which are lacking in rural and small town areas.  


*iHelp* is our attempt to resolve this problem. With the help of Deep Learning, VGG algorithms and Machine training, we have built an inexpensive and convenient alternative to costly equipment like OCT machines. 

This code can be implemented through regular eye scanners for an early detection of Diabetic Retinopathy, thus preventing possible permanent blindness due to diabetic complications. 

## Tools used for development :

### Frontend - 
- **HTML and CSS**:- Used to create a visually appealing webpage and add styling, layout and control the look and feel of the website. 

- **Flask**:- It is a lightweight, open source web application framework for Python that we have used to deploy the deep learning model to the website.

### Backend -
- **TensorFlow**:- We have used tensorflow API to train our model which predicts the current stage of DR disease based on the eye scan image uploaded by the user.

- **KerasAPI**:- Keras is a high level neural network library. We have used it to train our deep learning model using the VGG19 Algorithm.

- **VGG16**:-VGG16 is a convolutional neural network architecture with 16 layers, known for its deep structure and strong performance in image classification tasks. It consists of multiple convolutional layers 5-max pooling layers, ending with 3 fully connected layers for prediction.

## Our Features : 
- Detection of 5 stages of Diabetic Retinopathy.
- Interactive UI-based web-app
- A chatbot on our web-app for service assistance and ease of usage.
- Generated DR report is sent to patient’s email.
- This report is also backed up on our IPFS web3 storage.
- Shows location of nearest eye hospital.

## Implementation :
- The eye scan is fed into our model through the interface.
- This scan is analysed and a DR detection report is generated, based on our dataset of about 3,600 images of DR retina scans from IEEE.
- The detailed report is sent to the patient's email, and stored in MongoDB.
- All our data in MongoDB is backed up in our decentralised IPFS web3 storage.
- Google Maps API has been used for showing the nearest eye hospital as a suggestion to the patient, based on the current location of the user.
- If the patient has any queries, they can get the required answers through our chatbot on our web-app.
  
### Here's our [project demonstration](https://youtu.be/34BKagFus_A) on youtube

## Output Screenshots:
### Output 1:
i-Help web app user interface

![UI1 (1)](https://github.com/PMalvikaReddy/Technoverse_iHelp-DiabeticRetinopathyDetection/assets/116015331/be84ec36-7547-4490-a25a-54587b0d462d)

### Output 2:
User interface 2

![UI1 (2)](https://github.com/PMalvikaReddy/Technoverse_iHelp-DiabeticRetinopathyDetection/assets/116015331/ab8a1eee-fdc1-4d2d-8c80-9a309d38d5e0)

### Output 3:
Nearest hospital location

![UI1 (3)](https://github.com/PMalvikaReddy/Technoverse_iHelp-DiabeticRetinopathyDetection/assets/116015331/c26d0c87-c242-4a6d-85df-7049f2117173)

### Output 4:
ChatBot implementation in the web app.

![UI1_chatbot](https://github.com/PMalvikaReddy/Technoverse_iHelp-DiabeticRetinopathyDetection/assets/116015331/bcd33001-ac75-4c50-9320-0b8857c8445a)

### Output 5:
Diabetic Retinopathy Detection by uploading the eye scan image.

![UI1_prediction](https://github.com/PMalvikaReddy/Technoverse_iHelp-DiabeticRetinopathyDetection/assets/116015331/52212b2b-a2ee-4ebb-a101-59ef5352679f)

### Output 6:
MongoDb database to store user information and the ipfs report pdf url.

![UI1_mongodb](https://github.com/PMalvikaReddy/Technoverse_iHelp-DiabeticRetinopathyDetection/assets/116015331/1cacc278-10fe-4578-8a14-bd15d37f24a4)

### Output 7:
The email is generateed once the prediction happens from the image uploaded by the user. The email consists of an attachment of the medical report generated.

![UI1_email](https://github.com/PMalvikaReddy/Technoverse_iHelp-DiabeticRetinopathyDetection/assets/116015331/049800d7-f6e5-4cfa-82b5-5b53e0f9d0f9)

### Output 8:
The generated report after prediction stored on the ipfs web3 storage using the moralis api:

![ipfs_pdf](https://github.com/PMalvikaReddy/Technoverse_iHelp-DiabeticRetinopathyDetection/assets/116015331/bbd4a376-8fdc-4ba2-9420-8e2c10b11cc6)

## Our unique value proposition :
This is **iHelp**.
We provide an interactive user-friendly interface for patients to  use, so that anyone can have access to a quick and free diagnosis of Diabetic Retinopathy disease. By **SOLVING THIS PROBLEM** our vision is to help every Indian at the risk of or suffering from dementia and enable them to lead quality life with better vision.








