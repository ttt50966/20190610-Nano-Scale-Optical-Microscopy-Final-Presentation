---
title       : "Nanoscale Optical Microscopy and Spectroscopy"
subtitle    : "Rapid and Reliable Thickness Identification of Two-Dimensional Nanosheets Using Optical Microscopy"
author      : Kuan-Chia Chiu (D06222003)
job         : "Physics Department @ NTU"
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, quiz, bootstrap] # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
github      :
  user: "ttt50966"
  repo: "20190610-Nano-Scale-Optical-Microscopy-Final-Presentation"
---


<!-- Center image on slide -->
<script src="http://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.7.min.js"></script>
<script type='text/javascript'>
$(function() {
    $("p:has(img)").addClass('centered');
});
</script>


## Outline

1. <font size=6>**Introduction**</font>
  - Transition Metal Dichalcogenides (**TMDCs**)  
  - Determinate the number of layers of TMDCs
2. <font size=6>**Method**</font>
  - the Optical Identification Method
3. <font size=6>**Experiment**</font>
  - Optical Identification of Graphene Nanosheets
  - Optical Identification of MoS$_{2}$ Nanosheets
4. <font size=6>**Conclusion**</font>
5. <font size=6>**Q&A**</font>


--- .class #id

## Introduction
### **Transition Metal Dichalcogenides (TMDCs)** 
TMDCs are thin semiconductors of the type MX$_{2}$, with **M** as a transition metal atom (Mo, W, etc.) and **X** as a **chalcogen** atom (S, Se, or Te).  

### **Monolayers of TMDCs**
- Having Direct band gap can be used in electronics as transistors and in optics as emitter or detector
  - MoS$_{2}$, WS$_{2}$, MoSe$_{2}$, WSe$_{2}$, MoTe$_{2}$
- TMD monolayers has no inversion center, which allow to access a new dgree of freedom of charge carrier, namely the **k-valley** index
  - **+K** valley and **-K** valley
- The strong spin-orbit coupling in TMD monolayers

###### [Transition metal dichalcogenide monolayers on Wikipedia](https://en.wikipedia.org/w/index.php?title=Transition_metal_dichalcogenide_monolayers&oldid=891064104) (last visited June 3, 2019).


--- .class #id &twocol w1:40% w2:60%


## Introduction
### **How to determinate the number of layers of TMDCs?** 
*** =left
 
- Atomic Force Microscope (AFM)
- Photoluminescence (PL)
- Raman spectroscopy
- Optical Microscopy (**this paper**)

<img src="./assets/img/Ref_1_fig_3_a.png" width="400">

##### Wang, Q. H.; Kalantar-Zadeh, K.; Kis, A.; Coleman, J. N.;Strano, M. S. *Nat. Nanotechnol* **7**, 699-712 (2012).


*** =right
<br></br>
<br></br>
<img src="./assets/img/Ref_1_fig_5_b.png" width="300">






---

## Method
### Description of the Optical Identification Method

1. C$_{D}$ = C - C$_{S}$
2. C<font color=red>$_{DR}$</font> = C<font color=red>$_{R}$</font> - C<font color=red>$_{SR}$</font>
3. C<font color=green>$_{GR}$</font> = C<font color=green>$_{G}$</font> - C<font color=green>$_{SG}$</font>
4. C<font color=blue>$_{DB}$</font> = C<font color=blue>$_{B}$</font> - C<font color=blue>$_{SB}$</font>

The optical contrast of a nanosheet (defined as C) and substrate (defined as C$_{S}$) was directly measured from its color optical image by using a free software (`ImageJ`)


###### H. Li, J. Wu, X. Huang, G. Lu, J. Yang, X. Lu, Q. Xiong, and H. Zhang, *ACS Nano* **7**, 10344 (2013).

--- &twocol w1:40% w2:60%

## Experiment

*** =left
<img src="./assets/img/fig_1.png" width="350">

*** =right

<br></br><br></br>
### The contrast values with different poistions
| Layers | Contrast |
| ------ | -------- |
| 0 substracte | 120.4 |
| 6 layers | 118.6 |
| 8 layers | 162.3 |

###### H. Li, J. Wu, X. Huang, G. Lu, J. Yang, X. Lu, Q. Xiong, and H. Zhang, *ACS Nano* **7**, 10344 (2013).


---

### Optical Identification of Graphene Nanosheets
<img src="./assets/img/fig_2.png" width="800">

###### H. Li, J. Wu, X. Huang, G. Lu, J. Yang, X. Lu, Q. Xiong, and H. Zhang, *ACS Nano* **7**, 10344 (2013).

---

### Optical Identification of MoS2 Nanosheets
<img src="./assets/img/fig_3.png" width="800">

###### H. Li, J. Wu, X. Huang, G. Lu, J. Yang, X. Lu, Q. Xiong, and H. Zhang, *ACS Nano* **7**, 10344 (2013).

--- &twocol w1:50% w2:50%

*** =left

<img src="./assets/img/fig_4_1.png" width="330">
<img src="./assets/img/fig_4_2.png" width="330">
<img src="./assets/img/fig_4_3.png" width="330">
<img src="./assets/img/fig_4_4.png" width="330">

*** =right
<br></br> 
<br></br> 

<img src="./assets/img/fig_4_5.png" width="330">
<img src="./assets/img/fig_4_6.png" width="330">

###### H. Li, J. Wu, X. Huang, G. Lu, J. Yang, X. Lu, Q. Xiong, and H. Zhang, *ACS Nano* **7**, 10344 (2013).

---

<img src="./assets/img/fig_5.png" width="800">

###### H. Li, J. Wu, X. Huang, G. Lu, J. Yang, X. Lu, Q. Xiong, and H. Zhang, *ACS Nano* **7**, 10344 (2013).


---

## Conclusion
- a universal optical method has been developed for simple, rapid, and reliable identification of 1L-15L 2D nanosheets
  - including graphene, MoS$_{2}$, WSe$_{2}$, and TaS$_{2}$, on 90 and 300 nm SiO$_{2}$/Si.
- By processing the gray scale and three <font color=red>R</font><font color=green>G</font><font color=blue>B</font> channel in `ImageJ`, they could clear found different contrast transition in three channels.
- Based on this method, it is very easy and quick to use PDMS to transfer single-layer TMDCs to the desired substracte and position.

---

<br></br>
<br></br>
<br></br>
<br></br>
<div style='text-align: center;'>
    <font size = 20 color=#535e43> Thank you for your attention!</font>
</div>


---

<br></br>
<img src="./assets/img/Ref_1_table_1.png" width="1000">
##### Wang, Q. H.; Kalantar-Zadeh, K.; Kis, A.; Coleman, J. N.;Strano, M. S. *Nat. Nanotechnol* **7**, 699-712 (2012).

