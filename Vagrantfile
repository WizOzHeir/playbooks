VAGRANT_API_V = "2"

Vagrant.configure(VAGRANT_API_V) do |config|
  config.vm.box = "peru/ubuntu-18.04-server-amd64"
  config.vm.network :forwarded_port, guest: 80, host: 8080
  config.vm.network :forwarded_port, guest: 443, host: 8443 
end
