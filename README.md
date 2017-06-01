# mass-shootings
Data analysis for Everytown's database of mass shootings in the U.S. from January 2009 to December 2016.

Assumptions
-----------

The following things are assumed to be true in this documentation.

* You are running OSX.
* You are using Python 2.7. (Probably the version that came OSX.)
* You have [virtualenv](https://pypi.python.org/pypi/virtualenv) and [virtualenvwrapper](https://pypi.python.org/pypi/virtualenvwrapper) installed and working.

For more details on the technology stack used with the app-template, see our [development environment blog post](http://blog.apps.npr.org/2013/06/06/how-to-setup-a-developers-environment.html).


Bootstrap the project
---------------------

```
cd mass-shootings
mkvirtualenv mass-shootings
pip install -r requirements.txt
```

**Problems installing requirements?** You may need to run the pip command as ``ARCHFLAGS=-Wno-error=unused-command-line-argument-hard-error-in-future pip install -r requirements.txt`` to work around an issue with OSX.

Run the notebook
---------------

`
jupyter notebook
`

The homepage of the notebook should open automatically in your preferred browser. Notebooks generally run on `localhost:8888` if it is the sole notebook running.


Data sources
---------------

TKTK
