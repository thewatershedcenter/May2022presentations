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
## Site
<!-- _color: green -->
![bg right:56%](img/Region.png)


---
## Tree Canopy
<!-- _color: green -->
![bg right:56%](img/sale_2.png)

- CHM
- TTOPS
- Crowns


---
### Tree Canopy - CHM
<!-- _color: green -->
![bg right:56%](img/CHMonSLP2.png)


- Shown here over slope

---

### Tree Canopy - CHM
<!-- _color: green -->
![bg right:56%](img/CHMonSLP.png)

- Same image
- Larger scale


---
#### Tree Canopy - Normalized Height
<!-- _color: green -->
![bg right:56%](img/Norm1.png)


---
#### Tree Canopy - ZQ95
<!-- _color: green -->
![bg right:56%](img/ZQ95.png)


---
#### Tree Canopy - other ZQ95 
<!-- _color: green -->
![bg right:56%](img/2_5dZQ95.png)


---
## Topography
<!-- _color: green -->
![bg right:56%](img/sale_2.png)

- Slope
- Shaded relief
- Openness
- Red Relief
- High Pass Filter
- Geomorphons


---
### Topography - Slope
<!-- _color: green -->
![bg right:56%](img/slp_05.png)

- Slope of DEM


---
### Topography - Shaded relief
<!-- _color: green -->
![bg right:56%](img/shd_05.png)

- A Classic visualization

---
### Topography - Openness
<!-- _color: green -->
![bg right:56%](img/openess_15_05.png)

- Integration of relative horizontal elevation in 16 directions within 15 pixel search window on DEM
- i.e., Is there stuff around this pixel?


---
### Topography - Red Relief
<!-- _color: green -->
![bg right:56%](img/HIS_slp_op_RRIM.png)

- Nice for visualization
- Based on slope and openness


---
#### Topography - High Pass Filter
<!-- _color: green -->
![bg right:56%](img/hp_15_05.png)

- Sharpens local features
- Here with 7.5m focal mean and 0.5 m pixels


---
#### Topography - High Pass FIlter
<!-- _color: green -->
![bg right:56%](img/hp_15_05_outliers.png)

- Sharpens local features
- Here with 7.5m focal mean and 0.5 m pixels...
- leaving out vertical changes < |0.2 m|


---
#### Topography - Another Compound visualization
<!-- _color: green -->
![bg right:56%](img/rgb_open_slp_hp.png)

- Nice visualization based on openness, slope and high pass filter


---
### Topography - Geomorphons
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

- Here showing high frequency spatial data 
- i.e. small features


---
### Topography - Geomorphons
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

- Here showing intermediate frequency spatial data
- i.e., medium sized features



