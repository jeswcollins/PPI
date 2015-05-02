# PPI
Interactive protein-protein network visualization based on [vis.js](http://visjs.org/).

Based on discussions with colleagues Phil Snyder (Vertex) and Venky Soundararajan (nference), I decided to start putting together a protein-protein interaction network visualization. 

The idea was to see if we could find any second-order effects of a small molecular therapeutic. Such molecules might target one or more proteins, and inhibiting or activating one protein might be a way to cure a disease. But what other proteins does the small molecule interact with? Moreover, what proteins do the original protein target, and any unintended targets, interact with? Can we predict effects from such 2nd degree interactions in a precise, even personalized way to improve clinical trials, reduce potential for toxicity, or design improved therapeutics?

I performed such a network analysis, based on data at http://string-db.org/, to find potential means by which VX-680, a small molecule anti-cancer therapeutic, might cause unintended effects on the heart: CXCR4 (via FLT3), MEF2A & MEF2C (via ABL1), DLG1 (via BCR).

VX680 interactions:
![VX680](images/vx680.png)

MEF2A:
![MEF2A](images/MEF2A.png)
