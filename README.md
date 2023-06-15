### Dataset - Le Monde Guerre en Ukraine
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)



As a reader of Le Monde —and the comments section ;) I would regularly encounter familiar subscribers’ names.<br>
One in particular –more on that on the notebook, would manually keep track, count & cite “pro-russian” contributors, directly in the comments.<br>
That triggered my need to collect and perform some analysis in a bit more data-science oriented fashion.<br>

You might also want to check the custom API & tools I used to build the dataset —or simply download it, on the [sibling repo /lmd_ukr](https://github.com/matthieuvion/lmd_ukr)


### Cool things
---
- Source notebook (`lmd_viz/playground.ipynb`) is rendered as a live article [-> github.io/lmd_viz](https://matthieuvion.github.io/lmd_viz/), via `Quarto`.
- Most of data operations are done using `Polars` instead of `Pandas`. Made sure to include a lot of annotations for re-use.
- Aggregations include cohort analysis and I like those viz.
- Curated and benchmarked a few `SBert` models for documents embedding + Semantic search efficiently via a `Faiss` index.

