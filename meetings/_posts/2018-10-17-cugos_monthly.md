---
layout: meeting
title: October 17th 2018, 6pm - Anderson Hall, UW
location: University of Washington
address: UW Anderson Hall, Forest Club room 207
time: 6:00pm
excerpt: October 17 2018 CUGOS Monthly Meeting
lat: 47.651737
lng: -122.307540
category: meetings
notes: It's the room with the elk in it.
---


## Agenda

**[@powersa](https://github.com/powersa)** will discuss efforts to create CUGOS T-Shirts.

**[@christyheaton](https://github.com/christyheaton)** will give a practice run of her North Bay Python talk, [Map it with Python! Intro to GIS and Python mapping modules.](https://2018.northbaypython.org/schedule/presentation/14/) featuring Jupyter Notebooks as a fabulous open source mapping application.

**[@jharpster](https://github.com/jharpster)** will provide a re-cap of [Microsoft OpenMaps](https://github.com/Microsoft/Open-Maps/) team and ongoing work in OpenStreetMap in Australia and the latest on building footprint extractions.

**[@shaybstrong](https://twitter.com/shaybstrong)** Shay Strong, Director of Data Science and Machine Learning at [EagleView](https://www.eagleview.com/), will talk about disaster response using Deep Learning with satellite and aerial imagery.

**[@you](http://cugos.org/people/)** tell us about something cool you are working on

## UW Event Wifi

```
UW NetID:      event0896
Password:      4a5V/6f4H/6o4H
```


# Meeting Notes

## [Christy Heaton](https://github.com/christyheaton) -- North Bay Python Conference Presentation

Christy is giving a talk at the [North Bay Python Conference](https://2018.northbaypython.org/schedule/presentation/14/). This is a preview. 

Christy often gets the question "hasn't everything already been mapped?". Well, people often think of Base Maps when they talk about maps. Base maps need to be updated. Thematic Maps are another category of map with which people are familiar. Thematic maps generally tell a specific story that hasn't been told. There are also non-earth based maps. Think outer space or imaginary landscapes.

On to Python. Matplotlib: plotting library that is very powerful. Shapely: manipulation of geospatial data. Pandas: high performance easy to use data structures.

GeoPandas installs come with a few sample datasets. They're a really good place to start. Check out Christy's [Notebook](https://github.com/christyheaton/mapitwithpython) to see what she did.


## [Jubal Harpster](https://github.com/jharpster) -- [Microsoft OpenMaps](https://github.com/Microsoft/Open-Maps/)

Their goal at Microsoft is to have the best data for the end user. OSM is part of that. They don't have fleets of cars, they don't have a lot mobile but they do have a lot of engineers and a lot of compute. Is OSM good enough? It's become a lot easier to open source at Microsoft.

Lots of highlights here. 125M building footprints were released. It's out on github, go get it. They brought all their data into the Microsoft system. They use computer vision to fill in gaps where OSM is missing footprints.

First stage, recognize building pixels with a neural net. Then polygonize them. The training data was built internally.

They also do roads, including paved/unpaved attribution. They haven't released that yet.

Australia is a big market for them. Really good community down there. They've been receptive to MS data. 


## [Shay Strong](https://twitter.com/shaybstrong) -- Data Science @ [EagleView](https://www.eagleview.com/)

Shay is the Director of Data Science and Machine Learning at EagleView. New to Seattle, has a PhD in Astronomy and did a lot of atmospheric monitoring at government agencies. Wanted to make a change. Moved to OmniEarth, a DC startup. They did a lot of cool work around analytics with aerial/satellite imagery. They got acquired by EagleView.

EagleView has been around for 18 years and is an aerial imagery provider at 3-1 inch per pixel. Machine learning helps them derive insight from imagery. 

The state of California wanted to identify over users of water, and EagleView was able to get down to the parcel level using a neural network. They apply the same technologies to a bunch of different problems. The nice thing about Machine Learning is that it's a good way to scale robustly and consistently.

They're working on tools and pipelines to get information out as quickly as possible after a major storm. They need 0.5 meter to 0.3 meter resolution imagery. They generally start with satellite imagery. Once the weather clears, they can send out planes or drones to collect more accurate imagery. All these different data types add complexity to scalable processing.

Different models, for different sensors, for different conditions is not ideal. However, you can still drive a lot of value for the customers.

