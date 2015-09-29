layout: post
title: "Meeting: April 6th - Application Performance Management"
date: 2015-04-06 11:30:00
tags:
- APM
- New Relic
- Browser Tools
- Plugins
post_asset_folder: true
---

### Monday
### April 6, 2015
#### 11:30 a.m.
#### @Prototek


## About
An in-depth look into a mix of Application Performance Management (APM) + Plugins + Browser tools to gain a holistic, end-to-end perspective into application performance.

<!-- more -->
## Speaker

### Ugesen (Yogi) Pillay
#### Enterprise Sale Engineer
<!-- {% img speaker-headshot /images/david_walker.jpg "David Walker" "" %} -->

Ugesen (Yogi) Pillay is an Enterprise Sales Engineer with New Relic. He brings a number of years of software development experience, most recently working on developing supply chain management applications for @Walmartlabs. Prior to that, he worked in IT for the State of California's Employment Development Department and in small business sales for the Geek Squad at Best Buy.

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
