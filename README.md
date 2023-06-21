# Tamil-Actor-Image-Classification
The project demonstrates the potential of combining computer vision techniques and machine learning algorithms to solve image classification tasks



Project Description:

Title: Tamil Actor Image Classification using Head Detection, Eye Counting, Wavelet Transformation, and SVC Algorithm

Overview:
This project focuses on classifying images of Tamil actors using a combination of computer vision techniques and machine learning algorithms. The dataset consists of images of five Tamil actors, and the goal is to accurately classify each image based on the actor depicted.

Methodology:
The project employed several steps and techniques to achieve accurate image classification. The process began by utilizing the OpenCV library to detect and extract the head portion from each actor's image. This step aimed to isolate the relevant region containing the actor's face.

Next, eye counting was performed on each extracted head image using computer vision techniques. By calculating the number of eyes present in each photo, the project aimed to filter out incorrect or irrelevant images. Images with zero or an unexpected number of eyes were considered erroneous and removed from further analysis.

Following the eye filtering step, wavelet transformation was applied to the remaining head images. Wavelet transformation is a powerful tool in image processing that extracts features and patterns at multiple scales. This transformation aimed to capture distinct visual characteristics unique to each actor's image, enhancing the discriminative ability of the classification model.

Finally, the processed head images, transformed through wavelet analysis, were fed into a Support Vector Classifier (SVC) algorithm. The SVC algorithm is a popular choice for image classification tasks due to its ability to handle complex data and find optimal decision boundaries between different classes. The model was trained using the processed images and their corresponding actor labels to learn the patterns and relationships necessary for accurate classification.

Results:
The developed image classification model achieved successful classification of Tamil actor images. By employing the combination of head detection, eye counting, wavelet transformation, and the SVC algorithm, the model accurately classified the images into their respective actor categories.

Implications:
Accurate image classification of Tamil actors has practical implications in various domains. This model can be used in movie databases or social media platforms to automatically tag or identify Tamil actors in images. It can also assist in organizing actor-specific photo collections, aiding fans and enthusiasts in easily accessing and browsing images of their favorite actors.

Conclusion:
This project successfully implemented an image classification system for Tamil actors. By utilizing head detection, eye counting, wavelet transformation, and the SVC algorithm, the model accurately classified the images based on the actors depicted. The developed system has practical implications in the organization of actor-specific image collections and can be integrated into various applications to automatically tag or identify Tamil actors in images.
