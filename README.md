# AR Knick Knack

[![react][react]]

## Project Overview
This project is an augmented reality knick knack built using Unity and the Vuforia AR framework. The application tracks a cube using a webcam and attaches a virtual scene to the cube in real time.

The knick knack represents **Hollywood**, showing elements such as the Hollywood sign, a palm tree, a street scene, and a car to represent the environment and atmosphere of the location.

The project demonstrates how physical objects can be used as anchors for digital content in augmented reality applications.

---

## Design

### AR Tracking
The application uses **Vuforia cube target tracking**. When the webcam detects the cube marker, the AR scene appears attached to the cube surface.

This allows the user to rotate or move the cube and see the scene from different perspectives.

### Scene Elements
The scene contains several models placed on top of the cube base.

**External models used**
- Hollywood sign
- Palm tree
- Car model

**Custom models created**
- Building
- Street light

These models together create a small environment that represents the Hollywood area.

### Lighting
A directional light was added to illuminate the models and improve visibility. Lighting helps give depth to the scene and prevents models from appearing flat.

### Sound
Ambient sound was added using Unity's audio system. The sound plays while the AR scene is visible and helps make the scene feel more immersive.

---

## Implementation

### Tools Used
- Unity
- Vuforia Engine
- Blender
- Visual Studio Code
- 3D asset libraries

### Development Process
1. Create a Unity project and enable Vuforia support.
2. Import cube target assets and configure tracking.
3. Import 3D models and textures.
4. Position models on the cube to create the scene.
5. Add lighting and ambient audio.
6. Test the scene using the webcam to verify tracking stability.

---

## Challenges
One challenge during development was ensuring the cube was detected reliably by the webcam. Lighting conditions and glare could sometimes affect tracking accuracy.

Another challenge involved correctly scaling and positioning imported models so they appeared natural within the scene.

---

## Future Improvements
Possible improvements include:

- Adding weather and time information to the cube sides
- Supporting multiple AR knick knacks simultaneously
- Adding interactive elements when the cube is rotated or flipped
- Improving model detail and scene complexity

---

## Demo

---

## Credits

The following 3D assets were used in this project. Full credit goes to their original creators.

**Hollywood Sign Model**  
Creator: matousekfoto
Source: https://sketchfab.com/3d-models/hollywood-2abad7ece47b433696da30063f35dc75

**Palm Tree Model**  
Creator: lucq22
Source: https://sketchfab.com/3d-models/low-poly-palm-tree-10365d785677428291aecc4464bf0f2d

**Car Model**  
Creator: Vladyslav Holhanov 
Source: https://sketchfab.com/3d-models/free-low-poly-car-38d83155e7724a14b300e156b134a1bb

All assets are used for educational purposes as part of a university AR project.

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[react]: https://cdn.discordapp.com/attachments/880274195093811313/1481861561436864653/image.png?ex=69b4da9f&is=69b3891f&hm=b49c83dde0a11462177655ceb0c32d963d3a390c32a6c287d1985ec25a1e0e07&
