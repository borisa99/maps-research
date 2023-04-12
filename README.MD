# Description

We are building a new feature in our React application that requires a map user interface with the ability to draw polygons and retrieve their coordinates. Our users need to be able to draw multiple polygons and have the ability to edit or delete them as needed. We have researched several JavaScript libraries and have narrowed our search down to three popular options: [Leaflet](#leaflet), [Mapbox GL](#mapbox-gl), and [OpenLayers](#openlayers).

In the following sections, we will evaluate each library's ability to meet our specific requirements, as well as their overall maturity, popularity, and community support. We will also consider factors such as ease of use, available features, and any potential limitations or drawbacks. By the end of our evaluation, we hope to choose the best library for our needs and create a reliable and user-friendly map user interface for our application.

## Leaflet <a name="leaflet"></a>

- Weekly downloads: over 3 million (npm trends)
- Open source: Yes
- Behind it: Vladimir Agafonkin and a team of contributors
- GitHub repository: [https://github.com/Leaflet/Leaflet](https://github.com/Leaflet/Leaflet), [https://github.com/PaulLeCam/react-leaflet](https://github.com/PaulLeCam/react-leaflet)
- In Leaflet, required functionality is provided by the Leaflet.draw plugin, which allows users to draw and edit vector shapes (including polygons) on the map, and returns the coordinates of those shapes as GeoJSON.

### Pros

- Lightweight and fast
- Open Source
- Easy to learn and use, with a simple and intuitive API
- Good documentation and community support
- Has been around for over a decade, making it a mature and stable library
- Very popular, with a large user base and ecosystem of plugins and extensions

### Cons

- Limited advanced features and customization options compared to other libraries
- Can be more difficult to build complex maps with many layers or data sources
- Less suitable for large-scale or enterprise-level web mapping applications

## Mapbox GL <a name="mapbox-gl"></a>

- Weekly downloads: over 1.7 million (npm trends)
- Open source: Yes, but mapbox core is not (Requires Mapbox API key)
- Behind it: Mapbox and a team of contributors
- GitHub repository: [https://github.com/mapbox/mapbox-gl-js](https://github.com/mapbox/mapbox-gl-js)
- In Mapbox GL, required functionality is provided by the Mapbox GL Draw library, which also allows users to draw and edit vector shapes (including polygons) on the map, and returns the coordinates of those shapes as GeoJSON.

### Pros

- Powerful and feature-rich, with advanced mapping capabilities like 3D maps, custom styles, and real-time data visualization
- Supports a wide range of data sources and formats, including vector tiles, raster tiles, and GeoJSON
- Offers more flexibility and customization options than Leaflet
- Good documentation and community support
- Popular, with a large user base and strong support from Mapbox as a company

### Cons

- More complex and difficult to learn than Leaflet, with a steeper learning curve
- Heavier and slower than Leaflet, which can affect performance on some devices or networks
- Has a free tier but starts to get expensive at scale

## OpenLayers <a name="openlayers"></a>

- Weekly downloads: over 800,000 (npm trends)
- Open source: Yes
- Behind it: The OpenLayers community and a team of contributors
- GitHub repository: [https://github.com/openlayers/openlayers](https://github.com/openlayers/openlayers)
- In OpenLayers, required functionality is provided by the ol.interaction.Draw class, which allows users to draw vector shapes (including polygons) on the map, and returns the coordinates of those shapes as GeoJSON.

### Pros

- Full-featured and powerful, with a comprehensive set of tools for building complex web mapping applications
- Supports a wide range of data sources and formats, including vector data, WMS services, and GeoJSON
- Offers a high degree of customization and flexibility
- Good documentation and community support
- Has been around for over a decade, making it a mature and stable library
- Popular, with a large user base and strong support from the OpenLayers community

### Cons

- More complex and difficult to learn than Leaflet or Mapbox GL, with a steep learning curve
- Can be heavy and slower than Leaflet or Mapbox GL, especially with many layers or data sources
- Less suitable for smaller or simpler web mapping applications
