# Simple Samples of the Zoomdata JavaScript Client Library

This directory contains a set of HTML files, each demonstrating functions available in the Zoomdata JavaScript client library.

## What's In The Box?

### changeColorAndFilter.html
The sample demonstrates the following:
* Embedding a visualization
* Using HTML controls with a visualization
* Changing color scheme at runtime
* Changing filters at runtime

### dataQuery_tabular.html
The sample demonstrates the following:
* Configuring a data query
* Running a data query with the run() method
* Using data from a query to build a table
* Making the table pretty using the [DataTables library](https://www.datatables.net/).

###simplesample.css
Optional - the CSS used to make the samples pretty

## Running the Samples

1. Make sure you have a simple server like http-server available at NPM.

1. Clone this repository.

1. On the command line, navigate (cd) to the simpleSamples folder.

1. Run `http-server`.

1. Open in a text editor the sample that you wish to run.

1. Search for each instance of the string _XYZ_.

1. Replace each instance with server or credential information as indicated by surrounding comments.

1. Open your browser and point it to `localhost:8080\SAMPLE-TO-RUN.html`, for example, `localhost:8080\dataQuery_tabular.html`.

## Credits and Resources

Contributed by Zoomdata employee Ryan H.

[DataTables library](https://www.datatables.net/) helped make our data pretty.