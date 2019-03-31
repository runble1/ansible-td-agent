Vagrant.configure(2) do |config|
  config.ssh.insert_key = false
  config.vm.define "webserver1" do |webserver1|
    webserver1.vm.hostname = "webserver1"
    webserver1.vm.box = "bento/centos-6.7"
    webserver1.vm.network "private_network", ip: "192.168.11.21"
  end
  config.vm.define "webserver2" do |webserver2|
    webserver2.vm.hostname = "webserver2"
    webserver2.vm.box = "bento/centos-6.7"
    webserver2.vm.network "private_network", ip: "192.168.11.22"
  end
end
