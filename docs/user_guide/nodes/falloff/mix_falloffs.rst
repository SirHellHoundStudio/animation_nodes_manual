Mix Falloffs
============

Description
-----------

This node takes two or multiple falloffs and mix them together using one of the available algorithms.

.. image:: images/mix_falloffs_node.png
   :width: 160pt

Options
-------

- **Max** - The output float will be the largest float of all falloffs.
- **Min** - The output float will be the lowest float of all falloffs.
- **Add** - The output will be the sum of the floats of the falloffs.
- **Multiply** - The output will be the product of the floats of the falloffs.
- **Use Falloff List** - It is the option you see beside the menu, if enabled, the input will be a falloff list.

Inputs
------

- **A** - A falloff.
- **B** - A falloff.
- **Falloffs**- The falloffs. If **Use Falloffs List** is enabled.

Outputs
-------

- **Falloff** - The actual falloff object.

Advanced Node Settings
----------------------

- N/A

Examples of Usage
-----------------

.. image:: gifs/mix_falloffs_node_example.gif
