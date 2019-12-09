# Automated-Car-Parking-Tracker

## MOBILITY DEVELOPER TECH CAMP : TEAM – 1

**Problem Statement** : A major problem in modern cities and city blocks is the lack of an automation system for parking. Hence we need to find a one stop solution for handling this issue. There are also problems of misalignment of a vehicle in a parking spot, backroad blockage, long queue of cars during rush hours.

**Proposed Solution** :In the various parking lots available we need to use computer vision to detect cars instead of empty spots, putting the collected data through an algorithm and updating the same on a mobile application for the user to use. We could simply set up YOLO and use it to detect vehicles. Calculate data on the server end by using a backend system. Updating the same data through REST API’s on a mobile application.

**Technologies to be used** :  Flutter, Django, YOLO

**Timeline / Modular segmentation : We will first start by setting up a basic Flutter application UI to denote parking spaces, and parking slots inside them. Different colors signifying empty or occupied. Then write the resource classes to access REST API’s and update the application state. Then comes the hard part, setting up YOLO. Once we have that up and running we can simply link a small django API with the same and test the mobile app. Now that is complete in itself but there is always room for improvement and we can use many more features like Google Maps.

**Resources/Links** :

https://medium.com/flutter-community/what-are-the-key-points-to-remember-for-flutter-app-development-5dd9711ebdd5
https://medium.com/shecodeafrica/getting-started-with-django-1-beginner-series-e47a8b20d8b4
https://medium.com/@jonathan_hui/real-time-object-detection-with-yolo-yolov2-28b1b93e2088
https://docs.djangoproject.com/en/3.0/
https://towardsdatascience.com/yolo-you-only-look-once-real-time-object-detection-explained-492dc9230006
https://flutter.dev/docs

