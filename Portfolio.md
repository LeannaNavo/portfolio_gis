---
layout: default
title: Portfolio
description: Images and descriptions of previous projects
---

# Projects I've Completed on ArcGIS Pro

***

## Habitat Suitability Analysis for Puma concolor coryi

### Research Question: 

Where are critical areas of protection, restoration, expansion, or reintroduction for Florida Panthers?

#### Reclassification Table

<table class="suitability-table">
  <thead>
    <tr>
      <th>Factors</th>
      <th>5<br>Highly Suitable</th>
      <th>4<br>Suitable</th>
      <th>3<br>Moderately Suitable</th>
      <th>2<br>Marginally Suitable</th>
      <th>1<br>Not Suitable</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Land Cover</td>
      <td>Natural Forests</td>
      <td>Wetlands</td>
      <td>Emergent Wetlands</td>
      <td>Agriculture</td>
      <td>Urban / Developed</td>
    </tr>
    <tr>
      <td>VCI</td>
      <td>&gt; 0.85</td>
      <td>0.70–0.85</td>
      <td>0.5–0.7</td>
      <td>0.35–0.50</td>
      <td>&lt; 0.35</td>
    </tr>
    <tr>
      <td>Distance to Roadways (meters)</td>
      <td>&gt; 5,000</td>
      <td>2,500–5,000</td>
      <td>1,000–2,500</td>
      <td>500–1,000</td>
      <td>&lt; 500</td>
    </tr>
    <tr>
      <td>Storm Surge</td>
      <td>No Flooding / Cat 5</td>
      <td>Cat 4</td>
      <td>Cat 3</td>
      <td>Cat 2</td>
      <td>Cat 1</td>
    </tr>
  </tbody>
</table>

#### Weights

1. Land Cover- 35%
1. Distance to Roadways- 30%
1. Vegetation Condition- 20%
1. Storm Surge Risk- 15%

### Maps

![Transformed Land](/assets/images/transformed_land.png)

![Transformed Road](/assets/images/transformed_road.png)

![Transformed Storm](/assets/images/transformed_storm.png)

![Transformed Vegetation](/assets/images/transformed_vegetation.png)

![Suitability Model](/assets/images/suitability_model.png)

#### Tools Used
* Euclidean Distance
* Clip Raster
* Reclassify Raster
* Suitability Modeler
* Raster Calculator
* Polygon to Raster Calculator 


Data Sources:

Florida Department of Transportation

USDA Farm Services Agency

National Land Cover Database

NOAA Hurricane Center

 

***

## Threatened Coral Reefs in the Florida Keys 

### Research Question:

How have rising global sea surface temperatures in 2016, 2018, 2020, 2022, and 2024 been associated with threats to coral reef health?

### Maps

<figure>
  <img src="/assets/images/coralthreatened.gif"
       alt="Coral Threatened by High SST">
  <figcaption>Note: Unnaturally straight lines are due to data limitations, SST raster has spatial resolution of 0.25°</figcaption>
</figure>

#### Tools Used

* Eliminate Polygon Part Tool
* Select by Attributes
* Clip
* Polygon to Raster
* Make Multidimensional Raster Layer
* Aggregate Multidimensional Raster
* Reclassify
* Resample
* Raster Calculator

Data Sources:

NOAA

Florida Fish and Wildlife Conservation Commission

*** 

## Air-Polluting Facilities and Respiratory Health in Florida 

### Research Question: 

What is the association between incinerator locations and rates of asthma in Florida?

### Maps

![Asthma rates map](/assets/images/asthmarates.jpg)

![Asthma hotspots map](/assets/images/asthmahotspots.jpg)

![Air polluting facil map](/assets/images/air_polluting_rates.png)

![Air polluting facil hot spots map](/assets/images/air_polluting_hotspots.png)

<figure>
  <img src="/assets/images/asthmaline.png"
       alt="Association between Asthma Rates and Number of Incinerators in Florida Counties">
  <figcaption>Association between Asthma Rates and Number of Incinerators in Florida Counties</figcaption>
</figure>

#### Tools Used 
* XY to Point tool
* Spatial Join
* Hotspot Analysis 

Data Sources:

epa.gov

flhealthcharts.gov

Geodata.dep.state.fl.us 

Energyjustice.net

*** 
[Home](./)
