# Awesome Dataviz with stars

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 527,769 | 🐛 105 | 📅 2026-09-02 ![Test](https://github.com/hal9ai/awesome-dataviz/actions/workflows/main.yaml/badge.svg)

A curated list of awesome **open-source** data visualizations frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python) ⭐ 331,510 | 🐛 23 | 🌐 Python | 📅 2026-10-29 and originally created by [fasouto](https://github.com/fasouto).

Browse it at **[awesomedataviz.com](https://awesomedataviz.com)**: search, rankings, live GitHub stats, comparisons and an MCP server for AI assistants, all generated from this README.

## Contents

* [Awesome dataviz](#awesome-dataviz)
  * [JavaScript tools](#javascript-tools)
    * [Charting libraries](#charting-libraries)
    * [Charting libraries for graphs](#charting-libraries-for-graphs)
    * [Financial charts](#financial-charts)
    * [Maps](#maps)
    * [d3](#d3)
    * [React](#react)
    * [React Native](#react-native)
    * [Misc](#misc)
  * [Android tools](#android-tools)
  * [C++ tools](#c-tools)
  * [Dashboards and BI](#dashboards-and-bi)
  * [Flutter tools](#flutter-tools)
  * [Golang tools](#golang-tools)
  * [iOS tools](#ios-tools)
  * [Julia tools](#julia-tools)
  * [JVM tools](#jvm-tools)
  * [Machine Learning tools](#machine-learning-tools)
  * [.NET tools](#net-tools)
  * [Python tools](#python-tools)
    * [Core plotting libraries](#core-plotting-libraries)
    * [Matplotlib extensions](#matplotlib-extensions)
    * [Grammar of graphics and declarative](#grammar-of-graphics-and-declarative)
    * [Interactive web charts](#interactive-web-charts)
    * [Dashboards and data apps](#dashboards-and-data-apps)
    * [Exploratory data analysis and profiling](#exploratory-data-analysis-and-profiling)
    * [Maps and geospatial](#maps-and-geospatial)
    * [3D and scientific visualization](#3d-and-scientific-visualization)
    * [High-performance and GPU](#high-performance-and-gpu)
    * [Robotics and computer vision](#robotics-and-computer-vision)
    * [Finance and trading](#finance-and-trading)
    * [Terminal plotting](#terminal-plotting)
    * [Text visualization](#text-visualization)
  * [R tools](#r-tools)
  * [Ruby tools](#ruby-tools)
  * [Rust tools](#rust-tools)
  * [Markup-based tools](#markup-based-tools)
  * [Other tools](#other-tools)
* [Resources](#resources)
  * [Books](#books)
  * [Catalogs](#catalogs)
  * [Podcasts](#podcasts)
  * [Twitter accounts](#twitter-accounts)
  * [Websites](#websites)
* [Contributing](#contributing)
* [Contributors](#contributors)
* [License](#license)

## JavaScript tools

### Charting libraries

* [Apache ECharts](https://github.com/apache/echarts) ⭐ 67,646 | 🐛 1,491 | 🌐 TypeScript | 📅 2026-10-13 - Highly customizable and interactive charts ready for big datasets.
* [Plotly.js](https://github.com/plotly/plotly.js/) ⭐ 18,373 | 🐛 808 | 🌐 JavaScript | 📅 2026-10-29 - Powerful declarative library with support for 20 chart types.
* [Frappe Charts](https://github.com/frappe/charts) ⭐ 15,090 | 🐛 150 | 🌐 JavaScript | 📅 2026-10-19 - Simple, responsive SVG charts with zero dependencies.
* [G2](https://github.com/antvis/G2) ⭐ 12,649 | 🐛 182 | 🌐 TypeScript | 📅 2026-10-28 - An interactive and responsive charting library based on the grammar of graphics, maintained by Alibaba.
* [uPlot](https://github.com/leeoniya/uPlot) ⭐ 10,604 | 🐛 133 | 🌐 JavaScript | 📅 2026-10-30 - Small, fast canvas-based charts for time series, lines, areas, OHLC and bars.
* [C3.js](https://github.com/c3js/c3) ⭐ 9,352 | 🐛 774 | 🌐 JavaScript | 📅 2026-10-20 - D3-based reusable chart library.
* [chart.xkcd](https://github.com/timqian/chart.xkcd) ⭐ 7,870 | 🐛 3 | 🌐 JavaScript | 📅 2026-10-21 - Chart library that renders line, bar, pie and other charts in a hand-drawn xkcd style.
* [dc.js](https://github.com/dc-js/dc.js) ⭐ 7,429 | 🐛 410 | 🌐 JavaScript | 📅 2024-07-31 - Multi-dimensional charting built to work natively with crossfilter.
* [NVD3](https://github.com/novus/nvd3) ⭐ 7,228 | 🐛 565 | 🌐 JavaScript | 📅 2023-09-15 - A reusable charting library written in d3.js.
* [roughViz](https://github.com/jwilber/roughViz) ⭐ 7,166 | 🐛 13 | 🌐 JavaScript | 📅 2024-04-26 - Sketchy, hand-drawn style charts for the browser, based on Rough.js.
* [Charts.css](https://github.com/ChartsCSS/charts.css) ⭐ 6,584 | 🐛 36 | 🌐 HTML | 📅 2026-04-04 - CSS framework that styles HTML tables as charts.
* [heatmap.js](https://github.com/pa7/heatmap.js) ⭐ 6,382 | 🐛 164 | 🌐 JavaScript | 📅 2023-10-31 - Canvas-based library for rendering heatmaps, with plugins for Leaflet and Google Maps.
* [Frappe Gantt](https://github.com/frappe/gantt) ⭐ 6,157 | 🐛 81 | 🌐 JavaScript | 📅 2026-06-18 - Simple, interactive SVG Gantt chart library.
* [billboard.js](https://github.com/naver/billboard.js) ⭐ 6,025 | 🐛 76 | 🌐 TypeScript | 📅 2026-10-27 - Reusable D3.js-based chart library with SVG and Canvas rendering, maintained by NAVER.
* [Flot](https://github.com/flot/flot) ⭐ 5,903 | 🐛 630 | 🌐 JavaScript | 📅 2023-11-08 - jQuery plotting library for line, bar and pie charts with zooming and other interactive features.
* [Observable Plot](https://github.com/observablehq/plot) ⭐ 5,417 | 🐛 351 | 🌐 HTML | 📅 2026-10-30 - A JavaScript library for exploratory data visualization.
* [TOAST UI Chart](https://github.com/nhn/tui.chart) ⚠️ Archived - Complete library with support for legacy browsers.
* [Epoch](https://github.com/epochjs/epoch) ⭐ 4,937 | 🐛 69 | 🌐 HTML | 📅 2019-02-14 - Perfect to create real-time charts.
* [ChartGPU](https://github.com/ChartGPU/ChartGPU) ⭐ 3,263 | 🐛 4 | 🌐 TypeScript | 📅 2026-10-18 - WebGPU charting library for large datasets, real-time streaming and multi-chart dashboards.
* [Cal-Heatmap](https://github.com/wa0x6e/cal-heatmap) ⭐ 3,126 | 🐛 59 | 🌐 TypeScript | 📅 2026-10-27 - Time-series calendar heatmaps, similar to GitHub's contribution graph, built on D3.
* [Unovis](https://github.com/f5/unovis) ⭐ 2,861 | 🐛 112 | 🌐 TypeScript | 📅 2026-10-29 - Modular data visualization framework for React, Angular, Svelte, Vue and vanilla TypeScript, by F5.
* [ECharts GL](https://github.com/ecomfe/echarts-gl) ⭐ 2,711 | 🐛 359 | 🌐 JavaScript | 📅 2026-06-24 - Extension for Apache ECharts that adds 3D plots, globe visualizations and WebGL-accelerated series.
* [Vizzu](https://github.com/vizzuhq/vizzu-lib) ⭐ 2,047 | 🐛 3 | 🌐 JavaScript | 📅 2026-04-20 - Library for animated data visualizations and data stories.
* [DHTMLX Gantt](https://github.com/DHTMLX/gantt) ⭐ 1,867 | 🐛 6 | 🌐 JavaScript | 📅 2026-09-03 - Gantt chart component for project schedules, with task dependencies and drag-and-drop editing.
* [VChart](https://github.com/VisActor/VChart) ⭐ 1,854 | 🐛 229 | 🌐 TypeScript | 📅 2026-10-30 - Cross-platform charting library with animation and storytelling features, from ByteDance's VisActor.
* [Carbon Charts](https://github.com/carbon-design-system/carbon-charts) ⭐ 1,055 | 🐛 278 | 🌐 HTML | 📅 2026-10-29 - Chart library from IBM's Carbon Design System, built on D3, with React, Angular, Vue and Svelte wrappers.
* [lit-line](https://github.com/apinet/lit-line) ⭐ 22 | 🐛 1 | 🌐 TypeScript | 📅 2024-12-18 - SVG Line Chart Web Component - light, fast, interactive & fully responsive.
* [Glyph](https://github.com/seanhanca/glyph) ⭐ 4 | 🐛 1 | 🌐 HTML | 📅 2026-06-05 - Deterministic chart library that renders the same JSON spec to identical SVG on every platform, with DuckDB inside and an MCP server for AI agents.
* [ApexCharts](https://apexcharts.com/) - Modern & Interactive SVG Charts.
* [Chart.js](https://www.chartjs.org/) - Charts with the canvas tag.
* [Chartist.js](https://gionkunz.github.io/chartist-js/) - Responsive charts with great browser compatibility.
* [Dygraphs](https://dygraphs.com/) - Interactive line charts library that works with huge datasets.
* [Google Charts](https://developers.google.com/chart) - Interactive charts for browsers and mobile devices.
* [GraphicsJS](http://www.graphicsjs.org) - Lightweight JS graphics library with intuitive API, based on SVG/VML.
* [MetricsGraphics.js](https://metricsgraphicsjs.org/) - Optimized for time-series data.

### Charting libraries for graphs

* [xyflow](https://github.com/xyflow/xyflow) ⭐ 38,850 | 🐛 152 | 🌐 TypeScript | 📅 2026-10-29 - React Flow and Svelte Flow: libraries for building node-based editors, flow charts and interactive diagrams.
* [G6](https://github.com/antvis/g6) ⭐ 12,367 | 🐛 333 | 🌐 TypeScript | 📅 2026-10-27 - Graph visualization library powered by Javascript & Typescript, maintained by Alibaba
* [Vue Flow](https://github.com/bcakmakoglu/vue-flow) ⭐ 6,926 | 🐛 19 | 🌐 TypeScript | 📅 2026-07-14 - Flowchart and node-based graph component for Vue 3.
* [X6](https://github.com/antvis/X6) ⭐ 6,746 | 🐛 156 | 🌐 TypeScript | 📅 2026-10-23 - Diagramming library for DAGs, ER diagrams, flowcharts and other graph editors, maintained by Alibaba.
* [3d-force-graph](https://github.com/vasturiano/3d-force-graph) ⭐ 6,518 | 🐛 250 | 🌐 HTML | 📅 2026-09-29 - 3D force-directed graph component using Three.js/WebGL.
* [dagre](https://github.com/dagrejs/dagre) ⭐ 5,842 | 🐛 172 | 🌐 TypeScript | 📅 2026-10-24 - Directed graph layout library for JavaScript.
* [JointJS](https://github.com/clientIO/joint) ⭐ 5,396 | 🐛 57 | 🌐 JavaScript | 📅 2026-10-29 - SVG-based JavaScript diagramming library for interactive diagrams and graph editors.
* [Viz.js](https://github.com/mdaines/viz-js) ⭐ 4,356 | 🐛 13 | 🌐 JavaScript | 📅 2026-09-28 - Graphviz compiled to WebAssembly for rendering DOT graphs in the browser and Node.js.
* [VivaGraph](https://github.com/anvaka/VivaGraphJS) ⭐ 3,865 | 🐛 115 | 🌐 JavaScript | 📅 2026-03-06 - Graph drawing library for JavaScript.
* [elkjs](https://github.com/kieler/elkjs) ⭐ 2,868 | 🐛 98 | 🌐 JavaScript | 📅 2026-10-28 - Eclipse Layout Kernel (ELK) graph layout algorithms for JavaScript.
* [Uber React Digraph](https://github.com/uber/react-digraph) ⭐ 2,640 | 🐛 91 | 🌐 JavaScript | 📅 2023-09-05 - React.js based directed graph library maintained by UBER.
* [force-graph](https://github.com/vasturiano/force-graph) ⭐ 2,157 | 🐛 151 | 🌐 JavaScript | 📅 2026-09-28 - Force-directed graph component rendered on HTML5 canvas.
* [diagram.js](https://github.com/bpmn-io/diagram-js) ⭐ 1,928 | 🐛 28 | 🌐 JavaScript | 📅 2026-10-30 - Javascript diagram library serving as the basis for camunda's online BPMN modeler.
* [cosmos.gl](https://github.com/cosmosgl/graph) ⭐ 1,305 | 🐛 14 | 🌐 TypeScript | 📅 2026-10-29 - GPU-accelerated force graph layout and rendering engine that runs entirely in WebGL shaders.
* [Vizdom](https://github.com/vizdom-dev/vizdom) ⭐ 193 | 🐛 1 | 📅 2025-02-16 - A declarative graph layout and rendering engine for Javascript/Typescript powered by Rust/WebAssembly.
* [Cola.js](https://marvl.infotech.monash.edu/webcola/) - A tool to create diagrams using constraint-based optimization techniques. Works with d3 and svg.js.
* [Cytoscape.js](https://js.cytoscape.org/) - JavaScript library for graph drawing maintained by [Cytoscape](https://www.cytoscape.org) core developers.
* [Sigma.js](https://sigmajs.org/) - JavaScript library dedicated to graph drawing.

### Financial charts

* [Lightweight Charts](https://github.com/tradingview/lightweight-charts) ⭐ 17,734 | 🐛 132 | 🌐 TypeScript | 📅 2026-10-30 - Performant HTML5 canvas financial charts, from TradingView.
* [KLineChart](https://github.com/klinecharts/KLineChart) ⭐ 4,281 | 🐛 31 | 🌐 TypeScript | 📅 2026-10-29 - Lightweight, highly customizable candlestick (k-line) chart with zero dependencies and mobile support.
* [HQChart](https://github.com/jones2000/HQChart) ⭐ 3,421 | 🐛 14 | 🌐 JavaScript | 📅 2026-10-08 - K-line and stock charts with a technical indicator scripting engine, for web pages and WeChat mini programs.
* [React Financial Charts](https://github.com/react-financial/react-financial-charts) ⭐ 1,425 | 🐛 58 | 🌐 TypeScript | 📅 2024-03-09 - React components for financial charts: candlesticks, technical indicators, overlays and drawing tools.
* [Vela](https://github.com/LuxAlgo/Vela) ⭐ 1,250 | 🐛 54 | 🌐 TypeScript | 📅 2026-10-30 - Financial charting library with a headless core, native WebGL2 renderer and plugin SDK, from LuxAlgo.
* [chartjs-chart-financial](https://github.com/chartjs/chartjs-chart-financial) ⭐ 811 | 🐛 38 | 🌐 JavaScript | 📅 2025-05-08 - Chart.js module that adds candlestick and OHLC chart types.
* [dxcharts-lite](https://github.com/devexperts/dxcharts-lite) ⭐ 102 | 🐛 13 | 🌐 TypeScript | 📅 2026-10-08 - Flexible financial charting library based on HTML5 canvas.
* [TradeCanvas](https://github.com/bonguynvan/tradecanvas) ⭐ 31 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-30 - Financial charts with indicators, drawing tools and live feeds, drawn with Canvas 2D or WebGL.
* [TechanJS](https://techanjs.org/) - Stock and financial charts.

### Maps

* [Cesium](https://github.com/CesiumGS/cesium) ⭐ 15,901 | 🐛 1,755 | 🌐 JavaScript | 📅 2026-10-30 - WebGL 3D globes and maps.
* [OpenLayers](https://github.com/openlayers/openlayers) ⭐ 12,639 | 🐛 885 | 🌐 JavaScript | 📅 2026-10-26 - Library for interactive web maps with support for many data sources, formats and projections.
* [mapcn](https://github.com/AnmolSaini16/mapcn) ⭐ 12,352 | 🐛 27 | 🌐 TypeScript | 📅 2026-10-31 - Map components for React built on MapLibre GL, styled with Tailwind and compatible with shadcn/ui.
* [MapLibre GL JS](https://github.com/maplibre/maplibre-gl-js) ⭐ 11,983 | 🐛 301 | 🌐 TypeScript | 📅 2026-10-30 - WebGL-based interactive vector tile maps in the browser; community fork of Mapbox GL JS.
* [react-map-gl](https://github.com/visgl/react-map-gl) ⭐ 8,515 | 🐛 106 | 🌐 TypeScript | 📅 2026-10-24 - React components for MapLibre GL JS and Mapbox GL JS, maintained by vis.gl.
* [COBE](https://github.com/shuding/cobe) ⭐ 6,023 | 🐛 44 | 🌐 TypeScript | 📅 2026-09-22 - Lightweight WebGL globe library of about 5 kB, with configurable markers.
* [Potree](https://github.com/potree/potree) ⭐ 5,653 | 🐛 824 | 🌐 JavaScript | 📅 2026-01-08 - WebGL point cloud viewer for large datasets such as LiDAR scans.
* [maptalks.js](https://github.com/maptalks/maptalks.js) ⭐ 4,538 | 🐛 120 | 🌐 HTML | 📅 2026-10-22 - Pluggable JavaScript library for integrated 2D/3D maps.
* [L7](https://github.com/antvis/L7) ⭐ 4,075 | 🐛 212 | 🌐 TypeScript | 📅 2026-10-20 - Large-scale WebGL-powered Geospatial Data Visualization analysis framework, maintained by Alibaba
* [DataMaps](https://github.com/markmarkoh/datamaps) ⭐ 3,799 | 🐛 229 | 🌐 JavaScript | 📅 2026-02-10 - Interactive SVG maps using D3.js.
* [React Simple Maps](https://github.com/zcreativelabs/react-simple-maps) ⭐ 3,390 | 🐛 170 | 🌐 TypeScript | 📅 2026-09-12 - Composable SVG map charts for React, based on d3-geo and TopoJSON.
* [globe.gl](https://github.com/vasturiano/globe.gl) ⭐ 3,218 | 🐛 133 | 🌐 HTML | 📅 2026-08-22 - UI component for globe data visualization using Three.js/WebGL.
* [TerriaJS](https://github.com/TerriaJS/terriajs) ⭐ 1,375 | 🐛 877 | 🌐 TypeScript | 📅 2026-10-29 - Library for building web-based 2D and 3D geospatial data explorers with catalogs of map layers.
* [Mapael](https://github.com/neveldo/jQuery-Mapael) ⭐ 1,004 | 🐛 71 | 🌐 JavaScript | 📅 2022-02-09 - jQuery plugin based on raphael.js to display vector maps.
* [Pharos AI](https://conflicts.app) - Open-source OSINT conflict-tracking dashboard with geospatial visualization using Deck.gl, MapLibre, and React. ([Source Code](https://github.com/Juliusolsson05/pharos-ai) ⭐ 183 | 🐛 24 | 🌐 TypeScript | 📅 2026-05-16)
* [L7 Plot](https://github.com/antvis/L7Plot) ⭐ 92 | 🐛 23 | 🌐 TypeScript | 📅 2024-07-15 - Geospatial Visualization Chart Library, maintained by Alibaba
* [Dipper](https://github.com/antvis/dipper) ⚠️ Archived - Map application development framework powered by L7, maintained by Alibaba.
* [Globedots](https://github.com/swamoth/globedots) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-18 - Dot-matrix WebGL2 globe in 17 kB with markers, arcs, labels, heat maps, and a day-night line.
* [CanvasGlobe](https://github.com/Shree-hari/canvas-globe) ⭐ 0 | 🐛 13 | 🌐 JavaScript | 📅 2026-10-31 - Interactive Canvas 2D globes and flat world maps for JavaScript and React.
* [Deck.gl](https://deck.gl/) - WebGL framework for visual exploratory data analysis of large datasets.
* [Leaflet](https://leafletjs.com) - JavaScript library for mobile-friendly interactive maps.
* [VectorAtlas](https://vectoratlas.menelabs.com/) - Free, 80KB SVG world map with one path per country, id-keyed by ISO 3166-1 alpha-2 code, ready for choropleths.

### d3

* [D3.js](https://github.com/d3/d3) ⭐ 113,829 | 🐛 22 | 🌐 Shell | 📅 2026-10-21 - JavaScript library for producing dynamic, data-driven visualizations with SVG, Canvas and HTML.
* See [Awesome D3](https://github.com/wbkd/awesome-d3) ⭐ 5,324 | 🐛 6 | 📅 2023-01-13 for D3 plugins, examples and tutorials.

### React

* [Recharts](https://github.com/recharts/recharts) ⭐ 27,675 | 🐛 468 | 🌐 TypeScript | 📅 2026-10-30 - Declarative react components to render D3 charts.
* [visx](https://github.com/airbnb/visx) ⭐ 21,091 | 🐛 160 | 🌐 TypeScript | 📅 2026-06-22 - Low-level visualization components that combine D3 with React, by Airbnb.
* [Tremor](https://github.com/tremorlabs/tremor-npm) ⭐ 16,467 | 🐛 63 | 🌐 TypeScript | 📅 2025-01-13 - React components for building charts and dashboards, based on Recharts and Tailwind CSS.
* [nivo](https://github.com/plouc/nivo) ⭐ 14,129 | 🐛 75 | 🌐 TypeScript | 📅 2026-07-21 - Supercharged dataviz components for React with isomorphic ability, [demo](https://nivo.rocks).
* [React-vis](https://github.com/uber/react-vis) ⭐ 8,787 | 🐛 343 | 🌐 JavaScript | 📅 2024-12-18 - React components to build data visualizations.
* [react-chartjs-2](https://github.com/reactchartjs/react-chartjs-2) ⭐ 6,938 | 🐛 111 | 🌐 TypeScript | 📅 2026-10-29 - React components for Chart.js.
* [BizCharts](https://github.com/alibaba/BizCharts) ⭐ 6,184 | 🐛 360 | 🌐 TypeScript | 📅 2025-05-23 - Data visualization library based on G2 and React.
* [MUI X Charts](https://github.com/mui/mui-x/tree/master/packages/x-charts) ⭐ 5,869 | 🐛 1,172 | 🌐 TypeScript | 📅 2026-10-31 - React chart components from MUI; the community package is MIT-licensed.
* [echarts-for-react](https://github.com/hustcc/echarts-for-react) ⭐ 5,012 | 🐛 52 | 🌐 TypeScript | 📅 2026-01-21 - React wrapper for Apache ECharts.
* [react-force-graph](https://github.com/vasturiano/react-force-graph) ⭐ 3,344 | 🐛 218 | 🌐 HTML | 📅 2026-09-29 - React components for 2D, 3D, VR and AR force-directed graphs.
* [Graphic Walker](https://github.com/Kanaries/graphic-walker) ⭐ 3,282 | 🐛 48 | 🌐 TypeScript | 📅 2026-10-13 - An embeddable React component that functions as an open source alternative to Tableau, which allows data scientists to analyze data and visualize patterns with simple drag-and-drop operations.
* [Semiotic](https://github.com/nteract/semiotic) ⭐ 2,717 | 🐛 207 | 🌐 TypeScript | 📅 2026-10-29 - React data visualization library for charts, network graphs and streaming data.
* [Ant Design Charts](https://github.com/ant-design/ant-design-charts) ⭐ 2,242 | 🐛 274 | 🌐 JavaScript | 📅 2026-03-26 - React chart library based on AntV, with statistical charts, graphs and maps.
* [Graphin](https://github.com/antvis/Graphin) ⭐ 1,099 | 🐛 64 | 🌐 TypeScript | 📅 2025-11-18 - Graph visualization library powered by React & Typescript (built on top of G6), maintained by Alibaba.
* [react-plotly.js](https://github.com/plotly/react-plotly.js) ⭐ 1,097 | 🐛 143 | 🌐 JavaScript | 📅 2026-09-16 - React component for Plotly.js charts, maintained by Plotly.
* [React Svg Textures](https://github.com/finnfiddle/react-svg-textures) ⭐ 32 | 🐛 2 | 🌐 JavaScript | 📅 2018-04-17 - Textures.js ported to React. Fully isomorphic.
* [DevExtreme React Chart](https://devexpress.github.io/devextreme-reactive/react/chart/) - High-performance plugin-based React chart for Bootstrap and Material Design.
* [Victory](https://formidable.com/open-source/victory/) - Composable components for building interactive data visualizations

### React Native

* [react-native-maps](https://github.com/react-native-maps/react-native-maps) ⭐ 16,014 | 🐛 102 | 🌐 TypeScript | 📅 2026-10-19 - Map view component for iOS and Android in React Native.
* [F2](https://github.com/antvis/F2) ⭐ 7,993 | 🐛 301 | 🌐 JavaScript | 📅 2026-05-19 - An elegant, interactive and flexible charting library for mobile, maintained by Alibaba
* [React Native Chart Kit](https://github.com/chart-kit/react-native-chart-kit) ⭐ 3,116 | 🐛 6 | 🌐 TypeScript | 📅 2026-09-06 - Line, bar, pie, progress and contribution graph charts for React Native.
* [react-native-graph](https://github.com/margelo/react-native-graph) ⭐ 2,638 | 🐛 24 | 🌐 TypeScript | 📅 2026-10-13 - Animated, high-performance line graphs for React Native, built with Skia.
* [react-native-charts-wrapper](https://github.com/wuxudong/react-native-charts-wrapper) ⭐ 2,495 | 🐛 215 | 🌐 Java | 📅 2026-05-31 - React Native wrapper for MPAndroidChart and DGCharts on Android and iOS.
* [react-native-gifted-charts](https://github.com/Abhinandan-Kushwaha/react-native-gifted-charts) ⭐ 1,373 | 🐛 102 | 🌐 TypeScript | 📅 2026-10-27 - Bar, line, area, pie, radar, bubble and candlestick charts for React Native, with animations.
* [Victory Native](https://github.com/FormidableLabs/victory-native-xl) ⭐ 1,235 | 🐛 90 | 🌐 TypeScript | 📅 2026-10-20 - High-performance charting library for React Native, built on React Native Skia.

### Misc

* [blessed-contrib](https://github.com/yaronn/blessed-contrib) ⭐ 15,776 | 🐛 97 | 🌐 JavaScript | 📅 2026-05-01 - Terminal dashboards with charts, maps, gauges and tables, built with Node.js and ASCII/ANSI art.
* [Perspective](https://github.com/perspective-dev/perspective) ⭐ 11,368 | 🐛 31 | 🌐 Rust | 📅 2026-10-27 - Interactive analytics and visualization component for large and streaming datasets, built on WebAssembly.
* [vue-echarts](https://github.com/ecomfe/vue-echarts) ⭐ 10,748 | 🐛 4 | 🌐 TypeScript | 📅 2026-10-28 - Vue.js component for Apache ECharts.
* [vue-chartjs](https://github.com/apertureless/vue-chartjs) ⭐ 5,718 | 🐛 30 | 🌐 TypeScript | 📅 2026-10-30 - Vue.js wrapper for Chart.js.
* [Flint](https://github.com/microsoft/flint-chart) ⭐ 4,519 | 🐛 42 | 🌐 TypeScript | 📅 2026-10-31 - Chart specification language from Microsoft that compiles to Vega-Lite, ECharts, Chart.js or Plotly.
* [ngx-charts](https://github.com/swimlane/ngx-charts) ⭐ 4,362 | 🐛 893 | 🌐 TypeScript | 📅 2026-10-29 - Declarative charting framework for Angular, using D3 for math and Angular for rendering.
* [vis-timeline](https://github.com/visjs/vis-timeline) ⭐ 2,576 | 🐛 307 | 🌐 JavaScript | 📅 2026-10-31 - Interactive timelines and 2D graphs with items and ranges, from the vis.js project.
* [Vue Data UI](https://github.com/graphieros/vue-data-ui) ⭐ 2,455 | 🐛 0 | 🌐 Vue | 📅 2026-10-29 - Vue 3 component library of charts, gauges, tables and other data visualizations.
* [ng2-charts](https://github.com/valor-software/ng2-charts) ⭐ 2,397 | 🐛 60 | 🌐 TypeScript | 📅 2026-10-19 - Angular directives for Chart.js charts.
* [Piecon](https://github.com/lipka/piecon) ⭐ 2,293 | 🐛 8 | 🌐 JavaScript | 📅 2022-10-12 - Pie charts in your favicon.
* [asciichart](https://github.com/kroitor/asciichart) ⭐ 2,110 | 🐛 23 | 🌐 Python | 📅 2026-10-30 - ASCII line charts for the console in Node.js and browsers, with ports to other languages.
* [Layer Cake](https://github.com/mhkeller/layercake) ⭐ 1,796 | 🐛 2 | 🌐 Svelte | 📅 2026-10-20 - Graphics framework for building reusable charts with Svelte.
* [Graphology](https://github.com/graphology/graphology) ⭐ 1,764 | 🐛 91 | 🌐 JavaScript | 📅 2026-09-02 - A robust & multipurpose Graph object for javascript & TypeScript; Serves as a base library to power other graph visualization libraries.
* [vtk.js](https://github.com/Kitware/vtk-js) ⭐ 1,545 | 🐛 296 | 🌐 JavaScript | 📅 2026-10-28 - JavaScript implementation of the Visualization Toolkit (VTK) for scientific visualization on the web.
* [Mosaic](https://github.com/uwdata/mosaic) ⭐ 1,399 | 🐛 145 | 🌐 TypeScript | 📅 2026-10-31 - Framework for linking databases such as DuckDB with interactive views to visualize large datasets.
* [LayerChart](https://github.com/techniq/layerchart) ⭐ 1,368 | 🐛 70 | 🌐 TypeScript | 📅 2026-10-30 - Composable Svelte chart components for cartesian, radial, hierarchical, graph and geo charts.
* [gp-treemap](https://github.com/imbue-ai/gp-treemap) ⭐ 10 | 🐛 5 | 🌐 HTML | 📅 2026-05-20 - Open source HTML canvas treemap component supporting millions of nodes, and some functional resource usage tools, like disk and S3 usage visualization ([GrandPerspective](https://grandperspectiv.sourceforge.net/)-style)
* [ODataMap](https://github.com/CherishChenCherish/odatamap) ⭐ 10 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-04 - Interactive scientific research data map. Visualizes 250M+ papers across 7 knowledge continents using D3.js. [Demo](https://odatamap.cherishchen2510.workers.dev)
* [Textures.js](https://riccardoscalco.github.io/textures/) - A library to create SVG patterns.
* [Timeline.js](https://timeline.knightlab.com/) -  Create interactive timelines.
* [Vega](https://vega.github.io/vega/) - Vega is a visualization grammar, a declarative format for creating, saving, and sharing interactive visualization designs.
* [Vega-Lite](https://vega.github.io/vega-lite/) - is a high-level grammar of interactive graphics. It provides a concise JSON syntax for rapidly generating visualizations to support analysis.
* [Vis.js](https://visjs.org/) - A dynamic visualization library including timeline, networks and graphs (2D and 3D).

## Android tools

* [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) ⭐ 38,187 | 🐛 1 | 🌐 Kotlin | 📅 2026-10-09 - A powerful & easy to use chart library.
* [HelloCharts](https://github.com/lecho/hellocharts-android) ⭐ 7,561 | 🐛 292 | 🌐 Java | 📅 2021-06-01 - Android chart library with line, column, pie, bubble and combo charts, plus zoom and scroll.
* [WilliamChart](https://github.com/diogobernardino/WilliamChart) ⭐ 5,094 | 🐛 35 | 🌐 Kotlin | 📅 2025-10-04 - Simple chart library.
* [Vico](https://github.com/patrykandpatrick/vico) ⭐ 3,200 | 🐛 4 | 🌐 Kotlin | 📅 2026-10-30 - Extensible chart library for Jetpack Compose and Compose Multiplatform.
* [DecoView](https://github.com/bmarrdev/android-DecoView-charting) ⭐ 984 | 🐛 25 | 🌐 Java | 📅 2022-02-28 - Animated circular wheel chart library.

## C++ tools

* [Serial Studio](https://github.com/Serial-Studio/Serial-Studio) ⭐ 7,283 | 🐛 21 | 🌐 C | 📅 2026-10-31 - Real-time telemetry dashboard for data from serial ports, Bluetooth LE, network sockets and other sources.
* [PlotJuggler](https://github.com/PlotJuggler/PlotJuggler) ⭐ 6,284 | 🐛 69 | 🌐 C++ | 📅 2026-10-15 - open-source Qt5 application to plot charts (based on Qwt).
* [ImPlot](https://github.com/epezent/implot) ⭐ 6,266 | 🐛 121 | 🌐 C++ | 📅 2026-10-25 - Immediate-mode plotting library for Dear ImGui.
* [F3D](https://github.com/f3d-app/f3d) ⭐ 4,949 | 🐛 317 | 🌐 C++ | 📅 2026-10-31 - Cross-platform, fast, and minimalist 3D viewer with scientific visualization tools.
* [Matplot++](https://github.com/alandefreitas/matplotplusplus) ⭐ 4,942 | 🐛 82 | 🌐 C++ | 📅 2026-04-02 - C++ graphics library for data visualization with a MATLAB-like API.
* [Mapnik](https://github.com/mapnik/mapnik) ⭐ 3,973 | 🐛 732 | 🌐 C++ | 📅 2026-10-29 - Toolkit for rendering maps, widely used to render OpenStreetMap tiles.
* [ROOT](https://github.com/root-project/root) ⭐ 3,333 | 🐛 659 | 🌐 C++ | 📅 2026-10-31 - CERN framework for analyzing, storing and visualizing large scientific datasets.
* [Visualization Toolkit (VTK)](https://github.com/Kitware/VTK) ⭐ 3,223 | 🐛 0 | 🌐 C++ | 📅 2026-10-31 - open-source library for 3d Graphics, image processing and visualization.
* [MapLibre Native](https://github.com/maplibre/maplibre-native) ⭐ 2,292 | 🐛 628 | 🌐 C++ | 📅 2026-10-31 - Interactive vector tile map rendering for iOS, Android and other native platforms.
* [Polyscope](https://github.com/nmwsharp/polyscope) ⭐ 2,223 | 🐛 127 | 🌐 C++ | 📅 2026-09-06 - Viewer and user interface for 3D geometry processing.
* [ParaView](https://github.com/Kitware/ParaView) ⭐ 1,716 | 🐛 8 | 🌐 C++ | 📅 2026-10-31 - Multi-platform data analysis and visualization application based on VTK.
* [OpenSpace](https://github.com/OpenSpace/OpenSpace) ⭐ 1,295 | 🐛 727 | 🌐 C++ | 📅 2026-10-30 - Interactive software for visualizing the known universe, from astronomy catalogs to space missions.
* [ImPlot3D](https://github.com/brenocq/implot3d) ⭐ 1,278 | 🐛 46 | 🌐 C++ | 📅 2026-10-25 - Immediate-mode 3D plotting extension for Dear ImGui, inspired by ImPlot.
* [LargeVis](https://github.com/lferry007/LargeVis) ⭐ 711 | 🐛 31 | 🌐 C++ | 📅 2023-05-31 - implementation of the [LargeVis paper](https://arxiv.org/abs/1602.00370), used to visualize large-scale and high-dimensional data.
* [VisIt](https://github.com/visit-dav/visit) ⭐ 537 | 🐛 1,945 | 🌐 C | 📅 2026-10-31 - Visualization and analysis tool for large mesh-based scientific data, developed at LLNL.
* [TTK](https://github.com/topology-tool-kit/ttk) ⭐ 481 | 🐛 24 | 🌐 C++ | 📅 2026-10-25 - Topological data analysis and visualization.
* [QCustomPlot](https://www.qcustomplot.com/) - Qt C++ widget for plotting and data visualization.

## Dashboards and BI

* [Grafana](https://github.com/grafana/grafana) ⭐ 77,595 | 🐛 3,361 | 🌐 TypeScript | 📅 2026-10-31 - Observability and data visualization platform for metrics, logs and traces from many data sources.
* [Apache Superset](https://github.com/apache/superset) ⭐ 75,381 | 🐛 601 | 🌐 Python | 📅 2026-10-31 - Data exploration and visualization platform with a no-code chart builder, SQL IDE and dashboards.
* [Metabase](https://github.com/metabase/metabase) ⭐ 50,051 | 🐛 4,642 | 🌐 Clojure | 📅 2026-10-31 - Business intelligence tool for querying data and building dashboards, with embedded analytics.
* [Redash](https://github.com/getredash/redash) ⭐ 28,855 | 🐛 786 | 🌐 TypeScript | 📅 2026-10-30 - Query data sources with SQL, then visualize the results and build dashboards.
* [Kibana](https://github.com/elastic/kibana) ⭐ 21,353 | 🐛 14,782 | 🌐 TypeScript | 📅 2026-10-31 - Visualization and dashboard UI for data stored in Elasticsearch.
* [Evidence](https://github.com/evidence-dev/evidence) ⭐ 7,078 | 🐛 18 | 🌐 TypeScript | 📅 2026-10-30 - Business intelligence as code: build reports and dashboards with SQL and Markdown.
* [Lightdash](https://github.com/lightdash/lightdash) ⭐ 6,215 | 🐛 1,122 | 🌐 TypeScript | 📅 2026-10-31 - BI tool that turns dbt projects into metrics, charts and dashboards.
* [Observable Framework](https://github.com/observablehq/framework) ⭐ 3,673 | 🐛 183 | 🌐 TypeScript | 📅 2026-05-15 - Static site generator for data apps, dashboards and reports using JavaScript, SQL and Markdown.
* [Rill](https://github.com/rilldata/rill) ⭐ 2,974 | 🐛 186 | 🌐 Go | 📅 2026-10-30 - BI tool for fast, metrics-first dashboards powered by OLAP engines such as DuckDB and ClickHouse.
* [Perses](https://github.com/perses/perses) ⭐ 2,512 | 🐛 273 | 🌐 Go | 📅 2026-10-31 - CNCF dashboard tool and open dashboard specification for observability data such as Prometheus metrics.
* [datart](https://github.com/running-elephant/datart) ⭐ 2,310 | 🐛 415 | 🌐 TypeScript | 📅 2025-02-10 - Data visualization platform for building reports, dashboards and data stories.
* [OpenSearch Dashboards](https://github.com/opensearch-project/OpenSearch-Dashboards) ⭐ 2,140 | 🐛 1,668 | 🌐 TypeScript | 📅 2026-10-30 - Visualization and dashboard UI for OpenSearch; Apache-2.0 fork of Kibana 7.10.
* [DataLens](https://github.com/datalens-tech/datalens) ⭐ 1,708 | 🐛 55 | 🌐 PLpgSQL | 📅 2026-08-24 - Business intelligence and data visualization system, originally developed at Yandex.

## Flutter tools

* [fl\_chart](https://github.com/imaNNeo/fl_chart) ⭐ 7,592 | 🐛 393 | 🌐 Dart | 📅 2026-10-30 - Customizable Flutter chart library with line, bar, pie, scatter and radar charts.
* [flutter\_map](https://github.com/fleaflet/flutter_map) ⭐ 3,026 | 🐛 74 | 🌐 Dart | 📅 2026-10-28 - Vendor-free, customizable interactive map package for Flutter.
* [Graphic](https://github.com/entronad/graphic) ⭐ 1,791 | 🐛 85 | 🌐 Dart | 📅 2026-02-25 - Grammar of graphics data visualization and charting library for Flutter.

## Golang tools

* [termui](https://github.com/gizak/termui) ⭐ 13,583 | 🐛 106 | 🌐 Go | 📅 2025-07-10 - Terminal dashboard and widget library with charts, gauges, sparklines and more.
* [go-echarts](https://github.com/go-echarts/go-echarts) ⭐ 7,657 | 🐛 65 | 🌐 Go | 📅 2026-10-06 - Simple yet powerful data visualizing library for Go.
* [go-diagrams](https://github.com/blushft/go-diagrams) ⭐ 5,235 | 🐛 16 | 🌐 Go | 📅 2025-03-22 - Diagram-as-code library for system architecture diagrams in Go, rendered with Graphviz.
* [asciigraph](https://github.com/guptarohit/asciigraph) ⭐ 3,099 | 🐛 8 | 🌐 Go | 📅 2026-10-17 - Lightweight ASCII line graphs for command-line apps.
* [termdash](https://github.com/mum4k/termdash) ⭐ 3,046 | 🐛 49 | 🌐 Go | 📅 2026-09-14 - Terminal-based dashboard library with line charts, bar charts, gauges and donuts.
* [plot](https://github.com/gonum/plot) ⭐ 2,971 | 🐛 93 | 🌐 Go | 📅 2026-04-22 - API for building and drawing plots in Go.
* [svgo](https://github.com/ajstarks/svgo) ⭐ 2,255 | 🐛 16 | 🌐 Go | 📅 2022-12-09 - Go Language Library for SVG generation.

## iOS tools

* [Charts](https://github.com/ChartsOrg/Charts) ⭐ 27,970 | 🐛 978 | 🌐 Swift | 📅 2026-03-07 -  iOS port of MPAndroidChart. You can create charts for both platforms with very similar code.
* [PNChart](https://github.com/kevinzhow/PNChart) ⭐ 9,630 | 🐛 173 | 🌐 Objective-C | 📅 2018-07-02 - A simple and beautiful chart lib used in Piner and CoinsMan.
* [ChartView](https://github.com/AppPear/ChartView) ⭐ 5,650 | 🐛 96 | 🌐 Swift | 📅 2026-03-02 - Line, bar and pie chart views built with SwiftUI.
* [JBChartView](https://github.com/Jawbone/JBChartView) ⭐ 3,689 | 🐛 10 | 🌐 Objective-C | 📅 2018-08-06 - Charting library for both line and bar graphs.
* [Core Plot](https://github.com/core-plot/core-plot) ⭐ 2,755 | 🐛 47 | 🌐 Objective-C | 📅 2026-05-04 - 2D plotting framework for macOS, iOS and tvOS.
* [BEMSimpleLineGraph](https://github.com/Boris-Em/BEMSimpleLineGraph) ⚠️ Archived - Highly customizable and interactive line graphs.
* [SwiftCharts](https://github.com/ivnsch/SwiftCharts) ⭐ 2,570 | 🐛 55 | 🌐 Swift | 📅 2023-05-09 - Customizable charts library for iOS.

## Julia tools

* [Makie](https://github.com/MakieOrg/Makie.jl) ⭐ 2,829 | 🐛 949 | 🌐 Julia | 📅 2026-10-31 - Interactive, high-performance plotting ecosystem for Julia with OpenGL, WebGL and Cairo backends.
* [Plots.jl](https://github.com/JuliaPlots/Plots.jl) ⭐ 1,958 | 🐛 890 | 🌐 Julia | 📅 2026-10-29 - Plotting meta-package for Julia with a single API over multiple backends.
* [Gadfly.jl](https://github.com/GiovineItalia/Gadfly.jl) ⭐ 1,932 | 🐛 276 | 🌐 Julia | 📅 2025-10-04 - Statistical graphics for Julia based on the grammar of graphics.
* [UnicodePlots.jl](https://github.com/JuliaPlots/UnicodePlots.jl) ⭐ 1,555 | 🐛 15 | 🌐 Julia | 📅 2026-10-03 - Unicode-based scientific plotting in the terminal for Julia.
* [AlgebraOfGraphics.jl](https://github.com/MakieOrg/AlgebraOfGraphics.jl) ⭐ 519 | 🐛 69 | 🌐 Julia | 📅 2026-09-04 - Algebraic grammar-of-graphics visualization for Julia, built on Makie.

## JVM tools

* [XChart](https://github.com/knowm/XChart) ⭐ 1,596 | 🐛 47 | 🌐 Java | 📅 2026-10-29 - Lightweight Java library for plotting data.
* [JFreeChart](https://github.com/jfree/jfreechart) ⭐ 1,392 | 🐛 164 | 🌐 Java | 📅 2025-11-22 - 2D chart library for Java applications using Swing, JavaFX or server-side rendering.
* [Kandy](https://github.com/Kotlin/kandy) ⭐ 745 | 🐛 150 | 🌐 Kotlin | 📅 2026-10-15 - Kotlin plotting library with a typed DSL, developed by JetBrains.
* [Lets-Plot for Kotlin](https://github.com/JetBrains/lets-plot-kotlin) ⭐ 486 | 🐛 10 | 🌐 Kotlin | 📅 2026-07-02 - Grammar of graphics plotting API for Kotlin, built on Lets-Plot.

## Machine Learning tools

* [Netron](https://github.com/lutzroeder/netron) ⭐ 33,638 | 🐛 19 | 🌐 JavaScript | 📅 2026-10-31 - Viewer for neural network, deep learning and machine learning models.
* [PlotNeuralNet](https://github.com/HarisIqbal88/PlotNeuralNet) ⭐ 25,068 | 🐛 87 | 🌐 TeX | 📅 2023-08-21 - LaTeX code for drawing neural network architecture diagrams.
* [Opik](https://github.com/comet-ml/opik) ⭐ 23,064 | 🐛 172 | 🌐 Python | 📅 2026-10-31 - Formerly CometLLM. Debug, evaluate, and monitor LLM applications with tracing and dashboards.
* [Phoenix](https://github.com/Arize-ai/phoenix) ⭐ 12,080 | 🐛 1,220 | 🌐 Python | 📅 2026-10-31 - ML observability in a notebook with UMAP visualizations
* [FiftyOne](https://github.com/voxel51/fiftyone) ⭐ 11,253 | 🐛 694 | 🌐 TypeScript | 📅 2026-10-30 - Tool for visualizing, curating and evaluating computer vision datasets and models.
* [Visdom](https://github.com/fossasia/visdom) ⭐ 10,326 | 🐛 173 | 🌐 Python | 📅 2026-10-30 - Tool for real-time visualization and monitoring of live data such as ML experiments.
* [BertViz](https://github.com/jessevig/bertviz) ⭐ 8,209 | 🐛 21 | 🌐 Python | 📅 2026-01-08 - Visualize attention in Transformer language models such as BERT and GPT-2.
* [TensorBoard](https://github.com/tensorflow/tensorboard) ⭐ 7,243 | 🐛 758 | 🌐 TypeScript | 📅 2026-10-29 - TensorFlow's visualization toolkit for metrics, model graphs, embeddings and more.
* [Aim](https://github.com/aimhubio/aim) ⭐ 6,291 | 🐛 483 | 🌐 Python | 📅 2026-10-30 - Experiment tracker with a UI to explore and compare ML runs and metrics.
* [NN-SVG](https://github.com/alexlenail/NN-SVG) ⭐ 5,693 | 🐛 28 | 🌐 JavaScript | 📅 2026-06-02 - Web tool for drawing publication-ready neural network architecture diagrams and exporting them to SVG.
* [Embedding Atlas](https://github.com/apple/embedding-atlas) ⭐ 5,007 | 🐛 37 | 🌐 TypeScript | 📅 2026-10-29 - Interactive visualization of large embeddings with search, filtering and density views, by Apple.
* [VisualDL](https://github.com/PaddlePaddle/VisualDL) ⭐ 4,879 | 🐛 157 | 🌐 HTML | 📅 2025-01-22 - Deep learning visualization toolkit for metrics, graphs, embeddings and more, from PaddlePaddle.
* [Yellowbrick](https://github.com/DistrictDataLabs/yellowbrick) ⭐ 4,408 | 🐛 124 | 🌐 Python | 📅 2025-02-19 - Visual analysis and diagnostic tools for machine learning model selection with scikit-learn.
* [LIT](https://github.com/PAIR-code/lit) ⭐ 3,671 | 🐛 138 | 🌐 TypeScript | 📅 2026-10-07 - Learning Interpretability Tool: interactive visual analysis of ML model behavior, by Google PAIR.
* [TensorWatch](https://github.com/microsoft/tensorwatch) ⭐ 3,479 | 🐛 54 | 🌐 Jupyter Notebook | 📅 2026-03-30 - Debugging and visualization tool for data science and machine learning
* [dtreeviz](https://github.com/parrt/dtreeviz) ⭐ 3,161 | 🐛 75 | 🌐 Jupyter Notebook | 📅 2026-01-02 - Decision tree visualization and model interpretation library for Python.
* [Model Explorer](https://github.com/google-ai-edge/model-explorer) ⭐ 1,587 | 🐛 77 | 🌐 JavaScript | 📅 2026-10-30 - Hierarchical graph visualizer and debugger for ML models, from Google.
* [LightlyStudio](https://github.com/lightly-ai/lightly-studio) ⭐ 901 | 🐛 48 | 🌐 Python | 📅 2026-10-30 - Interactive embedding plot and sample grid to explore image and video datasets, with annotation overlays.
* [Comet](https://github.com/comet-ml/comet-examples) ⭐ 175 | 🐛 27 | 🌐 Jupyter Notebook | 📅 2026-10-22 - An MLOps platform for tracking, visualizing, and debugging your machine learning workflows from training straight through to production.

## .NET tools

* [ScottPlot](https://github.com/ScottPlot/ScottPlot) ⭐ 6,791 | 🐛 248 | 🌐 C# | 📅 2026-08-15 - Interactive plotting library for .NET with WinForms, WPF, Avalonia, Blazor and other controls.
* [LiveCharts2](https://github.com/Live-Charts/LiveCharts2) ⭐ 5,504 | 🐛 70 | 🌐 C# | 📅 2026-07-20 - Animated, interactive charts, maps and gauges for .NET UI frameworks.
* [XCharts](https://github.com/XCharts-Team/XCharts) ⭐ 3,801 | 🐛 8 | 🌐 C# | 📅 2026-07-17 - Charting and data visualization library for Unity, built on UGUI.
* [OxyPlot](https://github.com/oxyplot/oxyplot) ⭐ 3,544 | 🐛 632 | 🌐 C# | 📅 2026-10-17 - Cross-platform plotting library for .NET.
* [Microcharts](https://github.com/microcharts-dotnet/Microcharts) ⭐ 2,076 | 🐛 1 | 🌐 C# | 📅 2026-10-26 - Simple cross-platform charts for .NET, drawn with SkiaSharp.
* [Mapsui](https://github.com/Mapsui/Mapsui) ⭐ 1,579 | 🐛 166 | 🌐 C# | 📅 2026-10-27 - .NET map component for MAUI, Avalonia, Uno Platform, Blazor, WPF and WinUI.
* [MSAGL](https://github.com/microsoft/automatic-graph-layout) ⭐ 1,503 | 🐛 136 | 🌐 C# | 📅 2026-10-27 - Microsoft Automatic Graph Layout: tools for graph layout and viewing in .NET.
* [Plotly.NET](https://github.com/plotly/Plotly.NET) ⭐ 862 | 🐛 46 | 🌐 F# | 📅 2026-10-29 - Interactive charts for F# and C#, based on Plotly.js.

## Python tools

### Core plotting libraries

* [pygal](https://github.com/Kozea/pygal) ⭐ 2,772 | 🐛 201 | 🌐 Python | 📅 2026-07-21 - SVG charting library for Python with many chart types and interactive output.
* [matplotlib](https://matplotlib.org/) - 2D plotting library.
* [seaborn](https://seaborn.pydata.org/) - A library for making attractive and informative statistical graphics.
* [toyplot](https://toyplot.readthedocs.io/en/stable/) - The kid-sized plotting toolkit for Python with grownup-sized goals.
* [veusz](https://veusz.github.io/) - Python multiplatform GUI plotting tool and graphing library

### Matplotlib extensions

* [SciencePlots](https://github.com/garrettj403/SciencePlots) ⭐ 9,352 | 🐛 19 | 🌐 Python | 📅 2026-06-23 - Matplotlib styles for scientific figures and journal publications.
* [mpld3](https://github.com/mpld3/mpld3) ⭐ 2,412 | 🐛 234 | 🌐 Jupyter Notebook | 📅 2026-10-31 - Renders matplotlib figures as interactive D3.js graphics in the browser.
* [Quibbler](https://github.com/Technion-Kishony-lab/quibbler) ⭐ 333 | 🐛 25 | 🌐 Python | 📅 2025-08-30 - Your data and anything you plot is effortlessly live and interactive.
* [syd](https://github.com/landoskape/syd) ⭐ 30 | 🐛 1 | 🌐 Python | 📅 2026-08-11 - A package for making GUIs around matplotlib figures easy, fast, and streamlined.

### Grammar of graphics and declarative

* [plotnine](https://github.com/has2k1/plotnine) ⭐ 4,779 | 🐛 80 | 🌐 Python | 📅 2026-10-29 - Grammar of graphics for Python, based on R's ggplot2.
* [ggplot](https://github.com/yhat/ggpy) ⚠️ Archived - plotting system based on [R's](#r-tools) ggplot2.
* [Lets-Plot](https://github.com/JetBrains/lets-plot) ⭐ 1,783 | 🐛 146 | 🌐 Kotlin | 📅 2026-07-02 - Grammar of graphics plotting library for Python and Kotlin, by JetBrains.
* [hvPlot](https://github.com/holoviz/hvplot) ⭐ 1,359 | 🐛 408 | 🌐 Python | 📅 2026-10-26 - High-level plotting API for pandas, xarray, Dask, NetworkX and other data structures, built on HoloViews.
* [altair](https://altair-viz.github.io/) - Declarative statistical visualizations, based on Vega-Lite.
* [holoviews](https://holoviews.org/) - Complex and declarative visualizations from annotated data.

### Interactive web charts

* [plotly](https://plotly.com/python/) - Interactive web based visualization built on top of [plotly.js](https://github.com/plotly/plotly.js) ⭐ 18,373 | 🐛 808 | 🌐 JavaScript | 📅 2026-10-29
* [pyecharts](https://github.com/pyecharts/pyecharts) ⭐ 15,782 | 🐛 6 | 🌐 Python | 📅 2026-10-26 - Python binding for Echarts library.
* [bqplot](https://github.com/bqplot/bqplot) ⭐ 3,693 | 🐛 278 | 🌐 TypeScript | 📅 2026-10-27 - Plotting library for IPython/Jupyter notebooks.
* [Chartify](https://github.com/spotify/chartify) ⭐ 3,656 | 🐛 56 | 🌐 Python | 📅 2024-10-16 - Bokeh wrapper that makes it easy for data scientists to create charts.
* [ipychart](https://github.com/nicohlr/ipychart) ⭐ 133 | 🐛 0 | 🌐 Python | 📅 2024-08-24 - The power of Chart.js in Jupyter Notebook.
* [bokeh](https://bokeh.org/) - Interactive Web Plotting for Python.

### Dashboards and data apps

* [Streamlit](https://github.com/streamlit/streamlit) ⭐ 46,177 | 🐛 1,188 | 🌐 Python | 📅 2026-10-31 - Framework for turning Python scripts into interactive data apps.
* [Dash](https://github.com/plotly/dash) ⭐ 24,474 | 🐛 434 | 🌐 Python | 📅 2026-10-30 - Framework for building data apps and dashboards in Python, built on Plotly.js and React.
* [Taipy](https://github.com/Avaiga/taipy) ⭐ 19,454 | 🐛 233 | 🌐 Python | 📅 2026-08-10 - Python framework for building data and AI web applications with interactive charts and dashboards.
* [Voilà](https://github.com/voila-dashboards/voila) ⭐ 5,956 | 🐛 331 | 🌐 Python | 📅 2026-10-05 - Turns Jupyter notebooks into standalone interactive web applications.
* [Panel](https://github.com/holoviz/panel) ⭐ 5,807 | 🐛 908 | 🌐 Python | 📅 2026-10-30 - Data exploration and web app framework for Python that works with many plotting libraries.
* [Vizro](https://github.com/mckinsey/vizro) ⭐ 3,817 | 🐛 3 | 🌐 Python | 📅 2026-10-30 - Low-code toolkit from McKinsey for building data visualization apps and dashboards, built on Dash.
* [Shiny for Python](https://github.com/posit-dev/py-shiny) ⭐ 1,765 | 🐛 465 | 🌐 Python | 📅 2026-10-31 - Python version of the Shiny reactive framework for interactive data apps.

### Exploratory data analysis and profiling

* [PyGWalker](https://github.com/Kanaries/pygwalker) ⭐ 15,999 | 🐛 71 | 🌐 Python | 📅 2026-09-05 - Turns dataframes into a drag-and-drop visual analysis UI in Jupyter, based on Graphic Walker.
* [ydata-profiling](https://github.com/Data-Centric-AI-Community/fg-data-profiling) ⭐ 13,746 | 🐛 325 | 🌐 Python | 📅 2026-10-31 - Generates statistical analytic reports with visualization for quick data analysis (formerly pandas-profiling).
* [D-Tale](https://github.com/man-group/dtale) ⭐ 5,235 | 🐛 71 | 🌐 TypeScript | 📅 2026-07-24 - Web-based visual explorer for pandas DataFrames with charts, summaries and correlations.
* [missingno](https://github.com/ResidentMario/missingno) ⭐ 4,212 | 🐛 14 | 🌐 Python | 📅 2024-05-14 - provides flexible toolset of data-visualization utilities that allows quick visual summary of the completeness of your dataset, based on matplotlib.
* [LIDA](https://github.com/microsoft/lida) ⭐ 3,288 | 🐛 87 | 🌐 Jupyter Notebook | 📅 2024-08-08 - Generates visualizations and infographics from data with large language models, from Microsoft.
* [Sweetviz](https://github.com/fbdesignpro/sweetviz) ⭐ 3,131 | 🐛 41 | 🌐 Python | 📅 2026-04-11 - Generates self-contained HTML reports that visualize and compare datasets for exploratory analysis.

### Maps and geospatial

* [prettymaps](https://github.com/marceloprates/prettymaps) ⭐ 14,320 | 🐛 24 | 🌐 Python | 📅 2026-07-30 - Draws stylized maps from OpenStreetMap data, using osmnx and matplotlib.
* [folium](https://github.com/python-visualization/folium) ⭐ 7,414 | 🐛 76 | 🌐 Python | 📅 2026-10-30 - Builds interactive Leaflet.js maps from Python data.
* [leafmap](https://github.com/opengeos/leafmap) ⭐ 3,794 | 🐛 0 | 🌐 Python | 📅 2026-10-31 - Interactive mapping and geospatial analysis in Jupyter with multiple mapping backends.
* [Cartopy](https://github.com/SciTools/cartopy) ⭐ 1,625 | 🐛 329 | 🌐 Python | 📅 2026-10-30 - Cartographic projections and geospatial data plotting with matplotlib.
* [ipyleaflet](https://github.com/jupyter-widgets/ipyleaflet) ⭐ 1,543 | 🐛 300 | 🌐 TypeScript | 📅 2026-05-07 - Interactive Leaflet maps in Jupyter notebooks, built on ipywidgets.
* [Lonboard](https://github.com/developmentseed/lonboard) ⭐ 975 | 🐛 104 | 🌐 Python | 📅 2026-10-26 - Fast, interactive geospatial data visualization in Jupyter, built on deck.gl and GeoArrow.
* [PyGMT](https://github.com/GenericMappingTools/pygmt) ⭐ 880 | 🐛 187 | 🌐 Python | 📅 2026-10-28 - Python interface to the Generic Mapping Tools (GMT) for maps and figures in the geosciences.

### 3D and scientific visualization

* [PyVista](https://github.com/pyvista/pyvista) ⭐ 3,869 | 🐛 517 | 🌐 Python | 📅 2026-10-31 – 3D plotting and mesh analysis through a streamlined interface for the Visualization Toolkit (VTK)
* [napari](https://github.com/napari/napari) ⭐ 2,791 | 🐛 1,308 | 🌐 Python | 📅 2026-10-30 - Fast, interactive viewer for multi-dimensional images in Python.
* [vedo](https://github.com/marcomusy/vedo) ⭐ 2,274 | 🐛 170 | 🌐 Python | 📅 2026-10-28 - Library for scientific analysis and visualization of 3D objects based on VTK.
* [pptk](https://github.com/heremaps/pptk) ⭐ 635 | 🐛 59 | 🌐 C++ | 📅 2020-09-17 - Visualize and work with 2D/3D pointclouds
* [yt](https://github.com/yt-project/yt) ⭐ 559 | 🐛 506 | 🌐 Python | 📅 2026-10-30 - Toolkit for analysis and visualization of volumetric data.
* [three.py](https://github.com/stemkoski/three.py/) ⭐ 121 | 🐛 4 | 🌐 Python | 📅 2023-01-19 - Easy to use 3D library based on PyOpenGL. Inspired by Three.js.
* [mayavi](https://docs.enthought.com/mayavi/mayavi/) - interactive scientific data visualization and 3D plotting in Python.
* [vtk](https://www.vtk.org/) - 3D computer graphics, image processing, and visualization that includes a Python interface.

### High-performance and GPU

* [Datashader](https://github.com/holoviz/datashader) ⭐ 3,570 | 🐛 152 | 🌐 Python | 📅 2026-10-29 - Renders very large datasets into accurate images by rasterizing them.
* [fastplotlib](https://github.com/fastplotlib/fastplotlib) ⭐ 1,533 | 🐛 173 | 🌐 Python | 📅 2026-10-16 - GPU-accelerated plotting library built on WGPU and pygfx for fast interactive visualization.
* [glumpy](https://github.com/glumpy/glumpy) ⭐ 1,279 | 🐛 100 | 🌐 Python | 📅 2025-07-15 - OpenGL scientific visualizations library.
* [PyQtGraph](https://www.pyqtgraph.org/) - Interactive and realtime 2D/3D/Image plotting and science/engineering widgets.
* [VisPy](https://vispy.org/) - High-performance scientific visualization based on OpenGL.

### Robotics and computer vision

* [Rerun](https://github.com/rerun-io/rerun) ⭐ 11,673 | 🐛 1,238 | 🌐 Rust | 📅 2026-10-30 - An SDK for logging computer vision and robotics data paired with a visualizer for exploring that data over time.
* [viser](https://github.com/viser-project/viser) ⭐ 2,842 | 🐛 122 | 🌐 Python | 📅 2026-09-25 - Web-based 3D visualization library for computer vision and robotics, with GUI building blocks.

### Finance and trading

* [mplfinance](https://github.com/matplotlib/mplfinance) ⭐ 4,456 | 🐛 178 | 🌐 Python | 📅 2024-08-08 - Financial market data visualization (candlestick, OHLC, volume) using matplotlib.
* [lightweight-charts-python](https://github.com/louisnw01/lightweight-charts-python) ⭐ 2,164 | 🐛 122 | 🌐 TypeScript | 📅 2024-09-28 - Python interface to TradingView's Lightweight Charts for financial charts.

### Terminal plotting

* [termgraph](https://github.com/mkaz/termgraph) ⭐ 3,302 | 🐛 27 | 🌐 Python | 📅 2026-10-26 - Draws bar charts, histograms and other basic graphs in the terminal, as a CLI or Python library.
* [Plotext](https://github.com/piccolomo/plotext) ⭐ 2,211 | 🐛 3 | 🌐 Python | 📅 2026-09-07 - Plots data directly in the terminal with a matplotlib-like syntax.
* [uniplot](https://github.com/olavolav/uniplot) ⭐ 460 | 🐛 4 | 🌐 Python | 📅 2026-10-29 - Lightweight plotting to the terminal. 4x resolution via Unicode.
* [diagram](https://github.com/tehmaze/diagram) ⭐ 408 | 🐛 3 | 🌐 Python | 📅 2022-04-13 - Text mode diagrams using UTF-8 characters

### Text visualization

* [WordCloud](https://github.com/amueller/word_cloud) ⭐ 10,540 | 🐛 142 | 🌐 Python | 📅 2026-01-22 - Word cloud generator for Python.
* [scattertext](https://github.com/JasonKessler/scattertext) ⭐ 2,348 | 🐛 23 | 🌐 Python | 📅 2026-07-04 - Interactive scatterplot visualizations of how language differs between groups of documents.

## R tools

* [plotly](https://github.com/plotly/plotly.R) ⭐ 2,685 | 🐛 761 | 🌐 R | 📅 2026-07-25 - Interactive charts (including adding interactivity to ggplot2 output), cartograms and simple network diagrams
* [patchwork](https://github.com/thomasp85/patchwork) ⭐ 2,619 | 🐛 82 | 🌐 R | 📅 2025-08-25 - Composes multiple ggplot2 plots into a single figure.
* [ggstatsplot](https://github.com/IndrajeetPatil/ggstatsplot) ⭐ 2,207 | 🐛 0 | 🌐 R | 📅 2026-10-22 - ggplot2-based plots with statistical test details included in the graphic.
* [rayshader](https://github.com/tylermorganwall/rayshader) ⭐ 2,184 | 🐛 48 | 🌐 R | 📅 2026-10-30 - 2D and 3D mapping and data visualization in R, including 3D renders of ggplot2 plots.
* [gt](https://github.com/rstudio/gt) ⭐ 2,162 | 🐛 265 | 🌐 R | 📅 2026-10-15 - Builds publication-quality display tables in R.
* [gganimate](https://github.com/thomasp85/gganimate) ⭐ 1,984 | 🐛 90 | 🌐 R | 📅 2025-09-04 - Grammar of animated graphics that extends ggplot2.
* [esquisse](https://github.com/dreamRs/esquisse) ⭐ 1,865 | 🐛 55 | 🌐 R | 📅 2025-02-21 - Drag-and-drop interface for building ggplot2 charts in RStudio or Shiny.
* [DiagrammeR](https://github.com/rich-iannone/DiagrammeR) ⭐ 1,751 | 🐛 172 | 🌐 R | 📅 2026-04-27 - Graph and network diagrams in R, rendered with Graphviz and mermaid.
* [ComplexHeatmap](https://github.com/jokergoo/ComplexHeatmap) ⭐ 1,561 | 🐛 232 | 🌐 R | 📅 2026-04-02 - Highly customizable heatmaps for genomic and other matrix data (Bioconductor).
* [ggpubr](https://github.com/kassambara/ggpubr) ⭐ 1,282 | 🐛 6 | 🌐 R | 📅 2026-07-31 - ggplot2-based functions for publication-ready plots with statistical annotations.
* [ggrepel](https://github.com/slowkow/ggrepel) ⭐ 1,263 | 🐛 23 | 🌐 R | 📅 2026-10-09 - Repels overlapping text labels away from each other in ggplot2 plots.
* [ggraph](https://github.com/thomasp85/ggraph) ⭐ 1,121 | 🐛 59 | 🌐 R | 📅 2025-08-25 - Grammar of graphics for graphs and networks, extending ggplot2.
* [circlize](https://github.com/jokergoo/circlize) ⭐ 1,028 | 🐛 67 | 🌐 R | 📅 2023-11-11 - Circular visualization in R, such as chord diagrams and Circos-style genomic plots.
* [tmap](https://github.com/r-tmap/tmap) ⭐ 907 | 🐛 48 | 🌐 R | 📅 2026-10-16 - Thematic maps in R, with a ggplot2-like layered syntax and static or interactive output.
* [ggiraph](https://github.com/davidgohel/ggiraph) ⭐ 882 | 🐛 6 | 🌐 R | 📅 2026-10-28 - Makes ggplot2 graphics interactive, with tooltips, hover effects and selections.
* [Leaflet for R](https://github.com/rstudio/leaflet) ⭐ 843 | 🐛 321 | 🌐 JavaScript | 📅 2025-10-08 - R interface to the Leaflet JavaScript library for interactive maps.
* [htmlwidgets](https://github.com/ramnathv/htmlwidgets) ⭐ 801 | 🐛 133 | 🌐 R | 📅 2026-04-22 - Framework for binding JavaScript visualization libraries to R, for use in R Markdown and Shiny.
* [r2d3](https://github.com/rstudio/r2d3) ⭐ 529 | 🐛 40 | 🌐 R | 📅 2024-01-09 - Renders custom D3.js visualizations from R, in RStudio, R Markdown and Shiny.
* [ggplot2](https://ggplot2.tidyverse.org/) - A plotting system based on the grammar of graphics.
* [ggvis](https://ggvis.rstudio.com/) - A data visualization package with a syntax similar to ggplot2 which allows you to create rich interactive graphics.
* [lattice](https://lattice.r-forge.r-project.org) - trellis graphics for R
* [rbokeh](https://hafen.github.io/rbokeh/) - R Interface to Bokeh.
* [rgl](https://cran.r-project.org/web/packages/rgl/index.html) - 3D Visualization Using OpenGL
* [shiny](https://shiny.rstudio.com) - Framework for creating interactive applications/visualisations
* [visNetwork](https://datastorm-open.github.io/visNetwork/) - Interactive network visualisations

## Ruby tools

* [Chartkick](https://github.com/ankane/chartkick) ⭐ 6,526 | 🐛 7 | 🌐 Ruby | 📅 2026-10-22 - Create charts with one line of Ruby.
* [YouPlot](https://github.com/red-data-tools/YouPlot) ⭐ 4,877 | 🐛 13 | 🌐 Ruby | 📅 2026-10-24 - Command-line tool that draws plots in the terminal from piped data.
* [Blazer](https://github.com/ankane/blazer) ⭐ 4,806 | 🐛 33 | 🌐 Ruby | 📅 2026-10-31 - Business intelligence tool for Rails apps: explore data with SQL and build charts and dashboards.
* [Gruff](https://github.com/topfunky/gruff) ⭐ 1,399 | 🐛 14 | 🌐 Ruby | 📅 2026-09-06 - Graphing library for Ruby that renders charts as images using RMagick.

## Rust tools

* [Plotters](https://github.com/plotters-rs/plotters) ⭐ 4,640 | 🐛 186 | 🌐 Rust | 📅 2026-04-13 - Drawing library for data plotting in Rust, with bitmap, SVG, WebAssembly and GUI backends.
* [Charming](https://github.com/yuankunzhang/charming) ⭐ 2,607 | 🐛 23 | 🌐 Rust | 📅 2026-10-31 - Chart rendering library for Rust powered by Apache ECharts.
* [Plotly.rs](https://github.com/plotly/plotly.rs) ⭐ 1,458 | 🐛 21 | 🌐 Rust | 📅 2026-10-28 - Plotly.js-based interactive plotting library for Rust.
* [malevich](https://github.com/shergin/malevich) ⭐ 75 | 🐛 0 | 🌐 Rust | 📅 2026-10-19 - Terminal plotting: line, scatter, bar, histogram, heatmap, box plot, violin and more, with automatic axes.

## Markup-based tools

* [Mermaid](https://github.com/mermaid-js/mermaid) ⭐ 90,945 | 🐛 2,022 | 🌐 TypeScript | 📅 2026-10-31 - Generate diagrams and flowcharts from markdown-like text definitions, with a [live editor](https://mermaid.live).
* [Diagrams](https://github.com/mingrammer/diagrams) ⭐ 42,773 | 🐛 400 | 🌐 Python | 📅 2026-10-27 - Diagram as code in Python for prototyping cloud system architectures.
* [D2](https://github.com/d2lang/d2) ⭐ 25,771 | 🐛 543 | 🌐 Go | 📅 2026-10-11 - Declarative diagram scripting language that turns text into diagrams.
* [PlantUML](https://github.com/plantuml/plantuml) ⭐ 13,390 | 🐛 592 | 🌐 Java | 📅 2026-10-31 - Generates UML, Gantt, mind map and other diagrams from plain text.
* [Markmap](https://github.com/markmap/markmap) ⭐ 13,210 | 🐛 61 | 🌐 TypeScript | 📅 2026-09-12 - Builds interactive mind maps from Markdown.
* [flowchart.js](https://github.com/adrai/flowchart.js) ⭐ 8,695 | 🐛 104 | 🌐 JavaScript | 📅 2026-10-23 - Draws SVG flowcharts from a textual description.
* [Penrose](https://github.com/penrose/penrose) ⭐ 8,010 | 🐛 182 | 🌐 TypeScript | 📅 2026-10-31 - Creates diagrams from mathematical notation in plain text, from Carnegie Mellon University.
* [C4-PlantUML](https://github.com/plantuml-stdlib/C4-PlantUML) ⭐ 7,449 | 🐛 0 | 🌐 PlantUML | 📅 2026-10-13 - PlantUML macros and styles for drawing software architecture diagrams with the C4 model.
* [LikeC4](https://github.com/likec4/likec4) ⭐ 5,998 | 🐛 188 | 🌐 TypeScript | 📅 2026-10-31 - Architecture-as-code language and tools that generate live, interactive diagrams.
* [Kroki](https://github.com/yuzutech/kroki) ⭐ 4,390 | 🐛 138 | 🌐 JavaScript | 📅 2026-10-30 - Unified API that renders diagrams from many text formats, including PlantUML, Mermaid, Graphviz and D2.
* [Svgbob](https://github.com/ivanceras/svgbob) ⭐ 4,235 | 🐛 39 | 🌐 Rust | 📅 2026-04-22 - Converts ASCII art diagrams into SVG.
* [Pele](https://github.com/obsidianmd/pele) ⭐ 3,962 | 🐛 9 | 🌐 TypeScript | 📅 2026-10-31 - Small, dependency-free renderer that turns Mermaid diagrams into SVG, from Obsidian.
* [Flowchart Fun](https://github.com/tone-row/flowchart-fun) ⭐ 3,411 | 🐛 12 | 🌐 TypeScript | 📅 2026-10-16 - Web app that generates flowcharts and diagrams from indented text.
* [nomnoml](https://github.com/skanaar/nomnoml) ⭐ 2,840 | 🐛 16 | 🌐 TypeScript | 📅 2026-08-19 - Draws UML diagrams from a simple text syntax.
* [CeTZ](https://github.com/cetz-package/cetz) ⭐ 1,863 | 🐛 75 | 🌐 Typst | 📅 2026-10-27 - Drawing library for Typst with a TikZ-inspired API, for diagrams and plots.
* [PGF/TikZ](https://github.com/pgf-tikz/pgf) ⭐ 1,368 | 🐛 290 | 🌐 TeX | 📅 2026-10-09 - TeX packages for programmatically drawing vector graphics and diagrams in LaTeX.
* [PGFPlots](https://github.com/pgf-tikz/pgfplots) ⭐ 261 | 🐛 238 | 🌐 TeX | 📅 2026-08-26 - TeX package for drawing 2D and 3D plots directly in LaTeX documents.
* [WaveDrom](https://wavedrom.com/) - Draws timing diagrams and waveforms from simple textual descriptions.

## Other tools

Tools that are not tied to a particular platform or language.

* [JSON Crack](https://github.com/AykutSarac/jsoncrack.com) ⭐ 44,590 | 🐛 46 | 🌐 TypeScript | 📅 2026-09-14 - Visualizes JSON, YAML, XML and CSV data as interactive graphs.
* [FlameGraph](https://github.com/brendangregg/FlameGraph) ⭐ 19,811 | 🐛 173 | 🌐 Perl | 📅 2024-10-20 - Stack trace visualizer that generates interactive SVG flame graphs from profiling data.
* [Data Formulator](https://github.com/microsoft/data-formulator) ⭐ 17,635 | 🐛 119 | 🌐 Python | 📅 2026-10-30 - AI-assisted tool for transforming data and creating visualizations, from Microsoft Research.
* [Sampler](https://github.com/sqshq/sampler) ⭐ 14,811 | 🐛 64 | 🌐 Go | 📅 2024-02-22 - Terminal dashboard that runs shell commands and visualizes their output, configured with YAML.
* [QGIS](https://github.com/qgis/QGIS) ⭐ 14,746 | 🐛 5,509 | 🌐 C++ | 📅 2026-10-31 - Desktop geographic information system for viewing, editing, analyzing and mapping geospatial data.
* [Gource](https://github.com/acaudwell/Gource) ⭐ 13,182 | 🐛 132 | 🌐 C++ | 📅 2026-03-06 - Animated visualization of software version control history.
* [VisiData](https://github.com/saulpw/visidata) ⭐ 9,434 | 🐛 3 | 🌐 Python | 📅 2026-10-29 - Terminal spreadsheet multitool for exploring and arranging tabular data, with basic plotting.
* [GeoLibre](https://github.com/opengeos/GeoLibre) ⭐ 8,320 | 🐛 25 | 🌐 TypeScript | 📅 2026-10-31 - Cloud-native GIS app for visualizing and analyzing geospatial data on the web, desktop and mobile.
* [SandDance](https://github.com/microsoft/SandDance) ⭐ 7,154 | 🐛 97 | 🌐 TypeScript | 📅 2026-10-27 - Visual data exploration and presentation with animated unit visualizations, from Microsoft Research.
* [Gephi](https://github.com/gephi/gephi) ⭐ 6,695 | 🐛 442 | 🌐 Java | 📅 2026-10-31 - An open-source platform for visualizing and manipulating large graphs
* [Spark](https://github.com/holman/spark) ⭐ 6,062 | 🐛 16 | 🌐 Shell | 📅 2022-05-07 - Sparklines for the shell. It has several [implementations in different languages](https://github.com/holman/spark/wiki/Alternative-Implementations) ⭐ 6,062 | 🐛 16 | 🌐 Shell | 📅 2022-05-07.
* [Orange](https://github.com/biolab/orange3) ⭐ 5,737 | 🐛 114 | 🌐 Python | 📅 2026-10-26 - Visual programming tool for data mining, machine learning and interactive data visualization.
* [RATH](https://github.com/Kanaries/Rath) ⭐ 4,688 | 🐛 68 | 🌐 TypeScript | 📅 2026-08-14 - Automatic Exploratory Data Analysis & Data Visualization tool which is powered by an AI-assisted Augmented Analytics engine.
* [mcp-server-chart](https://github.com/antvis/mcp-server-chart) ⭐ 4,408 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-27 - MCP server from AntV that lets AI agents generate more than 25 chart types.
* [Charted](https://github.com/mikesall/charted) ⚠️ Archived - A charting tool that produces automatic, shareable charts from any data file.
* [sqliteviz](https://github.com/lana-k/sqliteviz) ⭐ 2,360 | 🐛 20 | 🌐 JavaScript | 📅 2026-10-17 - Browser app that loads CSV, JSON or SQLite files, runs SQL and charts the results offline.
* [uMap](https://github.com/umap-project/umap) ⭐ 1,628 | 🐛 393 | 🌐 JavaScript | 📅 2026-10-30 - Web app for creating maps with OpenStreetMap layers and embedding them in websites.
* [SankeyMATIC](https://github.com/nowthis/sankeymatic) ⭐ 1,436 | 🐛 54 | 🌐 JavaScript | 📅 2026-07-13 - Web tool for building Sankey diagrams from a plain-text description of flows.
* [ttyplot](https://github.com/tenox7/ttyplot) ⭐ 1,386 | 🐛 11 | 🌐 C | 📅 2026-10-13 - Real-time terminal plotting utility that reads data from standard input.
* [GMT](https://github.com/GenericMappingTools/gmt) ⭐ 990 | 🐛 227 | 🌐 C | 📅 2026-10-31 - Command-line tools for processing geographic data and making publication-quality maps and plots.
* [DAC](https://github.com/bruin-data/dac) ⭐ 801 | 🐛 11 | 🌐 Go | 📅 2026-10-29 - Dashboard-as-code tool that builds interactive dashboards from YAML and TSX definitions
* [Cytoscape](https://github.com/cytoscape/cytoscape) ⭐ 737 | 🐛 14 | 🌐 Shell | 📅 2026-10-09 - Desktop platform for network analysis and visualization, widely used in bioinformatics.
* [Datavzrd](https://github.com/datavzrd/datavzrd) ⭐ 683 | 🐛 15 | 🌐 Rust | 📅 2026-10-27 - Turns CSV, TSV, JSON or Parquet tables into interactive, self-contained HTML reports, configured with a short YAML file.
* [LabPlot](https://github.com/KDE/labplot) ⭐ 487 | 🐛 0 | 🌐 C++ | 📅 2026-10-31 - KDE application for interactive scientific plotting, data analysis and visualization.
* [Resseract Lite](https://github.com/abistarun/resseract-lite) ⭐ 7 | 🐛 6 | 🌐 Java | 📅 2024-08-24 - A Data Analytics and Visualization Tool with flexible architecture to visualize and analyse data
* [ink-uplot](https://github.com/planadecu/ink-uplot) ⭐ 1 | 🐛 16 | 🌐 TypeScript | 📅 2026-10-28 - Render uPlot charts in the terminal (React Ink) with truecolor Unicode and kitty/sixel/iTerm2 graphics.
* [csvtodashboard](https://csvtodashboard.com) - Turn a CSV or Excel file into an auto-built dashboard in the browser - client-side, no upload.
* [gnuplot](http://www.gnuplot.info/) - Command-line driven program for 2D and 3D plots, with many output formats.
* [Graphviz](https://graphviz.org/) - Open source graph visualization command line tool and library. From input text to SVG,PDF,interactive web graph browser.
* [Kepler.gl](https://kepler.gl/) - Geospatial analysis tool for large-scale data sets.
* [Plotivy](https://plotivy.app/) - Scientific data visualization tool, with AI-generated reproducible Python code, and research-oriented design best practices built in.
* [RAW](https://rawgraphs.io) - Create web visualizations from CSV or Excel files.
* [sankeydiagram.net](https://sankeydiagram.net/) - Web app for creating and sharing Sankey diagrams of flows and budgets without code.
* [Squey](https://squey.org) - Visualization software for exploring and understanding large amounts of tabular data (using parallel coordinates, timeseries and scatter plots).

# Resources

## Books

* [Design for Information](https://www.amazon.com/Design-Information-Introduction-Histories-Visualizations/dp/1592538061) by Isabel Meirelles.
* [The Best American Infographics 2014](https://www.amazon.com/Best-American-Infographics-2014/dp/0547974515) by Gareth Cook.
* [The Grammar of Graphics](https://www.amazon.com/Grammar-Graphics-Statistics-Computing/dp/0387245448/) by Leland Wilkinson. Basic visualization theory.
* [The Visual Display of Quantitative Information](https://www.amazon.com/Visual-Display-Quantitative-Information/dp/0961392142) by Edward Tufte.
* [The Wall Street Journal Guide to Information Graphics](https://www.amazon.com/Street-Journal-Guide-Information-Graphics/dp/0393347281) by Dona M. Wong
* [Visualization Analysis and Design](https://www.amazon.com/Visualization-Analysis-Design-AK-Peters/dp/1466508914) by Tamara Munzner.
* [R in Action, Third Edition](https://www.manning.com/books/r-in-action-third-edition) by Robert I. Kabacoff. A complete learning resource for R and tidyverse.
* [Everyday Data Visualization](https://www.manning.com/books/everyday-data-visualization) by Desireé Abbott. A field guide for design techniques that will improve the charts, reports, and data dashboards you build every day.
* [Interactive Data Visualization for the Web](https://chimera.labs.oreilly.com/books/1230000000345) by Scott Murray. Available to read online. Focused on D3.
* [Data Visualisation: A Handbook for Data Driven Design](https://www.amazon.com/Data-Visualisation-Handbook-Driven-Design/dp/1526468921/) by Andy Kirk

## Catalogs

* [The Data Visualization Catalogue](https://www.datavizcatalogue.com) - A collection of data visualization methods, with pros and cons.
* [Data Viz Project](https://datavizproject.com)
* [The R Graph Gallery](https://www.r-graph-gallery.com)
* [From data to Viz](https://www.data-to-viz.com)
* [Chartopedia](https://www.anychart.com/chartopedia)
* [Interactive Chart Chooser](https://depictdatastudio.com/charts/) by Depict Data Studio
* Wikipedia
  * [Data visualization techniques](https://en.wikipedia.org/wiki/Data_visualization#Techniques)
  * [List of graphical methods](https://en.wikipedia.org/wiki/List_of_graphical_methods)
  * [Types of diagrams](https://en.wikipedia.org/wiki/Diagram#Gallery_of_diagram_types)
  * [Types of plots](https://en.wikipedia.org/wiki/Plot_\(graphics\)#Types_of_plots)
  * [Types of charts](https://en.wikipedia.org/wiki/Chart#Types)

## Podcasts

* [Data Stories](https://datastori.es/)
* [DataFramed](https://www.datacamp.com/community/podcast)
* [Data Viz Today](https://dataviztoday.com/)

## Twitter accounts

* [Alberto Cairo](https://twitter.com/albertocairo)
* [Andrei Kashcha](https://twitter.com/anvaka)
* [Benjamin Wiederkehr](https://twitter.com/datavis)
* [Jan Žák](https://twitter.com/zakjan)
* [Mara Averick](https://twitter.com/dataandme)
* [Martin Wattenberg](https://twitter.com/wattenberg)
* [Mike Bostock](https://twitter.com/mbostock)
* [Nadieh Bremer](https://twitter.com/NadiehBremer)
* [NYT Graphics](https://twitter.com/nytgraphics)
* [Visualizing](https://twitter.com/VisualizingOrg)

## Websites

* [Ann K. Emery](https://annkemery.com/)'s blog
* [Data Visualization Society](https://www.datavisualizationsociety.com/) - The Data Visualization Society is an organization dedicated to fostering community for data visualization professionals.
* [eagereyes](https://eagereyes.org/)
* [EvergreenData](https://stephanieevergreen.com/)
* [Global Data Tracker](https://globaldatatracker.com/) - Interactive country-statistics explorer with historical charts and globe views.
* [FlowingData](https://flowingdata.com/)
* [Information is Beautiful](https://www.informationisbeautiful.net/)
* [Junk Charts](https://junkcharts.typepad.com/) - Kaiser Fung takes apart why certain datavizes work/don't work
* [Lisa Rost thinks and discusses about why we dataviz](https://lisacharlotterost.github.io/)
* [Makeover Monday](https://www.makeovermonday.co.uk/) blog - [#MakeoverMonday](https://twitter.com/search?q=%23makeovermonday) on twitter
* [Plottie](https://plottie.art) - Open-access library of scientific plots for inspiration and AI visualization tool.
* [The Open News](https://source.opennews.org/articles/) blog -  Open news has some good dataviz related articles from time to time
* [The Planet Thinks](https://theplanetthinks.com/) - Real-time visualization of Wikipedia edits on a 3D globe
* [The Pudding](https://pudding.cool/)
* [Truth & Beauty Operations](https://truth-and-beauty.net/)
* [University of Washington Interactive Data Lab Papers](https://idl.cs.washington.edu/papers)
* [vis4.net](https://www.vis4.net/blog/) - Random thoughts on visualization and data journalism by Gregor Aisch
* [VivaMap](https://vivamap.ch) - Interactive quality-of-life map of Swiss and Dutch municipalities, scored on an H3 hexagon grid.
* [Marble Taxonomy Explorer](https://ashutoshsinghpr7.github.io/marble-taxonomy-explorer/) - Interactive knowledge graph visualization of 1,590 learning topics using Cytoscape.js with force-directed, concentric, and BFS layouts. [Source](https://github.com/ashutoshsinghpr7/marble-taxonomy-explorer) ⭐ 10 | 🐛 0 | 🌐 Svelte | 📅 2026-10-25

# Contributing

Suggestions are welcome! Please read [Suggesting a Library](CONTRIBUTING.md) first: it covers what we list, the star and age guidelines, and the entry format.

Thanks for your suggestions!

# Contributors

* [Fabio Souto](https://fabiosouto.me/) originally created this repo.
* [Javier Luraschi](https://github.com/javierluraschi) is the current maintainer.
* [Hal9](https://hal9.com) is the corporate sponsor.
* [Cloudish](https://cloudish.ai) hosts [awesomedataviz.com](https://awesomedataviz.com).

# License

Released under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](LICENSE).

***

If you have any question about this opinionated list, do not hesitate to contact me [@javierluraschi](https://twitter.com/javierluraschi) on Twitter or [open a GitHub issue](https://github.com/hal9ai/awesome-dataviz/issues/new).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-31._
