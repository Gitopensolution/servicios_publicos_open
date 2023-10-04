Facturacion Electrónica
=======================

.. _installation:

Configuracion
-------------

**Series**

Es el número de serie que utiliza el contribuyente para control
interno de su información. Este campo acepta de 1 hasta 25
caracteres alfanuméricos.

.. image:: images/serie-diario.png

.. note::

   Normalmente se utilizan de acuerdo a la usanza palabras de 3 letras para 
   diferenciar las sucursales de la matriz, al dia de hoy, formalmente se usa
   LugardeExpedicion, donde se debe registrar el código postal del lugar de expedición del
   comprobante (domicilio de la matriz o de la sucursal)

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

