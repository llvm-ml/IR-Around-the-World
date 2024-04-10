---
layout: default
title: IR Around the World
---

<center>
    <h2>Abstract</h2>
</center>

Within this walk, we present statistical analyses of the properties of the generated IR, and the optimization pipeline itself. We quantify a number of factors related to the optimization pipeline including which optimizations are run, how long they take, and perform an analysis of the code at the end on a massive corpus of multi-language IR. We anticipate our results to be a starting point for deeper specific investigations on issues like the optimality of the current pass pipelines and help to better understand where compile time is spent. Initial results are presented here but the talk will focus on knowledge filtered out of this data and more we will gather in the meantime.

<center>
    <h2>ComPile at a Glance</h2>
    <img src="ComPile_PieChart.png" width="600" alt="ComPile Pie Chart" />
</center>

Broken down into the specific sizes of the content of ComPile in the different LLVM-based languages contained in ComPile:

<center>
    <img src="ComPileTable.png" alt="ComPile Table" />
</center>

The dataset is filtered for [MIT](https://spdx.org/licenses/MIT.html), [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html), [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause-Clear.html), and [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html) licenses.

> See the _LLVM-IR-Dataset-Utils - Scalable Tooling for IR Datasets_ technical talk on the dataset tooling behind ComPile!

<center>
    <h2>Statistical Analyses</h2>
    <h3>Distribution of ComPile's Compile Times</h3>
    <img src="o3_cpp_hist.png" width="750" alt="Distribution of ComPile's Compile Times" />
    <h3>Scatter Plot of Compile Times</h3>
    <img src="compile_time_plot_cxx.png" width="750" alt="Scatter Plot of Compile Times" />
    <h3>Relative Wall Time Distribution</h3>
    <img src="rel_wall_dist.png" width="650" alt="Relative Wall Time Distribution" />
    <h3>Absolute Time vs. Relative Time</h3>
    <img src="abs_rel_plot2.png" width="650" alt="Absolute Time vs. Relative Time" />
    <h3>Outlier Function Extraction</h3>
    <img src="outlier_extraction_flowchart.png" width="700" alt="Outlier Function Extraction Flowchart" />
    <img src="gvn_outlier_fn.png" width="650" alt="Outliers" />
    <h2>Authors</h2>
</center>

<div style="display:table;margin: 0 auto;">
<div class="cards">
    <div class="card">
        <img src="kallai.jpg" height="200" width="200" alt="andrew" />
        <p style="text-align:center;"><a href="https://www.linkedin.com/in/andrew-kallai-a990b41a7">Andrew Kallai</a></p>
    </div>
    <div class="card">
        <img src="nguyen.jpg" height="200" width="200" alt="khoi" />
        <p style="text-align:center;"><a href="https://www.linkedin.com/in/khoidng">Khoi Nguyen</a></p>
    </div>
    <div class="card">
        <img class="middle-img" src="paehler.jpg" height="200" width="200" alt="ludger" />
        <p style="text-align:center;"><a href="https://ludger.fyi">Ludger Paehler</a></p>
    </div>
    <div class="card">
        <img src="grossman.png" height="200" width="200" alt="aiden" />
        <p style="text-align:center;"><a href="https://www.linkedin.com/in/aiden-grossman-40213a248/">Aiden Grossman</a></p>
    </div>
    <div class="card">
        <img src="doerfert.jpg" height="200" width="200" alt="johannes" />
        <p style="text-align:center;"><a href="https://people.llnl.gov/doerfert1">Johannes Doerfert</a></p>
    </div>
    <div class="card">
        <img class="middle-img" src="chandrasekaran.jpg" height="200" width="200" alt="sunita" />
        <p style="text-align:center;"><a href="https://crpl.cis.udel.edu/sunita/">Sunita Chandrasekaran</a></p>
    </div>
</div>
</div>

<center>
    <h2>Corresponding Author</h2>
    Johannes Doerfert (<a href="mailto:jdoerfert@llnl.gov">jdoerfert@llnl.gov</a>)
</center>
