layout: post
title: "Meeting: January 4th Planning Meeting/Social"
date: 2016-01-04 11:30:00
tags:
- planning
- social
post_asset_folder: true
---

### Monday
### January 4th, 2016
#### 11:30 a.m.
#### @Prototek


## About
Come join us Monday January 4th where we will have an open discussion about making 2016 our best year yet.  Bring your ideas for speaker topics, technical workshops, or anything that will help us bring value to our members.

There is NO OKC-Sharp without it's awesome members, so come out and help us make this group the best it can be.

This will also be a great time to network with other developers and see what others are doing in our communtiy.

And finally, free pizza!

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

