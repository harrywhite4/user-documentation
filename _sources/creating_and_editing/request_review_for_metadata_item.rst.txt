
How to request your metadata item to be endorsed by a registrar
===============================================================

From the Dashboard side panel, go to "My Sandbox" to view all the items you've created that haven't been registered.

.. screenshot::
   :server_path: /account/home
   :login: {'url': '/login', "username": "alice", "password": "Administrator"}
   :crop_element: a[href="/account/sandbox"]
   :clicker: a[href="/account/sandbox"]
   
In your Sandbox, you will see a list of your items that you’ve created 
but haven’t registered. Select one item you want to register, or select multiple items to bulk register.

.. screenshot::
   :server_path: /account/sandbox
   :crop_element: form[action="/action/bulkaction?next=/account/sandbox"]

Ticking this box selects all of the items on the page.
   
.. screenshot::
   :server_path: /account/sandbox
   :clicker: input[id="all_in_queryset"]
   :crop_element: form[action="/action/bulkaction?next=/account/sandbox"]
   :crop_element_padding: 10,10,-500,400
   
After selecting the item you wish to register, go to the bottom and select "bulk actions".    
   
.. screenshot::
   :server_path: /account/sandbox
   :crop_element: button[class="btn btn-default dropdown-toggle"]
   :crop_element_padding: 100,100
   
Select "review request from the list of bulk actions.

.. screenshot::
   :server_path: /account/sandbox
   :crop_element: button[class="btn btn-default dropdown-toggle"]
   :crop_element_padding: 300,200,5,5 
   :clicker: i[class="fa fa-fw fa-flag"]
   
   browser.find_element_by_css_selector('button[class="btn btn-default dropdown-toggle"]').click()
   
