---
layout: single
permalink: /tools/
author_profile: true
---

{% include base_path %}

<!-- {% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %} -->

# Interactive Web App Tools 

This section is to share interactive tools that visualize methods in machine learning to reduce the barrier to understanding the core concepts. Details on the tools are available in my [GitHub repository](https://github.com/IBChung/interactive_visualization_tools)

# Bayesian Optimization (BO)
- This tool aims to show how BO adaptively updates the model to find the optimum
- Students can familiarize themselves with sequential approximate optimization
- Students can observe what BO does by interacting with the sampling process
- Students can see how different GP and BO parameters affect the optimization iterations
- Supports 1D and 2D design space examples

<style>
.app-mini {
  /* the only three numbers you need to touch */
  --app-w: 1500px;    /* width the app renders at (keeps the wide layout) */
  --app-h: 1100px;    /* height the app renders at */
  --scale: 0.45;      /* 0.33 = a third, 0.5 = half */

  width:  calc(var(--app-w) * var(--scale));
  height: calc(var(--app-h) * var(--scale));
  position: relative;
  overflow: hidden;
  margin: 1.5rem auto;
  border: 1px solid rgba(128,128,128,0.35);
  border-radius: 8px;
}
.app-mini iframe {
  width:  var(--app-w);
  height: var(--app-h);
  border: 0;
  position: absolute;
  top: 0; left: 0;
  transform: scale(var(--scale));
  transform-origin: top left;
}
</style>

<div class="app-mini">
  <iframe
    src="https://interactivevisualizationtools-bayesian-optimization.streamlit.app/?embed=true&embed_options=dark_theme"
    title="Graph Neural Network Explorer"
    loading="lazy"></iframe>
</div>

<p style="text-align:center">
  <a href="https://interactivevisualizationtools-bayesian-optimization.streamlit.app/"><strong>Open the full-size version →</strong></a>
</p>


# Graph Neural Network (GNN)
- This tool aims to show how network representations are learned using GNN
- Students can familiarize themselves with the network representation
- Students can learn how the features are propagated through message passing and aggregation
- Students can see how the different operators affect the final feature space of the network
- Supports undirected graphs with node features and with both node and edge features

<style>
.app-mini {
  /* the only three numbers you need to touch */
  --app-w: 1500px;    /* width the app renders at (keeps the wide layout) */
  --app-h: 1100px;    /* height the app renders at */
  --scale: 0.45;      /* 0.33 = a third, 0.5 = half */

  width:  calc(var(--app-w) * var(--scale));
  height: calc(var(--app-h) * var(--scale));
  position: relative;
  overflow: hidden;
  margin: 1.5rem auto;
  border: 1px solid rgba(128,128,128,0.35);
  border-radius: 8px;
}
.app-mini iframe {
  width:  var(--app-w);
  height: var(--app-h);
  border: 0;
  position: absolute;
  top: 0; left: 0;
  transform: scale(var(--scale));
  transform-origin: top left;
}
</style>

<div class="app-mini">
  <iframe
    src="https://interactivevisualizationtools-graph-neural-network.streamlit.app/?embed=true&embed_options=dark_theme"
    title="Graph Neural Network Explorer"
    loading="lazy"></iframe>
</div>

<p style="text-align:center">
  <a href="https://interactivevisualizationtools-graph-neural-network.streamlit.app/"><strong>Open the full-size version →</strong></a>
</p>

