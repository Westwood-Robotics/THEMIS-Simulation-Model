# THEMIS Models for Simulation.

TH02-A7 is the newest and only model of THEMIS that is beeing mass produced. TH02-A7 is equiped with 7-DoF arms and Westwood Robotics' open source 7-DoF three-finger end-effector [EN02](https://github.com/Westwood-Robotics/EN02-OP). Please note that all other models except for TH02-A7 has been discountinued as of September 25, 2025. 

## Alternative Meshes
### Models
We have included two versions of model mesh files: detailed and simplified, each with two levels of mesh qualities: HD and SD:<br />
| Model | HD | SD |
| -- | --| --|
| detailed  | High quality mesh with detailed models <br />Model size: 340 MB | Low quality mesh with detailed models <br />Model size: 36.7 MB |
| simplified | High quality mesh with simplied leg and body models <br />Model size: 18 MB | High quality mesh with simplied leg and body models <br />Model size: 5.57 MB |

You may use the detailed models for better visual effects, while use the simplied models for lower graphic load on your system, or for simplified collision handling. 

### How to use
All models are located in /alternative_meshes. Copy all files of the mesh model you would like to use and replace the original files in /meshes.<br />
The default files in /meshes are the SD version of the simplified model.

## Future Updates:
1. Support for IsaacLab and Mujoco
2. Integrate detailed model of EN02
