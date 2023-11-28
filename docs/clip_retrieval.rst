*********************
:mod:`clip-retrieval`
*********************

.. contents:: Table of Contents

Prerequisites
================

If necessary, create an additional conda environment: ``conda create --name NEW_ENV_NAME``.

Activate your desired conda environment, ``ENV_NAME``: ``conda activate ENV_NAME``.

If necessary, install pip in your conda environment: ``conda install pip`` (will install ``python 3.12``) or ``conda install python=3.8``.

Before installation, please ensure that the following is installed:
   * ``python 3.8+`` (installed when you also install ``pip``)
   * ``requests`` (``pip install requests``)

Installation
================

Client package is located at ``/nfs/ssd1/packages``, under the name ``Aizip_ClipRetrieval_Client-0.1.0-py3-none-any.whl``.

Ensure that you are installing this package to the correct environment: ``which pip``.

Run ``pip install Aizip_ClipRetrieval_Client-0.1.0-py3-none-any.whl``.

To check if the package successfully installed, try ``conda list`` and see if ``aizip-clipretrieval-client`` appears.

ClipBaseQuery
===================
.. automodule:: aizip_clipretrieval_client.base_query
    :members: 
    :private-members:

ClipClassifierQuery
===================
.. automodule:: aizip_clipretrieval_client.cls_query
    :members: 
    :private-members:

ClipImgQuery
===================
.. automodule:: aizip_clipretrieval_client.img_query
    :members: 
    :private-members: