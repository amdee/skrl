.. _gaussian-noise:

Gaussian noise
==============

Noise generated by normal distribution.

.. raw:: html

    <br><hr>

Usage
-----

The noise usage is defined in each agent's configuration dictionary. A noise instance is set under the :literal:`"noise"` sub-key. The following examples show how to set the noise for an agent:

|

.. image:: ../../../_static/imgs/noise_gaussian.png
    :width: 75%
    :align: center
    :alt: Gaussian noise

.. raw:: html

    <br><br>

.. tabs::

    .. group-tab:: |_4| |pytorch| |_4|

        .. literalinclude:: ../../../snippets/noises.py
            :language: python
            :emphasize-lines: 1, 4
            :start-after: [torch-start-gaussian]
            :end-before: [torch-end-gaussian]

    .. group-tab:: |_4| |jax| |_4|

        .. literalinclude:: ../../../snippets/noises.py
            :language: python
            :emphasize-lines: 1, 4
            :start-after: [jax-start-gaussian]
            :end-before: [jax-end-gaussian]

.. raw:: html

    <br>

API (PyTorch)
-------------

.. autoclass:: skrl.resources.noises.torch.gaussian.GaussianNoise
    :undoc-members:
    :show-inheritance:
    :inherited-members:
    :private-members: _update
    :members:

.. raw:: html

    <br>

API (JAX)
---------

.. autoclass:: skrl.resources.noises.jax.gaussian.GaussianNoise
    :undoc-members:
    :show-inheritance:
    :inherited-members:
    :private-members: _update
    :members:
