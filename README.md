## Aimed at: 
Anyone interested in using Python for Biomodelling. The material in 
this workshop will help you get the most out of the other workshops 
run during the week.

## Requirements: 
Basic knowledge of Python e.g. as in [https://chryswoods.com/beginning_python](https://chryswoods.com/beginning_python)

## Abstract: 
This workshop will introduce more intermediate features of Python that 
are useful for biomolecular modellers. This will include the use of 
Jupyter notebooks, how to write Python functions and classes, and 
how to properly structure, document and test code. The second
part will introduce you to data analysis tools such as Pandas, 
NumPy and MatplotLib.

## Training Material

The workshop consists of a series of Jupyter notebooks. These are available
below, and can be run using the
<a href="https://workshop.biosimspace.org/hub/tmplogin" target="_blank">workshop Jupyter server</a>.

Start the server by <a href="https://workshop.biosimspace.org/hub/tmplogin" target="_blank">clicking here</a>.
This will open a Jupyter notebook interface. Be patient as this may take 30-60 seconds.
Once this has opened, navigate to the `python_and_data` directory and you will find the
notebooks there.

The workshops are numbered sequentially from `01_jupyter_howto.ipynb` to
`17_regular_expressions.ipynb`. They cover a variety of useful Python topics,
and are *mostly* independent. Feel free to go through them in the order you
prefer, and to skip topics that you feel you are already comfortable with.

There are exercises in many of the topics. You can find answers in the 
equivalent notebook in the `answers` directory.

Below is a summary of each topic, together with links to view html versions
of the notebooks the their answers, and to download the notebooks.

## Contents

### [01_jupyter_howto.ipynb](01_jupyter_howto.html) ([answers](answers/01_jupyter_howto.html))

Introduction to Jupyter notebooks, including how to use the interface,
how to view molecules, draw graphs, download files, and start a bash
terminal.

[download](html/01_jupyter_howto.ipynb) | [download answers](html/answers/01_jupyter_howto.ipynb)

### [02_lists.ipynb](02_lists.html) ([answers](answers/02_lists.html))

Something

[download](html/02_lists.ipynb) | [download answers](html/answers/02_lists.ipynb)

### [03_dictionaries.ipynb](03_dictionaries.html) ([answers](answers/03_dictionaries.html))

Something

[download](html/03_dictionaries.ipynb) | [download answers](html/answers/03_dictionaries.ipynb)

### [04_functions.ipynb](04_functions.html) ([answers](answers/04_functions.html))

Something

[download](html/04_functions.ipynb) | [download answers](html/answers/04_functions.ipynb)

### [05_objects.ipynb](05_objects.html) ([answers](answers/05_objects.html))

Something

[download](html/05_objects.ipynb) | [download answers](html/answers/05_objects.ipynb)

### [06_classes.ipynb](06_classes.html) ([answers](answers/06_classes.html))

Something

[download](html/06_classes.ipynb) | [download answers](html/answers/06_classes.ipynb)

### [07_documentation.ipynb](07_documentation.html) ([answers](answers/07_documentation.html))

Something

[download](html/07_documentation.ipynb) | [download answers](html/answers/07_documentation.ipynb)

### [08_class_documentation.ipynb](08_class_documentation.html) ([answers](answers/08_class_documentation.html))

Something

[download](html/08_class_documentation.ipynb) | [download answers](html/answers/08_class_documentation.ipynb)

### [09_exceptions.ipynb](09_exceptions.html) ([answers](answers/09_exceptions.html))

Something

[download](html/09_exceptions.ipynb) | [download answers](html/answers/09_exceptions.ipynb)

### [10_error_handling.ipynb](10_error_handling.html) ([answers](answers/10_error_handling.html))

Something

[download](html/10_error_handling.ipynb) | [download answers](html/answers/10_error_handling.ipynb)

### [11_modules.ipynb](11_modules.html) ([answers](answers/11_modules.html))

Something

[download](html/11_modules.ipynb) | [download answers](html/answers/11_modules.ipynb)

### [12_pandas.ipynb](12_pandas.html) ([answers](answers/12_pandas.html))

Something

[download](html/12_pandas.ipynb) | [download answers](html/answers/12_pandas.ipynb)

### [13_basic_numpy.ipynb](13_basic_numpy.html) ([answers](answers/13_basic_numpy.html))

Something

[download](html/13_basic_numpy.ipynb) | [download answers](html/answers/13_basic_numpy.ipynb)

### [14_more_numpy.ipynb](14_more_numpy.html) ([answers](answers/14_more_numpy.html))

Something

[download](html/14_more_numpy.ipynb) | [download answers](html/answers/14_more_numpy.ipynb)

### [15_matplotlib.ipynb](15_matplotlib.html) ([answers](answers/15_matplotlib.html))

Something

[download](html/15_matplotlib.ipynb) | [download answers](html/answers/15_matplotlib.ipynb)

### [16_viewing_molecules.ipynb](16_viewing_molecules.html) ([answers](answers/16_viewing_molecules.html))

Something

[download](html/16_viewing_molecules.ipynb) | [download answers](html/answers/16_viewing_molecules.ipynb)

### [17_regular_expressions.ipynb](17_regular_expressions.html) ([answers](answers/17_regular_expressions.html))

Something

[download](html/17_regular_expressions.ipynb) | [download answers](html/answers/17_regular_expressions.ipynb)

## How to download to run at home

While this workshop is running using cloud servers generously supplied
by [Microsoft Azure](https://azure.microsoft.com/en-us/services/container-service/kubernetes/),
you can also download and run this workshop on your own computer if
you are using docker (and your computer has an X86-64 processor that
supports AVX, e.g. like most Intel processors since 2011). To run on
your own computer type;

```
docker run -it --rm -p 8888:8888 chryswoods/bss-workshop:latest
```

This will download the image (may take a while...) and will run it on
your computer. It will print out the URL of the notebook which you should navigate
to in your browser (it will look something like `http://localhost:8888/?token=7f4b6be12ff1cec13903d0f27bab2ad7ea3eeaa9f0098dee`)
