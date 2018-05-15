.. meta::
   :robots: index, follow
   :description: gumath documentation
   :keywords: gumath, trigonometry, sin, Python

.. sectionauthor:: Vital Fernandez <vital-fernandez at gmail.com>

.. _sin:
sin
===

Trigonometric sine, element-wise.

:param x: `(array_like)` Angle, in radians (:math:`2\pi` rad equals 360 degrees).

:returns: `(array_like)` The sine of each element of x.

Example
^^^^^^^

.. doctest::

   >>> import gumath as gm
   >>> from xnd import xnd
   >>> x = [0.0, 45 * 3.14159/180, 90 * 3.14159/180]
   >>> gm.sin(xnd(x))
   xnd([0.0, 0.70710, 0.99999], type='3 * float64')

.. _cos:
cos
===

Trigonometric cosine, element-wise.

:param x: `(array_like)` Angle, in radians (2*pi rad equals 360 degrees).

:returns: `(array_like)` The cosine of each element of x.

Example
^^^^^^^

.. doctest::

   >>> import gumath as gm
   >>> from xnd import xnd
   >>> x = [0.0, 45 * 3.14159/180, 90 * 3.14159/180]
   >>> gm.cos(xnd(x))
   xnd([1.0, 0.70710, 6.12323e-17], type='3 * float64')