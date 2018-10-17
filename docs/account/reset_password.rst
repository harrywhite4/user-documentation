Reset Password
==============

Forgotten Password
------------------

If you have forgotten it. Go to the login page and click on the forgotten password link

.. screenshot::
   :server_path: /logout?next=/login
   :alt: Forgotten Password Link
   :browser_height: 733
   :box: a.forgot
   
Then enter your email and click reset password. You will then recieve an email with a password reset link

.. screenshot::
   :server_path: /user/password/reset
   :alt: Password Reset
   :browser_height: 733
   :box: #id_email
   
Change current password
-----------------------

If you just want to change your current password, go to your profile and click on the "Change Password" button under actions

.. screenshot::
   :server_path: /account/profile
   :alt: Alternate text for screen reader
   :browser_height: 733
   :login: {'url': '/login', "username": "alice@aristotle.example.com", "password": "Administrator"}
   
Then fill in the form to change your password

.. screenshot::
   :server_path: /account/password/change
   :alt: Password Change
   :browser_height: 733
