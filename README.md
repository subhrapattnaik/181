# 181




working code

https://snack.expo.dev/@subhra/pro-c181-code-ref


show your face to the camera

check the log












Face FILTER Mobile App
————————————

Face filters are effects which are applied over the face while clicking a selfie

Filters are used for changing the background or frames in the picture.


Filters are computer generated effects which are placed on the real world image.


Since these filters or effects are added on the real life image after clicking by front/back camera, these are called augmented reality filters or AR FILTERS

you much have heard about various apps using face filters these days.

These apps are designed in such a way where use can apply filters on your face and click selfies.

Examples: Snapchat,instagram

its fun to use those filters while taking a selfie.

——————————————

We have to open smart phone camera

we should know how to recognize the face of the person
we should be able to detect facial features like eyes, nose and mouth,head etc to place filters over them.

detecting a face requires a lot of algorithims to work together.

Steps:

1.capturing face images
2.face detection algorithm
3.detecting facial features.
4.matching the face
5.generate the faces id and array of face objects with other data related to faces

we will use expo react native api to get this data
————————————————————

Face Recognition App(FRAPP)

expo init frapp

cd frappe

expo install expo-camera
expo install expo-face-detector
expo install expo-permissions

FaceDetector is a module developed by Expo to help detect faces from the camera.
Once it detects the faces, it gives us a lot of information about them.

https://docs.expo.dev/versions/latest/sdk/facedetector/

We will have two screens in the app:

● One screen will be the camera screen where we will ask the
user to use their camera so we can apply filters to their faces.
This screen will also allow the users to click a selfie with the
filter applied.

● The second screen would be the preview of this image where
we will provide the user with a share button, so they can share
this image at different social media platforms.

----------------------------------------------
We will create a new folder called
screens in our root directory and then
create a file Main.js inside this folder:

SafeAreaView is used to render
content within the safe area
boundaries of a device.

Now we would write the “Main” class
component and import it in the App.js.

——————————————————

The first screen is where we want to
use a camera so that we can apply
filters to their faces.
And this screen will also allow the
users to 



