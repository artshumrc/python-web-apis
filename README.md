# Python Web API Workshop Materials: Fall 2019

This repository contains example code to use in learning to work with RESTful
web APIs in Python. The main notebook file is called `harvard_art_museum_api.pynb`.

You will need authentication credentials from two sources:
- Harvard Art Museum API key set up via [Harvard Art Museum site](https://www.harvardartmuseums.org/collections/api)
- GeoNames account (from [GeoNames login page](https://www.geonames.org/login))`

You can download the repository either with
- `git clone https://github.com/artshumrc/python-web-apis.git` from the terminal,
- or by clicking the green button towards the top right that says "Clone or download" and clicking "Download ZIP".
Make sure you're grabbing the code from the Fall 2019 branch!

The code uses Python 3.7 with the `requests`, `pandas`, and `folium` modules. We recommend the Anaconda distribution of Python, which comes with everything that we’ll use for the workshop. Be sure to get the Python 3.7 version (Python 2 is a totally different beast and will reach end of life in December 2019). It’s a rather large download, so be sure to install it before you get to the workshop.
 
We’ll be using a Jupyter notebook for the interactive portion of the workshop, so be sure that you can launch Jupyter Notebook or Jupyter Lab on your computer. Jupyter Lab is a newer tool, but is still a little rough around the edges (no automatic scrolling for outputs is particularly annoying). Both tools are available through Anaconda Navigator, which is bundled with Anaconda, as well as through the terminal with `jupyter notebook` or `jupyter lab`. If you can launch Jupyter Notebooks locally and navigate through the folders you’ll see when it launches, you’ll be ready to go.