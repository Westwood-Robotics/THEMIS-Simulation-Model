# THEMIS Models for Simulation.

TH02-A7 is the newest and only model of THEMIS that is beeing mass produced. TH02-A7 is equiped with 7-DoF arms and Westwood Robotics' open source 7-DoF three-finger end-effector [EN02](https://github.com/Westwood-Robotics/EN02-OP). Please note that all other models except for TH02-A7 has been discountinued as of September 25, 2025. 

## Alternative Meshes
### Models
We have included two versions of model mesh files: detailed and simplified, each with different levels of mesh qualities: FHD, HD and SD:<br />
| Model | FHD | HD | SD |
| :--: | --| --| --|
|detailed<br /><img src="./pic/detailed.png" alt="drawing" width="200"/>| High quality mesh<br />Detailed models <br /><br />Model size: 340 MB | Moderate quality mesh<br />Detailed models <br /><br />Model size: 36.7 MB | Low quality mesh<br />Detailed models <br /><br />Model size: 20.2 MB |
|simplified<br /><img src="./pic/simplified.png" alt="drawing" width="200"/>| High quality mesh<br />Simplied leg and body models <br /><br />Model size: 18 MB | Moderate quality mesh<br />Simplied leg and body models <br /><br />Model size: 5.57 MB |



You may use the detailed models for better visual effects, while use the simplied models for lower graphic load on your system, or for simplified collision handling. 

### How to use
All models are located in /alternative_meshes. Copy all files of the mesh model you would like to use and replace the original files in /meshes.<br />
The default files in /meshes are the FD version of the simplified model.

## Future Updates:
1. Support for IsaacLab and Mujoco
2. Integrate detailed model of EN02
