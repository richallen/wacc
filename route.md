---
layout: post-no-feature
title: "The Route"
tags: [Cycling, West Africa, Maps, Sierra Leone, Liberia]
---


<script src='https://api.tiles.mapbox.com/mapbox-gl-js/v0.45.0/mapbox-gl.js'></script>
<link href='https://api.tiles.mapbox.com/mapbox-gl-js/v0.45.0/mapbox-gl.css' rel='stylesheet' />
<style>
    body { margin:0; padding:0; }
    #map { vertical-align: middle;
        min-height: 360px;
        height: 85vh;
        width: 100%;
        max-height: 800px;
        background-position: center center;
        background-size: cover;
        vertical-align: middle;
        -webkit-background-size: cover;
        -moz-background-size: cover;
        -o-background-size: cover;
        position: relative;
        top: 0;
        z-index: -1;}
</style>    


The route started in Bo, Sierra Leone, through the rural south of Sierra Leone onto the border, over the river Mano and into Liberia until Robertsport.


<div id='map'></div>

<br />

<iframe height='405' width='100%' frameborder='0' allowtransparency='true' scrolling='no' src='https://www.strava.com/activities/1604275180/embed/438de37f24d7407ec656943f78b46b31cbbee7ec'></iframe>

<iframe height='405' width='100%' frameborder='0' allowtransparency='true' scrolling='no' src='https://www.strava.com/activities/1609489886/embed/5af0fee9bce70756ce6e6621cd5d51f1c875350c'></iframe>

<iframe height='405' width='100%' frameborder='0' allowtransparency='true' scrolling='no' src='https://www.strava.com/activities/1609489870/embed/4d3518e5b5a5d29968808ff45136e1196ffa15ac'></iframe>

<iframe height='405' width='100%' frameborder='0' allowtransparency='true' scrolling='no' src='https://www.strava.com/activities/1616984907/embed/12647c65b187893f5f81dbe5ba0c20abe75e224c'></iframe>

<script>
mapboxgl.accessToken = 'pk.eyJ1Ijoicm91cmtpZSIsImEiOiJ0Mlg4RTU0In0.jnyGthqO9MDP1JD1Rpl8eg';
var map = new mapboxgl.Map({
    container: 'map', // container id
    style: 'mapbox://styles/rourkie/cji2oc2nd0v4r2ss5gabc4cc8', // stylesheet location
    center: [-11.43, 7.26], // starting position [lng, lat]
    zoom: 8.4, // starting zoom
    pitch: 50
});
</script>
