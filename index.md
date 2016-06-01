---
layout: default
---

<div class="pageHolder">

  <div class="floatoneline">
    McLeans is a resturant in Muthill, Perthshire, serving homemade pizzas,
    sandwiches, soup, and ice cream. Stop by for a friendly welcome and some
    execllent food. The ice cream is especially good!
  </div>

  <div class="floatoneline">
    <script src='https://maps.googleapis.com/maps/api/js?v=3.exp'></script>
    <div style='overflow:hidden;height:300px;width:420px;'>
      <div id='gmap_canvas' style='height:300px;width:420px;'></div>
      <style>#gmap_canvas img{max-width:none!important;background:none!important}</style>
    </div>
    <a href='https://mapswebsite.net/'>google maps widget</a>
    <script type='text/javascript' src='https://embedmaps.com/google-maps-authorization/script.js?id=cbdee0669b6cce22be55ee0bc1f5a73c6db93c2d'></script>
    <script type='text/javascript'>function init_map(){var myOptions = {zoom:14,center:new google.maps.LatLng(56.332706852542536,-3.8333335777709765),mapTypeId: google.maps.MapTypeId.ROADMAP};map = new google.maps.Map(document.getElementById('gmap_canvas'), myOptions);marker = new google.maps.Marker({map: map,position: new google.maps.LatLng(56.332706852542536,-3.8333335777709765)});infowindow = new google.maps.InfoWindow({content:'<strong>McLeans</strong><br>Drummond St<br> Muthill<br>'});google.maps.event.addListener(marker, 'click', function(){infowindow.open(map,marker);});infowindow.open(map,marker);}google.maps.event.addDomListener(window, 'load', init_map);</script>
  </div>
</div>
