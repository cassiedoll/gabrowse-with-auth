gabrowse-with-auth
==================

This fork adds OAuth support to `googlegenomics/api-client-python <http://github.com/googlegenomics/api-client-python>`_.
See the README in that repo for questions not specific to OAuth.


Getting started
---------------

This Python client demonstrates a simple web-based genome browser that fetches data from the 
`Google Genomics API`_, through a web interface, and displays a pileup of reads
with support for zooming and basic navigation and search.

* Download and install `Google App Engine SDK for Python <https://developers.google.com/appengine/downloads>`_.

* Then, follow the `sign up instructions <https://developers.google.com/genomics>`_ to generate a valid ``client_secrets.json`` file.

* On Mac OS X you can setup and run the application through the GoogleAppEngineLauncher UI.
  To use the command line or to run on Linux::

    cd api-client-python
    dev_appserver.py .
  
  To run on Windows::

    cd api-client-python
    python c:\path\to\dev_appserver.py .

* Once running, visit ``http://localhost:8080`` in your browser to browse data from the API.

.. _Google Genomics Api: https://developers.google.com/genomics