My Sandbox
==========

What is in My Sandbox?
----------------------

Your Sandbox contains all of the items you have created, only you will be able to see this content

To access your Sandbox, go to you Dashboard side panel and select "My Sandbox" 

.. screenshot::
   :server_path: /account/home      
   :alt: My Dashboard side panel
   :login: {'url': '/login', "username": "alice", "password": "Administrator"}
   :crop_element: nav[id="user_sidebar"] 
   :clicker: a[href="/account/sandbox"]
   
You will be able to see all of the item you have created that haven't been registered, requested for a review, or added to a Workgroup

.. screenshot::
   :server_path: /account/sandbox     
   :alt: My Sandbox contents

In you Sandbox, you can perform "bulk" actions to your items

.. screenshot::
   :server_path: /account/sandbox     
   :alt: My Sandbox contents
   :clicker: button[class="btn btn-default dropdown-toggle"]

   browser.find_element_by_css_selector('.dropup button').click()
   
To do this, select the items you want the bulk actions performed on. You can individually select the items or tick the "select all" box

.. screenshot::
   :server_path: /account/sandbox     
   :box: *[id="all_in_queryset"]
   
