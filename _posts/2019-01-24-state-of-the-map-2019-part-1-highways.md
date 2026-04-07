---
title: The State of the Map Scotland 2019 - Part 1 Highways
date: 2019-01-24
categories: [OpenStreetMap]
tags: [SoTMScotland2019]
---

It's been a while, but I thought it would be interesting to have a look at how the map in Scotland is looking at the start of 2019. Hopefully this will be a series of posts over the next few weeks looking at different aspects of the map.

I've been organised enough to download the Scotland extract on the 1st January. I also have a set of data up to the 30th September 2015, so I can look at progress over the last 2 and quarter years.

First up is Highways:

![](/assets/img/post-assets/2019-01-24-sotm1/scotland_highways_grey.png)

And listed by length:

| highway | 2019 km | Oct 2015 | % change |
| --- | --- | --- | --- |
| track | 36439.04 | 25883.02 | 40.8 |
| unclassified | 17577.05 | 19022.80 | -7.6% |
| service | 15228.94 | 10134.13 | 50.27% |
| residential | 14795.73 | 14311.34 | 3.38% |
| path | 10078.21 | 7350.05 | 37.12 % |
| tertiary | 9635.97 | 8564.57 | 12.51 % |
| footway | 9393.48 | 7888.44 | 19.08 % |
| primary | 7632.37 | 7557.44 | 0.99% |
| secondary | 7423.45 | 7416.27 | 0.10 % |
| trunk | 3609.15 | 3553.73 | 1.56% |
| cycleway | 2079.69 | 1810.81 | 14.85% |
| motorway | 863.83 | 827.14 | 4.44 % |
| motorway_link | 241.17 | 219.95 | 9.65 % |
| trunk_link | 155.97 | 145.52 | 7.18 % |
| road | 131.84 | 316.48 | -58.34% |
| steps | 118.65 | 88.80 | 33.61% |
| proposed | 114.39 | 122.88 | -6.91% |
| pedestrian | 103.90 | 70.01 | 48.41% |
| construction | 97.87 | 253.78 | -61.44% |
| bridleway | 73.26 | 77.59 | -5.58% |
| primary_link | 46.28 | 37.13 | 24.65% |
| bus_stop | 29.57 |  |  |
| living_street | 27.96 | 15.95 | 15.95% |
| raceway | 16.61 | 13.75 | 20.80% |
| secondary_link | 10.28 | 8.92 | 15.25% |
| tertiary_link | 5.84 | 8.50 | -31.29% |
| abandoned | 4.15 | 3.30 | 25.76% |
| no | 2.63 | 2.20 | 19.55% |
| corridor | 0.78 |  |  |
| disused | 0.44 |  |  |
| escape | 0.10 | 0.10 | 0.00% |
| services | 0.05 | 0.57 | -91.23% |
| layby | 0.04 | 0.34 | -88.24% |
| crossing | 0.02 |  |  |
| dismantled | 0.02 |  |  |
| TOTAL | 135 938 | 115 707 | 17% |

To start with, lets look at the roads. As has been the case for a number of years mapping the main road network in Scotland was completed a number of years ago, and the recent changes have been related to some big construction projects such as the Queensferry Crossing, M8 Upgrades and the Queensferry Crossing.

![All motorways in Scotland, red shows the new Motorways](/assets/img/post-assets/2019-01-24-sotm1/scotland_motorways_2015vs2018.png)
_All motorways in Scotland, red shows the new Motorways_

The only road type showing a drop in length is unclassified. This is largely down to improvements in the classifications of roads, in particular to [tertiary](https://wiki.openstreetmap.org/wiki/Tag:highway=tertiary?uselang=en-GB).

![Service Roads in Scotland](/assets/img/post-assets/2019-01-24-sotm1/scotland_service_roads.png)
_Service Roads in Scotland_

We've also seen a big increase in Service roads, it's worth noting that a number of these have been added by Amazon Logistics - they seem to be adding just the last little bit connecting roads to buildings, the service road from road to the house or the office. These edits definitely have been rocky at times, such as the [removal of a car park, just mapped](https://www.openstreetmap.org/changeset/61074110) based on out of imagery. In general I've very happy to see commercial edits, but as this shows new mappers need to be properly trained on how to assess the general state of the map especially before removing things.

![Paths Tracks and Cycleways - New highways are shown in red](/assets/img/post-assets/2019-01-24-sotm1/scotland_paths_tracks_cycleways.png)
_Paths Tracks and Cycleways - New highways are shown in red_

I'm very pleased to see big increases in the mapping of tracks and paths as well as the increase in cycleways although I think these are largely fine tuning of tagging of paths. Hopefully it won't be long until we have full coverage of all paths and tracks and these will be much more stable.

Finally we have the long tail of tags, of these highway=road, which is really a placeholder and shouldn't be used still has far too many entries so for the moment, I've made a list of these to work through - <https://github.com/osm-scotland/scotland-issues/issues/4> if anyone wants to help then jump in, let me know if you need permission for the github link.

The same thing applies to highway=no; These have mostly been used where a highway has been removed. This is useful as it signals to remote mappers (such as the amazon logistics folks above) that the road has been removed. However once the imagery updates having these no longer makes sense. In case any one wants to look at these, I've made a list at: <https://github.com/osm-scotland/scotland-issues/issues/5>

Hopefully I'll be getting a part 2 out in the next few weeks.
