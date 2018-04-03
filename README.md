# Python for Biomolecular Modellers, Parts 1 and 2

## Aimed at: 
Anyone interested in using Python for Biomodelling. The material in 
this workshop will help you get the most out of the other workshops 
run during the week.

## Requirements: 
Basic knowledge of Python e.g. as in https://chryswoods.com/beginning_python

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
[workshop jupyter server](https://workshop.biosimspace.org/hub/tmplogin).

Start the server by [clicking here](https://workshop.biosimspace.org/hub/tmplogin).
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

### [01_jupyter_howto.ipynb](01_jupyter_howto.ipynb) ([answers](answers/01_jupyter_howto.ipynb))

Introduction to Jupyter notebooks, including how to use the interface,
how to view molecules, draw graphs, download files, and start a bash
terminal.

[html](html/01_jupyter_howto.html) | [answers](html/answers/01_jupyter_howto.ipynb)

### [01_jupyter.ipynb](01_jupyter.ipynb) ([answers](answers/01_jupyter.ipynb))

Introduction to Jupyter notebooks, including how to use the interface,
how to view molecules, draw graphs, download files, and start a bash
terminal.

[html](html/01_jupyter.html) | [answers](html/answers/01_jupyter.ipynb)

