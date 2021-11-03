# MAPTY PROJECT

This is a app that will help you map your workouts.
this project was part of complete-javascript-course by jonas schmedtmann on Udemy.

## Technologies and Libraries

- [leaflet](https://leafletjs.com/): open-source javascript library for mobile-friendle interactive maps

```
var map = L.map('map').setView([51.505, -0.09], 13);
L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
}).addTo(map);

L.marker([51.5, -0.09]).addTo(map)
.bindPopup('A pretty CSS3 popup.<br> Easily customizable.')
.openPopup();

```

## LICENSE

[MIT License](LICENSE)

```

```
