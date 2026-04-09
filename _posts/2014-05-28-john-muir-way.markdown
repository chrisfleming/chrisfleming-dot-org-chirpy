---
title: John Muir Way
date: 2014-05-28 23:21
categories: [OpenStreetMap]
tags: [OSM, Cycling]
---

So the [John Muir Way](http://johnmuirway.org/) has been open since the 21st of April. This long distance route is a Coast to Coast route between Helensburgh in the West—from where John Muir set off to the United States where he inspired the conservation movement and the creation of its national parks—to Dunbar on the East Coast where he was born and grew up.

We've covered most of the route in OpenStreetMap for a while. But until recently we've had a tiny gap missing. I was trying to figure out getting over to do it when I saw Martin McMahon had filled it in with a 9-mile walk between train stations—great effort!

[twitter: to map that gap took 2 trains 1 to Helensburgh a 9 miles walk then train from Balloch. Great day](/post-assets/2014-05-28-john-muir-way/twitter.webp)

So with some not insignificant effort, we now have the complete route mapped. These can easily be seen by looking at a raw view of either the [walking route](http://www.openstreetmap.org/relation/49215) or the [cycling route](http://www.openstreetmap.org/relation/3619145) on OpenStreetMap.

But where OSM comes into its own is the ability to actually do things with the data, so to kick things off I've created a set of GPX files of the route. These contain the full walking or cycling route and are suitable to be loaded into your GPS or phone app as aids to navigating the route.

- [john_muir_way_cycling.gpx](/post-assets/2014-05-28-john-muir-way/cycling.gpx)
- [john_muir_way_walking.gpx](/post-assets/2014-05-28-john-muir-way/walking.gpx)

Map wise, as always I'm disappointed to see the otherwise very nice John Muir Way website using Google Maps rather than an OpenStreetMap based map:

<link rel="stylesheet" href="https://unpkg.com/maplibre-gl@4.0.0/dist/maplibre-gl.css" />
<script src="https://unpkg.com/maplibre-gl@4.0.0/dist/maplibre-gl.js"></script>

<div id="map" style="width:100%; height:400px; border-radius:8px; margin: 1rem 0;"></div>
<div style="font-size: 0.9em; margin-bottom: 1rem;">
  <span style="color: #e63946;">━━</span> Walking route
  <span style="color: #2a9d8f; margin-left: 1rem;">━━</span> Cycling route
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  var map = new maplibregl.Map({
    container: 'map',
    style: 'https://tiles.openfreemap.org/styles/liberty',
    center: [-3.6, 56.0],
    zoom: 8
  });

  map.addControl(new maplibregl.NavigationControl());

  map.on('load', function() {
    // Walking route
    fetch('/post-assets/2014-05-28-john-muir-way/john_muir_way_walking.geojson')
      .then(r => r.json())
      .then(data => {
        map.addSource('walking', { type: 'geojson', data: data });
        map.addLayer({
          id: 'walking-line',
          type: 'line',
          source: 'walking',
          paint: {
            'line-color': '#e63946',
            'line-width': 3,
            'line-opacity': 0.8
          }
        });
      });

    // Cycling route
    fetch('/post-assets/2014-05-28-john-muir-way/john_muir_way_cycling.geojson')
      .then(r => r.json())
      .then(data => {
        map.addSource('cycling', { type: 'geojson', data: data });
        map.addLayer({
          id: 'cycling-line',
          type: 'line',
          source: 'cycling',
          paint: {
            'line-color': '#2a9d8f',
            'line-width': 3,
            'line-opacity': 0.8
          }
        });
      });
  });
});
</script>

There are also tools such as [Relation Analyser](http://ra.osmsurround.org/analyzeRelation?relationId=3619145). Interestingly this shows cycling distance as 206km and the walking distance as 213km while the route is officially 215 km (I guess they rounded up).
