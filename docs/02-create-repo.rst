Creating the package repository
===============================

The python package we create in this tutorial will be hosted from GitHub.
While your source code will be public, you should always expect the source code of your python packages and scripts to be visible.

Create the repository
---------------------

Log in to `GitHub
<https://www.github.com>`_ and create a new repository.
The package we create in this tutorial will generate and summarize a list of numbers, so we'll call both the project and package "summarize."

Make sure you initialize the repository with a README file, and choose an appropriate license.

.. image:: ./images/create_repo.png
   :target: ./images/create_repo.png
   :alt: Creating a Repository on GitHub

Then click **"Create repository"** to create your repository.

Clone the repository locally
----------------------------

Click the "clone" button to get the URL to clone your repository locally.

.. image:: ./images/clone.png
   :target: ./images/clone.png
   :alt: Get repository URL

The URL that was copied can then be used to "git clone".
After cloning the repository, enter the directory.

.. code-block::

   $ git clone <paste>
   $ cd [repo name]
