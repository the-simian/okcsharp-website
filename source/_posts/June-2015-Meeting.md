title: post
title: "Meeting: June 1st - Getting Started with Visual Studio 2015 RC and ASP.NET 5"
date: 2015-06-01 11:30:00
tags:
- ASP.NET 5
- Visual Studio 2015
- Multiple Speakers
post_asset_folder: true
---

###Monday
###June 1st, 2015
####11:30 a.m.
####@Prototek


##About
There have been some major changes in the past 2 months with the release of Visual Studio 2015 RC.  We will take a look at some of the new exciting features within VS as well as dive into what ASP.NET 5 development looks like. 

<!-- more -->
##Speaker

### Matthew Reily
#### Software Architect @ Interworks, Inc
{% img speaker-headshot /images/matthew_reily.jpg "Matthew Reily" "Matthew Reily" %}

Matthew Reily is an aspiring software craftsman who has a deep passion for learning and discussing new development technologies and practices. Matthew has worked diligently sharpening his skills for the past 15 years and has worn many hats. He has helped develop and deliver world class software, managed a couple of DevOps teams, and even spent a few years running his own consulting company. He loves to spending time with his family, running ultra-marathons, and working on his next IoT projects. Matthew is currently perfecting his craft as a software architect for InterWorks, Inc.

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
