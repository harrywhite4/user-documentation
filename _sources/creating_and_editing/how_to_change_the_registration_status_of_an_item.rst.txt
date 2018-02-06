How to Change the Registration Status of an Item from the Item Page
===================================================================

To change the registration status of an item, go to the item page you want to change the status of.

.. screenshot::
   :server_path: /account/home
   :alt: An item page
   :login: {'url': '/login', "username": "reggie", "password": "Registrar"}
   :crop_element: nav[id="user_sidebar"]
   :crop_element_padding: 100,200
   :clicker: i[class="fa fa-institution fa-fw"]
   
From the item page there are two ways to change the status, this will change depending on your permissions in the registry.  

.. screenshot::
   :server_path: /item/47/dataelementconcept/employeelast-day-of-employment
   :crop_element: div[id="content"]
   :crop_element_padding: 100,0,-350,-750
   
The first way is to go to the "Action bar" and select the drop-down "Actions" and select "change registration status" 

.. screenshot::
   :server_path: /item/47/dataelementconcept/employeelast-day-of-employment
   :crop_element: div[id="content"]
   :crop_element_padding: 80,10,-450,-700
   :box: a[href="/action/changestatus/47"]
   
   browser.find_element_by_css_selector('.fa.fa-fw.fa-pencil-square-o').click() 

This will open a modal window in the browser.

.. screenshot::
   :server_path: /item/47/dataelementconcept/employeelast-day-of-employment
   
   browser.find_element_by_css_selector('.fa.fa-fw.fa-pencil-square-o').click() 
   browser.find_element_by_css_selector('a[href="/action/changestatus/47"][data-toggle="modal"]').click()
   
   import time
   time.sleep(2) 

The second way to change the registration status on the item page, is to go into the "info box" and select "change" next to "Endorsed by".                      
  
.. screenshot::
   :server_path: /item/47/dataelementconcept/employeelast-day-of-employment
   :crop_element: div[id="content"]
   :crop_element_padding: 80,10,-450,-700
   :box: a[class="inline_action"]

