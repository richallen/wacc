---
layout: post-no-feature
title: "Route"
tags: [blog, graphic design]
---


<script src='https://api.tiles.mapbox.com/mapbox-gl-js/v0.45.0/mapbox-gl.js'></script>
<link href='https://api.tiles.mapbox.com/mapbox-gl-js/v0.45.0/mapbox-gl.css' rel='stylesheet' />
<style>
body { margin:0; padding:0; }
map { position:absolute; top:0; bottom:0; width:100%; }
</style>


<div id='map'></div>
<script>
mapboxgl.accessToken = 'pk.eyJ1Ijoicm91cmtpZSIsImEiOiJ0Mlg4RTU0In0.jnyGthqO9MDP1JD1Rpl8eg';
var map = new mapboxgl.Map({
    container: 'map', // container id
    style: 'mapbox://styles/rourkie/cji2oc2nd0v4r2ss5gabc4cc8', // stylesheet location
    center: [-11.20, 7.59], // starting position [lng, lat]
    zoom: 7 // starting zoom
});
</script>