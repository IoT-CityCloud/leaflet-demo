Front-end for IOT-CityClouds
============================

- JavaScript/Typescript
- scaffolding: gulp?
- visuals: d3, crossfilter, leaflet

voor later:

- query interface
- admin e.d.


Example 1: mobile data, Leaflet demo
====================================

- What to plot? GPS on leaflet + std-dev of accel?

- pseudo-backend, down-sampling, and processing: 
    - python, reading csv, pushing json (n=100..1000) with:
```json
{
    "header": {
        "lon": "degree",
        "lat": "degree",
        "height": "m",
        ...
    }
    "data": [
        {
            "lon": -6.0,
            "lat": 52.0,
            "height": -3.0,
            ...
        },
        ...
    ]
}
```

- front-end: reads json, plots using Leaflet
