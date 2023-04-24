# ARToolkit
An android application to demonstrate use of ARtoolkit.

ARToolKit is an open-source software library for developing Augmented Reality (AR) applications. It was created by Dr. Hirokazu Kato and his team at the Nara Institute of Science and Technology in Japan. ARToolKit allows developers to incorporate augmented reality into their own applications using computers, image recognition, GPS data, video capture devices, or even simple mobile phones.

ARToolKit works through the use of a camera that captures an image of the user's environment and a programming interface that analyzes and interprets it. It recognizes specific "markers" placed in the physical world or detected in real-time allowing to overlay digital information onto the physical environment on top of specific patterns seen by the camera. The software can then create virtual objects, display them on-screen interactively with real-world objects while keeping track of viewer position via optical tracking method called SLAM (Simultaneous Localization And Mapping). This allows developers to produce enhanced interactive experiences that can merge multimedia content directly with real world environments.

The combination of these technologies enables AR experiences which provide rich media content activated simply by pointing a device’s view toward targeted locations endowed with special patterns – animated paper, product packages, walls – practically anything you can think of!


Here are the general steps to create a Unity app with ARToolKit that shows a 3D image of a flower vase when projected onto a real flower vase:

1. First, you need to install ARToolKit and Unity on your computer.
2. Create a new Unity project and import the ARToolKit for Unity package into your project.
3. Download or create a 3D model of a flower vase that you want to project onto the real-world flower vase.
4. Import the 3D model into your Unity project and place it in front of the camera.
5. Create an ARMarker object in Unity and print out or display the marker on your real-world flower vase. You can generate this marker using ARToolKit's Marker Generator tool or download pre-existing marker images from the internet.
6. Configure your Virtual Camera in Unity so that it is pointed at the location where your real-world flower vase will be seen by the camera, and set up its projection matrix to match that of ARToolKit's projection matrix for calibrating with live video capture devices.
7. Write a script in C# that loads the 3D model into memory when detecting the specified marker from step 5 using custom commands written in blendshape/bitmask generation (if applicable).
8. Attach this script to an empty GameObject or ObjectRibbon element in front of camera through which you want to display virtual content.
9. Build and export your app as an Android/iOS application.
