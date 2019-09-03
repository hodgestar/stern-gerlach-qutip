stern-gerlach-qutip
===================

A very gentle introduction to qubits and QuTiP via exploring the Stern-Gerlach
experiment.

Nbviewer & Mybinder
-------------------

View the notebook in Nbviewer or Mybinder:

.. image:: https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg
   :target: https://nbviewer.jupyter.org/github/hodgestar/stern-gerlach-qutip/blob/master/qutip-measurement.ipynb

.. image:: https://mybinder.org/badge_logo.svg
   :target: https://mybinder.org/v2/gh/hodgestar/stern-gerlach-qutip/master

Warning: The Mybinder environment takes a *long* time to start.


Quickstart
----------

Install requirements::

  $ pip install numpy scipy==1.2 Cython  # required to build/install QuTiP
  $ pip install -r requirements.txt

Launch jupyter notebook::

  $ jupyter-notebook .

Work through the notebook.


Viewing the notebook as slides
------------------------------

Install slide requirements::

  $ pip install -r requirements-slides.txt

Open the notebook and press `Alt + r` to enter slide mode.


Image citations
---------------

1. `images/complex-movie-loop-f7.gif` -- private correspondence with
   Dr Claire Blackman, Department of Mathematics & Applied Mathematics,
   UCT.

2. `images/complex-movie-loop.gif` -- private correspondence with Dr
   Claire Blackman, Department of Mathematics & Applied Mathematics,
   UCT.

3. `images/stern-gerlach-apparatus-cm.png` -- drawing of the Stern-Gerlach
   apparatus, simplified/modified version of
   http://hyperphysics.phy-astr.gsu.edu/hbase/spin.html.

4. `images/stern-gerlach-fig13-results.jpg` -- results from the original
   Stern-Gerlach experiment (Gerlach and Stern, 1922a) via https://plato.stanford.edu/entries/physics-experiment/app5.html.


Further reading
---------------

1. QuTiP documentation [ http://qutip.org/ ]

2. Quantum Computing for the Determined by Michael Nielsen
   [ http://michaelnielsen.org/blog/quantum-computing-for-the-determined/ ]

3. Quantum Computing StackExchange
   [ https://quantumcomputing.stackexchange.com/ ]

4. History of the Stern-Gerlach experiment
   [ https://plato.stanford.edu/entries/physics-experiment/app5.html ]

5. Picking a random point on a sphere
   [ http://mathworld.wolfram.com/SpherePointPicking.html ]


License
-------

All original work licensed under the MIT license. See LICENSE file for
details.
