layout: post
title: "Meeting: April 4th Lightning Talks"
date: 2016-04-04 11:30:00
tags:
- lightning talks
post_asset_folder: true
---

### Monday
### April 4th, 2016
#### 11:30 a.m.
#### @Prototek


## Lightning Talks!
Lightning talks is a fantastic way to introduce our community to developers and allow developers the capability to share their passion. Community members have 5-15 minutes to present on a topic relating to .NET development. We give preference to new speakers to help strengthen and grow our community.

This months speakers:

Joe Shelton - Joe Shelton has been a leader at Robert Half Technology in OKC and has placed Software Developers in the OKC market for the last 4 years. Joe will be giving a presentation on the Robert Half Salary Guide as well as what he and his team are seeing in the constantly evolving job market.

Wil Isaacs - Wil Isaacs is a software developer at Surgical Care Affiliates with a particular interest in DevOps topics. He likes to do game development and brew beer in his free time.

David Miller - TBA

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
