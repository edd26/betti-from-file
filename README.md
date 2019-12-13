Jupyter notebook file for loading a symmetric matrix form a file and computing its clique topology.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
In order to run jupyter notebook with julia code, IJulia mus be installed to the julia enviroment. After launching julia in terminal, type following commands:

```
using Pkg
Pkg.add("IJulia")
```
After installing IJulia, you can quit julia application and verify installation.

More details on IJulia:
* [IJulia](https://github.com/JuliaLang/IJulia.jl)

### Installation verification

Launch jupyter notebook from terminal:
```
jupyter notebook
```
If the installation was successful, you should be able to create new notebook with Julia kernel (the upper right corner). This is presented on image below:

![New julia notebook](https://raw.githubusercontent.com/edd26/betti-from-file/master/docs/new_julia_notebook.png)

### Usage

Launch jupyter notebook from terminal:
```
jupyter notebook
```
Then run 'get_betti_from_file.ipynb'. Packages required for running the code 
can be installed with code included in the notebook file. 

