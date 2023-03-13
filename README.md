# [Obstacle] Data Processing Component

Installed on the Edge server, it computes the raw LiDAR data into ego-localized full-frame point clouds in PLY binary format.

![system](https://user-images.githubusercontent.com/80487132/224794520-227e36ad-7db9-4429-a631-140d74f330aa.png)

## Installation and execution

<details><summary>Installation</summary>

Simply run the script file 
```
./install.sh
```
in the program directory.

</details>
<details><summary>Execution</summary>

Simply run by the command
```
./run.sh
```

</details>
<details><summary>Docker</summary>

You can use a docker image with:

```
cd docker
./build.sh
./run.sh
```

</details>

## Documentation

<details><summary>General</summary>

- The more important parameters could be changed in the ```config``` JSON file.

</details>

## System

Full system repository ( [link](https://github.com/nsviel/Obstacle_detection_system) )
- [ ] Data acquisition module ( [link](https://github.com/nsviel/-Obstacle-Data_acquisition_module) )
- [x] Edge server module
  - [ ] Edge orchestrator component ( [link](https://github.com/nsviel/-Obstacle-Edge_orchestrator_component) )
  - [x] Data processing component
  - [ ] AI component 
- [ ] Control Interface module ( [link](https://github.com/nsviel/-Obstacle-Control_interface_module) )
