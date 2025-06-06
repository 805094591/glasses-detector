:fas:`download` Installation
============================

The packages requires at least `Python 3.12 <https://www.python.org/downloads/release/python-3120/>`_. To install the package via `pip <https://pypi.org/project/pip/>`_, simply run:

.. code-block:: bash

    pip install glasses-detector

Or, to install it from source, run:

.. code-block:: bash

    git clone https://github.com/mantasu/glasses-detector
    cd glasses-detector && pip install .

.. tip::

    You may want to set up `PyTorch <https://pytorch.org/get-started/locally/>`_ in advance to enable **GPU** support for your device. Note that *CUDA* is backwards compatible, thus even if you have the newest version of `CUDA Toolkit <https://developer.nvidia.com/cuda-toolkit>`_, *PyTorch* **GPU** acceleration should work just fine.

.. note::

    By default, the required models will be automatically downloaded and saved under *Torch Hub* directory, which by default is ``~/.cache/torch/hub/checkpoints``. For more information and how to change it, see `Torch Hub documentation <https://pytorch.org/docs/stable/hub.html#where-are-my-downloaded-models-saved>`_.