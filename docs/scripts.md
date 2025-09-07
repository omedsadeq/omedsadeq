Scripts and Client-Side APIs

Bootstrap and Dependencies

- jQuery 3.3.1 (CDN)
- Popper 1.14.7 (CDN)
- Bootstrap 4.3.1 JS (CDN)

Google Maps (contact.html)

- Script tag:
  `<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap" async defer></script>`
- Global function: `initMap()`
- Usage:
  1. Replace `YOUR_API_KEY` with a valid Google Maps API key
  2. Ensure a container with id `map-container` exists and has width/height via CSS
  3. Map centers on `{ lat: 36.658149, lng: 44.541448 }` and places a marker

Function Reference

initMap()

- Parameters: none
- Returns: void
- Side effects: Initializes a Google Map in `#map-container` and adds a marker
- Example:
```html
<div id="map-container"></div>
<script>
  function initMap() {
    var myLocation = { lat: 36.658149, lng: 44.541448 };
    var map = new google.maps.Map(document.getElementById('map-container'), {
      center: myLocation,
      zoom: 15
    });
    new google.maps.Marker({ map, position: myLocation });
  }
```

