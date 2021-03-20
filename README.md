# Ile-de-france Mobility Stylesheet 

A CSS stylesheet which displays Train, Subway, Bus and Tramway signs of Paris and its suburb. This repository is unofficial but based on the official [IDFM guidelines](https://data.iledefrance-mobilites.fr/pages/chartes-et-prescriptions/). This stylesheet aims to be light and easy to use with a similar render than SVG.

![](example.png)

## 1. Import the stylesheet

The library is divided into two files:

- `font.min.css` is used to import the necessary _Parisian_ font which is used for subway and train signs. The _IDF Voyageur_ font is used for tramway and bus signs;
- `signs.min.css` contains all rules related to colours and layout.

To use the library, add the stylesheets at your project:

	<link href="stylesheets/fonts.min.css" type="text/css">
	<link href="stylesheets/signs.min.css" type="text/css">
	
## 2. Display the route

The attribute `route` is use display the content and the style of the route image. 

	<div route="240"></div>
