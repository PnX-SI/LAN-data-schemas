| **Attributes**            | **Types** | **Mandatory** | **Descriptions**                                                 |
|---------------------------|-----------|---------------|------------------------------------------------------------------|
| **name**                  | string    | yes           | Trail name (multilingual)                                        |
| **geometry**              | geom      | yes           | Trail geometry (srid 4326, geojson/wkt)                          |
| **trail-uuid**            | string    | no            | Trail UUID                                                       |
| **activity**              | string    | no            | Trail activity (i.e pedestrian, bike, horse, trail, ...)         |
| **length**                | string    | yes           | Trail length in meters                                           |
| **duration**              | string    | no            | Trail duration in hours                                          |
| **start**                 | string    | yes           | Start of the trail                                               |
| **finish**                | string    | yes           | End of the trail                                                 |
| **elevation-gain**        | string    | no            | Trail elevation gain in meters                                   |
| **altitude-min**          | string    | no            | Trail minimum altitude in meters                                 |
| **altitude-max**          | string    | no            | Trail maximum altitude in meters                                 |
| **difficulty**            | string    | no            | Trail difficulty                                                 |
| **presentation**          | string    | no            | Trail general presentation  (multilingual)                       |
| **step-by-step-guidance** | string    | no            | Trail step-by-step guidance (multilingual)                       |
| **recommendation**        | string    | no            | Trail general recommendation from the data source (multilingual) |
| **OSM-id**                | integer   | no            | Trail OpenStreetMapid                                            |
| **url-picture**           | string    | no            | Trail main illustration                                          |
| **source**                | string    | no            | Trail data source of information                                 |


As part of the work on the data standard for nature based activities, an extension of this schema has been considered in order to integrate the concept of a **BREATHE score index**. The objective is not to challenge the proposed standard structure, but to supplement it in a manner that is consistent and interoperable with several criteria (strength, endurance, immune system, mental health, social health).


| Attributes            | Types   | Mandatory | Descriptions                                                              |
|-----------------------|---------|-----------|---------------------------------------------------------------------------|
| trail-uuid            | string  | yes       | Trail UUID                                                                |
| breathe-strength      | integer | yes       | Refers to the path and possible places along the way                      |
| breathe-endurance     | integer | yes       | Refers only to the path                                                   |
| breathe-immune-system | integer | yes       | Refers to the path and the immediate surroundings                         |
| breathe-mental-health | integer | yes       | Refers to the view, sound and impression from the path into the landscape |
| breathe-social-health | integer | yes       | Refers to the path, the wayside, and the view from the path               |
