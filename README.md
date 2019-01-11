# RDF-SPARQL
Codes for the labs sessions on RDF and SPARQL.

Read-only python scripts are presented using [Jupyter Notebook](http://jupyter.org/index.html), which you can directly browse the `.ipynb` files here.

1. [Lab-RDF.ipynb](https://nbviewer.jupyter.org/github/QMUL-ECS735P/RDF-SPARQL/blob/master/Lab-RDF.ipynb): get familiar with the Python language for creating simple Semantic Web programs, and know the RDFLib library to load and manipulate RDF graphs.

2. [Lab-SPARQL.ipynb](https://nbviewer.jupyter.org/github/QMUL-ECS735P/RDF-SPARQL/blob/master/Lab-SPARQL.ipynb): use SPARQL to query remotely semantic end points, merge RDF data from multiple sources, and visualise SPARQL queries.


### How to launch jupyter notebook & run python code locally

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

This will present the notebook in your browser, then you can open the `.ipynb` file and run python script cell by cell. See [Running the Notebook](https://jupyter.readthedocs.io/en/latest/running.html#running) for more details.

#### If you are using a managed desktop at ITL

TBC
