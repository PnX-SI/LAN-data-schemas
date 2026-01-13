| Attributes     | Types   | Formats | Mandatory | Descriptions                                                                     |
|----------------|---------|---------|-----------|----------------------------------------------------------------------------------|
| name           | string  |         | yes       | Official name of the protected area (default value)                              |
| name_en        | string  |         | no        | Official name of the protected area in English. Other languages can be added.    |
| name_sl        | string  |         | no        | Official name of the protected area                                              |
| name_de        | string  |         | no        | Official name of the protected area                                              |
| name_fr        | string  |         | no        | Official name of the protected area                                              |
| geometry       | string  | wkt ?   | yes       | geometry of the protected area (srid 4326, geojson/wkt)                          |
| type           | string  |         | yes       | Type code of the protected area (national park, regional park, ...)              |
| IUCN_category  | string  |         | no        | IUCN protected area categories             |
| description    | string  |         | no        | Free text (default value)                                                        |
| description_en | string  |         | no        | Free text in English. Other languages can be added                               |
| description_sl | string  |         | no        | Free text                                                                        |
| description_de | string  |         | no        | Free text                                                                        |
| description_fr | string  |         | no        | Free text                                                                        |
| country        | string  |         | no        | Country of the protected area / ISO 3166                                         |
| url-website    | string  | url     | no        | Link to the protected area website                                               |
| url-logo       | string  | url     | no        | Link to the logo of the national park                                            |
| source         | string  |         | no        | Source of the protected area data                                                |
| uuid           | string  | uuid    | no        | Uuid of the protected area (from source DB : DTP, Geotrek, INPN...)              |
| wikidata-id    | string  |         | no        | ID in wikidata                                                                   |
| wdpa-id        | integer |         | no        | ID in WDPA                                                                       |
| osm-id         | integer |         | no        | ID in OpenStreetMap                                                              |
