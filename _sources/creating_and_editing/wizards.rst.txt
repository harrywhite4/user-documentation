Using wizards to create metadata
================================

Before


.. screenshot:: 
   :server_path: /create/aristotle_mdr/objectclass
   :alt: A basic search screen
   :login: {'url': '/login', "username": "vicky", "password": "Viewer"}
   :form_data: [
      {'initial-name': 'Person', 'initial-definition': 'Something', '__submit__': False}
      ]

After:

.. screenshot:: 
   :form_data: [
      {'initial-name': 'Person', 'initial-definition': 'Something', '__submit__': True},
      ]
      
   import time
   time.sleep(2)



More after:

.. screenshot:: 
   :alt: A basic search screen
   :clicker: a[href="#tab_names"]
   :box: *[id="tab_names"]
   :form_data: [
      {'results-references': 'Person', '__submit__': False},
      ]

   import time
   time.sleep(2)
   browser.find_element_by_css_selector('a[href="#tab_names"]').click()
