The AI-Dermatologist

The AI-Dermatologist is the title of the Capstone project that I worked on along with my team as part of Post Graduate Program in Data Science in Praxis Business School, Bangalore.

Idea:
The idea behind this project is to create an application which would take the images of hair and skin issues and identifies the disease/ issue and give the medical prescription. We worked with a real Dermatologist who prescribed the medicines which was then fed into our model.

Data:
We used the images of 3 hair and 4 skin issues/disease along with images of healthy skin and hair/scalp to train our models. As getting medical images were difficult and very expensive, we had to depend on limited images from google, we have used augmentation technique to increase the number of images to train, validate and test our models. I have added the code that I used to augment the images in this repository.

Model:
We tried using various models like CNN, VGG16 and Densenet with various parameters and finally found Densenet to give good results in comparison to other models. So, our final model used for this project is Densenet. We have used 2 Densenet models, one for hair and one for skin. I have uploaded only the codes for hair model in this repository along with the saved model for the same.
![image](https://user-images.githubusercontent.com/99525796/221772953-0ade78ce-e3fc-43aa-9567-9462a8e524bc.png)
