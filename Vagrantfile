Vagrant.configure("2") do |config|
    config.vm.box = "geerlingguy/debian11"
    config.vm.network "private_network", ip: "192.168.56.10"

    # provisioning configuration for ansible
    config.vm.provision "ansible" do |ansible|
        ansible.playbook = "playbook.yml"
    end
end