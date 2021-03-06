De Leon-Berne Hamiltonian
=========================

This Hamiltonian has been studied as a model of isomerization of a single molecule that undergoes conformational change and exhibits regular and chaotic dynamics relevant for chemical reactions.

.. math::
    \mathcal{H}(x,y,p_x,p_y) = T(p_x, p_y) + V_{\rm DB}(x, y) = \frac{p_x^2}{2m_A} + \frac{p_y^2}{2m_B} + V_{\rm DB}(x, y)

where the potential energy function :math:`V_{\rm DB}(x,y)` is

.. math::
    \begin{align}
    V_{\rm DB}(x,y) = & V(x) + V(y) + V(x,y) \\
    V(y) = & 4y^2(y^2 - 1) + \epsilon_s \\
    V(x) = & D_x\left[ 1 - \exp(-\lambda x) \right]^2 \\
    V(x,y) = & 4y^2(y^2 - 1)\left[ \exp(-\zeta \lambda x) - 1 \right]
    \end{align}

The parameters in the model are :math:`m_A, m_B` which represent mass of the isomers, while :math:`\epsilon_s, D_x` denote the energy of the saddle, dissociation energy of the Morse oscillator, respectively, and will be kept fixed in this study, :math:`\lambda, \zeta` denote the range of the Morse oscillator and coupling parameter between the :math:`x` and :math:`y` configuration space coordinates, respectively.


.. image::  ../tests/plots/diff_corr_deleonberne_upos.png

Unstable periodic orbits at two values of the total energy for the De Leon-Berne Hamiltonian computed using differential correction method.

.. automodule:: deleonberne_hamiltonian
   :members:


