flask-oidc fork with enhancements
==========

This fork was created by `fabianlee <https://github.com/fabianlee>`_ as a proof of concept for the following features:

* Tested against Windows 2019 ADFS as Authentication Server
* Tested against Keycloak as Authentication Server
* Tested against Google as Authentication Server
* Tested against okta Authentication Server
* Additional 'groups_required' attribute on method decorator, @oidc.accept_token
* Parameter 'prepopulate_from_well_known_url' loads most config URL from well-known/openid-configuration


Python OAuth2 Client App and Resource Server
----------

My `flask-oidc-python-tests <https://github.com/fabianlee/flask-oidc-python-tests>`_ github project implements a full OAuth2 Client App and Resource Server that exercises this enhanced fork.


OAuth2 Authentication Server configuration
----------

* `Read here <https://fabianlee.org/2022/08/22/microsoft-configuring-an-application-group-for-oauth2-oidc-on-adfs-2019/>`_ for details on configuring OAuth2 for Windows 2019 ADFS
* `Read here <https://fabianlee.org/2022/08/22/microsoft-configuring-an-application-group-for-oauth2-oidc-on-adfs-2019/>`_ for details on configuring OAuth2 for Keycloak
* `Read here <https://fabianlee.org/2022/09/13/oauth2-configuring-google-for-oauth2-oidc/>`_ for details on configuring OAuth2 for Google
* `Read here <https://fabianlee.org/2022/09/12/oauth2-configuring-okta-for-oauth2-oidc/>`_ for details on configuring OAuth2 for okta


Project status
----------

This fork was created purely to prove out various OAuth2/OIDC enhancements.  Please see the main project for active development.
