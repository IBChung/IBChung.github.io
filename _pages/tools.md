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
.app-embed {
  position: relative;
  left: 50%; right: 50%;
  width: 100vw;
  margin-left: -50vw; margin-right: -50vw;
}
.app-embed iframe { display: block; width: 100%; height: 1000px; border: 0; }
@media (max-width: 900px) { .app-embed iframe { height: 1400px; } }
</style>

<div class="app-embed">
  <iframe
    src="https://interactivevisualizationtools-bayesian-optimization.streamlit.app/?embed=true&embed_options=dark_theme"
    title="Bayesian Optimization Explorer"
    loading="lazy"
    allow="fullscreen"></iframe>
</div>

Cramped? [Open it full screen](https://interactivevisualizationtools-bayesian-optimization.streamlit.app/).



# Graph Neural Network (GNN)
- This tool aims to show how network representations are learned using GNN
- Students can familiarize themselves with the network representation
- Students can learn how the features are propagated through message passing and aggregation
- Students can see how the different operators affect the final feature space of the network
- Supports undirected graphs with node features and with both node and edge features

<style>
.app-embed {
  position: relative;
  left: 50%; right: 50%;
  width: 100vw;
  margin-left: -50vw; margin-right: -50vw;
}
.app-embed iframe { display: block; width: 100%; height: 1000px; border: 0; }
@media (max-width: 900px) { .app-embed iframe { height: 1400px; } }
</style>

<div class="app-embed">
  <iframe
    src="https://interactivevisualizationtools-graph-neural-network.streamlit.app/?embed=true&embed_options=dark_theme"
    title="Graph Neural Network Explorer"
    loading="lazy"
    allow="fullscreen"></iframe>
</div>

Cramped? [Open it full screen](https://interactivevisualizationtools-graph-neural-network.streamlit.app/).
