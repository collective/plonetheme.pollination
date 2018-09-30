======================
plonetheme.pollination
======================


Introduction
============

*plonetheme.pollination* package is an installable Plone_ Theme using the 
**theming** and **packaging** features available in `plone.app.theming`_ 
to make the `CSS Templates`_ theme `pollination`_ easily available in `Plone`.

This theme has been taken from http://www.freecsstemplates.org/
and integrated into as a diazo theme for Plone.


Requirements
============

- From the Plone 4.1.x To the Plone 4.3 latest version (https://plone.org/download)
- The ``plone.app.theming`` package (*will be installed as a dependency of this package*)


Screenshots
===========

Layout of the site when viewed in a computer resolution:

.. image:: https://github.com/collective/plonetheme.pollination/raw/master/plonetheme/pollination/static/preview.png


Features
========
- It's an installable Plone Theme package.
- After installation from Add-ons controlpanel, this theme is enabled automatically.
- Also it's a simple Diazo_ package (Zip file).
- It's have support for clean uninstallation.


Installation
============


Zip file
--------

If you are an **end user**, you might enjoy installation via zip file import.

1. Download a `zip file <https://raw.github.com/collective/plonetheme.pollination/master/pollination.zip>`_.
2. Import the theme from the Diazo theme control panel.


Buildout
--------

If you are a **developer user**, you might enjoy installing it via buildout.

For install ``plonetheme.pollination`` package add it to your ``buildout`` section's 
*eggs* parameter e.g.: ::

   [buildout]
    ...
    eggs =
        ...
        plonetheme.pollination


and then running ``bin/buildout``.

Or, you can add it as a dependency on your own product ``setup.py`` file: ::

    install_requires=[
        ...
        'plonetheme.pollination',
    ],


Enabling the theme
^^^^^^^^^^^^^^^^^^

Select and enable the theme from the Diazo control panel. That's it!


Help
====

Obviously there is more work to be done. If you want to help, pull requests accepted! Some ideas:

* Add a diazo rule to import Plone editing styles
* Configure styles to use portal_css
* Add quick installer support
* Improve styles 


Contribute
==========

- Issue Tracker: https://github.com/collective/plonetheme.pollination/issues
- Source Code: https://github.com/collective/plonetheme.pollination

Authors
-------

This product was developed by `RedTurtle <http://www.redturtle.it/>`_ Technology team.

.. image:: http://www.redturtle.net/redturtle_banner.png
   :alt: RedTurtle Technology Site
      :target: http://www.redturtle.it/


Collaborations
--------------

- Irene Capatti (nekorin at redturtle dot it)

- Andrew Mleczko (andrew at mleczko dot net)

- Leonardo J. Caballero G. (leonardocaballero at gmail dot com).

- Full Name (mail at mailserver dot com)

You can find an updated list of all the contributors visit: https://github.com/collective/plonetheme.pollination/graphs/contributors


License
=======

The author is not a "license guy", but the pollination theme is distributed via CC 3.0 license [1]_ and this package is GPL version 2 (assuming that makes sense).

.. _`pollination`: http://www.freecsstemplates.org/preview/pollination/
.. _`Plone`: http://plone.org
.. _`plone.app.theming`: https://pypi.org/project/plone.app.theming/
.. _`Diazo`: http://diazo.org
.. _`CSS Templates`: http://www.freecsstemplates.org/

.. [1] http://www.freecsstemplates.org/license/
