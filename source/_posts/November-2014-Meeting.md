layout: post
title: "Meeting: November 3 - Three Native Apps in an Afternoon with Xamarin Forms"
date: 2014-10-28 08:39:26
tags:
- xamarin
- mobile
post_asset_folder: true
---

### Monday
### November 3, 2014
#### 11:30 a.m.
#### @Prototek


## About
"It would be nice if..." those magical words customers like to say at the end of a project. In our case the customer wanted a mobile app, something we had no plans to build; to go along with the web application we just created. For many development teams this would require extra meetings, and a longer backlog. But because we have Xamarin Forms, that was not the case. Using Xamarin and their forms library, our team is able share UI code on every mobile device platform with familiar languages like C# and Xaml.

Join Tim Sneed as he discusses how he and his team surprised their customer by building three
native mobile applications in an afternoon.


<!-- more -->

## Speaker  




### Tim Sneed

{% img speaker-headshot /images/TimSneed.jpg  "Tim Sneed" %}


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
