Title 1
==========

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur ante est,
facilisis vitae ultricies sed, malesuada fringilla erat. Nullam imperdiet
mollis porta. Sed hendrerit tempor nulla, nec accumsan ligula sagittis ut.

Proin rhoncus eleifend posuere. Proin cursus orci nisl, quis imperdiet metus
interdum eget. Praesent lacinia odio urna, in blandit elit viverra vitae.
Maecenas non mauris vel quam efficitur pulvinar. Vestibulum at lacus ipsum.
Praesent ornare molestie aliquam. Mauris fermentum nisl sed feugiat lobortis.
Morbi laoreet porttitor tellus eu venenatis. Donec gravida mi non ultrices
consequat.

Title 2
==========

Lorem ipsum dolor sit amet, consectetur **Bold Text** adipiscing elit.

Proin rhoncus eleifend posuere. Proin *Italic Text* cursus orci nisl, quis imperdiet metus
interdum eget.

Mauris fermentum nisl :code:`inline code or command` sed feugiat lobortis.

.. uml::

    == Initialization ==
  
    Alice -> Bob: Authentication Request
    Bob --> Alice: Authentication Response
  
    == Repetition ==
  
    Alice -> Bob: Another authentication Request
    Alice <-- Bob: another authentication Response

.. math::

    n_{\mathrm{offset}} = \sum_{k=0}^{N-1} s_k n_k


Sub-Title 1
-------------

Lorem ipsum dolor sit amet, consectetur adipiscing elit. 

=====  =====  ======
Inputs        Output
------------  ------
  A      B    A or B
=====  =====  ======
False         False
------------  ------
True   False  True
False  True   True
True          True
============  ======


Sub-Title 2
-------------

Lorem ipsum dolor sit amet, consectetur adipiscing elit. 

.. code-block::

  # Console
  sudo apt-get update
  
  
.. code-block:: python

  # Python
  print('Hello, world!')


.. code-block:: cpp
  
  // C++
  #include <iostream>
  using namespace std;
  
  int main() {
      // prints the string enclosed in double quotes
      cout << "This is C++ Programming";
      return 0;
  }

