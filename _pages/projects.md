---
permalink: /projects/
title: "Projects"
toc: true
toc_label: "Projects"
---

A selection of things I've built and run. Everything is open source on
[GitHub](https://github.com/babsey?tab=repositories).

## Full-stack

### NEST Desktop

Lead developer since 2019. A web application for building, running and analysing spiking neural
network simulations in the browser, without writing code. Used in university teaching and available on the
EBRAINS research infrastructure. Published in
[eNeuro (2021)](https://doi.org/10.1523/ENEURO.0274-21.2021).

<span class="tag">Vue</span> <span class="tag">Vuetify</span> <span class="tag">TypeScript</span> <span class="tag">Python</span> <span class="tag">D3.js</span> <span class="tag">Plotly.js</span> <span class="tag">Three.js</span>

[Source](https://github.com/nest-desktop/nest-desktop){: .btn .btn--primary}
[Legacy version (Angular)](https://github.com/babsey/nest-desktop-legacy){: .btn .btn--inverse}

### nuSPIC

A competitive web application where users explore neural network simulations through a web
interface to the NEST simulator (2010 – 2013). Published in
[Frontiers in Neuroinformatics (2013)](https://doi.org/10.3389/fninf.2013.00043).

<span class="tag">Django</span> <span class="tag">Python</span> <span class="tag">JavaScript</span>

## DevOps

### NEST Desktop on Rancher

Deployment setup for running NEST Desktop and its simulation backend on a Rancher-managed cluster.

<span class="tag">Rancher</span> <span class="tag">Docker</span> <span class="tag">Kubernetes</span>

[Source](https://github.com/babsey/nest-desktop-rancher){: .btn .btn--primary}

### NEST in containers

Container images for the NEST simulator, built with Apptainer/Singularity for HPC environments
and with Docker.

<span class="tag">Apptainer</span> <span class="tag">Singularity</span> <span class="tag">Docker</span> <span class="tag">Bash</span>

[Singularity](https://github.com/babsey/nest-simulator-singularity){: .btn .btn--primary}
[Docker](https://github.com/babsey/nest-docker-grabber){: .btn .btn--inverse}

### NEST Web API

An early web API for driving NEST simulations over HTTP. It preceded the REST server that NEST
ships with today.

<span class="tag">Python</span> <span class="tag">Flask</span> <span class="tag">REST</span>

[Source](https://github.com/babsey/nest-web-api){: .btn .btn--primary}

## Agentic coding & code generation

### Code Graph

A modular code generator: compose nodes into a graph and generate runnable code from it.

<span class="tag">TypeScript</span> <span class="tag">Code generation</span>

[Source](https://github.com/babsey/code-graph){: .btn .btn--primary}

### NEST Lab Xircuits

NEST projects for the Xircuits JupyterLab extension: simulations built as visual workflows that
compile to Python.

<span class="tag">Python</span> <span class="tag">JupyterLab</span> <span class="tag">Visual programming</span>

[Source](https://github.com/babsey/nest-lab-xircuits){: .btn .btn--primary}

### This website

Rebuilt with an AI coding agent: reviewing the old setup, restructuring it, porting the CV data and
setting up a GitHub Actions deployment, all as reviewed pull requests.

<span class="tag">Jekyll</span> <span class="tag">GitHub Actions</span> <span class="tag">AI agents</span>

[Source](https://github.com/babsey/babsey.github.io){: .btn .btn--primary}

## Research code

### Spatio-temporal activity sequences

Simulation code for [From space to time (PLoS Comput Biol, 2019)](https://doi.org/10.1371/journal.pcbi.1007432).

<span class="tag">Python</span> <span class="tag">NEST</span> <span class="tag">NumPy</span>

[Source](https://github.com/babsey/spatio-temporal-activity-sequence){: .btn .btn--primary}
