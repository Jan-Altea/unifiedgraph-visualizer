# VsML PSV Demo

Explore how a platform supply vessel (PSV) is represented in a federated manner. The demo connects a 3D vessel model with ship systems, design calculations, and business relationships, linking ontologies across business, maths, functional, and spatial layers.

**[Open the interactive demo](https://jan-altea.github.io/unifiedgraph-visualizer/)** · [VsML instance data](https://vsml.no/#instance)

- **Integrated View** shows connections between the model layers and lets you query them.
- **Spatial & Scene** includes the Rhino vessel model and its USD scene hierarchy.
- **Logic and Business** show the relationships within each layer.

To try a design change, open the SPARQL query panel in Integrated View, select **Length +10% (LPP = LOA)**, and run it. The results distinguish calculated changes from dependencies that need review.

This repository publishes the compiled demo and its PSV assets through GitHub Pages. The example calculations are for demonstration and have not been validated for engineering use.
