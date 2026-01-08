====================
Customization
====================

Overriding the Default Stylesheet
=================================

The theme allows you to override the main stylesheet (which defaults to ``css/basicstrap.css``) by setting the ``style`` variable in ``html_context`` within your ``conf.py``.

This is useful if you want to completely replace the base styles or provide a different CSS file located in your ``_static`` directory.

Example configuration in `conf.py`:

.. code-block:: python

    html_context = {
        'style': 'my_custom_style.css',
    }

In this example, Sphinx will look for ``_static/my_custom_style.css`` and use it instead of the default theme CSS.
