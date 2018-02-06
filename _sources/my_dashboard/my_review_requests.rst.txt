My Review Requests
==================

To request a review for an item that you haven't requested a review for previously, go to "My Sandbox"

.. screenshot::
   :server_path: /account/sandbox
   :login: {'url': '/login', "username": "alice", "password": "Administrator"}
   :alt: My Sandbox
   :browser_height: 733
   
From here, you can select an item individually, or you can bulk request items for review

.. screenshot::
   :server_path: /account/sandbox
   :alt: My Sandbox
   :crop_element: input[id="id_items_50"]
   :crop_element_padding: (40,400) 

   browser.find_element_by_css_selector('input[id="id_items_50"]').click()
   
After selecting what you want to request a review for, go down to the "bulk action" button and select "request review" 

.. screenshot::
   :server_path: /account/sandbox
   :alt: My Sandbox
   :crop_element: button[class="btn btn-default dropdown-toggle"]
   :crop_element_padding: (10,10,200,300)




