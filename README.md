# EuroCC-knowledgepool
Knowledge pool documentation page for the danish EuroHPC competence center

## Setup
The webpage is created using [MkDocs](https://www.markdownguide.org/). This means that you only have to write markdown dokuments which then is translated to HTML files by MkDocs.

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
