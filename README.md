CSW cookiecutter project
====================

A cookiecuter project used within CSW

Requirements
------------
Install `cookiecutter` command line: `pip install cookiecutter`    

Usage
-----
To start a new science project:

`cookiecutter gh:menno94/cookiecutter-csw`

Project Structure
-----------------

```
.
├── AUTHORS.md
├── LICENSE
├── README.md
├── Project_management <- documents related to project management
├── References         <- References
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
├── simulations     <- folder with simulations
├── results         <- results
├── reports         <- For a manuscript source, e.g., LaTeX, Markdown, etc., or any project reports
│   └── figures        <- Figures for the manuscript or reports
└── scripts            <- scripts for this project
    ├── data           <- scripts and programs to process data
    ├── external       <- Any external source code, e.g., pull other git projects, or external libraries
    ├── models         <- Source code for your own model
    ├── tools          <- Any helper scripts go here
    └── visualization  <- Scripts for visualisation of your results, e.g., matplotlib, ggplot2 related.
```

Check out my latest research project, which successfully applied the `cookiecutter` philosophy: [SEMIC: an efficient surface energy and mass balance model applied to the Greenland ice sheet](https://gitlab.pik-potsdam.de/krapp/semic-project).

License
-------
This project is licensed under the terms of the [BSD License](/LICENSE)
