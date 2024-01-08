Markdown Cheat Sheet
====================

Thanks for visiting `The Markdown
Guide <https://www.markdownguide.org>`__!

This Markdown cheat sheet provides a quick overview of all the Markdown
syntax elements. It can’t cover every edge case, so if you need more
information about any of these elements, refer to the reference guides
for `basic syntax <https://www.markdownguide.org/basic-syntax/>`__ and
`extended syntax <https://www.markdownguide.org/extended-syntax/>`__.

Basic Syntax
------------

These are the elements outlined in John Gruber’s original design
document. All Markdown applications support these elements.

Heading
~~~~~~~

H1
==

H2
--

H3
~~

Bold
~~~~

**bold text**

Italic
~~~~~~

*italicized text*

Blockquote
~~~~~~~~~~

   blockquote

Ordered List
~~~~~~~~~~~~

1. First item
2. Second item
3. Third item

Unordered List
~~~~~~~~~~~~~~

-  First item
-  Second item
-  Third item

Code
~~~~

``code``

Horizontal Rule
~~~~~~~~~~~~~~~

--------------

Link
~~~~

`Markdown Guide <https://www.markdownguide.org>`__

Image
~~~~~

.. figure:: https://www.markdownguide.org/assets/images/tux.png
   :alt: alt text

   alt text

Extended Syntax
---------------

These elements extend the basic syntax by adding additional features.
Not all Markdown applications support these elements.

Table
~~~~~

========= ===========
Syntax    Description
========= ===========
Header    Title
Paragraph Text
========= ===========

Fenced Code Block
~~~~~~~~~~~~~~~~~

::

   {
     "firstName": "John",
     "lastName": "Smith",
     "age": 25
   }

Footnote
~~~~~~~~

Here’s a sentence with a footnote.  [1]_

Heading ID
~~~~~~~~~~

.. _custom-id:

My Great Heading
~~~~~~~~~~~~~~~~

Definition List
~~~~~~~~~~~~~~~

term
   definition

Strikethrough
~~~~~~~~~~~~~

[STRIKEOUT:The world is flat.]

Task List
~~~~~~~~~

-  ☒ Write the press release
-  ☐ Update the website
-  ☐ Contact the media

Emoji
~~~~~

That is so funny! :joy:

(See also `Copying and Pasting
Emoji <https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji>`__)

Highlight
~~~~~~~~~

I need to highlight these ==very important words==.

Subscript
~~~~~~~~~

H\ :sub:`2`\ O

Superscript
~~~~~~~~~~~

X\ :sup:`2`

.. [1]
   This is the footnote.
