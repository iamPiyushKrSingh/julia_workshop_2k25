# Julia Workshop Notebooks

This repo contains all the notebooks which are used in Julia Workshop conducted by Slashdot, IISER Kolkata.

Topics covered in the workshop:

- Basic REPL commands & Features
- Introduction to Julia
- Data Structures
- Functions and Modules
- Plotting with Plots.jl
- DataFrames.jl
- Working with CSV files
- Basic Statistics
- Linear Algebra

Advanced topics:

- Parallel Computing
- Meta-programming

## How to follow along the workshop

Few things to keep in mind, we have designed this workshop to be conducted in Computer Centre (CC) of IISER Kolkata. So, first thing you need to do is to install Julia in your system. You can download the latest version of Julia just by running the following command in your terminal:

```bash
curl -fsSL https://install.julialang.org | sh
```

After installing Julia, you can start the Julia REPL by running the following command in your terminal:

```bash
julia
```

To run the notebooks, you will need a Julia package called `IJulia`, which provides a Jupyter notebook interface for Julia. You can install it by running the following command in the Julia REPL:

```julia
using Pkg
Pkg.add("IJulia")
```

After installing the package, you can start the Jupyter notebook server by running the following command in the Julia REPL:

```julia
using IJulia
notebook()
```

${\color{red}\textsf{It may happen that you don't see the Julia kernel in Jupyter Notebook.}}$

In that case, you can manually install the Julia kernel for Jupyter by running the following command in the Julia REPL:

```julia
using IJulia
installkernel("Julia")
```

### Structure of the Workshop Notebooks

The workshop notebooks are structured in a way that each topic is covered in a separate notebook. You can find the notebooks in the `notebooks` directory. Each notebook contains code examples, explanations, and exercises to help you understand the concepts better.

The notebooks are organized as follows:

- [`00_repl_and_more.ipynb`](./notebooks/00_repl_and_more.ipynb): Introduction to the Julia REPL, basic commands, and features.
- [`01_introduction_to_julia.ipynb`](./notebooks/01_introduction_to_julia.ipynb): Introduction to Julia, its features, and basic syntax.
- [`02_data_structures.ipynb`](./notebooks/02_data_structures.ipynb): Introduction to data structures in Julia, including arrays, tuples, and dictionaries.
- [`03_iterators.ipynb`](./notebooks/03_iterators.ipynb): Introduction to iterators and loops in Julia.

## Requirements

In this workshop, I assume that you have some basic knowledge of programming concepts like variables, control flow, and functions.

From the software side, you will need the following:

- Julia 1.11 or later
- Jupyter Notebook or JupyterLab:
