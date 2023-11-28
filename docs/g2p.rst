
*********************
:mod:`G2P`
*********************

.. contents:: Table of Contents

Prerequisites
================

If necessary, create an additional conda environment: ``conda create --name NEW_ENV_NAME``.

Activate your desired conda environment, ``ENV_NAME``: ``conda activate ENV_NAME``.

If necessary, install pip in your conda environment: ``conda install pip``.

Before installation, please ensure that the following is installed:
   * ``python 3.10+`` (installed when you also install ``pip``)
   * ``requests`` (``pip install requests``)

Installation
================

Client package is located at ``/nfs/ssd1/packages``, under the name ``Aizip_G2P_Client-0.1.0-py3-none-any.whl``.

Ensure that you are installing this package to the correct environment: ``which pip``.

Run ``pip install Aizip_G2P_Client-0.1.0-py3-none-any.whl``.

To check if the package successfully installed, try ``conda list`` and see if ``aizip-g2p-client`` appears.

G2P client
================

.. automodule:: aizip_g2p.api
    :members: 
    :private-members:
    :special-members: __call__

