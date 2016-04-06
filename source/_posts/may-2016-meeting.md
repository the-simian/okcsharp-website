layout: post
title: "Meeting: Xamarin’s FREE! Quick let’s build something with David Roberts"
date: 2016-05-02 11:30:00
tags:
- xamarin
post_asset_folder: true
---

### Monday
### May 2nd, 2016
#### 11:30 a.m.
#### @Prototek


## Xamarin’s FREE! Quick let’s build something
Now that we can all get Xamarin with Visual Studio, even the Community edition let’s see what this thing can do. You will get to see how to start building an Android and an IOS app using Visual Studio with the Xamarin Extension. This isn’t Cordova, this is C# to a native mobile app. Come see how you can make your own mobile app right inside Visual Studio.

## Speaker: David Roberts

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
