3.2.0
=====
* added a new API endpoint - `/api/v1/settings/logging/test/` - for testing
  external log aggregrator connectivity
  [[#5164](https://github.com/ansible/ansible-tower/issues/5164)]
* allow passing `-e create_preload_data=False` to skip creating default
  organization/project/inventory/credential/job_template during Tower
  installation
  [[#5746](https://github.com/ansible/ansible-tower/issues/5746)]
