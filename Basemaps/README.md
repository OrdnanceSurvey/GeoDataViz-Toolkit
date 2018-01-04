## GeoDataViz Toolkit - Basemaps

Often referred to as a contextual or backdrop map, a basemap contains reference information used to both orient the map and add context to any data that is overlaid. Basemaps come in a variety of types, styles, and scales, from full detail to understated ‘background’ styles.

_This repository contains the colour values for the OS range of basemap styles and some information regarding the use of them. Use these colours to style up your own vector data._

## The OS range of basemap styles

We have created four house styles for our basemaps:

**Road:** A familiar style with a focus on transport networks - specifically highlighting the Great British road network. High in contrast with lots of detail and colour, this style will fit many uses and satisfy those who are familiar with traditional OS maps.

**Outdoor:** Designed for outdoor leisure and used within our OS Maps desktop and mobile application. Borrowing certain design elements from our traditional paper maps this style focusses on terrain and land cover, has a minimal colour palette and contains familiar symbology.

**Light:** Designed specifically for data visualisation, this style has a subtle palette and is simple and clear. Use it to add geographic context and make your own data shine.

**Night:** Night mode mapping that&#39;s great in dark environments. It&#39;s at its best on a mobile device, and the dark pixels can help save your battery. See your own data really pop using this style.

![OS basemap styles](https://raw.githubusercontent.com/OrdnanceSurvey/GeoDataViz-Toolkit/master/img/os-basemap-styles.gif?token=AF3wjbzATJxMRVi8_JehUx0Gd6JiNdXMks5Z-acjwA%3D%3D)

## Selecting the right basemap style

If you are not intending to add any data overlays then use the **Road** style. If your application is Leisure focused or if the road network is of particular importance then you should use **Outdoor**. If you want to overlay additional layers of data and you are looking for a basemap to simply add context then you should use **Light** or **Night** – the decision as to which is purely an aesthetic one however, using a dark basemap can be arguably more &#39;eye-catching&#39;, yet Light can be more &#39;practical&#39;.

_The colours we use have been tested for accessibility and all maintain a clear visual hierarchy._

## OS Maps API

All of these basemaps are available through the [OS Maps API](https://developer.ordnancesurvey.co.uk/os-maps-api-enterprise). 
More information and the documentation can be found [here](https://apidocs.os.uk/docs/os-maps-overview).

## Raster or Vector

If you are using a **raster** basemap then you have less control over the styling. You can still improve it by desaturating the colours or even converting it to greyscale.

If you are using **vector** data to design your own basemap then you have full control over the content and the style. Feel free to use the colours provided in this repository or tweak them to meet your own requirements. We have a range of [cartographic stylesheets](https://www.ordnancesurvey.co.uk/resources/carto-design/cartographic-stylesheets.html) that can help you get started when using OS data products.

## Other useful resources

[Effective basemaps](https://www.ordnancesurvey.co.uk/blog/2017/12/effective-basemaps/) - this blog post explores the options available and shares some useful tips for presenting your contextual data effectively.

## Feedback

If you have any feedback about these basemap colour values or the OS Maps API then please raise an issue on this repository.

Thank you

OS GeoDataViz team
