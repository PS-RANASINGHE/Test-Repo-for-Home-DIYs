# Test-Repo-for-Home-DIYs


# Finnish Mushrooms
| Mushroom (English / Finnish)               | Scientific Name          | Edibility                                |
|--------------------------------------------|--------------------------|------------------------------------------|
| Chanterelle / Kantarelli                   | *Cantharellus cibarius*  | Edible, choice                           |
| Porcini / Herkkutatti                      | *Boletus edulis*         | Edible, choice                           |
| Funnel Chanterelle / Suppilovahvero        | *Craterellus tubaeformis*| Edible                                   |
| Slippery Jack / Rasvaturvesieni            | *Suillus luteus*         | Edible                                   |
| Saffron Milk Cap / Keltavahvero            | *Lactarius deliciosus*   | Edible                                   |
| Birch Bolete / Lehmustatti                 | *Leccinum scabrum*       | Edible                                   |
| Giant Puffball / Iso lakki                 | *Calvatia gigantea*      | Edible (when young)                      |
| False Morel / Korvasieni                   | *Gyromitra esculenta*    | Poisonous raw; edible after thorough cooking |
| Fly Agaric / Kärpässieni                   | *Amanita muscaria*       | Poisonous (hallucinogenic)               |
| Death Cap                                  | *Amanita phalloides*     | Deadly poisonous                        |



![image](https://github.com/user-attachments/assets/4b1a5179-5ec6-4f26-8165-09c5508c8998)

# Vehicle stat in Finland

| Brand             | New Registrations in 2024 |
|-------------------|---------------------------:|
| Toyota            | 12 464                     |
| Volvo             |  7 801                     |
| Škoda             |  7 379                     |
| Volkswagen        |  6 578                     |
| Kia               |  5 316                     |
| Mercedes-Benz     |  3 876                     |
| Tesla             |  3 717                     |
| BMW               |  3 717                     |
| Hyundai           |  3 100                     |
| Nissan            |  2 956                     |


![image](https://github.com/user-attachments/assets/28cd6033-765d-4961-9d31-d68a62b11ab2)


# This is a video for testing 

https://github.com/user-attachments/assets/5eb584f2-d79d-4c5d-98e3-3aa50ed9baf6

```mermaid
pie
  title New Registrations by Brand in 2024
  "Toyota": 12464
  "Volvo": 7801
  "Škoda": 7379
  "Volkswagen": 6578
  "Kia": 5316
  "Mercedes-Benz": 3876
  "Tesla": 3717
  "BMW": 3717
  "Hyundai": 3100
  "Nissan": 2956
```
# bar chart for test purposes

![Bar Graph][image](https://github.com/user-attachments/assets/0527fbd9-022f-4871-a171-27d25e17fd5b)


# Testing maps


```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```

```topojson
{
  "type": "Topology",
  "transform": {
    "scale": [0.0005000500050005, 0.00010001000100010001],
    "translate": [100, 0]
  },
  "objects": {
    "example": {
      "type": "GeometryCollection",
      "geometries": [
        {
          "type": "Point",
          "properties": {"prop0": "value0"},
          "coordinates": [4000, 5000]
        },
        {
          "type": "LineString",
          "properties": {"prop0": "value0", "prop1": 0},
          "arcs": [0]
        },
        {
          "type": "Polygon",
          "properties": {"prop0": "value0",
            "prop1": {"this": "that"}
          },
          "arcs": [[1]]
        }
      ]
    }
  },
  "arcs": [[[4000, 0], [1999, 9999], [2000, -9999], [2000, 9999]],[[0, 0], [0, 9999], [2000, 0], [0, -9999], [-2000, 0]]]
}
```
