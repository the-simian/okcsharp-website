title: about
date: 2014-08-13 02:12:09
comments: true
---

#OKC-Sharp

We are a .Net centric usergroup located in Oklahoma City, Oklahoma. 

Oklahoma City is an emerging technology hub with hundreds of .Net developers working in the area. 

The usergroup will meet the First monday of every month at Prototek in downtown Oklahoma City.

#Conatct
For more informartion or to help out, please contact Matthew Reily via email <me@mattreily.com> or on twitter @matthewreily

#Meeting Location - Prototek
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
  padding: 5px 15px 5px 0px; 
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