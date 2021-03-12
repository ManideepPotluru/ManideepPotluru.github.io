# Navajo Nation Water Quality Interactive Map

# Dr. Yang comments and suggestions

* 3/1/2021 (Minor suggestions for your alpha submission)
  * It is nice you have the scroll function implemented for the popup, to make it more readable, I would suggestion the following: (1) add a blank line between "WELL INFORMATION- NAVAJO NATION WELL" and the first popup item (i.e., FID), (2) bold the header name (e.g., "FID:", "well_no:") for each popup item, and add a space after the ":", and remove the ";" at the end, (e.g., "FID:743;" to  "**FID:** 743"). Also, I would suggest you  remove the "OBJECTID:", as I do not think they give useful info.
  * Nice looking About modal, well done. One minor suggestion here, change "About this Website:" to "ABout This Project:" or "About this Web Map App", as it is not simple a website, it is an interactive web app.


# Examples of interactive plots:
1. Overall layout, including histograms, data-table and crossfilter.js:
Austin Lyons "Dc.js Leaflet Untapped"
https://github.com/austinlyons/dcjs-leaflet-untappd

2. Scatterplot Matrix Brushing in dc.js 
https://dc-js.github.io/dc.js/examples/splom.html

3. heatmap examples using dc.js
    * https://dc-js.github.io/dc.js/examples/heatmap-filtering.html. (this example used d3v6 as well)
    * https://stackoverflow.com/questions/51122700/dc-js-rectangular-brush-for-heat-map. (working fiddleJS demo for this post: https://jsfiddle.net/gordonwoodhull/bs9to0hd/8/)

4. dc.js DataTable download example
http://dc-js.github.io/dc.js/examples/download-table.html


5. Correlogram:
Harry Stevens Correlation Matrix
https://bl.ocks.org/HarryStevens/302d078a089caf5aeb13e480b86fdaeb


# Dr. Yang added resources about dealing with differnt d3 versions
* D3 API reference:
  * https://github.com/d3/d3/blob/master/API.md
    * For changes between major versions, see [CHANGES](https://github.com/d3/d3/blob/master/CHANGES.md); see also the [release notes](https://github.com/d3/d3/releases) and the [3.x reference](https://github.com/d3/d3-3.x-api-reference/blob/master/API-Reference.md).
* load multiple d3 version in one html file *(this might be one solution, but maybe not, because dc.js is based on d3.js, so it is not just a simply include different d3 version in one html file)*
  * https://stackoverflow.com/questions/16156445/multiple-versions-of-a-script-on-the-same-page-d3-js
  * https://stackoverflow.com/questions/44173693/using-different-d3-versions-on-same-html-page
  * https://chewett.co.uk/blog/2021/how-to-load-multiple-d3-versions-at-once/

* if the conversion is too much work, then maybe we can consider to use heatmap, instead of scatterplot matrix (this is just a back up plan), see below for some heatmap examples using dc.js
  * https://dc-js.github.io/dc.js/examples/heatmap-filtering.html
  * https://stackoverflow.com/questions/51122700/dc-js-rectangular-brush-for-heat-map. (working fiddleJS demo for this post: https://jsfiddle.net/gordonwoodhull/bs9to0hd/8/)
 

