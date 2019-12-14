Please open the html file by Firefox to see the texture.

DESCRIPTION:
This project draws a scene of modified solar system with binary suns and other eight planets by three.js. The two suns revolve around each other approximately 20 times per earth year. We also add a second, geostationary moon (the red one) to the Earth. To make the planets more clearly, we scale the volume by about 5 times.To simplify the scenario, we simulate planets’ orbits by cycle and omit some details like the satellites of other planets.

The Earth and its moons have a 40 degree tilt towards minus x axis. We implement this tilt by first rotate the earth around z axis by 40 degrees then apply another rotation an increment degree around axis (-sin(40),cos(40),0) by using technique of quaternion.

CONTROL CAMERA:
Left clicking to zoom in
Right clicking to zoom out
Move the mouse to move camera

TEAMWORK 
Chonghao Ju: Model the planets and Sun, add small stars(usimg particle system) as background, texture the plants and Sun, add camera controller

Jiayuan Wang: Tilt, add geostationary moon, build binary suns, add background texture

Congrong Guan: Add the ring on the Saturn, design the movement of the Planet and the Sun(including the hierarchy rotation of the moon), add material properties of all
