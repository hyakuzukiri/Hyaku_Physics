.. HyakuZuKiri documentation master file, created by
   sphinx-quickstart on Thu Apr 29 14:36:54 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.
   .. graphviz:: external.dot

Introduction!
=======================================

**Hyakuzu Zukiri**

Train physics with graph and diagram.

1 Force :math:`a^2 + b^2 = c^2`.

2 Elctrical

3 Thermal

4 Optical

5 Mordern Physics

6 Misc.

.. math::

   (a + b)^2 = a^2 + 2ab + b^2

   (a - b)^2 = a^2 - 2ab + b^2
   
   
.. math::
   :nowrap:

   \begin{eqnarray}
      y    & = & ax^2 + bx + c \\
      f(x) & = & x^2 + 2xy + y^2
   \end{eqnarray}
   
**GraphViz**      

.. graph:: foo

   "bar" -- "baz";
   
   
   
.. digraph:: foo

   "bar" -> "baz" -> " :math:`a` ";
   
      
   
End of Brief documentation!


.. graphviz::

   digraph foo {
      "bar" -> "baz";
   }
   

