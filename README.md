### Introduction

Due to the paper space limitation,  we upload the detail of all the configurations and results of the experiments on this website. The experiments show our method can handle such complex cases efficiently with satisfactory success rates.

### Experiment

#### Settings

We evaluate our PED method, both the global path-encoding-based ($PED_G$) and decomposed path-encoding-based ($PED_D$) strategy, on various compositional hybrid systems, all involving discontinuous behavior that cannot be solved by gradient-based methods. Our approach is implemented in Java and all the experiments are conducted on the same PC(Intel Core i7 2.30GHz, 32GB RAM, Windows 10).

Our approach is evaluated on three different systems, the robotic arm systems(marked as Arm), quadcopter drone systems (marked as Drone), and three different vehicle systems, with respect to different scenarios of the straight road (Veh-a), crossroad (Veh-b), and T-junction (Veh-c). The description for each system in file ```models``` is ended with ```.xml```.

For each scenario, we set the number of components in the system as $1$,$2$,$3$ and $5$ respectively. For example, Arm-2 stands for the robotic arm system with first two components, ```Arm-1.cfg``` and ```Arm-2.cfg``` , while Drone-5 stands for the system with all five drones.

#### Result

The experimental result is shown in [result]([PED2022/Experiment (github.com)](https://github.com/PED2022/Experiment/blob/main/Experimental result.pdf))。

