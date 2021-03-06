================
Bold with italic
================

This is normal text.

*This is italics.*

**This is bold.**

:bolditalic:`This is bold and italic using the :bolditalic: role.`

.. raw:: html

   <b><i>This is bold and italics using raw html.</i></b>

.. role:: strike

:strike:`This is struckthrough.`

:strike:`Bold italic and strikethrough.`


Stackoverflow examples
~~~~~~~~~~~~~~~~~~~~~~

.. container:: strike

   Here the full block of test is striked through.

.. rst-class:: strike

   This paragraph too is is striked through.

.. admonition:: cancelled
   :class: strike

   I strike through cancelled text.


Hybrids
~~~~~~~

.. container:: strike

   Here is some text :bolditalic:`that is bold and italic`.


RST native
~~~~~~~~~~

*This style* is the same as :emphasis:`this style`.

**This style** is the same as :strong:`this style`.

.. container:: emphasis

   Does this work? No it does not.


Replacement
~~~~~~~~~~~

I recommend you try |Python|.

.. |Python| replace:: Python, *the* best language around


Different approach
~~~~~~~~~~~~~~~~~~

.. role:: b(emphasis)

:b:`Is this bold italic?`

.. role:: strike(strong)

:strike:`This is bold struck.`
