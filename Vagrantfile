# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant::Config.run do |config|
      config.vm.network :hostonly, "39.39.39.22"

  config.vm.box = "learn-logstash"
  config.vm.box_url = "https://vagrant-jls.objects.dreamhost.com/learn-logstash-1.box"
  config.vm.forward_port 5601, 5601
  config.vm.forward_port 9200, 9200
  config.vm.forward_port 5001, 5001
end
