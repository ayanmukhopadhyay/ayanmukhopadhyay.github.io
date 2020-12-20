---
title: "Raptor Join: In-situ Processing of Big Raster + Vector Data"
collection: publications
permalink: /publications/icde21
venue: "37th IEEE International Conference on Data Engineering (ICDE 2021)"
---

[[PDF]](https://ayanmukhopadhyay.github.io/files/icde21.pdf)

## Abstract
There has been a rapid increase in the amount of spatial data due to the advancements in remote sensing and the increasing use of smart devices. This has allowed for greater research opportunities and efforts have been made to develop systems that can process big amounts of data to facilitate this research. Spatial data can be represented using two data models, raster and vector. Raster data refers to satellite imagery while vector data includes GPS data, Tweets, regional boundaries, etc. Traditional systems implement algorithms that work with only one of these data models. However, there exist problems that require combining both forms of data. We propose a formal raster-vector join algorithm, {\em Raptor Join} that can process the combination of raster and vector data. It is modeled as a relational join operator in Spark that can easily be combined with other operators, while also offering the advantage of in-situ processing. This makes it ideal for ad-hoc query processing. We run an extensive experimental evaluation on large scale satellite data with up-to a trillion pixels, and big vector data with up-to hundreds of millions of edges and billions of points, and show that the proposed method can scale to big data with up-to three orders of magnitude performance gain over GeoTrellis and Google Earth Engine.