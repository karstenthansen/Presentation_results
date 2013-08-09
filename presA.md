---
title       : Aging and Private Label Use
subtitle    : Results 
author      : Karsten T. Hansen, Romana Khan and Vishal Singh
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : prettify  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
ext_widgets     : {rCharts: ["libraries/highcharts", "libraries/nvd3", "libraries/morris", "libraries/dimple", "libraries/Rickshaw"]}           
widgets     : mathjax    #{quiz, bootstrap}
mode        : selfcontained # {standalone, draft,selfcontained}
---



















--- &twocol w1:10% w2:90%

### Two Column Layout   

This slide has two columns

*** left
- point 1
- point 2
- point 3

*** right
- tst

---
### Model
<!-- MotionChart generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Fri Aug 09 10:09:17 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataMotionChartID24d01a481964 () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 "Apples",
2008,
"West",
98,
78,
20,
"2008-12-31" 
],
[
 "Apples",
2009,
"West",
111,
79,
32,
"2009-12-31" 
],
[
 "Apples",
2010,
"West",
89,
76,
13,
"2010-12-31" 
],
[
 "Oranges",
2008,
"East",
96,
81,
15,
"2008-12-31" 
],
[
 "Bananas",
2008,
"East",
85,
76,
9,
"2008-12-31" 
],
[
 "Oranges",
2009,
"East",
93,
80,
13,
"2009-12-31" 
],
[
 "Bananas",
2009,
"East",
94,
78,
16,
"2009-12-31" 
],
[
 "Oranges",
2010,
"East",
98,
91,
7,
"2010-12-31" 
],
[
 "Bananas",
2010,
"East",
81,
71,
10,
"2010-12-31" 
] 
];
data.addColumn('string','Fruit');
data.addColumn('number','Year');
data.addColumn('string','Location');
data.addColumn('number','Sales');
data.addColumn('number','Expenses');
data.addColumn('number','Profit');
data.addColumn('string','Date');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartMotionChartID24d01a481964() {
  var data = gvisDataMotionChartID24d01a481964();
  var options = {};
options["width"] =    550;
options["height"] =    450;

     var chart = new google.visualization.MotionChart(
       document.getElementById('MotionChartID24d01a481964')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  var chartid = "motionchart";

  // Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
  var i, newPackage = true;
  for (i = 0; newPackage && i < pkgs.length; i++) {
    if (pkgs[i] === chartid)
      newPackage = false;
  }
  if (newPackage)
    pkgs.push(chartid);

  // Add the drawChart function to the global list of callbacks
  callbacks.push(drawChartMotionChartID24d01a481964);
})();
function displayChartMotionChartID24d01a481964() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
    var pkgCount = pkgs.length;
    google.load("visualization", "1", { packages:pkgs, callback: function() {
      if (pkgCount != pkgs.length) {
        // Race condition where another setTimeout call snuck in after us; if
        // that call added a package, we must not shift its callback
        return;
      }
      while (callbacks.length > 0)
        callbacks.shift()();
    } });
  }, 100);
}
 
// jsFooter
 </script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartMotionChartID24d01a481964"></script>
 
<!-- divChart -->
  
<div id="MotionChartID24d01a481964"
  style="width: 550px; height: 450px;">
</div>



---
### Age Effects


