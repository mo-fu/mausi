# MAUSI

__Mausi__: short-text processing wrapper around [maui](https://github.com/zelandiya/maui) for subject indexing of economics literature with the [STW Thesaurus for Economics](http://zbw.eu/stw/).
Mausi makes training and application on short texts more convenient and efficient.

Here you can find the current development version.

Written by toem for [ZBW's automatic subject indexing working group](https://www.zbw.eu/de/ueber-uns/arbeitsschwerpunkte/metadatengenerierung/), 2016-2018

## Application

1. Build (package) the app, therefore you have to download the [STW Thesaurus for Economics](http://zbw.eu/stw/) and configure the [pom](pom.xml) accordingly.
1. Finally, adapt and run the control scripts: [link](control).

Training and application are based on simple file formats, in particular tab-separated values.
For details, please have a look at the [basic test class](src/main/java/eu/zbw/a1/mausi/MausiBasicTest.java) and the corresponding 
files [here](src/test/resources).