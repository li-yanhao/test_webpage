Usage
=====

Installation
-----------

To get started with the documentation, you'll need to install the required dependencies:

.. code-block:: bash

   pip install sphinx sphinx-rtd-theme

Building the Documentation
-------------------------

To build the documentation, follow these steps:

1. Navigate to the docs directory:

   .. code-block:: bash

      cd docs

2. Build the HTML documentation:

   .. code-block:: bash

      make html

3. The built documentation will be available in the ``_build/html`` directory.

Viewing the Documentation
------------------------

After building, you can view the documentation by opening ``_build/html/index.html`` in your web browser.

For local development, you can also use Python's built-in HTTP server:

.. code-block:: bash

   cd _build/html
   python -m http.server 8000

Then visit http://localhost:8000 in your web browser. 