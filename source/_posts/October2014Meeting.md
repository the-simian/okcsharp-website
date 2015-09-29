layout: post
title: "Meeting: October 6 - What is Visual Studio Online"
tags: []
post_asset_folder: true
categories: []
date: 2014-09-03 17:37:00
---



# What is Visual Studio Online?

Monday
### October 6, 2014
#### 11:30 a.m.
#### @Prototek


## About
Officially launched in 2013, Visual Studio Online is, in Microsoft's own words, "a collection of developer services that runs on Windows Azure and extends the developer experience in the cloud." That sounds awesome but what does it actually mean? Is it XBOX Live for Visual Studio? Not quite. In this hands-on session, Casey guides the audience through an example project covering Visual Studio Online's four core features ? source control (via Git), agile planning, automated builds and application insights. At the end of the session you will know all that you need to start using Visual Studio Online on your next major project. If you wish to follow along live, don't forget to bring your laptop with Visual Studio 2013 installed and sign up for your free (forever) Visual Studio Online account at http://www.visualstudio.com/products/visual-studio-online-user-plans-vs.

<!-- more -->

## Speaker  




### Casey Watson
#### Cloud Architect, Digital Recognition Network

{% img speaker-headshot /images/Casey_Watson.jpg  "Casey Watson" "Casey Watson" %}
Casey Watson is a passionate software architect, President of the North Dallas Cloud Computing Group, dedicated husband and proud father. Casey believes that is the responsibility of every serious developer to constantly "sharpen their saw" through both reading and community involvement and is a strong advocate of SOLID development practices. Over the last eight years, he has been focused primarily on the .NET platform but has recently taken a keen interest in cloud development both on Amazon's EC2 and Microsoft's Azure platform. Casey is heavily involved in the local development community having spoken at several user groups and conferences across the South Central region of the United States including Agile.NET, Dallas Days of .NET and TechX20. When not learning about, speaking on, writing about or building software, he can be found spending time with his family, updating his Twitter status (@_caseywatson), or enjoying an ice cold bottle of Blue Moon.


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