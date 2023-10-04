Facturacion Electrónica
=====

.. _installation:

Configuracion
------------

**Series**

Dentro de la guia de llenado del SAT, se indica un campo que pude ser llenado con una secuencia
.. image:: img/serie-diario.png

Timbrado Factura
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

