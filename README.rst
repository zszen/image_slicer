.. image:: https://badge.fury.io/py/image_slicer.png
    :target: http://badge.fury.io/py/image_slicer

.. image:: https://travis-ci.org/samdobson/image_slicer.svg?branch=master
    :target: http://travis-ci.org/samdobson/image_slicer?branch=master

.. image:: https://coveralls.io/repos/github/samdobson/image_slicer/badge.svg?branch=master
    :target: https://coveralls.io/github/samdobson/image_slicer?branch=master

documentation_ | website_


Image Slicer
============

Notice
----------------
I modified param for correct the command.

slice-image cake.jpg 5 1 split with 5x1 counts

What does it do?
----------------

Splits an image into ``n`` equally-sized tiles. Also capable of joining the pieces back together.

Whether you are planning a collaborative art project, creating a jigsaw puzzle, or simply get a kick out of dividing images into identical quadrilaterals... this package is for you!

Installation
------------

.. code-block:: bash (download with project)

	$ pip3 install -e ./

*Python versions supported:*

* 2.7+
* 3.4+

Usage
-----

Slice an image with Python:

.. code-block:: python

	>>> import image_slicer
	>>> image_slicer.slice('cake.jpg', 5, 1)

... or from the command line:

.. code-block:: bash

	$ slice-image cake.jpg 5 1

`Further examples`_ can be found in the documentation_.

About
-----

This module was developed for *collabart*, a web application for launching collaborative art projects.

.. _splitimag.es: http://splitimag.es
.. _Further examples: https://image-slicer.readthedocs.org/en/latest/examples/
.. _documentation: https://image-slicer.readthedocs.org/en/latest/
.. _website: http://samdobson.github.io/image_slicer
