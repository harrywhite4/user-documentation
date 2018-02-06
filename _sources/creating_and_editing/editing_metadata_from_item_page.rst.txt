Editing existing metadata
=========================

.. contents:: On this page
   :local:

.. note:: This section applies to logged in users with permission to edit metadata

Opening the editor for a metadata item
--------------------------------------

When viewing an item, click the "Actions" button in the top right of the screen
to open the Actions menu, then select "Open item editor".

.. attention:: If an edit link doesn't show on your screen, you may not have 
   permission to edit this metadata.


.. screenshot:: 
   :server_path: /item/18
   :alt: A basic search screen
   :login: {'url': '/login', "username": "suzie", "password": "Submitter"}
   :clicker: i.fa-pencil-square-o
   :browser_height: 733

   browser.find_element_by_css_selector('i.fa-pencil-square-o').click()

Clicking "Open item editor" will open in a modal window within the browser,
as shown below:

.. screenshot:: 
   :alt: A basic search screen
   :browser_height: 1000

   browser.find_element_by_css_selector('a[href="/item/18/edit"][data-toggle="modal"]').click()

   import time
   time.sleep(8)

Maximizing the metadata editor
------------------------------

When viewing a modal pop up dialog, click the 'expand' icon in the top right of
the dialog to force the editor to take up the whole window.

.. screenshot:: 
   :alt: A basic search screen
   :clicker: a i.fa.fa-expand


When expanded, the editor now takes up the whole screen, as shown below:

.. screenshot:: 
   :server_path: /item/18/edit
   :alt: A basic search screen



