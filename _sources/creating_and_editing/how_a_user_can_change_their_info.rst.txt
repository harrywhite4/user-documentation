How a User can Change Their Information
=======================================

Go to "My Dashboard" and in the left side menu, and click the cog icon. 

.. screenshot::
   :server_path: /account/home
   :alt:
   :login: {'url': '/login', "username": "alice", "password": "Administrator"}
   :crop_element: div#dashboard-nav a[href="/account/edit"]
   :crop_element_padding: [40, 300, 40, 300]

This lets the user change their account details, like their name and email address.

.. screenshot::
   :server_path: /account/edit
   :alt:
   :crop_element: div#dashboard-nav a[href="/account/edit"]
   :crop_element_padding: [40, 300, 40, 300]


If they want to change their password they have to click the cog icon and a drop down box will appear that says "change password".

.. screenshot::
   :server_path: /account/edit
   :alt:
   :crop_element: div#dashboard-nav a[href="/account/password/change"]
   :crop_element_padding: [40, 300, 40, 300]
   
The user can then change their password.

.. screenshot::
   :server_path: /account/password/change
   :crop_element: div[id="content"]
   :crop_element_padding: 100,-200,0,0
