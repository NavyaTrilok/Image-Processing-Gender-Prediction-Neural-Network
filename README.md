# Image-Processing-Gender-Prediction-Model

I have used Artificial Neural Network(ANN) using deep learning techniquest to predict the gender of the person in the image.

I have used OpenCV library for image processing:
To normalize the imput date
1) Detected and sliced the face of the person in the image
2) Converted the images to grayscale
3) Reshaped the images to 48 x 48 input size

Model is trained on 5 hidden layers with 1,102,902 Trainable parameters

This repo consists of 2 .ipynb files -
- Gender-Prediction-Model.ipynb - For Training and evaluation of the model and saved the model
- Testing-Model-with-Image.ipynb - For image processing of test image and predicting the gender of the person in image using saved model from above

I have highlighed the cases where model is going wrong in predicting the gender of the person in image. These are all the cases where the person in the image is kid. For kids even we as humans cannot define the gender of the kid by looking at face.

I have used the libraries -
- OpenCV for image processing
- FER for face detection
- Matplotlib to load and process image data
- numpy to process image data in the form of numpy arrays
- Keras for model building and saving the model

Gender prediction models using image processing can be applied in several real-time scenarios, including:
- Surveillance Systems: Analyzing video feeds for demographic insights in public spaces, helping to monitor and manage crowd behavior.
- Retail Environments: Understanding customer demographics in stores to optimize layouts, product placements, and marketing strategies based on the predicted gender of shoppers.
- Social Media Applications: Enhancing photo tagging and content recommendations by predicting the gender of users in images.
- Personalized User Experiences: Tailoring app interfaces or services based on the predicted gender of users in applications like dating or social networking.
- Interactive Marketing: Engaging customers in real-time advertisements or promotions based on gender recognition in physical or virtual environments.
- Facial Recognition Systems: Improving accuracy in identifying and categorizing individuals in security and access control applications.
- Autonomous Vehicles: Enhancing passenger interaction systems by predicting gender for more personalized experiences.
- Gaming: Adapting character designs or narratives based on the perceived gender of players through their avatars or images.


**Final predictions**

<img width="153" alt="image" src="https://github.com/user-attachments/assets/71ab8c41-aecd-4961-9a51-33c6085df7b9" />

<img width="145" alt="image" src="https://github.com/user-attachments/assets/b1dfe9a2-9498-429d-93bf-16ccd5333685" />

<img width="136" alt="image" src="https://github.com/user-attachments/assets/d5f20cab-7ea1-41e3-973e-433a00afd7cf" />


<img width="213" alt="image" src="https://github.com/user-attachments/assets/20b8b259-7f00-4809-b2c2-d9e3c48449c4" />


