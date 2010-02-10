====================
Sphinx color schemes
====================

Note: Scheme means Theme ;-)

Installation: 

1. Create a directory called ``_theme`` in your project directory.

2. Copy the scheme folder (for instance ``nature`` to this folder).

3. Alter the corresponding variables in your ``conf.py``::

    html_theme_path = ['_theme']
    html_theme = 'nature'

To read more about theming sphinx, `check out the official doc`_.

.. _check out the official doc: http://sphinx.pocoo.org/theming.html

Current schemes:
----------------

Nature
^^^^^^

`html_theme = 'nature'`

`Demo Nature <http://docs.mahner.org/django-generic-flatblocks/>`_


.. image:: http://cloud.github.com/downloads/bartTC/sphinx-schemes/nature.png

Apple Developer Connection
^^^^^^^^^^^^^^^^^^^^^^^^^^

`html_theme = 'adc'`

`Demo ADC <http://sphinxdoc.github.com/django-object-permissions/>`_

.. image:: http://github.com/coordt/ADCtheme/raw/master/static/scrn1.png
