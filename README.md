# RDF-SPARQL
Instructions for the labs sessions on RDF and SPARQL.

Python codes are presented using [Jupyter Notebook](http://jupyter.org/index.html). You can directly browse the following `.ipynb` files to start the lab.

1. [Lab-RDF.ipynb](https://nbviewer.jupyter.org/github/QMUL-ECS735P/RDF-SPARQL/blob/master/Lab-RDF.ipynb): get familiar with the Python language for creating simple Semantic Web programs, and know the RDFLib library to load and manipulate RDF graphs.

2. [Lab-SPARQL.ipynb](https://nbviewer.jupyter.org/github/QMUL-ECS735P/RDF-SPARQL/blob/master/Lab-SPARQL.ipynb): use SPARQL to query remotely semantic end points, merge RDF data from multiple sources, and visualise SPARQL queries.

You can either copy & paste the codes from the `.ipynb` files and run at a python console, or clone/download this repository to run the codes using Jupyter Notebook as introduced below.


### How to run python codes using Jupyter Notebook

#### If you are using ITL machines

The ITL machines should be already prepared to run the labs without further setup. 

1. Clone/Download the repository: run the following command at the Terminal
```
$ git clone https://github.com/QMUL-ECS735P/RDF-SPARQL.git
```

2. Launch the notebook by the following command:
```
$ jupyter notebook
```

This will present the notebook in your browser. You can navigate to the `RDF-SPARQL` folder and open a `.ipynb` file to run python code cell by cell. See [Running the Notebook](https://jupyter.readthedocs.io/en/latest/running.html#running) for more details.

#### If you are using your own computer

1. Install Python & Jupyter using Anaconda: we **strongly recommend** installing Python and Jupyter using the [Anaconda Distribution](https://www.anaconda.com/download/), which includes Python, the Jupyter Notebook, and other commonly used packages for scientific computing and data science. **We recommend downloading Anaconda’s latest Python 3 version.**

2. Clone/Download the repository: run the following command at the Terminal (Mac/Linux) or Command Prompt (Windows)
```
$ git clone https://github.com/QMUL-ECS735P/RDF-SPARQL.git
```

3. Install the requirements using pip, which is a package manager for Python packages. Pip is included in Anaconda so you do not need to install it.
```
$ cd RDF-SPARQL
$ pip install -r requirements.txt
```

4. Congratulations, you have installed Jupyter Notebook and required packages! To launch the notebook, run the following command:
```
$ jupyter notebook
```

This will present the notebook in your browser, then you can open a `.ipynb` file and run python code cell by cell. See [Running the Notebook](https://jupyter.readthedocs.io/en/latest/running.html#running) for more details.
