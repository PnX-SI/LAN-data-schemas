| **Attributes**                                                                 | **Types** | **Mandatory** | **Descriptions**                                                           |
|--------------------------------------------------------------------------------|-----------|---------------|----------------------------------------------------------------------------|
| **name**                                                                       | string    | yes           | Protected area official name (default value)                               |
| **name-en name-sl name-de name-fr names-it**                                   | string    | no            | Protected area official name (multilingual). Other languages can be added. |
| **geometry**                                                                   | geom      | yes           | Protected area geometry (srid 4326, geojson/wkt)                           |
| **type**                                                                       | string    | yes           | Protected area type code (national park, regional park, ...)               |
| **IUCN-category**                                                              | string    | no            | Protected area IUCN category                                               |
| **description**                                                                | string    | no            | Protected area general  description                                        |
| **description-en description-sl description-de description-fr description-it** | string    | no            | Protected area general description (multilingual)                          |
| **country**                                                                    | string    | no            | Protected area country / ISO 3166                                          |
| **url-website**                                                                | string    | no            | Link to the protected area website                                         |
| **url-logo**                                                                   | string    | no            | Link to the logo of the protected area                                     |
| **source**                                                                     | string    | no            | Source of the protected area data                                          |
| **pa-uuid**                                                                    | string    | yes           | Protected area UUID (from source DB : DTP, Geotrek, INPN...)               |
| **wikidata-id**                                                                | string    | no            | ID in wikidata                                                             |
| **wdpa-id**                                                                    | integer   | no            | ID in WDPA                                                                 |
| **osm-id**                                                                     | integer   | no            | ID in OpenStreetMap                                                        |
