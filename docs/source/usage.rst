Usage
=====

.. _installation:

Installation
------------

To install phyloNEON, you will need the `devtools` package:

.. code-block:: console

   library(devtools)

   install_github("NEONScience/phyloNEON/phyloNEON")



Accessing and using NEON genetic data 
-------------------------------------

NEON offers several data products that include genetic data. This repository is being developed to include tools and guidelines to help users of NEON data to better utilize the genetic data. 



.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

