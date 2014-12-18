layout: post
title: "Meeting: January 5 - Bring Your Own Tools - ASP.NET vNext Goes Cross-Platform"
date: 2014-12-01 16:18:27
tags: 
- ASP.NET
- vNext
- Open Source
post_asset_folder: true
---

###Monday
###January 5, 2014
####11:30 a.m.
####@Prototek


##About
Web development was a different game back in the early 2000s. Early versions of ASP.NET were aimed at Microsoft's existing customer base, and even tried to hide the nature of the web from developers who weren't ready for it. Gradually, the ASP.NET team began to open up, shipping open-source components and eventually open-sourcing much of the ASP.NET platform. The next version of ASP.NET goes even further, providing explicit support for development and hosting on non-Windows platforms. Come see how you can take advantage of the robust and full-featured ASP.NET platform while still using the tools you love: OS X, Sublime, Vim, and others.

<!-- more -->
##Speaker

### Brian Sullivan
#### Principal Consultant @ Improving Enterprises and Microsoft MVP

{% img speaker-headshot /images/Brian_Sullivan.jpg  "Brian Sullivan" "Brian Sullivan" %}
Brian Sullivan is a principal consultant for Improving Enterprises in Dallas. He got his start in programming maintaining legacy mainframe applications in COBOL at a large trucking company, but quickly realized he needed to find a more productive environment in order to stay sane. He jumped at the opportunity to help transition some of those COBOL applications to .NET, and he hasn’t looked back since. He has been working with Microsoft technologies since the .NET 1.0 days, and is interested in introducing modern web development techniques to the clients he works with. Brian is recipient of the Microsoft MVP award in ASP.NET and a graduate of Harding University.

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