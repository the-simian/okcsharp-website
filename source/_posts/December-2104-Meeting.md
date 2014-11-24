layout: post
title: "Meeting: December 1 - Lightning Talks"
date: 2014-12-01 16:18:27
tags:
post_asset_folder: true
---

###Monday
###December 1, 2014
####11:30 a.m.
####@Prototek


##About
This is our 1st Installment of Community Lightning Talks. Never heard of a lightning talk? Here is what’s up:

Lightning Talks are really fun. They are an open forum where our members can get up and talk about what they want. The talks need to be short - generally 5-10 minutes. You can cover anything that is .NET, or related to .NET. You can talk about a problem you’ve solved, a tool you like, a cool blog post you read, something you’re working on now, or pretty much any other way you’re using .NET to achieve your goals.

<!-- more -->

##Prototek
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