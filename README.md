
# Micro Challenge 2

## MUSEUM OF INNER PORTRAITS

[![Museum of inner portraits](/images/img08.png)](https://vimeo.com/692296732 "Museum of inner portraits")

### Team members: 
- [Andrea Arranz](https://andrea-arranz.github.io/website/)
- [Nikita](https://nikita-bandarevich.github.io/web_portfolio/)

### How is it linked to the memebers interests?

![plan](/images/img04.png)

In this challenge, we have teamed up based on directions we both wanted to explore such as gestures, language and non-verbal communication and the graphic representation of these. Nikita focused more on the emotional and descriptive part of the project while Andrea studied the different possibilities that LIDAR offered to represent movements.

### Initial Idea:

We start the week with various ideas;
- Generate a graphic language through symbols and gestures that would work on a graphic level. 
- Representing movements of the human body through the use of kinect and thus generating different images or online body languages and visualize them in VR.

![ideas](/images/img05.png)

### Planing

![planning](/images/img06.png)

### Purpose:

Our purpose during this microchallenge is to generate an immersive installation with which people can see different situations or emotions represented through 3D motion scanning. In this way we give more weight to language and non-verbal communication, often forgotten in online communication and generate a dialogue between the body and virtuality. 

--> --> --> --> --> --> --> --> -->

### System diagram:

![Diagram](/images/img07.png)

At first, we started using the kinect sensor to capture these movements, however, after many attempts we gave up on the option of using the LIDAR sensor, which is much more responsive to Apple's operating system. The links to the different libraries we have been investigating to connect the kinect v2 to a macbook are added in this repository, although with the warning that there are steps that must be solved from the terminal to be able to connect them. On a practical level we do not recommend linking kinect to macOS.

![kinect trials](/images/gif01.gif)
![](https://github.com/andrea-arranz/FabLab/blob/main/images/img03.png)


Kinect V2 MacOS and Processing

Library for Kinect V2 in MacOS https://github.com/OpenKinect/libfreenect2
(There's a miss step in openni2)

Later, we started using Apple's 3D scan app in its Point Cloud function and tried to perform the first post-processing of the scans. To do that, we search for a plugin for pointcloud visualization. 

Blender plug in visualizer: https://github.com/uhlik/bpy

![](https://github.com/andrea-arranz/FabLab/blob/main/images/img01.png)

Pointcloud example on Blender

![](https://github.com/andrea-arranz/FabLab/blob/main/images/img02.png)

Color adjustment in space 3D plugin

![color](/images/gif03.gif)

Camera adjust to create movement inside scenes.

![camera](/images/gif02.gif)


### Next Steps: 
We want to generate this experience within virtual reality so that it allows us to generate the immersivity that we wanted to achieve at the beginning of the challenge. To do this, we will use Unity as a bridge program that allows us to generate videos that can be viewed in VR.







