How to Deactivate a User
========================

.. note:: This can only be done be an Administrator
  
To deactivate a user, go to your dashboard side panel and click "Administrator Tools"

.. screenshot::
   :server_path: /account/home
   :login: {'url': '/login', "username": "alice", "password": "Administrator"}
   :crop_element: nav[id="user_sidebar"]
   :clicker: nav#user_sidebar i[class="fa fa-user-md fa-fw"]

From here, click on the "view all users" link

.. screenshot::
   :server_path: /account/admin
   :login: {'url': '/login', "username": "alice", "password": "Administrator"}
   :clicker: a[href="/account/registry/users/"]
   
Pick the user you are deactivating and select the "manage" button next to their name
  
.. screenshot::
   :server_path: /account/registry/users/
   :login: {'url': '/login', "username": "alice", "password": "Administrator"}
   :clicker: div[class="btn-group"]
   
You will then be prompted again if you are certain you want to deactivate the user or not

In case you accidently deactivate the wrong user or simply want to reactivate the user again, you can reactivate them again,
so there isn't a permanant deletion 
   

