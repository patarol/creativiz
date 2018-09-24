## Data Visualization
### website, libraries and blogs
#### 1. websites

- [the pudding](https://pudding.cool/)

- [flowing data](https://flowingdata.com/)
- [information is beautiful](https://informationisbeautiful.net/)

- [five thirty eigth](https://fivethirtyeight.com/)

- [story telling with data](http://www.storytellingwithdata.com/)

- [show me shiny](https://www.showmeshiny.com/) - gallery of `R` web apps


#### 2. blogs

- [Amber Thomas](http://amber.rbind.io/):
    She's collaborator at [the pudding](https://pudding.cool/) and her blog has some nice `D3` and `R` tutorials and integration between these two tools together. Also has lot of tutorials and stuff using `R` and `Rstudio` libraries.

- [Ilia Blinderman](http://iliablinderman.com/):
    Collaborator at the [the pudding](https://pudding.cool/) his webpage has some nice charts examples.

- [Nadieh Bremer](https://www.visualcinnamon.com/2016/05/real-life-motion-effects-d3-visualization.html): Awarded data visualization. Her blog brings some nice tutorials with `R` and `D3`. Worked for different webpages and journals (e.g. **Scientific American**, **The Guardian**, etc)

- [Mike Bostock](https://bost.ocks.org/mike/): key developer of `D3`. His page has several `D3` tutorials.

#### 3. libraries

There're several libraries/tools for interactive data visualization. Some of them have their wrapper for `R`.

  - [`D3`](https://d3js.org/): a `JavaScript` library for manipulating documents based on data. `D3` helps you bring data to life using `HTML`, `SVG`, and `CSS`. `D3’s` emphasis on web standards gives you the full capabilities of modern browsers without tying yourself to a proprietary framework, combining powerful visualization components and a data-driven approach to DOM manipulation. `r2d3` `R` package is tool to wrapper your date into `D3` format.

  - [`Highcharts`](https://www.highcharts.com/): used by some major companies across the world. This library has essentially every chart you could possibly need, it even offers an array of different Gauge charts in the style of activity, speedometer and even electrical meter-style gauges. It’s probably the most advanced library out there regarding types of charts available. Not free for commercial use. [`highcharter`](http://jkunst.com/highcharter/) is its wrapper for working in `R`.

  - [`Charts`](http://www.chartjs.org/):perfect for small projects – when you need flat, clean, elegant javascript charts, fast. It is a tiny open source library at just 11kb when minified and zipped. This includes 6 core chart types (line, bar, radar, polar, pie and doughnut), each in its own module, so you can even load only the ones your project needs, making your footprint even smaller.

  - [`echarts`](https://ecomfe.github.io/echarts-examples/public/index.html): a free, powerful charting and visualization library offering an easy way of adding intuitive, interactive, and highly customizable charts to your commercial products. It is written in pure `JavaScript` and based on zrender, which is a whole new lightweight canvas library. And its amazing `R` library [`echarts4r`](https://echarts4r.john-coene.com/index.html).

  - [`Vega-lite`](https://vega.github.io/vega-lite/): a high-level grammar of interactive graphics. It provides a concise `JS` syntax for rapidly generating visualizations to support analysis. `Vega-Lite` specifications can be compiled to Vega specification. Obviously it brings its `R` [wrapper](https://github.com/hrbrmstr/vegalite) and must be installed using `devtools`
