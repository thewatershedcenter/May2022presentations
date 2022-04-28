---
marp: true
theme: gaia
_class: lead
paginate: true
title: PAGE TITLE HERE
filename: docs/UpperTrinityLidar2022_04_27.md
backgroundColor: #000
---

<!-- _class: invert -->
<!-- _color: #ade396 -->
![bg](img/sale_2.png)


Lidar Forestry Applications in the Upper Trinity Watershed  <!-- fit -->
=====
---

## Topography
<!-- _color: green -->
![bg right:56%](img/sale_2.png)

Yes indeed


---

## Tree Canopy
<!-- _color: green -->
![bg right:56%](img/CHMonSLP2.png)

- CHM
- Shown here over slope

---

## Tree Canopy
<!-- _color: green -->
![bg right:56%](img/CHMonSLP.png)

- CHM
- Shown here over slope
---

## Tree Canopy
<!-- _color: green -->
![bg right:56%](img/sale_2.png)

- CHM
- TTOPS

--- 

## Tree Canopy
<!-- _color: green -->
![bg right:56%](img/sale_2.png)

- CHM
- TTOPS
- Crowns

---
## Slope
<!-- _color: green -->
![bg right:56%](img/HIS_slp_op_RRIM.png)

- Slope!


---
## Openness
<!-- _color: green -->
![bg right:56%](img/openess_15_05.png)

- Integration of relative horizontal elevation in 16 directions within 15 pixel search window on DEM
- i.e., Is there stuff around this pixel?


---
## Red Relief
<!-- _color: green -->
![bg right:56%](img/HIS_slp_op_RRIM.png)

- Nice for visualization
- Based on slope and openness


---
## High Pass Filter
<!-- _color: green -->
![bg right:56%](img/hp_15_05.png)

- Sharpens local features
- Here with 7.5m focal mean and 0.5 m pixels


---
## High Pass FIlter
<!-- _color: green -->
![bg right:56%](img/hp_15_05_outliers.png)

- Sharpens local features
- Here with 7.5m focal mean and 0.5 m pixels...
- leaving out vertical changes < |0.2 m|


---
## Another Compound visualization
<!-- _color: green -->
![bg right:56%](img/rgb_open_slp_hp.png)

- Nice visualization based on openness, slope and high pass filter


---


## Geomorphons
<!-- _color: green -->
<!-- _footer: "![](img/legend.png)" -->

<style>
footer {
    height: 330px;
    margin-bottom: 0 px;
    
}
footer img {

    float: center;
    width: 90%;
 }
</style>

![bg right:56%](img/Geomorphon03_0_0__05.png)

- High frequency spatial data 
- i.e. small features


---
## Geomorphons
<!-- _color: green -->
<!-- _footer: "![](img/geomorphon.png)" -->

<style>
footer {
    height: 330px;
    margin-bottom: 0 px;

}
footer img {

    float: center;
    width: 70%;
 }
</style>

![bg bottom right:56%](img/geomorphon15_03_01__05.png)

- Intermediate frequency spatial data
- i.e., medium sized features


---
## Total Animal Situation (TAS)
<!-- _color: green -->
![bg right:56%](img/shd_05.png)

- Fish
- Unicorn
- shd_05.png


---
## Total Animal Situation (TAS)
<!-- _color: green -->
![bg right:56%](img/slp_05.png)

- Mouse
- slp_05.png
- L. Ron Hubbard

