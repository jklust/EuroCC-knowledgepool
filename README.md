# EuroCC-knowledgepool
Knowledge pool [documentation page](https://deic-hpc.github.io/EuroCC-knowledgepool/) for the danish EuroHPC competence center

## Setup
The webpage is created using [MkDocs](https://www.markdownguide.org/). This means that you only have to write markdown documents which then is translated to HTML files by MkDocs.

It is easy to use. The configuration file (*mkdocs.yml*) is placed in the root folder, and contains the layout of the webpage. 

The files which can be edited is in the folder *develop*.

New files can be created by making a new markdown file in the *develop* folder, and adding its name in the configuration file *mkdocs.yml*.

After any changes to the markdown files, the corresponding HTML files can be updated by running 

```
$ mkdocs build
```

in the folder containing the configuration file *mkdocs.yml*. The updated HTML files appear in their respective folders. After this the work can be pushed to git and the webpage is updated.

Everything can also be seen in your own browser while developing by running

```
$ mkdocs serve
```

once run you must crtl-click on the http link, or copy it into your browser.

Note that the DeiC pages [Basics of HPC](https://www.deic.dk/da/Supercomputere/Vejledninger-og-guides/Basics-of-HPC), [Best practices of HPC](https://www.deic.dk/da/Supercomputere/Vejledninger-og-guides/Best-practices-for-HPC), and [HPC programming](https://www.deic.dk/da/Supercomputere/Vejledninger-og-guides/HPC-Programming) are all copied from the git as well. Therefore one should take care that these are parsed correctly when updating the knowledge pool (note that there is a 24 hour lag before the DeiC page is updated). However, there should be no problems as long as simple markdown are used.

## Installation of MkDocs
MkDocs can be installed via pip

```
$ pip install mkdocs
```

and apt

```
$ sudo apt install mkdocs
```

You must also install some additional dependencies

```
$ pip install mkdocs-material pymdown-extensions mkdocs-pdf-export-plugin
```
