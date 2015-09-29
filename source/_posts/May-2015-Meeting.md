layout: post
title: "Meeting: May 4th - Lightning Talks"
date: 2015-05-04 11:30:00
tags:
- Lightning Talks
- Community
- Multiple Speakers
post_asset_folder: true
---

### Monday
### May 4th, 2015
#### 11:30 a.m.
#### @Prototek


## About
Lightning Talks are a really fun event we put on every 3 months. Community members have 5 to 10 minutes to talk about .NET or topics related to .NET technologies. We give preference to new speakers to strengthen our community.

We still need Speakers! Please contact [Matthew Reily](mailto:matt@okcsharp.net) if you are interested in this opportunity.

<!-- more -->
## Speakers

You! Seriously though, if you are interested in giving a talk at this Lightning Talk, please email [Matthew Reily](mailto:matt@okcsharp.net)!

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
