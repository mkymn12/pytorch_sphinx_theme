
*********************
:mod:`audiocraft`
*********************

.. contents:: Table of Contents

Prerequisites
================

If necessary, create an additional conda environment: ``conda create --name NEW_ENV_NAME``.

Activate your desired conda environment, ``ENV_NAME``: ``conda activate ENV_NAME``.

If necessary, install pip in your conda environment: ``conda install pip`` or ``conda install python=3.11`` (since using ``python 3.12`` causes issues when installing ``torch``).

Before installation, please ensure that the following is installed:
   * ``python 3.10+`` (installed when you also install ``pip``)
   * ``requests`` (``pip install requests``)
   * ``torch`` (see pytorch installation instructions `here <https://pytorch.org/get-started/locally/>`__)
   * ``numpy`` (``pip install numpy``, not strictly necessary, but avoids warnings from ``torch`` if installed)
   * ``ffmpeg`` (``conda install "ffmpeg<5" -c conda-forge``, recommended for writing audio files)

Installation
================

Client package is located at ``/nfs/ssd1/packages``, under the name ``Aizip_Audiocraft_Client-0.1.0-py3-none-any.whl``.

Ensure that you are installing this package to the correct environment: ``which pip``.

Run ``pip install Aizip_Audiocraft_Client-0.1.0-py3-none-any.whl``.

To check if the package successfully installed, try ``conda list`` and see if ``aizip-audiocraft-client`` appears.

audiocraft client
==================

.. automodule:: aizip_audiocraft.api
    :members: 
    :private-members:

audiocraft audio_write
=======================

.. autoclass:: aizip_audiocraft.audio_tools.audio_write