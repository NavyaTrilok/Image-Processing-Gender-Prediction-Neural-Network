# Image-Processing-Gender-Prediction-Model

I have used Artificial Neural Network(ANN) using deep learning techniquest to predict the gender of the person in the image.

I have used OpenCV library for image processing:
To normalize the imput date
1) Detected and sliced the face of the person in the image
2) Converted the images to grayscale
3) Reshaped the images to 48 x 48 input size

Model is trained on 5 hidden layers with 1,102,902 Trainable parameters

This repo consists of 2 .ipynb files -
- For Training and evaluation of the model and saved the model
- For image processing of test image and predicting the gender of the person in image

I have highlighed the cases where model is going wrong in predicting the images of the person. These are all the cases where the person in the image is kid. For kids even we as humans cannot define the gender of the kid by looking at face.

Gender prediction models can be utilized in various real-time applications, including:
- Marketing and Advertising: Tailoring ads based on predicted gender to enhance engagement and conversion rates.
- Social Media Platforms: Enhancing user experience by personalizing content and recommendations based on gender insights.
- E-commerce: Customizing product recommendations and marketing strategies to target different gender demographics effectively.
- Customer Support: Adapting communication styles and responses in chatbots based on the predicted gender of users.
- Content Moderation: Filtering or categorizing user-generated content according to gender-related norms and sensitivities.
- Healthcare: Analyzing health-related trends and behaviors among different genders for better service delivery.
- Gaming: Personalizing in-game experiences or matchmaking based on user demographics, including gender.
- Event Planning: Customizing experiences or marketing for events based on the predicted gender of attendees.
