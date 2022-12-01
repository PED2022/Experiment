## Introduction

Due to the paper space limitation,  we upload the detail of all the configurations and results of the experiments on this website. The experiments show our method can handle such complex cases efficiently with satisfactory success rates.

## Experiment

### Settings
We evaluate our PED method, both the global path-encoding-based strategy, $PED_G$, and decomposed path-encoding-based strategy, $PED_D$, on various compositional hybrid systems, all involving discontinuous behavior that cannot be solved by gradient-based methods. Our approach is implemented in Java and all the experiments are conducted on the same PC (Intel Core i7 2.30GHz, 32GB RAM, Windows 10).

Our approach is evaluated on three different systems, the robotic arm systems(marked as Arm), quadcopter drone systems (marked as Drone), and three different vehicle systems, with respect to different scenarios of the straight road (Veh-a), crossroad (Veh-b), and T-junction (Veh-c). 

### File description
In folder ```models```, we have 30 files and can be divided into two categories, ```xml``` files and ```cfg``` files.  ```xml``` files describe the automata of systems, and ```cfg``` files detail the following infomation:
- system: the name of system
- initially: the initial parameters value or range
- target_x: the target position in $X$ axis
- target_y: the target position in $Y$ axis
- target_z (optional): the target position in $Z$ axis
- obj_function: the objective function of the component

For example, ```Drone.xml``` gives the automaton of a quadcopter drone system and ```Drone-2.cfg``` gives the information of the second component in drone system.

For each scenario, we set the number of components in the system as $1$, $2$, $3$ and $5$ respectively. For example, Arm-2 stands for the robotic arm system with first two components, ```Arm-1.cfg``` and ```Arm-2.cfg``` , while Drone-5 stands for the system with all five drones.

### Result

The experimental result is shown in [result.pdf](https://github.com/PED2022/Experiment/blob/main/result.pdf)。

