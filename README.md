# Flood Simulation Template

Demo application template built with the ArcGIS Maps SDK for JavaScript and Calcite Components.

- [ArcGIS Maps SDK for Javascript](https://developers.arcgis.com/javascript/latest/api-reference/)
- [Calcite Components](https://developers.arcgis.com/calcite-design-system/components/)

### Deploy

This demo is built as a _static_ web application.

1. Download and copy the root folder to a web accessible location
2. Update configuration parameters in application.json

### Configure

Update the parameters in ./config/application.json file in your favorite json editor:

|      parameter | details                                                           |
|---------------:|-------------------------------------------------------------------|
|  **portalUrl** | Organization or Enterprise URL; example: https://www.arcgis.com   |
| **oauthappid** | The OAuth ID of the Web Application item                          |
|   **authMode** | For public access set to 'anonymous' (and set oauthappid to null) |
|     **apiKey** | ArcGIS Platform API key                                           |
|     **webmap** | The item id of the web map                                        |
|   **webscene** | The item id of the web scene                                      |
|  **viewProps** | Additional view properties.                                       | 
|  **shareable** | List of shareable properties                                      |


### Web Map Layers Configuration
This application expects the layers to be configured and organized in the Web Map as shown below.  If you organize and name the layers in this manner, then there is no need to modify any code.  

> NOTE: the only exception is the layer called 'Stanwood Mitigation' which represents a visual representation of the barriers and is optional; the absence or different name for this layer will not affect the application code. 

![web map layer config](/assets/WebMapLayerConfig.png)


#### For questions about the demo web application:

> John Grayson | Prototype Specialist | Geo Experience Center\
> Esri | 380 New York St | Redlands, CA 92373 | USA\
> T 909 793 2853 x1609 | [jgrayson@esri.com](mailto:jgrayson@esri.com) | [GeoXC Demos](https://geoxc.esri.com) | [esri.com](https://www.esri.com)
