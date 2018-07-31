Vagrant.configure("2") do |config|

config.vm.define "server" do |server|
server.vm.box = "hashicorp/precise64"
server.vm.network "private_network", ip: "192.168.56.90"
#server.vm.hostname = "server"

end

config.vm.define "client" do |client|
client.vm.box = "centos/7"
client.vm.network "private_network", ip: "192.168.56.100"
#client.vm.hostname = "client"
end

end
