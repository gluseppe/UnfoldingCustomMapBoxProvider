# UnfoldingCustomMapBoxProvider
A small utility class building on the great Unfolding Maps that allows you to render your mapbox maps with no need to export mbtiles files.
Just put the class in your processing sketch folder and pass the istanciated provider to the unfolding map
Put your map_id and your access token from the mapbox profile and your good to go

map = new UnfoldingMap(this, new CustomMapBoxProvider(MAP_ID,ACCESS_TOKEN));

