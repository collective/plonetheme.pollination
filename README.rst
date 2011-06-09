
Introduction
============

The ``plonetheme.pollination`` package uses the **theming** and **packaging** features
available in `plone.app.theming`_ to make the `CSS Templates`_ theme `pollination`_ easily
available in `Plone 4.1`_.

.. image:: http://svn.plone.org/svn/collective/plonetheme.pollination/trunk/screenshot01.png

Installation
------------

Add Plone site
~~~~~~~~~~~~~~

Install Plone 4.1 with `plone.app.theming`_ and create a Plone site (if you have not already)
with Diazo theming configured.

Zip file
~~~~~~~~

If you are an end user, you might enjoy installation via zip file import.

1. Download the zip file: http://svn.plone.org/svn/collective/plonetheme.pollination/trunk/pollination.zip
2. Import the theme from the Diazo theme control panel.

Buildout
~~~~~~~~

If you are a developer, you might enjoy installation via buildout.

Add ``plonetheme.pollination`` to your ``plone.recipe.zope2instance`` section's *eggs* parameter e.g.::

    [instance]
    eggs =
        Plone
        …
        plonetheme.pollination

Select theme
~~~~~~~~~~~~

Select and enable the theme from the Diazo control panel. That's it!

Help
----

Obviously there is more work to be done. If you want to help, pull requests accepted! Some ideas:

* Add a diazo rule to import Plone editing styles
* Configure styles to use portal_css
* Add quick installer support
* Improve styles 

Authors
-------

This product was developed by RedTurtle Technology team.

.. image:: http://www.redturtle.net/redturtle_banner.png
   :alt: RedTurtle Technology Site
      :target: http://www.redturtle.it/

License
-------

The author is not a "license guy", but the pollination theme is distributed via CC 3.0 license [1]_ and this package is GPL version 2 (assuming that makes sense).

.. _`pollination`: http://www.freecsstemplates.org/preview/pollination/
.. _`plone.app.theming`: http://pypi.python.org/pypi/plone.app.theming
.. _`Plone 4.1`: http://pypi.python.org/pypi/Plone/4.1rc2
.. _`CSS Templates`: http://www.freecsstemplates.org/

.. [1] http://www.freecsstemplates.org/license/