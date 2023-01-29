ansible-role-openeo-k8s
=========

An ansible role that installs the OpenEO platform on top of a Kubernetes cluster using helm charts.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

    openeo_cert_manager_issuer: letsencrypt-staging-issuer
    openeo_dns_name: openeoendpoint.com

License
-------

Apache-2

Author Information
------------------

This role has been created by M. Antonacci in the framework of C-SCALE project.
