layout: post
title: "Intro to Continuous Delivery with Ryan Hoegg"
date: 2016-02-01 11:30:00
tags:
- continuous deployment
- devops
post_asset_folder: true
---

### Monday
### February 1st, 2016
#### 11:30 a.m.
#### @Prototek


## About
Continuous delivery is a central theme in the DevOps movement, and certainly a central component of the culture. It is the set of engineering techniques, practices, processes, and tools for releasing changes to software services frequently and reliably.

We'll review the concepts involved in CD, take a look a working CD pipeline for an example application, and discuss how this could apply to other projects.

<!-- more -->
## Speaker

### Ryan Hoegg
Ryan Hoegg still thinks software is one of the coolest things mankind has ever come up with. He serves as Vice President of Techlahoma, partly to help get lots of other people excited about it. His day job is Hoegg Software, Co., a software consulting startup in OKC.

## Prototek
Prototek
401 NW 10th,
Oklahoma City, Oklahoma
73101

<script
type="text/javascript"
src="http://maps.google.com/maps/api/js?sensor=false"
></script>
<style>
#gmap_canvas img{
max-width:none!important;
background:none!important;
}

.speaker-headshot {
  float: left;

  padding: 5px 100% 5px 0px;
}

</style>

<div style="overflow:hidden;height:200px;width:900px;">
<div id="gmap_canvas" style="height:200px;width:900px;"></div>
</div>
<script type="text/javascript">
function init_map() {
  var myOptions = {
    zoom: 14,
    center: new google.maps.LatLng(35.478527, -97.51941699999998),
    mapTypeId: google.maps.MapTypeId.ROADMAP
  };
  map = new google.maps.Map(document.getElementById("gmap_canvas"), myOptions);
  marker = new google.maps.Marker({
    map: map,
    position: new google.maps.LatLng(35.478527, -97.51941699999998)
    });
    infowindow = new google.maps.InfoWindow({
      content: "<b>Prototek</b><br/>401 NW 10th St, <br/>73103 Oklahoma City"
      });
      google.maps.event.addListener(marker, "click", function() {
        infowindow.open(map, marker);
        });
        infowindow.open(map, marker);
      }
      google.maps.event.addDomListener(window, 'load', init_map);
      </script>
