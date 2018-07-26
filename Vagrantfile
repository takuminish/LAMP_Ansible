Vagrant.configure(2) do |config|
  config.vm.box = "CentOS-7.0-x64"

  config.vm.define :node1 do |node|
    node.vm.box = "CentOS-7.0-x64"
    node.vm.network :private_network, ip: "192.168.33.91"
    node.vm.network :forwarded_port, host: 8081, guest: 80
  end

  config.vm.define :node2 do |node|
    node.vm.box = "CentOS-7.0-x64"
    node.vm.network :private_network, ip: "192.168.33.92"
    node.vm.network :forwarded_port, host: 8082, guest: 80
  end

end
