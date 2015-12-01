title: post
title: "Meeting: November 2nd - Adding intelligence to your applications with Project Oxford"
date: 2015-11-02 11:30:00
tags:
- intelligence
- api
- oxford
post_asset_folder: true
---

### Monday
### November 2nd, 2015
#### 11:30 a.m.
#### @Prototek


## About
Learn about Project Oxford and how to use the different APIs provided to enhance your application - with code samples and demos.

<!-- more -->
## Speaker

### Jason Fox
#### Technical Evangelist at Microsoft

As a Technical Evangelist at Microsoft, Jason gets to indulge his passion for educating and helping others be successful. He is a veteran software developer and technologist with over 13 years of experience in various industries - telecommunications, logistics, video games and defense. He has engineered large-scale systems including hardware, software and automation.

Jason grew up in Fort Worth, TX, where he currently resides with his family.

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
