# rv
Just like ["***fv***"](https://heasarc.gsfc.nasa.gov/ftools/fv/) from *ftools* (NASA).
## Description
Viewer app for table data powered by [Shiny](https://shiny.rstudio.com) and [Plotly](https://plotly.com/r/) using [`R`](https://www.r-project.org). This app can handle `csv`, `tsv`, `fits` (table only) data. Not only it can show the table content itself, but also is possible to summarize information of columns and show a simple plot, interactively. 

## Usage
```
# In terminal,
$ rv iris.csv
$ rv btable.fits
$ rv iris.csv btable.fits
```

## Installation
> 
1. Download into `"/some/rv/directory/"`
2. In your shell environment, add the path such as:

```
# For bash, 
$ vi ~/.bashrc

# Append this line:
export PATH="/some/rv/directory/:$PATH"
```

