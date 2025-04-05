# Interactive Notebooks for Element of Electronic Structure Theory

## Purpose

This repository contains a series of interactive Jupyter notebooks to showcase
various aspects of the book [Elements of Electronic Structure Theory](https://ifilot.pages.tue.nl/elements-of-electronic-structure-theory/index.html). 
You can easily open these notebooks via the MyBinder platform. Below, you can 
find a list of all the interactive notebooks.

> [!TIP]
> * The latest version of the textbook can be obtained [via this link](https://www.dropbox.com/s/8umppsfxwqdzb30/elements-of-electronic-structure-theory-filot.pdf?dl=1)
> * For more information about the course book and other associated electronic
>   resources, please visit [this link](https://ifilot.pages.tue.nl/elements-of-electronic-structure-theory/index.html)

> [!NOTE]
> Spot a mistake in any of the notebooks? Please 
> [raise van issue](https://github.com/ifilot/electronic-structure-interactive-notebooks/issues/new).

## Local installation

> [!NOTE]
> We assume that the user is already familiar with using Python and installing 
> packages in a development environment. The installation instructions provided 
> below are intentionally brief and meant as a quick reference.


To run these notebooks locally, it is recommended to use Python version 3.12 or
newer. First, create a virtual environment (optional but recommended):

```
python -m venv venv  
source venv/bin/activate        # On Windows: venv\Scripts\activate
```

Next, install all required packages using the provided requirements.txt file:

```
pip install -r requirements.txt
```

Finally, launch JupyterLab with:

```
jupyter lab
```

This will open JupyterLab in your default web browser. From there, you can navigate to and run the notebook interactively.

Note: If JupyterLab is not already installed, it will be installed automatically
through the requirements file.

## Interactive notebooks via MyBinder.org

If you're running this notebook via [mybinder.org](https://mybinder.org), please be aware that the service does not always operate reliably. You may occasionally encounter issues such as **"Internal Server Error"**, long loading times, or sluggish performance.

It's important to remember that **mybinder is a free, community-supported service**, and such limitations are to be expected. We should be empathetic to the fact that this generous resource is offered without cost and maintained by volunteers and open-source contributors.

The **links provided below** will take you to the **mybinder.org website**, where this notebook will be launched in a temporary online environment. No installation is needed — it's a great way to try things out quickly — but please keep in mind that performance and availability can vary.

For the **best performance and stability**, we recommend downloading the notebook and running it locally using **JupyterLab** or **Jupyter Notebook** on your own machine. This ensures faster load times, smoother interactivity, and a more responsive coding experience overall.

### Chapter 1

* [Completeness demo](https://mybinder.org/v2/gh/ifilot/electronic-structure-interactive-notebooks/master?urlpath=%2Fdoc%2Ftree%2Fchapter01%2Fcompleteness-demo.ipynb)
* [Parametric variational method](https://mybinder.org/v2/gh/ifilot/electronic-structure-interactive-notebooks/master?urlpath=%2Fdoc%2Ftree%2Fchapter01%2Fparametric-variational-method.ipynb)
* [Linear variational method](https://mybinder.org/v2/gh/ifilot/electronic-structure-interactive-notebooks/master?urlpath=%2Fdoc%2Ftree%2Fchapter01%2Flinear-variational-method.ipynb)

### Chapter 2

* [Visualization of atomic orbitals](https://mybinder.org/v2/gh/ifilot/electronic-structure-interactive-notebooks/master?urlpath=%2Fdoc%2Ftree%2Fchapter02%2Fatomic-orbital-visualization.ipynb)
* [Finding atomic orbitals via linear variational principle](https://mybinder.org/v2/gh/ifilot/electronic-structure-interactive-notebooks/master?urlpath=%2Fdoc%2Ftree%2Fchapter02%2Fatomic-orbital-minimization.ipynb)