.. Aristotle Metadata Registry User Documentation documentation master file, created by
   sphinx-quickstart on Sat Mar 11 00:33:15 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

How to read this document
=========================


.. contents:: On this page
   :local:
   

Throughout this document certain symbols or specially sylised boxes appear to help guide your
attention to important pieces of information.

Symbols used in screenshots
---------------------------

Screenshots in this document are based on the default theme for the Aristotle Metadata Registry.
Depending on customisations made to your registry, some screens may look different with controls in
different locations or with more information from customised metadata.

Clickers
........

When you are directed to click on onto a screen to perform an action a "clicker"
icon will show on the screenshot where you would click on a the screen. This clicker is a
semi-transparent orange circle and will be centered on the element to be clicked.

For example, below you can see the main header of Aristotle with the a clicker
showing where to click to perform a search within the registry.

.. screenshot::
   :server_path: /help
   :alt: A search interface with a highlighted button
   :clicker: form#quickSearch button
   :form_data: [{'q': 'Search term', '__submit__' : False }]
   :crop: (0,0,420,65)

Highlight Boxes
...............

When you are directed to observe a part of a screen with special information, a highlighted
box will show on the screenshot where the important information is shown. This box is
blue and will be around the area of the screen to observe.

For example, below you can see the main header of Aristotle with the search box
with a highlight box showing where to type to perform a search within
the registry.

.. screenshot::
   :server_path: /help
   :alt: A search interface with a highlighted search box
   :box: *[id="searchText"]
   :form_data: [{'q': 'Search term', '__submit__' : False }]
   :crop: (0,0,420,65)


Special information boxes
-------------------------

Note, Hints and Warnings
........................

.. note::

   This is a note!

.. hint::

   Hint boxes offer alternatives or short cuts that make using the application easier.

.. warning::

   Warnings will cover actions that may have large unintended effects on the 
   system such as altering user permissions or changing the visibility of content.

