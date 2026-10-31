---
title: "Workshop"
permalink: /workshop/
---

## When and where

**May 11–13, 2027**  
American Society for Microbiology (ASM) headquarters  
1752 N St. NW  
Washington, DC 20036

The workshop is NSF-sponsored and convenes researchers studying dormancy across diverse organisms, disciplines, and biological scales.

## Location map

<div id="workshop-map" role="application" aria-label="Interactive map with pins for ASM headquarters, Courtyard Dupont Circle, and The Beacon at Embassy Row" style="height:430px; width:100%; border-radius:8px; margin:1rem 0;"></div>
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" integrity="sha256-p4NxAoJBhIIN+hmNHrzRCf9tD/miZyoG45qZXqJEu8U=" crossorigin="">
<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js" integrity="sha256-20nQCchB9co0qIjJZRGuk2/Z9VM+kNiyxNV1lvTlZBo=" crossorigin=""></script>
<script>
  (function () {
    var map = L.map('workshop-map', { scrollWheelZoom: false });
    L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {
      maxZoom: 19,
      attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
    }).addTo(map);
    var places = [
      [38.9075, -77.0404, '<strong>Workshop venue: ASM headquarters</strong><br>1752 N St NW, Washington, DC 20036'],
      [38.907461, -77.039708, '<strong>Courtyard Dupont Circle</strong><br>1733 N St NW, Washington, DC 20036'],
      [38.90705, -77.03805, '<strong>The Beacon at Embassy Row</strong><br>1615 Rhode Island Ave NW, Washington, DC 20036']
    ];
    places.forEach(function (place) { L.marker([place[0], place[1]]).addTo(map).bindPopup(place[2]); });
    map.fitBounds(L.latLngBounds(places.map(function (place) { return [place[0], place[1]]; })), { padding: [55, 55], maxZoom: 16 });
  }());
</script>
<p><small>Click a pin to see its name and address. Map locations are approximate; use the linked street addresses for navigation.</small></p>

## Hotels

Participants will stay at one of these hotels:

- **[Courtyard by Marriott Washington, DC Dupont Circle](https://www.google.com/maps/search/?api=1&query=Courtyard%20by%20Marriott%20Washington%20DC%20Dupont%20Circle%2C%201733%20N%20St%20NW%2C%20Washington%2C%20DC%2020036)** — 1733 N St NW, Washington, DC 20036.
- **[The Beacon at Embassy Row](https://www.beaconhotelwdc.com/)** — [1615 Rhode Island Ave NW, Washington, DC 20036](https://www.google.com/maps/search/?api=1&query=The%20Beacon%20at%20Embassy%20Row%2C%201615%20Rhode%20Island%20Ave%20NW%2C%20Washington%2C%20DC%2020036).

Further arrival and travel details will be shared as plans are finalized.

For questions, contact [Jay T. Lennon](mailto:lennonj@iu.edu) or [Daniel A. Hahn](mailto:dahahn@ufl.edu).
