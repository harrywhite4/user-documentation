.. Aristotle Metadata Registry User Documentation documentation master file, created by
   sphinx-quickstart on Sat Mar 11 00:33:15 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Searching for content
=====================

.. screenshot::
   :server_path: /search
   :alt: A basic search screen
   :crop: (0,0,900,465)
   

Here are some results

.. screenshot::
   :server_path: /search?q=person
   :alt: A basic search screen
   :crop: (0,0,900,465)
   
   
How to refine your results with filters
---------------------------------------

"Item type" lets you search for a specific item 

.. screenshot::
   :server_path: /search?q=person
   :clicker: i[class="fa fa-puzzle-piece fa-fw"]
   :crop: (0,0,900,465)

   browser.find_element_by_css_selector('i.fa-puzzle-piece').click()

"Status" lets you choose the status of your items 

.. screenshot::
   :server_path: /search?q=person
   :clicker: i[class="fa fa-unlock-alt fa-fw"]
   :crop: (0,0,900,465)
   
   browser.find_element_by_css_selector('i.fa-unlock-alt').click()
   
"Authority" Lets you pick which Registration Authority you would like to see content from

.. screenshot::
   :server_path: /search?q=person
   :clicker: i[class="fa fa-university fa-fw"]
   :crop: (0,0,900,465)

   browser.find_element_by_css_selector('i.fa-university').click()
   
"Modified" You can pick when the content you are searching for was modified, you can be specific as you want

.. screenshot::
   :server_path: /search?q=person
   :crop: (0,0,900,465)

"Created" You can pick when the content you are searching for was created

.. screenshot::
   :server_path: /search?q=person
   :crop: (0,0,900,465)

   
   

