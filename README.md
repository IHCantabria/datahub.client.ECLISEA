<!-- logo -->
<p align="center"><img src="resources/eclisea.logo.png" alt="logo"></p>
<h2 align="center">datahub.client.ECLISEA</h3>


<!-- table of contents -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

# About The Project

This project contains notebooks with different usage examples for ECLISEA data.

The researcher will be able, with the help of the notebooks, to generate a code to work with the data in a simple way.


## Installation

To work with the different codes it is necessary to have [conda](https://www.anaconda.com/products/individual) (or [miniconda](https://docs.conda.io/en/latest/miniconda.html)).

To create an environment with the necessary dependencies we use the instruction:

```sh
conda env create -f environment.yml
```

Once we have the environment, we activate it

```sh
conda activate eclisea-jupyter
```

And we execute Jupyter, which will open a tab in the browser with its interface:

```sh
jupyter notebook
```