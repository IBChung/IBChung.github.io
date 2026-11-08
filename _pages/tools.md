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

# Derivative-based and Derivative-free Optimization Algorithms
- This tool aims to show various different algorithms that utilize derivatives and metaheuristics for optimization
- Students can learn the difference between the benefits of local and global optimizers
- Students can observe the behavior of the optimization algorithms through the process of finding the optimum
- Supports 1D and 2D design space examples
- Bayesian Optimization is a derivative-free algorithm that does NOT use metaheuristics (separate app available below)

<style>
.app-preview {
  display: block;
  margin: 1.5rem 0 0.5rem;
  cursor: zoom-in;
}

.app-preview img {
  display: block;
  width: 100%;
  height: auto;
  box-sizing: border-box;
  border: 1px solid rgba(128, 128, 128, 0.35);
  border-radius: 8px;
}
</style>

<a class="app-preview" href="{{ '/images/Opt_tool_example.png' | relative_url }}">
  <img src="{{ '/images/Opt_tool_example.png' | relative_url }}"
       alt="Example of the Optimization Algorithms Explorer -- 2D Genetic Algorithm">
</a>

<p style="text-align:center">
  <a href="https://interactivevisualizationtools-optimization-algorithms.streamlit.app/"><strong>Open app (may be asleep) →</strong></a>
</p>

# Bayesian Optimization (BO)
- This tool aims to show how BO adaptively updates the model to find the optimum
- Students can familiarize themselves with sequential approximate optimization
- Students can observe what BO does by interacting with the sampling process
- Students can see how different GP and BO parameters affect the optimization iterations
- Supports 1D and 2D design space examples


<a class="app-preview" href="{{ '/images/BO_tool_example.png' | relative_url }}">
  <img src="{{ '/images/BO_tool_example.png' | relative_url }}"
       alt="Example of the Bayesian Optimization Explorer -- 1D GP-based BO">
</a>

<p style="text-align:center">
  <a href="https://interactivevisualizationtools-bayesian-optimization.streamlit.app/"><strong>Open app (may be asleep) →</strong></a>
</p>


# Graph Neural Network (GNN)
- This tool aims to show how network representations are learned using GNN
- Students can familiarize themselves with the network representation
- Students can learn how the features are propagated through message passing and aggregation
- Students can see how the different operators affect the final feature space of the network
- Supports undirected graphs with node features and with both node and edge features


<a class="app-preview" href="{{ '/images/GNN_tool_example.png' | relative_url }}">
  <img src="{{ '/images/GNN_tool_example.png' | relative_url }}"
       alt="Example of the Graph Neural Network Explorer -- Summation Aggregation">
</a>

<p style="text-align:center">
  <a href="https://interactivevisualizationtools-graph-neural-network.streamlit.app/"><strong>Open app (may be asleep) →</strong></a>
</p>





<style>
  #app-lightbox {
    box-sizing: border-box;
    width: fit-content;
    max-width: 96vw;
    max-height: 94vh;
    padding: 0.75rem;
    border: 1px solid #555;
    border-radius: 10px;
    background: #171717;
    color: white;
  }

  #app-lightbox::backdrop {
    background: rgba(0, 0, 0, 0.8);
  }

  #app-lightbox button {
    display: block;
    margin: 0 0 0.6rem auto;
    padding: 0.35rem 0.8rem;
    border: 1px solid #888;
    border-radius: 5px;
    background: #292929;
    color: white;
    font: inherit;
    cursor: pointer;
  }

  #app-lightbox img {
    display: block;
    width: auto;
    height: auto;
    max-width: 100%;
    max-height: 78vh;
    margin: 0 auto;
  }
</style>

<dialog id="app-lightbox" aria-label="Enlarged app screenshot">
  <button type="button" autofocus>Close ×</button>
  <img alt="">
</dialog>

<script>
(() => {
  const viewer = document.getElementById('app-lightbox');
  if (!viewer || typeof viewer.showModal !== 'function') return;

  const image = viewer.querySelector('img');

  document.querySelectorAll('a.app-preview').forEach(link => {
    link.addEventListener('click', event => {
      // Preserve Ctrl-click / Cmd-click to open the PNG in a new tab.
      if (event.ctrlKey || event.metaKey || event.shiftKey || event.altKey) return;

      event.preventDefault();
      image.src = link.href;
      image.alt = link.querySelector('img').alt;
      viewer.showModal();
    });
  });

  viewer.querySelector('button').addEventListener('click', () => viewer.close());
})();
</script>
