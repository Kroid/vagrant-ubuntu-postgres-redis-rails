Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-16.04"
  # config.vm.box = "Kroid/hello-world"
  # config.vm.box_version = "1.0.0"
  # config.vm.provision "shell", path: "build.sh"
  config.vm.provision "ansible" do |ansible|
    ansible.verbose = "v"
    ansible.playbook = "playbook/setup.yml"
  end
end
