| **Attributes**          | **Types** | **Mandatory** | **Descriptions**                                                      |
|-------------------------|-----------|---------------|-----------------------------------------------------------------------|
| **protected-area-name** | string    | no            | Protected area official name                                          |
| **protected-area-uuid** | string    | yes           | Protected area UUID (from source DB : DTP, Geotrek, INPN...)          |
| **activity**            | string    | yes           | Nature based activity (defined list)                                  |
| **permission**          | string    | yes           | Allowed / allowed under certains conditions / forbidden               |
| **period-condition**    | string    | no            | Periods when the activity is allowed (seasonal or daily restrictions) |
| **geom-condition**      | geom      | no            | Areas within the protected area where the activity is allowed         |
| **other-condition**     | string    | no            | Description of additional conditions                                  |
| **pa-rule-uuid**        | string    | no            | Protected area rule UUID                                              |
| **description**         | string    | no            | General description (multilingual)                                    |
| **url-pictogram**       | string    | no            | Link to pictogram(s) of the activity and permission                   |
| **url-rules**           | string    | no            | Link to the official protected area rules                             |
