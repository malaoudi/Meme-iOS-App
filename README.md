# MemeCreator-iOS-App
An ios app that allows users to easily create memes and share them with having the option to add more features and being scalable.  
# Overview: 
Developed an iOS application using Swift and Objective-C that allows users to easily create and share memes. Integrated openCV
library allowing users to effortlessly apply photo filters and effects. Incorporated data storage to archive memes. Leveraged caching for recently
accessed memes. Designed RESTful backend server enabling memes to be stored persistently in an online database.
# Execution: 
This project began from taking Udacity's 'UIKit Fundamentals' online course. I retrofitted the app with data persistence, cloud
storage, and photo editing capabilites. I started off the Meme app with a single view application. Since meme's consist of pictures overlayed with
text, I used the UIImage view to contain the pictures, and textboxes for the text. Images can be obtained in two ways: taking a picture using the
onboard camera, or selecting an image from the users library. This was accomplished by calling the UIImagePickerController when the
camera/library button is pressed and passing the selected image to the Meme ViewControler.
In addition, I created a RESTful backend server to store the images and text in an online database. The server stores images using the Base64
image encoder and images are given a unique key using the NSUUID. I decided to bring image editing capabilities to the app by incorporating
openCV, an open source computer vision library. The library is written in Objective-C and C++, while my project is written in Swift. I created a
bridge header file in my project in order to allow the use of both languages. I created an "Edit" button that would take the Image displayed as an
input and output a filtered image. 
# Tools: 
Technologies Utilized in the application: Objective C, GIT, Swift, UIKit


# Demonstration: 
https://youtu.be/pgamJ66-vZg

# Documentation 

# Install 

The application offers the following features: <br>

Creating an application allowing to personalize and share Memes. <br/>
Adding personalized text. <br/>
Sharing Memes via SMS, e-mail, social media, etc. <br/>
View saved Memes as a list. <br/>
Delete saved Memes in your list. <br/>

Testing The App: <br/>

Download the project to your computer from this project page. <br/>
Once the project is downloaded, open the .xcodeproj file from the folder. <br/>
Run the project either using the iPhone simulator or your device. I recommend running the project on the latest iPhone device. It should be compiled with the latest version of Xcode. <br/>
If you choose to download it on your device, please plug in your device to your computer and make the device target your device model. Then click 'run'. <br/>

Closing: <br/>
In conclusion, I have learned a lot by working on this project. I became aquianted with UIKit and am able to successfully create applications using different scenes, functions and assets in order to create an exciting application.
