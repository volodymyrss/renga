.. _user_management:

**RENGA**'s identity management is based on Keycloak. We document the
steps to add or modify a user security settings. For more information, we
refer the reader to the Keycloak documentation, which can be found `here
(Keycloak 3.2) <http://www.keycloak.org/docs/3.2/index.html>`_.

Content
=======

- :ref:`im_user_account_service`
- :ref:`im_admin_console`

.. _im_user_account_service:

User Account Services
---------------------

Users can access their profiles through the Keycloak User Account service
at `<http://localhost/auth/realms/Renga/account>`_. This service allows
users to manage their account, change their credentials, update their
profiles, and view their login sessions.

.. _im_admin_console:

User Management
---------------

The bulk of the user management administrative tasks are done through the
Keycloak admin console. You can go to the console directly at
`<http://localhost/auth>`_.  This service allows the platform
administrator to create new realms, create new users, change user
attributes, impersonate users and configure the security settings of the
Keycloak service.
