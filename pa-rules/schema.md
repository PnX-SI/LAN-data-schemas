| **Attributes**      | **Types** | **Formats** | **Mandatory** | **Descriptions**                                                    |
| ------------------- | --------- | ----------- | ------------- | ------------------------------------------------------------------- |
| protected area name | string    |             | no            | Official name of the protected area                                 |
| protected area uuid | string    |             | yes           | UUID of the protected area (from source DB : DTP, Geotrek, INPN...) |
| activity            | string    |             | yes           | Nature based activity (defined list)                                |
| permission          | string    |             | yes           | Authorised / Not authorised / Authorised under certains conditions  |
| period-condition    | string    |             | no            | Activity allowed during certain period of the year / day            |
| geom-condition      |           |             | no            | Activity allowed on certain area of the protected area              |
| other condition     | string    |             | no            | Free text ...                                                       |
| uuid                | string    |             |               | UUID of the rule                                                    |
| description         | string    |             | no            | Free text                                                           |
| url-pictogram       | string    | url         | no            | Link to pictogram(s) of the activity and permission                 |
| url-rules           | string    | url         | no            | Link to the official protected area rules                           |
