Data repository 
===============

How to use this repository:
- when creating a new branch, start from branch "empty" so that you don't get lots of unneeded data
- if you want to edit a specific dataset, pull from the dataset's branch; when done, push to the same branch and send a pull request.
- the 'data' branch is meant to be the integration point of all datasets, and should not pe cloned unless you really need to.


Getting started
===============
running 'python load_data.py' within the 'tools' directory will load the data into the DB.
This currently assumes the open-data-server_ is running locally.

.. _open-data-server: https://github.com/akariv/open-data-server
