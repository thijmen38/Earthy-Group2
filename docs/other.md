## 0_Acknowledgements  
tell we got inspired by previous years and helped us like pirouz and shervin.

---
## 0_Literature

**References**

Türkmen, İ., Ekinci, E., Kantarcı, F., & Sarıcı, T. (2020). The mechanical and physical properties of unfired earth bricks stabilized with gypsum and Elazığ Ferrochrome slag. Retrieved 2 November 2020


---

## 1_Scripts

To produce the design as shown on the [design page](design.md) a lot of scripts were used.
Below we listed the most important scrips with a download link for anybody intereseted to study them.

**site selector**

**Bubble diagram maker**

**Gradient descent**

**Relaxer**  
To study our tessellations and there final form a grasshopper script was made that did the relaxing.
It takes in anchor curves and the tesselation as input. After meshing the tesselation it relaxes it.
The script is illustrated in the gif below and can be [downloaded here.](rev\scripts\tesselation_relaxer.gh).

![relaxing process](rev\forming\relaxer.gif)  
*Fig: showing the process of relaxing the roof using grasshopper*

**Structural calculation**

**Rib maker**  
This script was designed to make all the ribbed roofs for the project.
The only input it needs are the brick sizes and the curves over which it needs to place these bricks.
the gif below illustrates how the ribs are generated. The script can be [downloaded here.](rev\scripts\Rib_brickgen.gh).


![rib maker](rev\constructability\Rib-gif.gif)  
*Fig: Showing the process followed by the rib maker gif*

**Adobe 2.0 dome maker**
