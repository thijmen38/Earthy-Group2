## 0_Introduction *Beza*
general text about the project and brief of the project.(also talk about the site)
leading to the problem statment

### About Zaatari
text text site study

### Problem statement
talk about the problems we hope to tackle

### Design goal
xxxxxx intervention


### Design vision
ssssss Ease construction due to unskilled whatever else

### Overall flow chart

---
## 1_Configuration
introduction explaining the configuring phase and its goals.(from course brief)*Anagha*

### Site selection *Beza*
*flowchart*
*beza's gif*
explaining how we came to the selection of this site. Explain with apt conclusion why district 9 was chosen, link it to the site study.  
*Twinkle*
Explain the site surroundings and site orientation, add a google map/diagram - wind and sun path (brief study) 

### Program of requirements *Thijmen*  
Show table of requirements and provide link to downloadable document.
Explain why these programs fit our design goal.
and how were the numbers and parameters decided.

### Connectivity of spaces

**Rel chart**  
*Thijmen*  
What is a rel chart and how was it made, why are these rooms connected to the other room.
input for syntactic tool

**Bubble diagram**
*Thijmen*
syntactictool (reference)
explaining what it does, how we used it(including python part) and what was the outcome
how did we translate this into a manual diagram - parameters used and refer to the appendix for initial study of buble diagrams.

**Hierarchy of spaces**  
*Thijmen*  
<ins>*Depth chart*</ins>  
show depth chart explaining the logic behind it

<ins>*Metro link diagram*</ins>  
showing and explaining

### Summary or conclusion
*First do the rest*
---
## 2_Forming
introduction explaining the configuring phase and its goals.(from course brief)*Anagha*

### Spacial configuration

**Gradient descent optimization**  
*Anagha*  
Video/gif, excel, flowchart of the script and explanation
in 2D

**3D Study**  
*Shriya*
showing gif and explaining 3D study, why were certain spaces given a second floor important to mention here. Built vs unbuilt etc, first level of connectivity and vertical connections. 


### Configured design

**Modular grid**    
*Twinkle*  
talk about the grid 1.2m we first choose and how it transformed into the tartan grid explain why initially bands of 600mm was assumed- based on last years reference and our room sizes. 

**Floor plans**  
show (general) floor plans and there plan evolution (study on the courtyards and therfore the configuration that was informed)
*Siteplan*  
showing the site plan of the building and its surrounding, and the orientation (start with the first one and show how it evolved)  

**Wall modules**  
explain how the walls have been designed according to the tartan grid.
including the change of wall tickness (why we choose for 600mm bands in the tartan grid)

**roof modules**  
talk about Architectural charactaristics and show the different roof modules in the plan view - 4 types Crossvaults, Square domes, Rectangular domes and Domes with Skylight
talk about how these roofs have been designed using the tarten grid

**Sections**  
show sections and explain the heights etc

**details**

<ins>*Services*</ins>  

<ins>*Ventilation*</ins>  

<ins>*Detailed section*</ins>  

 
### Summary or conclusion

---

## 3_Structuring 
*Shriya*  
Introduction explaining the configuring phase and its goals.(from course brief)*Anagha*

### Tesellations
Flowchart showing the tesselation process 

**Exploration**

<ins>*Manual*</ins>   
*Shriya and Beza*  
Explain the different types of tesselations (dome/cross vault Jpegs) and meshing logic/strategy

<ins>*Computational*</ins>  
*Thijmen*  
Explain the mesh maker 4000, flowchart and the dynamic relaxation strengths and anchors, etc per module - total number of modules 7 + 1 (3- square domes, 3 rectangular domes,1 cross-vault, +1 is dome with skylight (Adobe 2.0))  
Mention the challenge with dome with Skylight and why it wasnt possible to relax an opening within the dome.

**Final Tesselation**  
*Shriya and Anagha*  
<ins>*Roof*</ins>   
Show the floor plan with all roof teseelations (evolution) and reason for choosing this particular meshing strategy
Use the colour code as per Twinkle's roof modules 3d 

<ins>*Walls*</ins>  
Though a computational method was used for the roofs, for the walls we opted a manual approach

**Simplification**  
*Shirya*  
Explain the Gif- explain the simplification process.

<ins>*Square domes*</ins>

![Square](img/square.gif)

Explain the gif and mention which modules use the same approach
Include impage of elliptical curve simplification

<ins>*Rectangular domes*</ins>

![Rectangle](img/Rectangle.gif)

