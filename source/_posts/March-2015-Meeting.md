layout: post
title: "Meeting: March 2nd - Azure vAwesome"
date: 2015-3-02 15:29:38
tags:
- Azure
- DocumentDb
- Machine Learning
post_asset_folder: true
---

###Monday
###March 2, 2015
####11:30 a.m.
####@Prototek


##About
Come see the awesome and powerful new features that are currently available in Preview on Microsoft's Computing Platform - Azure - including Machine Learning, DocumentDb, Search and more!

<!-- more -->
##Speaker

### David Walker
#### Sitecore MVP, Sitecore Architect, XCentium.com
{% img speaker-headshot /images/david_walker.jpg "David Walker" "" %}

David Walker is a Sitecore Architect for XCentium. He has over 20 years' experience in application development with over 50% of that employed as a consultant. He has been an MCP since 2003, MCAD and MCSD since 2005, and was a Microsoft MVP - ASP/ASP.NET from July 2007 - July 2009. Prior to joining Microsoft, he was formerly a board member for INETA (Vice President, Speakers Bureau), President of the Tulsa Developers .NET users group, founder and President of the Tulsa SQL Server Group and Tulsa Java Developers Group, and Vice President of the Tulsa SharePoint Interest Group. He has been the Chairman of the region's largest and highly successful technical training event, now going on its seventh consecutive year, TulsaTechFest.com.

Recently he has focused on a wide range of newer technologies, including: Azure, AppFabric, MEF (Managed Extensibility Framework), SharePoint, WindowsPhone and Windows8/WindowsStore applications. He has been using WCF (Windows Communication Foundation) and WPF (Windows Presentation Foundation) since the first Beta release back in 2005/2006!

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
