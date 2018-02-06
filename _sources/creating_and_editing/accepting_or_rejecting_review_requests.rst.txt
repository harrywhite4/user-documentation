How to Accept or Reject Review Requests
=======================================

In this section we are going to run through the steps of how to accept or reject an item or items that have been submitted to
an Administrator or Registrar for review.

.. note:: You must be either an Administrator or Registrar to accept or reject review requests

First, go to your Dashboard sidepanel and select "Registrar Tools"

.. screenshot::
   :server_path: /account/home
   :alt: Dashboard sidebar
   :login: {'url': '/login', "username": "alice", "password": "Administrator"}
   :crop_element: nav[id="user_sidebar"]
   :crop_element_padding: 100,200
   :clicker: i[class="fa fa-institution fa-fw"]

From here, you can view the Registration Authorities you are a registrar in. 

To see the review requests, go to "Review Lists" under "Registrar Tools" on the sidepanel.

.. screenshot::
   :server_path: /account/registrartools
   :clicker: i[class="fa fa-flag fa-fw"]

You will see a list of items that have been requested for review, and older requests that have been accepted or rejected. 

.. screenshot::
   :server_path: /account/registrartools/review

To accept or reject the item(s), click the green "check" to approve, or red "x" to reject. 

.. note:: Before the "accept review" or "reject review" goes through you will be able to confirm the action and leave feedback to the submitter as to why you chose the option you did. 
   
.. screenshot::
   :server_path: /account/registrartools/review 
   :crop_element: form[action="/action/bulkaction?next=/account/registrartools/review"]
   :crop_element_padding: 10,0,-300,-600 
   
