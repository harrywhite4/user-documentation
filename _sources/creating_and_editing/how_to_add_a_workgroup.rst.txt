How to Add a Workgroup
======================

.. note:: You have to be an Administrator to add a workgroup

1. Go to "Administrator Tools" at the bottom of the Dashboard side menu

.. screenshot::
   :server_path: /account/admin
   :alt: 
   :login: {'url': '/login', "username": "alice", "password": "Administrator"}
   :crop_element: div#dashboard-nav a[href="/account/admin"]
   
2. Select "add workgroup"

.. screenshot::
   :server_path: /account/admin
   :alt: 
   :crop_element: div#content a[href="/workgroups/create"]
   
3. You will then be asked to give the new workgroup a name, which helps members identify the workgroups they are in,
and then the definition of the workgroup, which let's people know what the role of the workgroup is

.. screenshot::
   :server_path: /workgroups/create
   :crop: [0,0,1200,650]

   import time
   time.sleep(5)


4. Then select the users you want in a particular workgroup, by assigning them to the roles they will perform:

.. screenshot::
   :crop: [0,700,1200,2100]
   
5. Once done, click "save and continue editing" or "save" to finish creating your new workgroup, 
you will then recieve a message at the top of your screen saying that you have sucessfully created a new workgroup 

.. screenshot::
   :alt: 
   :crop_element: div.admin-wrap button[type="Submit"]
