Vagrant.configure("2") do |config|
  config.vm.box = "berchev/xenial64"
  config.ssh.forward_x11 = true
  config.vm.provision "shell", path: "scripts/provision.sh"
end
