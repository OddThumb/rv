# rv

## Description
Viewer app for table data. This app can handle csv, tsv, fits data. Not only it can show the table contents itself, but also is possible to summarize information of the column and plot, interactively.

## Usage
```
# In terminal,
$ rv iris.csv
$ rv btable.fits
$ rv iris.csv btable.fits
```

## Installation
1. Download into `"/some/rv/directory/"`
2. In your shell environment, add the path such as:

```
# For bash, 
$ vi ~/.bashrc

# Append this line:
export PATH="/some/rv/directory/:$PATH"
```

