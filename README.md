# COPS Cookbook

<img src="thumbnails/cops_logo.png" alt="thumbnail" width="300"/>

[![nightly-build](https://github.com/huangynj/cookbook_test/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/huangynj/cookbook_test/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/huangynj/cookbook_test/main?labpath=notebooks)

This cookbook provides practical, reproducible examples for using the **Cloud Optical-array probe Processing Software (COPS)**.
The focus is on **hands-on notebooks** that demonstrate how to process and analyze optical array probe data.

---

## Motivation

The goal of this cookbook is to provide a comprehensive guide for researchers and developers working with COPS.
By the end of the cookbook, readers will be able to:

- Understand the structure of a reproducible scientific workflow
- Run and modify Jupyter notebooks interactively
- Adapt the provided examples to their own research or applications

---

## Authors

[Yongjie Huang](https://huangynj.github.io)

### Contributors

<a href="https://github.com/huangynj/cookbook_test/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=huangynj/cookbook_test" />
</a>

---

## Structure

This cookbook is organized into the following sections:

### 1. Foundations

This section introduces the core concepts, datasets, and Python tools used throughout the cookbook.  
It is intended to build the necessary background for the example workflows.

### 2. Example Workflows

This section contains complete, end-to-end notebook examples demonstrating how to apply the concepts introduced in the foundations section to real problems.

---

## Running the Notebooks

You can run the notebooks either **online using Binder** or **locally on your own machine**.

### Running on Binder

The simplest way to interact with the notebooks is through
[Binder](https://binder.projectpythia.org/).

1. Click the **Binder badge** at the top of this README
2. Wait for the environment to launch
3. Open a notebook and run cells using `Shift + Enter`

Binder allows you to execute and modify the notebooks without installing anything locally.

---

### Running on Your Own Machine

To run the notebooks locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/huangynj/cookbook_test.git
   cd cookbook_test
   ```

2. Create the environment:
   ```bash
   conda env create -f environment.yml
   conda activate cookbook-dev
   ```

3. Start the server:
   ```bash
   myst start
   ```

This will start a local web server and open the cookbook in your browser.
