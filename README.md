# Error Correction
This repo contains a Jupyter notebook focused on quantum error correction, stabilizer codes, and graph states. These are used in creating quantum algorithms that are meant to be robust against noise. Graph states can also be used in quantum cryptography and as a tool for verifying error correction on quantum computers, since certain classes of graph codes can be efficiently simulated on classical computers. 

---

## The Notebook

[Interactive Jupyter Notebook in Binder](https://github.com/The-Singularity-Research/error-correction/blob/master/error_correction.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/The-Singularity-Research/error-correction/master?filepath=error_correction.ipynb)


## The Shor Code

One well known example of error correction is the Shor code on nine qubits. It is capable of correcting arbitrary qubit errors. The circuit that prepares this state can be seen below. 

![Shor Code](Shor_code_v2.png)

This quantum circuit diagram was rendered in [quantikz](https://ctan.org/pkg/quantikz?lang=en), a TikZ library. If you are a Donald Knuth fan and love LaTeX as much as we do, check it out!


## Stabilizer Codes and Graph States

Stabilizer codes and graph states can be shown to be equivalent. Graph states can be defined in terms of graphs, such as the following:

![Graph](graph_state_graph.png)

The resulting quantum circuit diagram can be visualized in Qiskit:

![Graph State](graph_state.png)

These kinds of codes are useful in many applications such as error correction, efficient simulation of certain classes of quantum circuits, one-way or measurement based quantum computing, and various others. 

## Interested in contributing to this project? 
- Reach out via email to: thesingularity.research@gmail.com
- Be sure to include "Hacking the Universe" in the subject line, so that the email doesn't get overlooked. 
- Write a paragraph or two about how you would like to contribute.
- Ask to Join the Discord server. 
- Ask to Join the Slack Channel.

This is course material for a course on linear algebra and mathematical prerequisites for quantum computing. It contains Jupyter notebooks that can be downloaded as part of the course or opened in Binder as an online interactive notebook. 

[Become a Sponsor of The Singularity](https://github.com/sponsors/The-Singularity-Research)
