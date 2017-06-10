Forked from:

* https://github.com/infographicstw/example/tree/gh-pages/502
* https://github.com/jason2506/Taiwan.TopoJSON

原始 SHP 檔案的出處:

* 縣市 (county) http://data.gov.tw/node/7442
* 鄉鎮 (town) http://data.gov.tw/node/7441
* 村里 (village) http://data.gov.tw/node/7440

讀取 SHP 檔並輸出成 GeoJSON 格式

```
npm install topojson
topojson -s 0.0000001 -o county.json -p --shapefile-encoding big5 county.shp
topojson -s 0.0000001 -o town.json -p --shapefile-encoding big5 town.shp
topojson -s 0.0000001 -o village.json -p --shapefile-encoding big5 village.shp
```

d3js scale, transform and translate

* https://stackoverflow.com/questions/13274151/d3js-scale-transform-and-translate
