| Attributes      | Types    | Formats | Mandatory | Descriptions                                                                      |
|----------------|---------|---------|-----------|----------------------------------------------------------------------------------|
| name           | string  |         | yes       | Official name of the protected area                                              |
| name_en        | string  |         | no        | Official name of the protected area                                              |
| name_sl        | string  |         | no        | Official name of the protected area                                              |
| name_de        | string  |         | no        | Official name of the protected area                                              |
| name_fr        | string  |         | no        | Official name of the protected area                                              |
| geometry       | string  | wkt/geojson ? | yes       | geometry of the protected area (srid 4326, geojson/wkt)                          |
| type           | string  |         | yes       | Type of the protected area (national park, regional park, national reserve, ...) |
| description    | string  |         | no        | Free text                                                                        |
| description_en | string  |         | no        | Free text                                                                        |
| description_sl | string  |         | no        | Free text                                                                        |
| description_de | string  |         | no        | Free text                                                                        |
| description_fr | string  |         | no        | Free text                                                                        |
| country        | string  |         | no        | Country of the protected area / ISO 3166                                         |
| url-website    | string  | url     | no        | Link to the protected area website                                               |
| url-logo       | string  | url     | no        | Link to the logo of the national park                                            |
| source         | string  |         | no        | Source of the protected area data                                                |
| uuid           | string  | uuid    | no        | Uuid reference of the protected area (dtp, geotrek, inpn : db source)                                             |
| wikidata-id    | string  |         | no        | Id in wikidata                                                                   |
| wdpa-id        | integer |         | no        | Id in wdpa                                                                       |
| osm-id         | integer |         | no        | Id in open street map                                                            |
