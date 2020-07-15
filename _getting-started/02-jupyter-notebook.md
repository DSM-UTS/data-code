---
title: Jupyter Notebook
order: 2
excerpt: How to use the Jupyter Notebook and SWAN
last_modified_at: "July 10, 2019"
---

## CloudStor

![CloudStor-logo.png](https://CloudStor.aarnet.edu.au/plus/s/pwXdzeYzcZPxqw9/download)

**CloudStor** is a "file sharing and cloud storage solution for the research and education sector" (more information [here](https://www.aarnet.edu.au/network-and-services/cloud-services-applications/CloudStor)) offered by Australia’s Academic and Research Network (AARNet).

Basically, CloudStor is a service like Dropbox as it allows to store files online and optionally sync a folder located on your computer and all its files. 

UTS students (and staff) have access to the service (you also get out of the box 1TB of cloud storage).
  

To access CloudStor, you need to

1. Point your browser to [cloudstor.aarnet.edu.au](https://cloudstor.aarnet.edu.au/);

2. Login with your UTS credentials by selecting your institution (you need to search for "University of Technology Sydney" and not "UTS");

3. Accept the "Terms And Conditions Of Service" (don't worry, they won't sell your data - it's a not-for-profit service funded by the Australian government!).

If you want to take advantage of all the features offered by CloudStor --  including automatically syncing files located on your computer, you can have a look at [this guide](https://support.aarnet.edu.au/hc/en-us/articles/227469547-CloudStor-Getting-Started-Guide).

## Jupyter Notebook

<img src="https://CloudStor.aarnet.edu.au/plus/s/wp8ozshID6Aq2rF/download" alt="jupyter-logo" width="150">
  
**Jupyter Notebook** is a web application that allows you to interact with a document that contains live code.

Jupyter Notebook is part of the *Jupyter Project* which "exists to develop open-source software, open-standards, and services for interactive computing across dozens of programming languages." ([https://jupyter.org/](https://jupyter.org/))

When you reach a Jupyter web application, you will see something like this
  
![jupyter-dashboard](https://CloudStor.aarnet.edu.au/plus/s/Q3NPc7B5cv5Tuey/download)

At this point you can either create your interactive notebook (in Python or in any other supported programming languages) or open an existing file. A Python notebook is expected to have this extension: `.ipynb`.


### Notebook user interface

*Adapted from [here](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html\#notebook-user-interface).*

![jupyter-notebook-ui](https://CloudStor.aarnet.edu.au/plus/s/1K0ZuFi9rgp6ZgO/download)

* **Menu bar** The menu bar presents different options that may be used to manipulate the way the notebook functions.

* **Toolbar** The tool bar gives a quick way of performing the most-used operations within the notebook, by clicking on an icon. 

* **Code cell** The default type of cell. (But there are also markdown cells and raw cells).

### Structure of a notebook document

*Adapted from [here](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html\#structure-of-a-notebook-document).*

The notebook consists of a sequence of cells. A cell is a multiline text input field, and its contents when the cell is selected can be executed

* by using `Shift-Enter`;
* by clicking the "Play" button in the *toolbar*;
![jupyter-run-toolbar](https://CloudStor.aarnet.edu.au/plus/s/h7zsbwCyYEwfyuo/download)
* by clicking "Cell" -> "Run" in the *menu bar*.

### Code cells

*Adapted from [here]( https://jupyter-notebook.readthedocs.io/en/stable/notebook.html\#code-cells).*

A code cell allows you to edit and write new code, with full syntax highlighting that can help you detect possible errors. The programming language you use depends on the kernel, and the default kernel (IPython) runs Python code.

When a code cell is executed, code that it contains (as appears in the *display area* of the cell) is sent to the kernel associated with the notebook. The results that are returned from this computation are then displayed in the notebook as the cell's *output*. 

![jupyter-display-area](https://CloudStor.aarnet.edu.au/plus/s/rmzlYGqBYpfXjjC/download)
![jupyter-output-area](https://CloudStor.aarnet.edu.au/plus/s/XbRpPY2mazxBT27/download)


### Code cells

 Finally, the *input area* "is identified by the `In []:` prompt to the left of the cell. Between the brackets of the `In` prompt can be one of three items: *a number*, *an asterisk*, or *a blank*. A number indicates that this cell has been executed and the value of the number indicates the order of execution. For example, normally, after you execute the first cell after opening a notebook, its prompt will read `In [1]:`" (From [https://jupyter4edu.github.io/jupyter-edu-book/jupyter.html\#using-jupyter-notebooks](https://jupyter4edu.github.io/jupyter-edu-book/jupyter.html\#using-jupyter-notebooks)).

![jupyter-input-area](https://CloudStor.aarnet.edu.au/plus/s/QonWeNKSwEZ5yJe/download)

### Workflow

With a Jupyter Notebook, there are two possible workflow scenarios:

1. You create new cells and run them (for example, writing your own *project code*);
2. You edit and run existing cells (for example, doing *code exercises*).


#### Workflow for code exercises

When completing code exercises, you'll have your own notebook files where you can edit the code cells.

 It is suggested that before editing the cells, you make a copy of the file by clicking "File"  -> "Make a Copy..." in the menu bar.

After *editing* the code cell, you'll *run* it (see above if you forgot how!) and *inspect the output*. You can also save your edits by clicking "File"  -> "Save and Checkpoint..." in the menu bar (In a notebook, you can revert to different checkpoints that are different versions of the same document.).

If you want to clear all the output of the entire notebook, you can click "Kernel" -> "Restart & Clear Output" in the menu bar.

**Autosave**:  Jupyter Notebook will autosave all the edits you do to the file (and this includes the output after you run a cell). If you want to restart with an unedited file you can either download the original file again or keep a copy of it in your own folder. 

## CloudStor + Jupyter Notebook = SWAN

A Jupyter notebook will require a *kernel* to offer its interactive features (like running code). A kernel is an engine that executes the code and sends back the results to the user. Again, a notebook is not a simple document; it's an interactive document since you can run *cells* containing code.

Conveniently, CloudStor offers that kernel with **SWAN** (Service for Web-based ANalysis).

![swan-logo](https://CloudStor.aarnet.edu.au/plus/s/musvpeY3OfhnAdF/download)

To access SWAN from CloudStor, you need to

1. Point your browser to https://CloudStor.aarnet.edu.au/ and login;

2. Click on the SWAN button in the toolbar of CloudStor's web interface; ![swan-toolbar-button](https://CloudStor.aarnet.edu.au/plus/s/TdxJNpwKPiO0i9N/download)

3. If you don't have an active session you will need to start it by clicking "Start My Notebook Session".

![swan-start-my-session](https://cloudstor.aarnet.edu.au/plus/s/CrQRnJi5ccWfF9a/download)

4. What you  now see is your SWAN dashboard.

![swan-dashboard](https://cloudstor.aarnet.edu.au/plus/s/T02sRtakDessAP5/download)

### Using SWAN

#### Launching a new blank Jupyter Notebook

You can launch and create a new notebook by clicking on the "Python 3" icon. A new file will be created in your temporary directory.

**Danger!** If you want to save a notebook, make sure to move the file out of the temporary directory and into your CloudStor. 
{: .notice--danger}

[!swan-directory](https://cloudstor.aarnet.edu.au/plus/s/XyVpum5Mm4FeRbp/download)

You can also rename the new notebook by right-click on the file name.

![swan-new-notebook](https://cloudstor.aarnet.edu.au/plus/s/uFQDEdNztUBUpKj/download)



