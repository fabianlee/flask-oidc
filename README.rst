flask-oidc fork with enhancements
==========

This fork was created by `fabianlee <https://github.com/fabianlee>`_ as a proof of concept for the following features:

* Support Windows 2019 ADFS as OAuth2 Authentication Server
* Support Keycloak as OAuth2 Authentication Servr
* Additional 'groups_required' attribute on method decorator
* Parameter 'prepopulate_from_well_known_url' to load most config URL from well-known/openid-configuration


Python OAuth2 Client App and Resource Server
----------

`The flask-oidc-python-tests github project <https://github.com/fabianlee/flask-oidc-python-tests>`_ implements a full OAuth2 Client App and Resource Server that exercises this enhanced fork.


ADFS 2019 OAuth2 configuration
----------

`Read here <https://fabianlee.org/2022/08/22/microsoft-configuring-an-application-group-for-oauth2-oidc-on-adfs-2019/>`_ for details on configuring Windows 2019 ADFS for OAuth2


Project status
----------

This fork was created purely to prove out various OAuth2/OIDC enhancements.  Please see the main project for active development.
