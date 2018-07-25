Vagrant.configure(2) do |config|
  config.vm.box = "CentOS-7.0-x64"

  config.vm.define :node1 do |node|
    node.vm.box = "CentOS-7.0-x64"
    node.vm.network :private_network, ip: "192.168.33.91"
  end

end