<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="960px" height="528px" viewBox="0 0 960 528" version="1.1">
  <metadata xmlns:gridsvg="http://www.stat.auckland.ac.nz/~paul/R/gridSVG/">
    <gridsvg:generator name="gridSVG" version="1.3-0" time="2013-08-09 10:09:22"/>
    <gridsvg:argument name="name" value="erase_me.svg"/>
    <gridsvg:argument name="exportCoords" value="none"/>
    <gridsvg:argument name="exportMappings" value="none"/>
    <gridsvg:argument name="exportJS" value="none"/>
    <gridsvg:argument name="res" value="96"/>
    <gridsvg:argument name="prefix" value=""/>
    <gridsvg:argument name="addClasses" value="TRUE"/>
    <gridsvg:argument name="indent" value="TRUE"/>
    <gridsvg:argument name="htmlWrapper" value="FALSE"/>
    <gridsvg:argument name="usePaths" value="vpPaths"/>
    <gridsvg:argument name="uniqueNames" value="TRUE"/>
    <gridsvg:separator name="id.sep" value="."/>
    <gridsvg:separator name="gPath.sep" value="::"/>
    <gridsvg:separator name="vpPath.sep" value="::"/>
  </metadata>
  <g transform="translate(0, 528) scale(1, -1)">
    <g id="gridSVG" fill="none" stroke="rgb(0,0,0)" stroke-dasharray="none" stroke-width="1" font-size="16" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" opacity="1" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" stroke-opacity="1" fill-opacity="0" font-weight="normal" font-style="normal">
      <g id="layout.1" class="pushedvp viewport">
        <g id="GRID.gTableParent.115.1" class="gTableParent gTree grob gDesc">
          <defs>
            <clipPath id="layout::background.1-10-7-1.1.clipPath">
              <rect x="0" y="0" width="960" height="528" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::background.1-10-7-1.1" clip-path="url(#layout::background.1-10-7-1.1.clipPath)" class="pushedvp viewport">
            <g id="background.1-10-7-1.1" class="gTableChild rect grob gDesc">
              <rect id="background.1-10-7-1.1.1" x="0" y="0" width="960" height="528" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
            </g>
          </g>
          <defs>
            <clipPath id="layout::strip-top.3-4-3-4.1.clipPath">
              <rect x="63.65" y="488.2" width="253.84" height="20.6" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::strip-top.3-4-3-4.1" clip-path="url(#layout::strip-top.3-4-3-4.1.clipPath)" class="pushedvp viewport">
            <g id="strip-top.3-4-3-4.1" class="gTableChild absoluteGrob gTree grob gDesc">
              <g id="strip.background.rect.41.1" class="rect grob gDesc">
                <rect id="strip.background.rect.41.1.1" x="63.65" y="488.2" width="253.84" height="20.6" stroke-width="1.42" stroke="none" fill="rgb(204,204,204)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
              </g>
              <g id="strip.text.x.text.38.1" class="text grob gDesc">
                <g id="strip.text.x.text.38.1.1" transform="translate(190.57, 498.5)" stroke-width="0.1">
                  <g id="strip.text.x.text.38.1.1.scale" transform="scale(1, -1)">
                    <text x="0" y="0" id="strip.text.x.text.38.1.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                      <tspan id="strip.text.x.text.38.1.1.tspan.1" dy="5.5" x="0">Female_HH</tspan>
                    </text>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <defs>
            <clipPath id="layout::strip-top.3-6-3-6.1.clipPath">
              <rect x="322.29" y="488.2" width="253.84" height="20.6" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::strip-top.3-6-3-6.1" clip-path="url(#layout::strip-top.3-6-3-6.1.clipPath)" class="pushedvp viewport">
            <g id="strip-top.3-6-3-6.1" class="gTableChild absoluteGrob gTree grob gDesc">
              <g id="strip.background.rect.47.1" class="rect grob gDesc">
                <rect id="strip.background.rect.47.1.1" x="322.29" y="488.2" width="253.84" height="20.6" stroke-width="1.42" stroke="none" fill="rgb(204,204,204)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
              </g>
              <g id="strip.text.x.text.44.1" class="text grob gDesc">
                <g id="strip.text.x.text.44.1.1" transform="translate(449.22, 498.5)" stroke-width="0.1">
                  <g id="strip.text.x.text.44.1.1.scale" transform="scale(1, -1)">
                    <text x="0" y="0" id="strip.text.x.text.44.1.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                      <tspan id="strip.text.x.text.44.1.1.tspan.1" dy="5.5" x="0">Joint_HH</tspan>
                    </text>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <defs>
            <clipPath id="layout::strip-top.3-8-3-8.1.clipPath">
              <rect x="580.94" y="488.2" width="253.84" height="20.6" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::strip-top.3-8-3-8.1" clip-path="url(#layout::strip-top.3-8-3-8.1.clipPath)" class="pushedvp viewport">
            <g id="strip-top.3-8-3-8.1" class="gTableChild absoluteGrob gTree grob gDesc">
              <g id="strip.background.rect.53.1" class="rect grob gDesc">
                <rect id="strip.background.rect.53.1.1" x="580.94" y="488.2" width="253.84" height="20.6" stroke-width="1.42" stroke="none" fill="rgb(204,204,204)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
              </g>
              <g id="strip.text.x.text.50.1" class="text grob gDesc">
                <g id="strip.text.x.text.50.1.1" transform="translate(707.86, 498.5)" stroke-width="0.1">
                  <g id="strip.text.x.text.50.1.1.scale" transform="scale(1, -1)">
                    <text x="0" y="0" id="strip.text.x.text.50.1.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                      <tspan id="strip.text.x.text.50.1.1.tspan.1" dy="5.5" x="0">Male_HH</tspan>
                    </text>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <defs>
            <clipPath id="layout::panel.4-4-4-4.1.clipPath">
              <rect x="63.65" y="52.65" width="253.84" height="435.55" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::panel.4-4-4-4.1" clip-path="url(#layout::panel.4-4-4-4.1.clipPath)" class="pushedvp viewport">
            <g id="panel.4-4-4-4.1" class="gTableChild gTree grob gDesc">
              <g id="grill.gTree.65.1" class="gTree grob gDesc">
                <g id="panel.background.rect.58.1" class="rect grob gDesc">
                  <rect id="panel.background.rect.58.1.1" x="63.65" y="52.65" width="253.84" height="435.55" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                </g>
                <g id="panel.grid.minor.y.polyline.60.1" class="polyline grob gDesc">
                  <polyline id="panel.grid.minor.y.polyline.60.1.1" points="63.65,95.8 317.49,95.8" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.minor.y.polyline.60.1.2" points="63.65,243.77 317.49,243.77" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.minor.y.polyline.60.1.3" points="63.65,391.74 317.49,391.74" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                </g>
                <g id="panel.grid.major.y.polyline.62.1" class="polyline grob gDesc">
                  <polyline id="panel.grid.major.y.polyline.62.1.1" points="63.65,169.78 317.49,169.78" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.y.polyline.62.1.2" points="63.65,317.75 317.49,317.75" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.y.polyline.62.1.3" points="63.65,465.72 317.49,465.72" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                </g>
                <g id="panel.grid.major.x.polyline.64.1" class="polyline grob gDesc">
                  <polyline id="panel.grid.major.x.polyline.64.1.1" points="99.91,52.65 99.91,488.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.64.1.2" points="160.35,52.65 160.35,488.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.64.1.3" points="220.79,52.65 220.79,488.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.64.1.4" points="281.23,52.65 281.23,488.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                </g>
              </g>
              <g id="GRID.polyline.1.1" class="polyline grob gDesc">
                <polyline id="GRID.polyline.1.1.1" points="99.91,351.96 160.35,381.93 220.79,347.39 281.23,291.5" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.2" points="99.91,371.72 160.35,381.43 220.79,352.75 281.23,253.56" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.3" points="99.91,354.42 160.35,368.66 220.79,356.17 281.23,316.72" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.4" points="99.91,353.54 160.35,375.6 220.79,353.77 281.23,290.65" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.5" points="99.91,349.94 160.35,373.09 220.79,347.18 281.23,321.84" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.6" points="99.91,362.75 160.35,382.13 220.79,349.13 281.23,273.96" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.7" points="99.91,351.44 160.35,364.4 220.79,354.52 281.23,311.91" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.8" points="99.91,366.19 160.35,378.79 220.79,346.95 281.23,342.55" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.9" points="99.91,360.34 160.35,369.76 220.79,338.88 281.23,305.93" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.10" points="99.91,353.77 160.35,367.71 220.79,348.09 281.23,309.18" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.11" points="99.91,343.03 160.35,359.48 220.79,342.65 281.23,269.05" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.12" points="99.91,367.43 160.35,385.28 220.79,343.1 281.23,275.71" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.13" points="99.91,358.45 160.35,375.89 220.79,351.57 281.23,280.8" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.14" points="99.91,360.99 160.35,381.82 220.79,347.54 281.23,295.71" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.15" points="99.91,362.59 160.35,377.57 220.79,358.12 281.23,266.86" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.16" points="99.91,360.02 160.35,373.8 220.79,355.68 281.23,304.49" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.17" points="99.91,364.73 160.35,382.36 220.79,344.03 281.23,289.07" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.18" points="99.91,326.73 160.35,323.1 220.79,320.63 281.23,316.34" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.19" points="99.91,318.39 160.35,321.35 220.79,331.47 281.23,335.93" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.20" points="99.91,344.7 160.35,323.06 220.79,305.38 281.23,284.16" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.21" points="99.91,329.57 160.35,341.58 220.79,341.33 281.23,329.07" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.22" points="99.91,330.44 160.35,333.39 220.79,357.57 281.23,368.61" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.23" points="99.91,333.58 160.35,329.85 220.79,326.26 281.23,304" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.24" points="99.91,330.81 160.35,326.98 220.79,320.19 281.23,315.78" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.25" points="99.91,329.6 160.35,330.61 220.79,331.59 281.23,343.38" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.26" points="99.91,343.5 160.35,335.32 220.79,300.31 281.23,279.52" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.27" points="99.91,333.2 160.35,329.22 220.79,332.31 281.23,337.39" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.28" points="99.91,327.14 160.35,329.8 220.79,309.89 281.23,284.91" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.29" points="99.91,331.8 160.35,325.29 220.79,325.03 281.23,326.86" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.30" points="99.91,330.39 160.35,329.45 220.79,326.28 281.23,323.7" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.31" points="99.91,334.88 160.35,333.78 220.79,320.93 281.23,327.93" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.32" points="99.91,318.83 160.35,332.86 220.79,357.39 281.23,376.6" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.33" points="99.91,331.52 160.35,335.32 220.79,347.77 281.23,334.55" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.34" points="99.91,328.01 160.35,336.77 220.79,343.84 281.23,355.6" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.35" points="99.91,333.12 160.35,325.76 220.79,316.82 281.23,330.58" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.36" points="99.91,347.49 160.35,340 220.79,305.05 281.23,289.43" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.37" points="99.91,322.94 160.35,349.49 220.79,367.4 281.23,410.06" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.38" points="99.91,327.96 160.35,341.81 220.79,343.53 281.23,390.03" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.39" points="99.91,325.54 160.35,342.72 220.79,359.02 281.23,364.19" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.40" points="99.91,344.43 160.35,331.41 220.79,289.06 281.23,245.01" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.41" points="99.91,336.53 160.35,338.63 220.79,320.56 281.23,320.1" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.42" points="99.91,338.73 160.35,336.94 220.79,316.3 281.23,287.7" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.43" points="99.91,344.62 160.35,332.49 220.79,312.69 281.23,259.97" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.44" points="99.91,331.79 160.35,334.04 220.79,326.93 281.23,326.25" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.45" points="99.91,344.96 160.35,326.58 220.79,282.09 281.23,228.14" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.46" points="99.91,340.87 160.35,336.23 220.79,328.89 281.23,306.45" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.47" points="99.91,329.97 160.35,331.71 220.79,329.23 281.23,337.83" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.48" points="99.91,333.52 160.35,331.16 220.79,353.66 281.23,349.88" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.49" points="99.91,337.6 160.35,335.15 220.79,317.78 281.23,309.71" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.50" points="99.91,329.78 160.35,336 220.79,331.36 281.23,336.39" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.51" points="99.91,327.81 160.35,338.28 220.79,361.21 281.23,360.96" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.52" points="99.91,334.63 160.35,334.15 220.79,341.72 281.23,349.74" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.53" points="99.91,323.03 160.35,335.19 220.79,334.27 281.23,333.29" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.54" points="99.91,331.38 160.35,341.12 220.79,365.65 281.23,382.05" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.55" points="99.91,337.21 160.35,330.02 220.79,303.58 281.23,276.34" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.56" points="99.91,332.19 160.35,341.5 220.79,340.37 281.23,363.31" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.57" points="99.91,338.13 160.35,333.14 220.79,333.46 281.23,328.41" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.58" points="99.91,339.81 160.35,340.96 220.79,344.86 281.23,323.58" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.59" points="99.91,337.73 160.35,341.79 220.79,336.56 281.23,353.62" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.60" points="99.91,328.22 160.35,333.4 220.79,346.51 281.23,371.28" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.61" points="99.91,335.55 160.35,329.18 220.79,320.54 281.23,309" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.62" points="99.91,335.21 160.35,323.1 220.79,311.07 281.23,296.66" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.63" points="99.91,333.38 160.35,332.75 220.79,330.25 281.23,309.26" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.64" points="99.91,337.45 160.35,325.68 220.79,326.46 281.23,328.49" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.65" points="99.91,332.77 160.35,341.85 220.79,323.27 281.23,302" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.66" points="99.91,337.25 160.35,340.29 220.79,314.62 281.23,283.3" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.67" points="99.91,331.35 160.35,326.31 220.79,331.42 281.23,344.26" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.68" points="99.91,340.06 160.35,336.55 220.79,336.11 281.23,357.3" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.69" points="99.91,330.27 160.35,335.46 220.79,310.91 281.23,359.23" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.70" points="99.91,334.89 160.35,319.96 220.79,301.91 281.23,298.66" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.71" points="99.91,324.58 160.35,328.79 220.79,331.18 281.23,320.77" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.72" points="99.91,339.35 160.35,335.56 220.79,319.42 281.23,296.62" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.73" points="99.91,329.97 160.35,338.07 220.79,365.97 281.23,405" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.74" points="99.91,325.57 160.35,342.59 220.79,363.4 281.23,374.94" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.75" points="99.91,330.48 160.35,333.96 220.79,331.05 281.23,330.78" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.76" points="99.91,334.98 160.35,331.42 220.79,323.49 281.23,328.36" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.77" points="99.91,328.9 160.35,325.48 220.79,305.73 281.23,303.95" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.78" points="99.91,320.76 160.35,323.34 220.79,325.76 281.23,325.28" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.79" points="99.91,330.01 160.35,338.85 220.79,332.63 281.23,355.31" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.80" points="99.91,319.37 160.35,327.32 220.79,327.58 281.23,321.08" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.81" points="99.91,327.87 160.35,325.6 220.79,318.62 281.23,312.7" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.82" points="99.91,327.74 160.35,322.18 220.79,311.93 281.23,288.09" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.83" points="99.91,330.38 160.35,333.2 220.79,337.67 281.23,316.77" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.84" points="99.91,331.95 160.35,322.88 220.79,308.06 281.23,288.43" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.85" points="99.91,329.75 160.35,326.51 220.79,327.2 281.23,329.84" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.86" points="99.91,329.93 160.35,331.85 220.79,328.59 281.23,310.16" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.87" points="99.91,340.66 160.35,325.8 220.79,296.71 281.23,285.94" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.88" points="99.91,334.21 160.35,331.28 220.79,329.74 281.23,291.92" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.89" points="99.91,325.3 160.35,331.41 220.79,339.36 281.23,356.87" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.90" points="99.91,334.74 160.35,336.14 220.79,328.51 281.23,304.25" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.91" points="99.91,329.97 160.35,330.12 220.79,324.2 281.23,304.47" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.92" points="99.91,333.79 160.35,334.36 220.79,352.83 281.23,332.7" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.93" points="99.91,330.97 160.35,337.98 220.79,322.56 281.23,329.59" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.94" points="99.91,324.32 160.35,325.96 220.79,328.87 281.23,325.6" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.95" points="99.91,325.07 160.35,325.12 220.79,327.1 281.23,328.6" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.96" points="99.91,327.91 160.35,334.85 220.79,319.42 281.23,313.5" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.97" points="99.91,325.21 160.35,326.89 220.79,330 281.23,337.15" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.98" points="99.91,327.61 160.35,334.4 220.79,341.92 281.23,343.22" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.99" points="99.91,320.45 160.35,324.04 220.79,316.3 281.23,320.49" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.100" points="99.91,333.76 160.35,332.17 220.79,335.19 281.23,328.61" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.101" points="99.91,322.83 160.35,321.41 220.79,319.77 281.23,315.55" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.102" points="99.91,335.78 160.35,343.59 220.79,334.11 281.23,296.19" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.103" points="99.91,329.28 160.35,329.38 220.79,328.75 281.23,337.38" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.104" points="99.91,333.37 160.35,335.23 220.79,333.59 281.23,328.16" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.105" points="99.91,339.89 160.35,326.86 220.79,321.87 281.23,307.19" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.106" points="99.91,335.6 160.35,329.7 220.79,340.65 281.23,299.72" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.107" points="99.91,323.67 160.35,331.68 220.79,347.78 281.23,344.52" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.108" points="99.91,323.12 160.35,320.22 220.79,317.56 281.23,319.61" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.109" points="99.91,336.7 160.35,340.87 220.79,343.78 281.23,302.04" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.110" points="99.91,327.76 160.35,327.05 220.79,327.25 281.23,319.59" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.111" points="99.91,328.16 160.35,329.31 220.79,332.84 281.23,341.57" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.112" points="99.91,328.45 160.35,330.16 220.79,376.17 281.23,419.89" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.113" points="99.91,324.91 160.35,326.81 220.79,328.93 281.23,319.08" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.114" points="99.91,331.36 160.35,323.49 220.79,317.32 281.23,304.86" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.1.1.115" points="99.91,325.24 160.35,345.59 220.79,357.43 281.23,343.11" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
              </g>
              <g id="hlines.gTree.6.1" class="gTree grob gDesc">
                <g id="GRID.segments.4.1" class="segments grob gDesc">
                  <polyline id="GRID.segments.4.1.1" points="63.65,317.75 317.49,317.75" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                </g>
              </g>
            </g>
          </g>
          <defs>
            <clipPath id="layout::panel.4-6-4-6.1.clipPath">
              <rect x="322.29" y="52.65" width="253.84" height="435.55" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::panel.4-6-4-6.1" clip-path="url(#layout::panel.4-6-4-6.1.clipPath)" class="pushedvp viewport">
            <g id="panel.4-6-4-6.1" class="gTableChild gTree grob gDesc">
              <g id="grill.gTree.77.1" class="gTree grob gDesc">
                <g id="panel.background.rect.70.1" class="rect grob gDesc">
                  <rect id="panel.background.rect.70.1.1" x="322.29" y="52.65" width="253.84" height="435.55" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                </g>
                <g id="panel.grid.minor.y.polyline.72.1" class="polyline grob gDesc">
                  <polyline id="panel.grid.minor.y.polyline.72.1.1" points="322.29,95.8 576.14,95.8" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.minor.y.polyline.72.1.2" points="322.29,243.77 576.14,243.77" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.minor.y.polyline.72.1.3" points="322.29,391.74 576.14,391.74" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                </g>
                <g id="panel.grid.major.y.polyline.74.1" class="polyline grob gDesc">
                  <polyline id="panel.grid.major.y.polyline.74.1.1" points="322.29,169.78 576.14,169.78" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.y.polyline.74.1.2" points="322.29,317.75 576.14,317.75" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.y.polyline.74.1.3" points="322.29,465.72 576.14,465.72" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                </g>
                <g id="panel.grid.major.x.polyline.76.1" class="polyline grob gDesc">
                  <polyline id="panel.grid.major.x.polyline.76.1.1" points="358.56,52.65 358.56,488.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.76.1.2" points="419,52.65 419,488.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.76.1.3" points="479.44,52.65 479.44,488.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.76.1.4" points="539.87,52.65 539.87,488.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                </g>
              </g>
              <g id="GRID.polyline.2.1" class="polyline grob gDesc">
                <polyline id="GRID.polyline.2.1.1" points="358.56,354.77 419,327.24 479.44,319.86 539.87,256.89" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.2" points="358.56,374.75 419,368.23 479.44,325.9 539.87,242.18" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.3" points="358.56,361.54 419,358.04 479.44,340.96 539.87,292.49" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.4" points="358.56,370.06 419,391.64 479.44,357.78 539.87,302.55" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.5" points="358.56,359.3 419,372.76 479.44,351.47 539.87,342.53" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.6" points="358.56,357.17 419,384.08 479.44,307.27 539.87,217.78" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.7" points="358.56,357.48 419,351.91 479.44,326.01 539.87,286.83" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.8" points="358.56,371.55 419,362.28 479.44,346.33 539.87,325.15" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.9" points="358.56,371.81 419,337.88 479.44,313.68 539.87,279.24" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.10" points="358.56,356.09 419,338.58 479.44,338.69 539.87,281.64" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.11" points="358.56,361.04 419,350.89 479.44,282.14 539.87,223.16" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.12" points="358.56,374.77 419,370.61 479.44,337.11 539.87,255.29" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.13" points="358.56,358.49 419,343.1 479.44,318.58 539.87,251.47" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.14" points="358.56,361.42 419,367.34 479.44,323.61 539.87,244.66" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.15" points="358.56,356.8 419,345.1 479.44,339.87 539.87,305.03" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.16" points="358.56,362.49 419,346.51 479.44,302.47 539.87,257.9" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.17" points="358.56,357.98 419,351.27 479.44,280.55 539.87,248.47" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.18" points="358.56,310.68 419,297.78 479.44,284.06 539.87,261.61" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.19" points="358.56,314.44 419,312.74 479.44,318.71 539.87,325.83" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.20" points="358.56,305.91 419,270.46 479.44,222.02 539.87,190.31" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.21" points="358.56,324.78 419,324.78 479.44,285.47 539.87,270.7" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.22" points="358.56,321.84 419,332.82 479.44,342 539.87,366.91" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.23" points="358.56,342.67 419,324.51 479.44,295.55 539.87,277.91" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.24" points="358.56,321.77 419,309.12 479.44,295.51 539.87,291.47" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.25" points="358.56,324.7 419,312.17 479.44,301.33 539.87,312.39" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.26" points="358.56,314.32 419,273.15 479.44,228.24 539.87,198.33" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.27" points="358.56,317.96 419,312.42 479.44,287.33 539.87,279.89" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.28" points="358.56,307.17 419,286.95 479.44,236.87 539.87,198.15" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.29" points="358.56,322.15 419,308.48 479.44,291 539.87,289.96" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.30" points="358.56,319.35 419,307.92 479.44,287.08 539.87,277.77" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.31" points="358.56,304.43 419,267.29 479.44,231.2 539.87,229.79" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.32" points="358.56,324.03 419,333.62 479.44,343.42 539.87,372.75" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.33" points="358.56,328.41 419,337.16 479.44,346.04 539.87,364.44" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.34" points="358.56,319.73 419,321.66 479.44,318.75 539.87,330.03" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.35" points="358.56,310.76 419,287.16 479.44,263.82 539.87,256.96" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.36" points="358.56,340.68 419,263.46 479.44,183.89 539.87,165.23" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.37" points="358.56,296.54 419,337.58 479.44,374.19 539.87,390.03" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.38" points="358.56,330.46 419,322.95 479.44,333.95 539.87,371.88" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.39" points="358.56,343.88 419,389.4 479.44,381.28 539.87,372.14" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.40" points="358.56,323.58 419,277 479.44,208.14 539.87,158.19" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.41" points="358.56,329.53 419,315.28 479.44,289.45 539.87,261.84" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.42" points="358.56,323.11 419,305.97 479.44,256.62 539.87,249.86" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.43" points="358.56,327.5 419,258.18 479.44,191.2 539.87,143.43" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.44" points="358.56,322.33 419,307.21 479.44,291.19 539.87,282.18" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.45" points="358.56,294.72 419,224.58 479.44,128.84 539.87,72.45" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.46" points="358.56,328.71 419,278.6 479.44,215 539.87,181.06" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.47" points="358.56,327.87 419,316.3 479.44,303.95 539.87,308.65" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.48" points="358.56,329.47 419,299.87 479.44,289.62 539.87,300.74" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.49" points="358.56,323.42 419,306.82 479.44,289.6 539.87,286.8" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.50" points="358.56,331.74 419,319.63 479.44,309.29 539.87,319.41" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.51" points="358.56,330.08 419,337.87 479.44,360.42 539.87,377.12" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.52" points="358.56,327.78 419,330.45 479.44,314.38 539.87,328.5" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.53" points="358.56,323.28 419,322.49 479.44,320.02 539.87,327" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.54" points="358.56,320.2 419,336.81 479.44,368.26 539.87,376.99" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.55" points="358.56,319.14 419,297.83 479.44,258.13 539.87,202.97" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.56" points="358.56,312.75 419,291.02 479.44,301.5 539.87,319.14" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.57" points="358.56,306.05 419,296.64 479.44,285.56 539.87,273.15" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.58" points="358.56,324.93 419,323.27 479.44,284.89 539.87,283.85" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.59" points="358.56,344.68 419,326.34 479.44,306.59 539.87,331.19" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.60" points="358.56,329.64 419,369.83 479.44,403.93 539.87,468.4" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.61" points="358.56,321.69 419,310.01 479.44,294.25 539.87,284.61" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.62" points="358.56,321.76 419,300.43 479.44,285.72 539.87,271.55" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.63" points="358.56,313.02 419,296.3 479.44,274.88 539.87,269.24" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.64" points="358.56,304.9 419,291.74 479.44,264.52 539.87,269.25" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.65" points="358.56,327.99 419,318.38 479.44,276.21 539.87,262.67" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.66" points="358.56,323.5 419,310.95 479.44,263.61 539.87,238.72" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.67" points="358.56,325.28 419,315.38 479.44,298.09 539.87,300.38" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.68" points="358.56,336.64 419,329.68 479.44,320.74 539.87,306.1" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.69" points="358.56,322.42 419,319.05 479.44,296.64 539.87,336.29" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.70" points="358.56,323.39 419,286.12 479.44,255.53 539.87,251.21" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.71" points="358.56,326.3 419,305.84 479.44,291.56 539.87,322.99" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.72" points="358.56,322.16 419,304.18 479.44,276.68 539.87,216.33" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.73" points="358.56,329.84 419,357.83 479.44,376.26 539.87,415.75" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.74" points="358.56,332.17 419,359.24 479.44,382.39 539.87,399.7" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.75" points="358.56,325.68 419,327.85 479.44,317.79 539.87,317.37" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.76" points="358.56,322.28 419,312.31 479.44,293.05 539.87,304.84" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.77" points="358.56,319.98 419,320.62 479.44,313.11 539.87,307.6" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.78" points="358.56,324.93 419,321.09 479.44,320.58 539.87,327.02" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.79" points="358.56,331.04 419,344.43 479.44,314.18 539.87,269.26" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.80" points="358.56,323.79 419,330.34 479.44,328.12 539.87,320.16" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.81" points="358.56,324.74 419,313.64 479.44,298.93 539.87,298.71" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.82" points="358.56,321.49 419,310.27 479.44,293.27 539.87,280.59" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.83" points="358.56,334.19 419,339.69 479.44,321.66 539.87,308.08" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.84" points="358.56,319.37 419,298.83 479.44,267.8 539.87,248.86" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.85" points="358.56,320.47 419,300.33 479.44,305.62 539.87,298.67" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.86" points="358.56,333.84 419,322.79 479.44,300.38 539.87,269.86" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.87" points="358.56,328.71 419,290.53 479.44,237.85 539.87,206.82" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.88" points="358.56,321.04 419,319.23 479.44,301.69 539.87,285.04" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.89" points="358.56,323.39 419,335.47 479.44,350.81 539.87,382.52" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.90" points="358.56,326.18 419,307.59 479.44,272.56 539.87,242.28" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.91" points="358.56,319.25 419,321.53 479.44,315.95 539.87,311.04" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.92" points="358.56,362.62 419,369.37 479.44,361.35 539.87,367.16" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.93" points="358.56,331.52 419,316.84 479.44,319.77 539.87,312.92" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.94" points="358.56,319.67 419,327.49 479.44,326.98 539.87,311.86" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.95" points="358.56,322.82 419,314.19 479.44,311.56 539.87,308.52" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.96" points="358.56,336.93 419,322.79 479.44,306.05 539.87,293.57" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.97" points="358.56,319 419,308.07 479.44,307.47 539.87,313.67" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.98" points="358.56,314.52 419,316.85 479.44,327.1 539.87,360.63" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.99" points="358.56,327.67 419,330.75 479.44,333.41 539.87,346.83" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.100" points="358.56,356.01 419,385.96 479.44,363.17 539.87,415.73" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.101" points="358.56,322.31 419,318.57 479.44,316.13 539.87,315.95" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.102" points="358.56,355.97 419,374.38 479.44,337.64 539.87,301.81" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.103" points="358.56,323.25 419,310.06 479.44,284.16 539.87,307.07" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.104" points="358.56,330.76 419,322.57 479.44,322.82 539.87,332.73" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.105" points="358.56,325.23 419,341.22 479.44,321.95 539.87,323.98" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.106" points="358.56,327.17 419,316.1 479.44,298.72 539.87,232.16" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.107" points="358.56,309.3 419,313.06 479.44,329.14 539.87,305.59" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.108" points="358.56,318.06 419,308.69 479.44,304.1 539.87,307.91" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.109" points="358.56,345.29 419,352.74 479.44,338.4 539.87,313.51" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.110" points="358.56,316.86 419,315.37 479.44,323.77 539.87,371.82" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.111" points="358.56,330.1 419,338.8 479.44,343.61 539.87,351.88" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.112" points="358.56,327.83 419,341.46 479.44,374.7 539.87,392.31" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.113" points="358.56,328.28 419,330.44 479.44,331.91 539.87,349.52" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.114" points="358.56,330.44 419,315.85 479.44,293.34 539.87,286.24" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.2.1.115" points="358.56,339.18 419,400.52 479.44,425.59 539.87,396.62" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
              </g>
              <g id="hlines.gTree.9.1" class="gTree grob gDesc">
                <g id="GRID.segments.7.1" class="segments grob gDesc">
                  <polyline id="GRID.segments.7.1.1" points="322.29,317.75 576.14,317.75" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                </g>
              </g>
            </g>
          </g>
          <defs>
            <clipPath id="layout::panel.4-8-4-8.1.clipPath">
              <rect x="580.94" y="52.65" width="253.84" height="435.55" fill="none" stroke="none"/>
            </clipPath>
          </defs>
          <g id="layout::panel.4-8-4-8.1" clip-path="url(#layout::panel.4-8-4-8.1.clipPath)" class="pushedvp viewport">
            <g id="panel.4-8-4-8.1" class="gTableChild gTree grob gDesc">
              <g id="grill.gTree.89.1" class="gTree grob gDesc">
                <g id="panel.background.rect.82.1" class="rect grob gDesc">
                  <rect id="panel.background.rect.82.1.1" x="580.94" y="52.65" width="253.84" height="435.55" stroke-width="1.42" stroke="none" fill="rgb(229,229,229)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                </g>
                <g id="panel.grid.minor.y.polyline.84.1" class="polyline grob gDesc">
                  <polyline id="panel.grid.minor.y.polyline.84.1.1" points="580.94,95.8 834.78,95.8" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.minor.y.polyline.84.1.2" points="580.94,243.77 834.78,243.77" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.minor.y.polyline.84.1.3" points="580.94,391.74 834.78,391.74" stroke-width="0.71" stroke="rgb(242,242,242)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                </g>
                <g id="panel.grid.major.y.polyline.86.1" class="polyline grob gDesc">
                  <polyline id="panel.grid.major.y.polyline.86.1.1" points="580.94,169.78 834.78,169.78" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.y.polyline.86.1.2" points="580.94,317.75 834.78,317.75" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.y.polyline.86.1.3" points="580.94,465.72 834.78,465.72" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                </g>
                <g id="panel.grid.major.x.polyline.88.1" class="polyline grob gDesc">
                  <polyline id="panel.grid.major.x.polyline.88.1.1" points="617.2,52.65 617.2,488.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.88.1.2" points="677.64,52.65 677.64,488.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.88.1.3" points="738.08,52.65 738.08,488.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                  <polyline id="panel.grid.major.x.polyline.88.1.4" points="798.52,52.65 798.52,488.2" stroke-width="1.42" stroke="rgb(255,255,255)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                </g>
              </g>
              <g id="GRID.polyline.3.1" class="polyline grob gDesc">
                <polyline id="GRID.polyline.3.1.1" points="617.2,393.73 677.64,366.93 738.08,330.65 798.52,265.95" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.2" points="617.2,419.67 677.64,383.18 738.08,357.37 798.52,255.94" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.3" points="617.2,400.99 677.64,375.93 738.08,355.99 798.52,293.28" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.4" points="617.2,387.71 677.64,385.08 738.08,364.49 798.52,277.58" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.5" points="617.2,393.21 677.64,382.6 738.08,369.07 798.52,307.65" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.6" points="617.2,376.22 677.64,364.41 738.08,339.55 798.52,267.32" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.7" points="617.2,403.43 677.64,387.65 738.08,380.05 798.52,341.37" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.8" points="617.2,406.96 677.64,386.43 738.08,363.07 798.52,299.33" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.9" points="617.2,399.34 677.64,375.31 738.08,354.48 798.52,299.41" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.10" points="617.2,381.27 677.64,365.18 738.08,349.24 798.52,291.73" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.11" points="617.2,381.43 677.64,363.86 738.08,343.8 798.52,248.56" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.12" points="617.2,411.54 677.64,385.97 738.08,360.76 798.52,247.42" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.13" points="617.2,378.28 677.64,368.83 738.08,346.06 798.52,280.18" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.14" points="617.2,385.42 677.64,367.78 738.08,339.43 798.52,259.55" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.15" points="617.2,397.68 677.64,377.01 738.08,353.89 798.52,268.93" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.16" points="617.2,372.67 677.64,369.8 738.08,345.38 798.52,276.69" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.17" points="617.2,373.77 677.64,371.8 738.08,343.05 798.52,256.95" stroke="rgb(0,191,196)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.18" points="617.2,323.83 677.64,321.79 738.08,322.18 798.52,318.84" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.19" points="617.2,321.89 677.64,322.74 738.08,327.1 798.52,337.35" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.20" points="617.2,330.29 677.64,338.31 738.08,354.79 798.52,333.51" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.21" points="617.2,321.96 677.64,339.64 738.08,336.6 798.52,333.59" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.22" points="617.2,325.81 677.64,335.21 738.08,351.44 798.52,392.35" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.23" points="617.2,325.1 677.64,331.42 738.08,336.19 798.52,361.7" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.24" points="617.2,337.31 677.64,330.64 738.08,321.96 798.52,325.61" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.25" points="617.2,318.63 677.64,334.73 738.08,341.47 798.52,356.29" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.26" points="617.2,339.45 677.64,334.16 738.08,318.15 798.52,284.96" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.27" points="617.2,326.82 677.64,333.93 738.08,327.89 798.52,342.72" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.28" points="617.2,355.69 677.64,338.7 738.08,327.58 798.52,307.72" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.29" points="617.2,320.1 677.64,329.8 738.08,340.38 798.52,359.59" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.30" points="617.2,336.92 677.64,337.42 738.08,343.38 798.52,344.57" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.31" points="617.2,337.89 677.64,332.84 738.08,326.12 798.52,328.03" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.32" points="617.2,319.02 677.64,336.82 738.08,370.27 798.52,401.5" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.33" points="617.2,329.21 677.64,331.4 738.08,332.92 798.52,344.53" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.34" points="617.2,338.44 677.64,335.78 738.08,345.78 798.52,372.26" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.35" points="617.2,336.09 677.64,336.61 738.08,323.68 798.52,336.55" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.36" points="617.2,344.24 677.64,335.91 738.08,325.35 798.52,333.5" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.37" points="617.2,332.34 677.64,334.77 738.08,334.63 798.52,355.79" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.38" points="617.2,326.34 677.64,337.8 738.08,334.16 798.52,396.41" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.39" points="617.2,317.25 677.64,335.95 738.08,350.02 798.52,342.88" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.40" points="617.2,356.16 677.64,337.41 738.08,317.71 798.52,275.75" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.41" points="617.2,334.92 677.64,340.14 738.08,321.29 798.52,315.65" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.42" points="617.2,346.16 677.64,336.59 738.08,338.86 798.52,343.57" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.43" points="617.2,334.5 677.64,338.96 738.08,330.9 798.52,320.63" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.44" points="617.2,340.72 677.64,335.52 738.08,319.79 798.52,330.15" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.45" points="617.2,373.18 677.64,333.11 738.08,327.67 798.52,263.31" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.46" points="617.2,344.53 677.64,334.23 738.08,319.95 798.52,331.66" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.47" points="617.2,335.49 677.64,328.9 738.08,330.77 798.52,361.55" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.48" points="617.2,326.13 677.64,335.74 738.08,343.37 798.52,321.3" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.49" points="617.2,345.94 677.64,337.56 738.08,313.43 798.52,312.66" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.50" points="617.2,319.63 677.64,331.51 738.08,344.48 798.52,371.35" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.51" points="617.2,313.15 677.64,335.09 738.08,359.01 798.52,391.48" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.52" points="617.2,324.92 677.64,337.17 738.08,336.7 798.52,366" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.53" points="617.2,325.13 677.64,330.59 738.08,330.52 798.52,334.59" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.54" points="617.2,336.41 677.64,336.44 738.08,359.05 798.52,366.82" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.55" points="617.2,354.97 677.64,330.95 738.08,316.73 798.52,294.26" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.56" points="617.2,344.14 677.64,332.47 738.08,316.2 798.52,358.66" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.57" points="617.2,325.44 677.64,334.63 738.08,340.18 798.52,377.45" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.58" points="617.2,342.66 677.64,329.99 738.08,321.04 798.52,333.57" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.59" points="617.2,318.27 677.64,337.36 738.08,363.32 798.52,390.17" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.60" points="617.2,325.87 677.64,330.97 738.08,350.54 798.52,341.4" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.61" points="617.2,348.02 677.64,329.36 738.08,324.31 798.52,300.58" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.62" points="617.2,345.92 677.64,323.73 738.08,312.75 798.52,296.32" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.63" points="617.2,368.41 677.64,336.92 738.08,313.26 798.52,331.11" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.64" points="617.2,337.7 677.64,339.58 738.08,322.83 798.52,320.17" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.65" points="617.2,372.76 677.64,335.45 738.08,324.94 798.52,275.96" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.66" points="617.2,374.83 677.64,340.2 738.08,330.77 798.52,293.66" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.67" points="617.2,322.18 677.64,337.58 738.08,349.19 798.52,335.86" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.68" points="617.2,324.85 677.64,337.29 738.08,341.38 798.52,369.75" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.69" points="617.2,353.84 677.64,331.36 738.08,323.66 798.52,326.17" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.70" points="617.2,342.81 677.64,334.05 738.08,324.53 798.52,320.67" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.71" points="617.2,330.85 677.64,325.55 738.08,320.26 798.52,335.95" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.72" points="617.2,361.83 677.64,332.55 738.08,323.93 798.52,291.25" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.73" points="617.2,343.72 677.64,331.45 738.08,342.14 798.52,388.39" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.74" points="617.2,329.75 677.64,334.87 738.08,352.33 798.52,343.02" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.75" points="617.2,349.39 677.64,331.76 738.08,322.75 798.52,340.68" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.76" points="617.2,328.81 677.64,324.15 738.08,325.86 798.52,315.34" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.77" points="617.2,336.75 677.64,329.58 738.08,307.41 798.52,290.88" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.78" points="617.2,320.32 677.64,324.07 738.08,328.63 798.52,328.8" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.79" points="617.2,334.63 677.64,330.75 738.08,332.73 798.52,334.95" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.80" points="617.2,318.41 677.64,323.42 738.08,324.15 798.52,322.9" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.81" points="617.2,341.38 677.64,325.97 738.08,322.2 798.52,308.97" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.82" points="617.2,334.74 677.64,329.54 738.08,338.88 798.52,300.93" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.83" points="617.2,326.54 677.64,337.66 738.08,337.48 798.52,319.15" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.84" points="617.2,345.26 677.64,339.35 738.08,331.15 798.52,306.42" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.85" points="617.2,327.96 677.64,329.53 738.08,334.99 798.52,345.01" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.86" points="617.2,329.32 677.64,332.71 738.08,343.46 798.52,332.73" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.87" points="617.2,364.81 677.64,338.3 738.08,310.17 798.52,299.13" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.88" points="617.2,328.2 677.64,331.63 738.08,339.79 798.52,308.09" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.89" points="617.2,319.85 677.64,332.68 738.08,339.32 798.52,364.4" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.90" points="617.2,338.74 677.64,336.55 738.08,335.78 798.52,331.15" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.91" points="617.2,330.93 677.64,328.72 738.08,324.24 798.52,325.23" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.92" points="617.2,332.47 677.64,334.75 738.08,343.33 798.52,360.75" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.93" points="617.2,335.94 677.64,328.83 738.08,340.07 798.52,330.93" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.94" points="617.2,325.42 677.64,325.45 738.08,332.88 798.52,329.06" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.95" points="617.2,323.76 677.64,323.67 738.08,320.57 798.52,322.44" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.96" points="617.2,345.01 677.64,334.96 738.08,306.44 798.52,334.08" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.97" points="617.2,326.37 677.64,329.39 738.08,332.89 798.52,337.77" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.98" points="617.2,333.52 677.64,327.49 738.08,329.56 798.52,323.79" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.99" points="617.2,327.11 677.64,329.24 738.08,339.99 798.52,337.77" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.100" points="617.2,337.7 677.64,336.67 738.08,335.46 798.52,348.61" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.101" points="617.2,322.07 677.64,323.11 738.08,317.76 798.52,316.51" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.102" points="617.2,336.21 677.64,339.89 738.08,338.69 798.52,321.21" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.103" points="617.2,325.9 677.64,325.6 738.08,324.06 798.52,326.53" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.104" points="617.2,345.72 677.64,332.58 738.08,332.02 798.52,324.58" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.105" points="617.2,341.17 677.64,342.32 738.08,340.68 798.52,351.48" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.106" points="617.2,330.01 677.64,327.98 738.08,328 798.52,327.14" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.107" points="617.2,321.05 677.64,333.61 738.08,342.15 798.52,349.8" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.108" points="617.2,320.95 677.64,323.63 738.08,325.51 798.52,321.15" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.109" points="617.2,344.64 677.64,342.74 738.08,344.98 798.52,322.24" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.110" points="617.2,331.16 677.64,325.02 738.08,325.78 798.52,337.24" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.111" points="617.2,328.03 677.64,333.9 738.08,352.75 798.52,345.67" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.112" points="617.2,333.96 677.64,331.63 738.08,325.81 798.52,339.66" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.113" points="617.2,326.12 677.64,325.98 738.08,325.38 798.52,328.14" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.114" points="617.2,329.91 677.64,326.95 738.08,327.55 798.52,341.07" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
                <polyline id="GRID.polyline.3.1.115" points="617.2,324.87 677.64,339.39 738.08,364.34 798.52,359.36" stroke="rgb(248,118,109)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-linejoin="round" stroke-miterlimit="1" stroke-opacity="0.3" fill-opacity="0.3"/>
              </g>
              <g id="hlines.gTree.12.1" class="gTree grob gDesc">
                <g id="GRID.segments.10.1" class="segments grob gDesc">
                  <polyline id="GRID.segments.10.1.1" points="580.94,317.75 834.78,317.75" stroke="rgb(0,0,0)" fill="none" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill-opacity="1"/>
                </g>
              </g>
            </g>
          </g>
          <g id="layout::axis-l.4-3-4-3.1" class="pushedvp viewport">
            <g id="layout::axis-l.4-3-4-3::GRID.VP.4.1" class="pushedvp viewport">
              <g id="axis-l.4-3-4-3.1" class="gTableChild absoluteGrob gTree grob gDesc">
                <g id="layout::axis-l.4-3-4-3::GRID.VP.4::axis.1" class="pushedvp viewport">
                  <g id="GRID.gTableParent.128.1" class="gTableParent gTree grob gDesc">
                    <g id="layout::axis-l.4-3-4-3::GRID.VP.4::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                      <g id="axis.1-1-1-1.1" class="gTableChild text grob gDesc">
                        <g id="axis.1-1-1-1.1.1" transform="translate(54.2, 169.78)" stroke-width="0.1">
                          <g id="axis.1-1-1-1.1.1.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.1-1-1-1.1.1.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.1-1-1-1.1.1.tspan.1" dy="5.5" x="0">-0.1</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.1-1-1-1.1.2" transform="translate(54.2, 317.75)" stroke-width="0.1">
                          <g id="axis.1-1-1-1.1.2.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.1-1-1-1.1.2.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.1-1-1-1.1.2.tspan.1" dy="5.5" x="0">0.0</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.1-1-1-1.1.3" transform="translate(54.2, 465.72)" stroke-width="0.1">
                          <g id="axis.1-1-1-1.1.3.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.1-1-1-1.1.3.text" text-anchor="end" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.1-1-1-1.1.3.tspan.1" dy="5.5" x="0">0.1</tspan>
                            </text>
                          </g>
                        </g>
                      </g>
                    </g>
                    <g id="layout::axis-l.4-3-4-3::GRID.VP.4::axis::axis.1-2-1-2.1" class="pushedvp viewport">
                      <g id="axis.1-2-1-2.1" class="gTableChild polyline grob gDesc">
                        <polyline id="axis.1-2-1-2.1.1" points="57.98,169.78 63.65,169.78" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-2-1-2.1.2" points="57.98,317.75 63.65,317.75" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-2-1-2.1.3" points="57.98,465.72 63.65,465.72" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <g id="layout::axis-b.5-4-5-4.1" class="pushedvp viewport">
            <g id="layout::axis-b.5-4-5-4::GRID.VP.1.1" class="pushedvp viewport">
              <g id="axis-b.5-4-5-4.1" class="gTableChild absoluteGrob gTree grob gDesc">
                <g id="layout::axis-b.5-4-5-4::GRID.VP.1::axis.1" class="pushedvp viewport">
                  <g id="GRID.gTableParent.133.1" class="gTableParent gTree grob gDesc">
                    <g id="layout::axis-b.5-4-5-4::GRID.VP.1::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                      <g id="axis.1-1-1-1.2" class="gTableChild polyline grob gDesc">
                        <polyline id="axis.1-1-1-1.2.1" points="99.91,46.98 99.91,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.2" points="160.35,46.98 160.35,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.3" points="220.79,46.98 220.79,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.2.4" points="281.23,46.98 281.23,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      </g>
                    </g>
                    <g id="layout::axis-b.5-4-5-4::GRID.VP.1::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                      <g id="axis.2-1-2-1.1" class="gTableChild text grob gDesc">
                        <g id="axis.2-1-2-1.1.1" transform="translate(99.91, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.1.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.1.tspan.1" dy="11" x="0">35-44</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.2" transform="translate(160.35, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.2.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.2.tspan.1" dy="11" x="0">45-54</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.3" transform="translate(220.79, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.3.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.3.tspan.1" dy="11" x="0">55-64</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.1.4" transform="translate(281.23, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.1.4.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.1.4.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.1.4.tspan.1" dy="11" x="0">65+</tspan>
                            </text>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <g id="layout::axis-b.5-6-5-6.1" class="pushedvp viewport">
            <g id="layout::axis-b.5-6-5-6::GRID.VP.2.1" class="pushedvp viewport">
              <g id="axis-b.5-6-5-6.1" class="gTableChild absoluteGrob gTree grob gDesc">
                <g id="layout::axis-b.5-6-5-6::GRID.VP.2::axis.1" class="pushedvp viewport">
                  <g id="GRID.gTableParent.139.1" class="gTableParent gTree grob gDesc">
                    <g id="layout::axis-b.5-6-5-6::GRID.VP.2::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                      <g id="axis.1-1-1-1.3" class="gTableChild polyline grob gDesc">
                        <polyline id="axis.1-1-1-1.3.1" points="358.56,46.98 358.56,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.3.2" points="419,46.98 419,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.3.3" points="479.44,46.98 479.44,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.3.4" points="539.87,46.98 539.87,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      </g>
                    </g>
                    <g id="layout::axis-b.5-6-5-6::GRID.VP.2::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                      <g id="axis.2-1-2-1.2" class="gTableChild text grob gDesc">
                        <g id="axis.2-1-2-1.2.1" transform="translate(358.56, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.2.1.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.2.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.2.1.tspan.1" dy="11" x="0">35-44</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.2.2" transform="translate(419, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.2.2.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.2.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.2.2.tspan.1" dy="11" x="0">45-54</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.2.3" transform="translate(479.44, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.2.3.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.2.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.2.3.tspan.1" dy="11" x="0">55-64</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.2.4" transform="translate(539.87, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.2.4.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.2.4.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.2.4.tspan.1" dy="11" x="0">65+</tspan>
                            </text>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <g id="layout::axis-b.5-8-5-8.1" class="pushedvp viewport">
            <g id="layout::axis-b.5-8-5-8::GRID.VP.3.1" class="pushedvp viewport">
              <g id="axis-b.5-8-5-8.1" class="gTableChild absoluteGrob gTree grob gDesc">
                <g id="layout::axis-b.5-8-5-8::GRID.VP.3::axis.1" class="pushedvp viewport">
                  <g id="GRID.gTableParent.145.1" class="gTableParent gTree grob gDesc">
                    <g id="layout::axis-b.5-8-5-8::GRID.VP.3::axis::axis.1-1-1-1.1" class="pushedvp viewport">
                      <g id="axis.1-1-1-1.4" class="gTableChild polyline grob gDesc">
                        <polyline id="axis.1-1-1-1.4.1" points="617.2,46.98 617.2,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.4.2" points="677.64,46.98 677.64,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.4.3" points="738.08,46.98 738.08,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                        <polyline id="axis.1-1-1-1.4.4" points="798.52,46.98 798.52,52.65" stroke-width="1.42" stroke="rgb(127,127,127)" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="1" fill="none"/>
                      </g>
                    </g>
                    <g id="layout::axis-b.5-8-5-8::GRID.VP.3::axis::axis.2-1-2-1.1" class="pushedvp viewport">
                      <g id="axis.2-1-2-1.3" class="gTableChild text grob gDesc">
                        <g id="axis.2-1-2-1.3.1" transform="translate(617.2, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.3.1.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.3.1.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.3.1.tspan.1" dy="11" x="0">35-44</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.3.2" transform="translate(677.64, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.3.2.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.3.2.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.3.2.tspan.1" dy="11" x="0">45-54</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.3.3" transform="translate(738.08, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.3.3.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.3.3.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.3.3.tspan.1" dy="11" x="0">55-64</tspan>
                            </text>
                          </g>
                        </g>
                        <g id="axis.2-1-2-1.3.4" transform="translate(798.52, 43.2)" stroke-width="0.1">
                          <g id="axis.2-1-2-1.3.4.scale" transform="scale(1, -1)">
                            <text x="0" y="0" id="axis.2-1-2-1.3.4.text" text-anchor="middle" font-size="12.8" stroke="rgb(127,127,127)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(127,127,127)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                              <tspan id="axis.2-1-2-1.3.4.tspan.1" dy="11" x="0">65+</tspan>
                            </text>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <g id="layout::xlab.6-8-6-4.1" class="pushedvp viewport">
            <g id="xlab.6-8-6-4.1" class="gTableChild text grob gDesc">
              <g id="xlab.6-8-6-4.1.1" transform="translate(449.22, 20.9)" stroke-width="0.1">
                <g id="xlab.6-8-6-4.1.1.scale" transform="scale(1, -1)">
                  <text x="0" y="0" id="xlab.6-8-6-4.1.1.text" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                    <tspan id="xlab.6-8-6-4.1.1.tspan.1" dy="6.5" x="0">Effect2</tspan>
                  </text>
                </g>
              </g>
            </g>
          </g>
          <g id="layout::ylab.4-2-4-2.1" class="pushedvp viewport">
            <g id="ylab.4-2-4-2.1" class="gTableChild text grob gDesc">
              <g id="ylab.4-2-4-2.1.1" transform="translate(20.9, 270.42)" stroke-width="0.1">
                <g id="ylab.4-2-4-2.1.1.scale" transform="scale(1, -1)">
                  <text x="0" y="0" id="ylab.4-2-4-2.1.1.text" transform="rotate(-90)" text-anchor="middle" font-size="16" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                    <tspan id="ylab.4-2-4-2.1.1.tspan.1" dy="6.5" x="0">mean</tspan>
                  </text>
                </g>
              </g>
            </g>
          </g>
          <g id="layout::guide-box.4-9-4-9.1" class="pushedvp viewport">
            <g id="layout::guide-box.4-9-4-9::guide-box.4-9-4-9.1" class="pushedvp viewport">
              <g id="layout::guide-box.4-9-4-9::guide-box.4-9-4-9::guide-box.4-9-4-9.1" class="pushedvp viewport">
                <g id="GRID.gTableChild.155.1" class="gTableChild gTableParent gTree grob gDesc">
                  <g id="layout::guide-box.4-9-4-9::guide-box.4-9-4-9::guide-box.4-9-4-9::guides.2-2-2-2.1" class="pushedvp viewport">
                    <g id="layout::guide-box.4-9-4-9::guide-box.4-9-4-9::guide-box.4-9-4-9::guides.2-2-2-2::guides.2-2-2-2.1" class="pushedvp viewport">
                      <g id="layout::guide-box.4-9-4-9::guide-box.4-9-4-9::guide-box.4-9-4-9::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2.1" class="pushedvp viewport">
                        <g id="GRID.gTableChild.156.1" class="gTableChild gTableParent gTree grob gDesc">
                          <g id="layout::guide-box.4-9-4-9::guide-box.4-9-4-9::guide-box.4-9-4-9::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::background.1-6-6-1.1" class="pushedvp viewport">
                            <g id="background.1-6-6-1.1" class="gTableChild rect grob gDesc">
                              <rect id="background.1-6-6-1.1.1" x="848.16" y="233.34" width="79.26" height="74.18" stroke-width="1.42" stroke="none" fill="rgb(255,255,255)" stroke-dasharray="none" stroke-opacity="0" fill-opacity="1"/>
                            </g>
                          </g>
                          <g id="layout::guide-box.4-9-4-9::guide-box.4-9-4-9::guide-box.4-9-4-9::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::title.2-5-2-2.1" class="pushedvp viewport">
                            <g id="title.2-5-2-2.1" class="gTableChild text grob gDesc">
                              <g id="title.2-5-2-2.1.1" transform="translate(853.83, 296.34)" stroke-width="0.1">
                                <g id="title.2-5-2-2.1.1.scale" transform="scale(1, -1)">
                                  <text x="0" y="0" id="title.2-5-2-2.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="bold" font-style="normal">
                                    <tspan id="title.2-5-2-2.1.1.tspan.1" dy="5.5" x="0">medicine</tspan>
                                  </text>
                                </g>
                              </g>
                            </g>
                          </g>
                          <g id="layout::guide-box.4-9-4-9::guide-box.4-9-4-9::guide-box.4-9-4-9::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-3-1-bg.4-2-4-2.1" class="pushedvp viewport">
                            <g id="key-3-1-bg.4-2-4-2.1" class="gTableChild rect grob gDesc">
                              <rect id="key-3-1-bg.4-2-4-2.1.1" x="853.83" y="262.04" width="23.04" height="23.04" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(242,242,242)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                            </g>
                          </g>
                          <g id="layout::guide-box.4-9-4-9::guide-box.4-9-4-9::guide-box.4-9-4-9::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-3-1-1.4-2-4-2.1" class="pushedvp viewport">
                            <g id="key-3-1-1.4-2-4-2.1" class="gTableChild segments grob gDesc">
                              <polyline id="key-3-1-1.4-2-4-2.1.1" points="856.14,273.56 874.57,273.56" stroke="rgb(248,118,109)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="0.3" fill="none"/>
                            </g>
                          </g>
                          <g id="layout::guide-box.4-9-4-9::guide-box.4-9-4-9::guide-box.4-9-4-9::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-4-1-bg.5-2-5-2.1" class="pushedvp viewport">
                            <g id="key-4-1-bg.5-2-5-2.1" class="gTableChild rect grob gDesc">
                              <rect id="key-4-1-bg.5-2-5-2.1.1" x="853.83" y="239" width="23.04" height="23.04" stroke-width="1.42" stroke="rgb(255,255,255)" fill="rgb(242,242,242)" stroke-dasharray="none" stroke-opacity="1" fill-opacity="1"/>
                            </g>
                          </g>
                          <g id="layout::guide-box.4-9-4-9::guide-box.4-9-4-9::guide-box.4-9-4-9::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::key-4-1-1.5-2-5-2.1" class="pushedvp viewport">
                            <g id="key-4-1-1.5-2-5-2.1" class="gTableChild segments grob gDesc">
                              <polyline id="key-4-1-1.5-2-5-2.1.1" points="856.14,250.52 874.57,250.52" stroke="rgb(0,191,196)" stroke-width="1.42" stroke-dasharray="none" stroke-linecap="butt" stroke-opacity="0.3" fill="none"/>
                            </g>
                          </g>
                          <g id="layout::guide-box.4-9-4-9::guide-box.4-9-4-9::guide-box.4-9-4-9::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::label-3-3.4-4-4-4.1" class="pushedvp viewport">
                            <g id="label-3-3.4-4-4-4.1" class="gTableChild text grob gDesc">
                              <g id="label-3-3.4-4-4-4.1.1" transform="translate(879.75, 273.56)" stroke-width="0.1">
                                <g id="label-3-3.4-4-4-4.1.1.scale" transform="scale(1, -1)">
                                  <text x="0" y="0" id="label-3-3.4-4-4-4.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                    <tspan id="label-3-3.4-4-4-4.1.1.tspan.1" dy="5.5" x="0">FALSE</tspan>
                                  </text>
                                </g>
                              </g>
                            </g>
                          </g>
                          <g id="layout::guide-box.4-9-4-9::guide-box.4-9-4-9::guide-box.4-9-4-9::guides.2-2-2-2::guides.2-2-2-2::guides.2-2-2-2::label-4-3.5-4-5-4.1" class="pushedvp viewport">
                            <g id="label-4-3.5-4-5-4.1" class="gTableChild text grob gDesc">
                              <g id="label-4-3.5-4-5-4.1.1" transform="translate(879.75, 250.52)" stroke-width="0.1">
                                <g id="label-4-3.5-4-5-4.1.1.scale" transform="scale(1, -1)">
                                  <text x="0" y="0" id="label-4-3.5-4-5-4.1.1.text" text-anchor="start" font-size="12.8" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                                    <tspan id="label-4-3.5-4-5-4.1.1.tspan.1" dy="5.5" x="0">TRUE</tspan>
                                  </text>
                                </g>
                              </g>
                            </g>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
          <g id="layout::title.2-8-2-4.1" class="pushedvp viewport">
            <g id="title.2-8-2-4.1" class="gTableChild text grob gDesc">
              <g id="title.2-8-2-4.1.1" transform="translate(449.22, 508.8)" stroke-width="0.1">
                <g id="title.2-8-2-4.1.1.scale" transform="scale(1, -1)">
                  <text x="0" y="0" id="title.2-8-2-4.1.1.text" text-anchor="middle" font-size="19.2" stroke="rgb(0,0,0)" font-family="Helvetica, Arial, FreeSans, Liberation Sans, Nimbus Sans L, sans-serif" fill="rgb(0,0,0)" stroke-opacity="1" fill-opacity="1" font-weight="normal" font-style="normal">
                    <tspan id="title.2-8-2-4.1.1.tspan.1" dy="7.5" x="0"> </tspan>
                  </text>
                </g>
              </g>
            </g>
          </g>
        </g>
      </g>
    </g>
  </g>
</svg>


---
### Google Line Chart
<!-- LineChart generated in R 3.0.1 by googleVis 0.4.3 package -->
<!-- Fri Aug 09 10:09:23 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataLineChartID24d06acc1644 () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 "US",
10,
23 
],
[
 "GB",
13,
12 
],
[
 "BR",
14,
32 
] 
];
data.addColumn('string','country');
data.addColumn('number','val1');
data.addColumn('number','val2');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartLineChartID24d06acc1644() {
  var data = gvisDataLineChartID24d06acc1644();
  var options = {};
options["allowHtml"] = true;
options["title"] = "Hello World";
options["titleTextStyle"] = {color:'red', 
                                           fontName:'Courier', 
                                           fontSize:16};
options["backgroundColor"] = "#D3D3D3";
options["vAxis"] = {gridlines:{color:'red', count:3}};
options["hAxis"] = {title:'Country', titleTextStyle:{color:'blue'}};
options["series"] = [{color:'green', targetAxisIndex: 0}, 
                                   {color: 'orange',targetAxisIndex:1}];
options["vAxes"] = [{title:'val1'}, {title:'val2'}];
options["legend"] = "bottom";
options["curveType"] = "function";
options["width"] =    500;
options["height"] =    300;

     var chart = new google.visualization.LineChart(
       document.getElementById('LineChartID24d06acc1644')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  var chartid = "corechart";

  // Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
  var i, newPackage = true;
  for (i = 0; newPackage && i < pkgs.length; i++) {
    if (pkgs[i] === chartid)
      newPackage = false;
  }
  if (newPackage)
    pkgs.push(chartid);

  // Add the drawChart function to the global list of callbacks
  callbacks.push(drawChartLineChartID24d06acc1644);
})();
function displayChartLineChartID24d06acc1644() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
    var pkgCount = pkgs.length;
    google.load("visualization", "1", { packages:pkgs, callback: function() {
      if (pkgCount != pkgs.length) {
        // Race condition where another setTimeout call snuck in after us; if
        // that call added a package, we must not shift its callback
        return;
      }
      while (callbacks.length > 0)
        callbacks.shift()();
    } });
  }, 100);
}
 
// jsFooter
 </script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartLineChartID24d06acc1644"></script>
 
<!-- divChart -->
  
<div id="LineChartID24d06acc1644"
  style="width: 500px; height: 300px;">
</div>



