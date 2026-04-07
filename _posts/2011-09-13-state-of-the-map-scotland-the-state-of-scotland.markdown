---
comments: true
date: 2011-09-13 14:14:35
layout: post
slug: state-of-the-map-scotland-the-state-of-scotland
title: State of the Map Scotland - The State of Scotland
wordpress_id: 350
categories:
- OpenStreetMap
---

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide02.jpg)

With the "Official" [State of the Map](http://stateofthemap.org/) Conference in Denver finishing over the weekend, I'm reminded that I've not yet put my talk from our little un-conference at the end of August up on, and as we have a [social in Edinburgh this evening, ](http://wiki.openstreetmap.org/wiki/Edinburgh#Social_Events) I though that I had better do that. So here are my slides and a rough version of what I talked about, we had a mixed group so who were new to OpenStreetMap and also regular mappers; my plan was to try and put something in for both groups.

The talk started by thinking about what is OpenStreetMap...

![OpenStreetMap creates and provides free geographic  data such as street maps to anyone who wants them. The project was started because most maps you think  of as free actually have legal or technical restrictions  on their use, holding back people from using them in  creative, productive, or unexpected ways.  ](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide03.jpg)


So we have the Open data definition of OpenStreetMap, but what does it actually look like:

![The OpenSteetMap Foundation The Map The Planet File The Website The Wiki Tools The Community  .???? ](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide04.jpg)


So what does OpenStreetMap Look Like? What tangible and untangible things do we have?

Well like it or not OSM was formed on an open principle of licensing so lets start there....

![CC-BY-SA](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide05.jpg)

So we started with a [CC-BY-SA license ](http://creativecommons.org/licenses/by-sa/2.0/) which is built on the principle that you are free to Share or Adapt, the work provided that you Attribute and Share Alike the resulting work. But there are problems with this for a database such as OSM's so there has been a process to create the ODBL:

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide06.jpg)


I'm not going to get into the nitty gritty now, and [Dair](http://refnum.com/) is going to be talking about the advantages of ODBL over CC-BY-SA later. But the ongoing process is not without pain, but the end result will be a map that is much easier to actually use, and that what we're about.

So is OSM about the MAP? We definitly have advantages over other maps, for example the A to Z might show:

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide07.jpg

A close where this is a row of houses as an Easter Egg.

Also our map can be much better than the alternatives: Take a look at one of the area's I first mapped on Bing:

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide09.jpg)

In google:

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide10.jpg)

and on OSM:

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide11.jpg)

As well as factual inaccuracies, such as Road naming, missing streets, and incorrect road geometries, there are also additional details such as cycle paths, foot paths, private roads, buildings, schools, parks, station platforms and steps on OSM.

We can also do more interesting things with maps, such as create our versions from the underlying data:

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide12.jpg)

This is from my work in Progress for [Edinburgh Festival Maps](http://edinburghfestivalmaps.co.uk/). Where I can choose what is displayed and what isn't, for example the fringe venues show their festival names and are shown in blue.

And all this is possible because it's a map we can Edit ourseleves.

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide131.jpg)

and the data model is pretty simple, at the bottom we have nodes, on there own these can represent point objects. Such as cycle parking, traffic lights, bollards. There can be connected together to for ways. There might represent roads or building, boundaries, rivers anything that might be represented by a line or a closed area.

Less simple, we also have relations, these are collections or ways or nodes, and are used to represent more complex objects such as the courtyard in a building or cycle routes.

On top of these we have a flexible tagging scheme:

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide14.jpg)

the tagging scheme is totally open, there are no rules enforced by the API or the database. This means that you are free to tag things however you want. But the community has a set of conventions that are documented on the wiki and generally these are adhered to. But the important thing here is when you find something new; there aren't any committees deciding how to tag, you just do it.

So is OSM the hardware?

[![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide15.jpg)](http://www.chrisfleming.org/osm/state-of-the-map-scotland-the-state-of-scotland/attachment/slide15/)


or the code?

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide16.jpg)

I would say that it's the community:

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide17.jpg)

Not that kind of community...

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide18.jpg)

This kind of community - this picture is from the Edinburgh Zoo mapping party where we mapped the zoo out:

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide19.jpg)](http://www.chrisfleming.org/osm/state-of-the-map-scotland-the-state-of-scotland/attachment/slide19/)

It's the same community that meant that in November 2007, Edinburgh looked like:

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide20.jpg)

and in August 2012:

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide21.jpg)

and overall the numbers against the ITO analysis look pretty good:

