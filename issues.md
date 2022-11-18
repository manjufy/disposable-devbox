# Issues

vagrant box list


vagrant plugin install vagrant-vmware-desktop


vagrant up
Vagrant encountered an error while attempting to load the utility
service key file. This error can occur if the Vagrant VMware Utility
has not yet been installed, or if it was installed incorrectly. If
this error persists after running the Vagrant VMware Utility installer
again, please contact support at: support@hashicorp.com

Information about the Vagrant VMware Utility, including installation
instruction, can be found here:

  https://www.vagrantup.com/docs/vmware/vagrant-vmware-utility.html

  Path:  /opt/vagrant-vmware-desktop/certificates/vagrant-utility.client.crt
  Error: No such file or directory @ rb_sysopen - /opt/vagrant-vmware-desktop/certificates/vagrant-utility.client.crt



  https://developer.hashicorp.com/vagrant/docs/providers/vmware/vagrant-vmware-utility

  Download https://developer.hashicorp.com/vagrant/downloads/vmware


  Utility certificates are here
  	/opt/vagrant-vmware-desktop/certificates


  Utility Service Configuration
  	/opt/vagrant-vmware-desktop/config


  	sudo launchctl unload -w /Library/LaunchDaemons/com.vagrant.vagrant-vmware-utility.plist
	sudo launchctl load -w /Library/LaunchDaemons/com.vagrant.vagrant-vmware-utility.plist


	Documentation: https://developer.hashicorp.com/vagrant/docs/providers/vmware/vagrant-vmware-utility


Vagrant encountered an unexpected communications error with the
Vagrant VMware Utility driver. Please try to run the command
again. If this error persists, please contact support@hashicorp.com


/opt/vagrant-vmware-desktop/bin/vagrant-vmware-utility service uninstall
/opt/vagrant-vmware-desktop/bin/vagrant-vmware-utility service install -port=9999



vagrant status --debug


ln -s /Applications/VMWare\ Fusion\ Tech\ Preview.app /Applications/VMWare\ Fusion.app

sudo tail -f /Library/Application\ Support/vagrant-vmware-utility/service.log

VMWare API Service: http://127.0.0.1:9999/



error="Failed to locate the vmrest executable"

https://stackoverflow.com/questions/72112571/vagrant-vmware-utility-driver


https://github.com/hashicorp/vagrant-vmware-desktop/issues/49

