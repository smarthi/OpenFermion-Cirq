.. currentmodule:: openfermioncirq
API Reference
=============

Gates
--------

Single-Qubit Gates
^^^^^^^^^^^^^^^^^^

.. autosummary::
    :toctree: generated/

    FermionicSwapGate
    XXYYGate
    YXXYGate
    ZZGate
    FSWAP
    XXYY
    YXXY
    ZZ

Three-Qubit Gates
^^^^^^^^^^^^^^^^^

.. autosummary::
    :toctree: generated/

    ControlledXXYYGate
    ControlledYXXYGate
    Rot111Gate
    CXXYY
    CYXXY
    CCZ


Primitives
----------

.. autosummary::
    :toctree: generated/

    bogoliubov_transform
    prepare_gaussian_state
    prepare_slater_determinant
    swap_network


Trotter
-------

.. autosummary::
    :toctree: generated/

    simulate_trotter
    trotter.TrotterStep
    trotter.TrotterAlgorithm
    trotter.LINEAR_SWAP_NETWORK
    trotter.SPLIT_OPERATOR
    trotter.LOW_RANK


Trotter Algorithms
^^^^^^^^^^^^^^^^^^

.. autosummary::
    :toctree: generated/

    trotter.LinearSwapNetworkTrotterAlgorithm
    trotter.SplitOperatorTrotterAlgorithm
    trotter.LowRankTrotterAlgorithm


Variational Algorithms
----------------------

.. autosummary::
    :toctree: generated/

    VariationalAnsatz
    VariationalStudy
    HamiltonianVariationalStudy

Variational Ansatzes
^^^^^^^^^^^^^^^^^^^^

.. autosummary::
    :toctree: generated/

    SwapNetworkTrotterAnsatz
    SplitOperatorTrotterAnsatz


Optimization
------------

.. autosummary::
    :toctree: generated/

    optimization.OptimizationAlgorithm
    optimization.OptimizationParams
    optimization.OptimizationResult
    optimization.OptimizationTrialResult
    optimization.ScipyOptimizationAlgorithm
    optimization.COBYLA
    optimization.L_BFGS_B
    optimization.NELDER_MEAD
    optimization.SLSQP
