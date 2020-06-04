# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.hostname = "zabbix"
  config.vm.box = "centos/7"
  config.vm.box_check_update = false

  config.vm.network "forwarded_port", guest: 80, host: 8088
end
