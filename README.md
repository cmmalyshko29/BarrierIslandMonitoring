<h1>Determing the Physical and Environmental Impact of Hurricanes on Mid-Atlantic Barrier Islands Using Remote Sensing</h1>

<h2>Description</h2>
This project aimed to quantify and display how barrier islands in the Mid-Atlantic Ocean are affected by hurricanes physically and environmentally. Using Google Earth Engine and ArcGIS Pro, Landsat satellite imagery from four barrier island locations on the east coast of the United States was analyzed to monitor island movement, vegetative changes (NDVI), and island land cover change before and after large hurricane events. 
<br />


<h2>Languages and Softwares Used</h2>

- <b>JavaScript</b> 
- <b>Google Earth Engine</b>
- <b>ArcGIS Pro Desktop</b>

<h2>Google Earth Engine Code Link per Barrier Island ROI</h2>

- [Chincoteague ](https://code.earthengine.google.com/0f71fd7095d7f153c0396f203f230c9f)
- [Great Bay](https://code.earthengine.google.com/9b3f2a6dd8858c48845ae7ccb10d19bd)
- [Pea Island](https://code.earthengine.google.com/7a2787e3e9aaa30298c61bb0f7175e37)
- [Sandy Hook](https://code.earthengine.google.com/77d477652702b674c1a2f6591a4b5090)

<h2>Selected Figures From Final Report </h2>

<ins> <b> Workflow Example: <br/>
- A: Landsat True Color Composite
- B: Random Forest Pixel Based Classification
- C and D: NDVI Change from 2010 to 2013
  
![Image](https://github.com/user-attachments/assets/50c905b6-0cea-431a-8fa8-1fbfb94f1fef)

*This figure includes examples of the steps utilized to acquire the results figures. Panel A shows a true color image created for Assateague Island, VA for March 1, 2016 to April 30, 2016.  Panel B represents a Random Forest Pixel-Based Classification map of the same ROI for March 1, 2018 to April 30, 2018. The yellow pixels represent sand, green represent estuary, and blue represents water (labeled). Panel C and D show a complete NDVI map from 2010 (left) to 2013 (right) calculated based on the isolated terrestrial land feature. The values are displayed on a gradient from -1 to 1, and with a red-white-green palette, red representing -1 and green representing 1.*
<br />

<ins> <b> Barrier Island Shoreline Movement: <br/>
![Image](https://github.com/user-attachments/assets/ab8a325c-9630-411d-80f3-9403f0676629) 

*This figure represents the total barrier island movement observed and feature position from 2010 to 2023/24. The red outline shows the island position during 2010, orange position during 2013, green position during 2016, cyan position during 2018, blue position during 2020 or 2021, and purple position during 2023 or 2024.*

<br />


<ins> <b> Barrier Island Centroid Movement: <br/>
![Image](https://github.com/user-attachments/assets/b0ef535e-fd91-4a24-a3f5-a920452af0b1)

*This figure represents how the centroid (center most point) of each barrier island moves through space and time. The points represent the individual time points and the arrows connecting them show the movement distance and direction by which they drifted.*

<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
