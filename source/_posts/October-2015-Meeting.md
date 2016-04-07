layout: post
title: "Meeting: October 5th - Opinionated Git Workflows and the People Who Love Them"
date: 2015-10-05 11:30:00
tags:
- Git
- Workflows
- Version Control
post_asset_folder: true
---

### Monday
### October 5th, 2015
#### 11:30 a.m.
#### @Prototek


## About
Sure, you know you're supposed to be using version control for your code, but what does that really look like? Is it the same for a single developer as it is for a team? What about local vs distributed?

I'll share some different workflows for personal, work, and community projects, along with tips on how to avoid some common pitfalls.

<!-- more -->
## Speaker

### Morgan Estes
#### Web Engineer @ 10up

Morgan is a Web Engineer with 10up, a distributed web development company with a focus on making online publishing easy and fun. He's also a core WordPress contributor, currently focusing on documentation and enhancements to the toolbar component. He speaks in GIFs, bad puns, PHP, and JavaScript, and tried C# once, but lost focus and fell flat

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