|------------------------------+---------+---------+--------------- ------------|
|Place                         |OS Locator   |Roads Missing  |% Complete        |
|------------------------------|---------|---------|----------------------------|
|Edinburgh                     |4,760    |0        |100                                        |
|------------------------------+---------+---------+-------------------------------------------|
|Midlothian                    |1,180    |0        |100                                        |
|------------------------------+---------+---------+-------------------------------------------|
|Clackmannanshire              |817      |5        |99.27                                      |
|------------------------------+---------+---------+-------------------------------------------|
|South Lanarkshire             |5432     |73       |98.55                                      |
|------------------------------+---------+---------+-------------------------------------------|
|West Dunbartonshire           |1,233    |18       |98.54                                      |
|------------------------------+---------+---------+-------------------------------------------|
|Shetland Islands              |309      |6        |98.06                                      |
|------------------------------+---------+---------+-------------------------------------------|
|Stirling                      |1,361    |29       |97.58                                      |
|------------------------------+---------+---------+-------------------------------------------|
|East Ayrshire                 |2039     |50       |97.5                                       |
|------------------------------+---------+---------+-------------------------------------------|
|Glasgow City                  |6758     |171      |97.44                                      |
|------------------------------+---------+---------+-------------------------------------------|
|West Lothian                  |2030     |48       |97.44                                      |
|------------------------------+---------+---------+-------------------------------------------|
|Inverclyde                    |1239     |32       |97.42                                      |
|------------------------------+---------+---------+-------------------------------------------|
|Na H Eileanan An Iar          |298      |5        |97.32                                      |
|------------------------------+---------+---------+-------------------------------------------|
|East Lothian                  |1343     |33       |97.1                                       |
|------------------------------+---------+---------+-------------------------------------------|
|North Ayrshire                |2180     |63       |97.06                                      |
|------------------------------+---------+---------+-------------------------------------------|
|Dundee City                   |2223     |65       |97.03                                      |
|------------------------------+---------+---------+-------------------------------------------|
|Angus                         |1877     |57       |96.91                                      |
|------------------------------+---------+---------+-------------------------------------------|
|South Ayrshire                |1803     |61       |96.45                                      |
|------------------------------+---------+---------+-------------------------------------------|
|Argyll And Bute               |1400     |50       |96.43                                      |
|------------------------------+---------+---------+-------------------------------------------|
|Monmouthshire                 |1529     |52       |96.34                                      |
|------------------------------+---------+---------+-------------------------------------------|
|Fife                          |5607     |217      |95.93                                      |
|------------------------------+---------+---------+-------------------------------------------|
|Scottish Borders              |1890     |78       |95.77                                      |
|------------------------------+---------+---------+-------------------------------------------|
|East Renfrewshire             |1323     |57       |95.62                                      |
|------------------------------+---------+---------+-------------------------------------------|
|Aberdeen City                 |2772     |125      |95.27                                      |
|------------------------------+---------+---------+-------------------------------------------|
|Highland                      |3443     |535      |84.05                                      |
|------------------------------+---------+---------+-------------------------------------------|
|Aberdeenshire                 |3886     |626      |83.63                                      |
|------------------------------+---------+---------+-------------------------------------------|
|Renfrewshire                  |2447     |430      |82.18                                      |
|------------------------------+---------+---------+-------------------------------------------|
|Perth and Kinross             |2409     |478      |79.91                                      |
|------------------------------+---------+---------+-------------------------------------------|
|Dumfries And Galloway         |2556     |586      |76.53                                      |
|------------------------------+---------+---------+-------------------------------------------|
|Moray                         |1545     |366      |75.92                                      |
|------------------------------+---------+---------+-------------------------------------------|


Until we get too the bottom of the table... but the total is still something to be proud of.

According to the ITO analysis, we're missing"4316 Roads compared to OS.

This means that Scotland is 93% "Complete" by this measure.

and when we are 100% complete on this measure there may be other measures to look at:

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide25.jpg)

such as the meridian analysis, but we need to complete the map first. For now, and I don't want to start a fight:

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide26.jpg)

we're going to do that by tracing:

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide27.jpg)


Which is great, people can use the maps with confidence; and across the country we know we at very least meet the google maps standard, but for the OSM standard we really need to have people on the ground, and we have a problem, there was a study done into [Who Maps in OpenStreetMap and Why?](SOTM 2010 Talk  Who Maps in OpenStreetMap and Why?)

This found that mappers are 96% Male and 78% have a degree and higher.

We also know that [more people looking at area's improved accuracy.](http://povesham.wordpress.com/2011/01/10/how-many-volunteers-does-it-take-to-map-an-area-well-the-validity-of-linus-law-to-volunteered-geographic-information/ )

So for the best freshest map we need people on the ground, in Moray and Dumfries and across Scotland.

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide30.jpg)

The OSM website shows 30 mappers within 1km of me in Edinburgh, yet we have huge area's of Scotland with no one.

The big challenge for OSM in Scotland is to get people across the country looking after there street, town and village in Scotland adding the details and seeing what has changed.

![](/post-assets/2011-09-13-state-of-the-map-scotland-the-state-of-scotland/Slide32.jpg)

#### Photo Credits ####

* [photo: http://www.flickr.com/photos/johnmueller/52621490/](Image from: http://www.flickr.com/photos/johnmueller/52621490/ )
* <http://farm6.static.flickr.com/5081/5237521828_536640e421_o.jpg>
* [photo: http://www.flickr.com/photos/sunfrog1/307110936/]( http://www.flickr.com/photos/sunfrog1/307110936/ )
* [Photo: http://www.flickr.com/photos/67155762@N00/3388293945/]( http://www.flickr.com/photos/67155762@N00/3388293945/)
* photo: <http://farm5.static.flickr.com/4041/4441209986_29ecf7f7b7_o.jpg>
* [photo: http://www.flickr.com/photos/mvjantzen/5028611938/sizes/l/in/photostream/]( http://www.flickr.com/photos/mvjantzen/5028611938/sizes/l/in/photostream/ )
