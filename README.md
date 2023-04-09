# factsnap

Hello! Welcome to FactSnap, a group portfolio project I created during my time at Northcoders Full Stack Programming Bootcamp.

I've put together a brief gif that provides an overview of the project, which you can find below. Further down, I'll explain some key aspects of the project, how it works, and the technologies I used to build it.

![](snapfact-preview.gif)


Introducing SnapFact, an app that allows users to snap a photo of a landmark or upload a photo and receive a short description or fact about it. The app is designed to be both educational and entertaining, providing users with valuable information about the world around them.

FactSnap was developed using React Native and Expo, ensuring compatibility with both iOS and Android platforms. For user authentication, Firebase Authentication was implemented, while Firebase Realtime Storage and Firebase Storage were utilized for handling real-time data and photo storage, respectively.

The app functions by having users take a photo of a landmark, which is then sent to Google Cloud's Landmark API for analysis using their built-in AI image recognition system. Once the landmark is identified, the relevant data is forwarded to Wikipedia to retrieve additional information about the landmark. Finally, this information is displayed to the user and stored in their personal photo library.