Explain the gif and mention which modules use the same approach
Include impage of elliptical curve simplification

<ins>*Cross vaults*</ins>

![Cross-vaults](img/cross-vaults.gif)

Explain the gif and mention which modules use the same approach
Include impage of Catenary arch simplification

**Material Selection**  
Mention the course requirement of the material, and then talk about the analysis/study not being part of the course brief due to the lack of lab access in Covid times, the material was chosen from the last years projects of material study (Reference)  
Material image

Mention Limit states

**Strcutural Analysis**
Flowchart if needed

<ins>*Process*</ins>

How it was done initially, explaining with an example module. Image of the first approach stages

Then talk about the Final approach with another image

<ins>*Module_1*</ins>

*Loadcases:*
Explain the load coonditions considered

*Support conditions*

*Results*

*Verification*

<ins>*Module_2*</ins>

*Loadcases:*
Explain the load coonditions considered

*Support conditions*

*Results*

*Verification*

<ins>*Module_3*</ins>

*Loadcases:*
Explain the load coonditions considered

*Support conditions*

*Results*

*Verification*

<ins>*Module_4*</ins>

*Loadcases:*
Explain the load coonditions considered

*Support conditions*

*Results*

*Verification*

<ins>*Module_5*</ins>

*Loadcases:*
Explain the load coonditions considered

*Support conditions*

*Results*

*Verification*

<ins>*Module_6*</ins>

*Loadcases:*
Explain the load coonditions considered

*Support conditions*

*Results*

*Verification*

<ins>*Module_7*</ins>

*Loadcases:*
Explain the load coonditions considered

*Support conditions*

*Results*

*Verification*

<ins>*Module_8*</ins>

*Loadcases:*
Explain the load coonditions considered

*Support conditions*

*Results*

*Verification*

### Summary or conclusion  

---
## 4_Constructability

Introduction explaining the construction phase and its goals.(from course brief)*Bez*

**Methodology**   

<ins>*relationship between different modules*</ins> 
*Beza*  
Explaining the scalable difference between each module, therfore each curve is double of the other, Mention how they are Different yet similar a the same time. 

<ins>*Rib system approach*</ins>  
*Beza*  
Selection of construction using ribs + infill method

**Interlocking bricks**  

<ins>*system exploration*</ins>   
*Beza and Twinkle*  
The different interlocking systems researched refer to appendix when neccessary to ensure that the information here is not too much. then add teh table ranking the different interlocking systems studied and tehrefore choosing the one we did

<ins>*design process*</ins> 
*Beza*

*Manual study*
*Beza*
Starting from the circular arch to the elliptical arc taht forms the Dome ribs.

*Computational tool development*  
*Thijmen*  
Flowchart of the script
Include the GIF
The adaptation of the tool for various modules

*Experiment*  
*Twinkle and Anagha*  
Add video and talk about teh brick infill making and 3d printing of the blocks

<ins>*Construction instrument*</ins>   
*Twinkle*  
*General concept and deisgn of the tool*  

*Adaptation to different modules* 

**Adobe 2.0** 

<ins>*Design concept*</ins>  
*Twinkle*   
mention fibonacci and the twist in the dome that creates the lamela dome look 

<ins>*Computational tool*</ins>  
*Anagha*  
Script flowchart Include the GIF and explanation. 

<ins>*Construction instrument*</ins>   
*Twinkle*    
*General concept and deisgn of the tool*  

**Brick Library**  
*Twinkle*  
Brick sizes and weights to be justified for constructability -  Brick Library with dimensions weights and moulds - which one is used where (which module)
In a 3D view colour code and nomenclate the bricks used per module

<ins>*construction sequence*</ins>   
*Beza*  
All the lovely Gifs and explanation of the process it selft
Foundation to walls to window/door openings and therefore roof modules

*Square domes*  
Gif.
3d image of the brick colour and nomenclature   

*Rectangular domes*  
Gif.
3d image of the brick colour and nomenclature   

*Cross vaults*  
Gif.
3d image of the brick colour and nomenclature  

*Adobe 2.0*  
Gif.
3d image of the brick colour and nomenclature  

### Summary or conclusion

---

## 5_Conclusion

---
## 6_Reflection

While going through the process of designing an earthy building as is being explained above a lot was learned. Below each group member will reflect on the process and how they have experienced it.

**Anagha Yoganand**

reflection

**Bezawit Z. Bekele**

reflection

**Shriya Balakrishnan**

reflection

**Thijmen Pluimers**

reflection

**Twinkle Nathani**

reflection
