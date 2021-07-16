Title 1
==========

The official reference of reStructuredText:

https://docutils.sourceforge.io/docs/ref/rst/restructuredtext.html

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

Morbi laoreet porttitor tellus eu [Link to Google](https://www.google.com) venenatis. Donec gravida mi non ultrices
consequat.

.. figure:: /static/swan-babies.jpg
    :alt: Swan Babies


Image with link and caption:

.. figure:: /static/swan-babies.jpg
  :alt: Swan Babies
  :target: http://www.google.com

  This is the caption of the figure with link to http://google.com

  **Quote:** Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur ante est,
  facilisis vitae ultricies sed, malesuada fringilla erat. Nullam imperdiet
  mollis porta. Sed hendrerit tempor nulla, nec accumsan ligula sagittis ut.
  

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

  # General
  Hello World!


.. code-block:: console

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


.. code-block:: json

  {
    "firstName": "John",
    "lastName": "Smith",
    "age": 25
  }
