# Covid-Police
This Project can be used in any Organization or Public place to allow or not allow people Entering the area on the basis of weather they are wearing mask or not

<h1> REAL TIME FACEMASK DETECTION </h1>
  

  ![image](https://user-images.githubusercontent.com/67271184/119336928-dd1c9700-bcab-11eb-83cb-60177664613d.png)
  
  
<font size=14> 
Masks are a key measure to suppress transmission and save lives.
Masks should be used as part of a comprehensive ‘Do it all!’ approach including physical distancing, avoiding crowded, closed, and close-contact settings, good ventilation, cleaning hands, covering sneezes and coughs, and more.
Depending on the type, masks can be used for either protection of healthy persons or to prevent onward transmission.

 ![image](https://user-images.githubusercontent.com/67271184/119337055-00dfdd00-bcac-11eb-8734-68b3d724fc93.png)


And to make sure that people wear masks whenever they went out of their homes.  
All people should be aware of wearing marks in public, And someone is not wearing the mask the person needs to be told to wear the mask and should not be allowed in public So that we can tackle this pandemic situation as soon as possible.

Here is my Project that can detect whether the person is wearing a mask or not within a fraction of a second in Real-time.

I have used MobilenetV2 which is faster than CNN to make the base model predict whether the person is wearing a mask or not. I am using a method called readNet which is under cv2.dnn for detecting the faces.

The model is made with a Learning rate of 0.0001 and It is trained with 20 EPOCHSI to have used the Data set from Kaggle and used 20% of Image as testing data. Getting Maximum accuracy of around 99%.



Here is The Accuracy Matrix Graph.
  
  
  ![image](https://user-images.githubusercontent.com/67271184/119337077-09d0ae80-bcac-11eb-81a6-dcac655e781f.png)

  
 HERE IS THE WORKING OF MY MODEL.
1)	When I am not wearing a mask the accuracy with which it detects is 100%

 
  ![image](https://user-images.githubusercontent.com/67271184/119337105-11905300-bcac-11eb-8628-266a5ebf60cf.png)

  
  
Also, work with multiple people.
 
  
  
  ![image](https://user-images.githubusercontent.com/67271184/119337123-16ed9d80-bcac-11eb-96a7-32a0b13c5cd6.png)


Above I am getting an accuracy of 100% for not wearing a mask and acc of 99% for the person wearing the mask.

2)	When I am wearing a mask the accuracy is 99.96%

 

  </font>
  
