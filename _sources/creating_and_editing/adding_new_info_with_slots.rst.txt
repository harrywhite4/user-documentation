Creating New Information with Slots
===================================

.. note:: Slots can only be created when the Aristotle Slots add-on is installed.

Slots are a ways of adding extra detail to metadata beyond what's available in the standard or Aristotle. 
Allows you to add extra context specific to a registry that describes a particular use. 

The following steps are ways to capture this infomation for an existing metadata item. 

.. note:: Only users with editing privledges for that metadata can create and edit slots for it.

1. To get started open the action menu from the page of the metadata you wish to annotate and select "Open Item Editor"

.. screenshot:: 
   :server_path: /item/18
   :alt: Screenshot of a person metadata item
   :login: {'url': '/login', "username": "suzie", "password": "Submitter"}
   :clicker: i.fa-pencil-square-o
   :browser_height: 733
   
   browser.find_element_by_css_selector('i.fa-pencil-square-o').click()

2. From the item editor select the "Slots" tab

.. screenshot:: 
   :server_path: /item/18/edit
   :alt: Edit screen
   :clicker: a[href="#tab_slots"]
   :browser_height: 733

   browser.find_element_by_css_selector('a[href="#tab_slots"]').click()

3. In the slots tab, enter the name and value of the slot in the appropriate fields. If extra slots are required, click the "Add slot" button.

.. screenshot:: 
   :alt: Edit screen
   :browser_height: 733
   :form_data: [
      {'slots-0-name':"plural",'slots-0-value':"people", '__submit__': False}
      ]

4. Once saved, the slots for the metadata show at in the page in the table under the section titled "Additional attributes" along with the number of metadata items with similar values.

.. screenshot:: 
   :alt: Edit screen
   :browser_height: 733
   :form_data: [
      {'slots-0-name':"plural",'slots-0-value':"people", '__submit__': True}
      ]
