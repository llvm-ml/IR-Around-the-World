---
layout: default
title: ComPile
---


## Abstract

Abstract to go here.

## ComPile at a Glance

![Treemap](ComPile_PieChart.png)

Broken down into the specific sizes of the content of ComPile in the different LLVM-based languages contained in ComPile:

| Language | C | C++ | Julia | Rust | Swift | Total |
|:-------------|:----|:----|:----|:----|:----|:----|
| Size (Bitcode) | 13 GB | 81 GB | 197 GB | 482 GB | 5 GB | 778 GB |
| Size (Text) | 61 GB | 334 GB | 1292 GB | 1868 GB | 22 GB | 3577 GB |
| Deduplicated Size (Bitcode) | 8 GB | 67 GB | 130 GB | 310 GB | 4 GB | 518 GB |
| Deduplicated Size (Text) | 34 GB | 266 GB | 856 GB | 1221 GB | 19 GB | 2395 GB |

To arrive at a permissively licensed subset we filter the dataset for the following 4 licenses:

The dataset is filtered for [MIT](https://spdx.org/licenses/MIT.html), [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html), [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause-Clear.html), and [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html) licenses.

> See the _LLVM-IR-Dataset-Utils - Scalable Tooling for IR Datasets_ technical talk on the dataset tooling behind ComPile!

## Statistical Analyses

tbd

## Authors

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

## Corresponding Authors

> Who else should be added here?

* Johannes Doerfert ([jdoerfert@llnl.gov](mailto:jdoerfert@llnl.gov?subject=IRAroundTheWorld))
