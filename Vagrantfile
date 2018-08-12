Vagrant.configure("2") do |config|
  config.vm.define :alpha do |alpha|
    alpha.vm.box = "hashicorp/precise64"
    alpha.vm.network :private_network, ip: "192.168.33.10"
  end

  config.vm.define :beta do |beta|
    beta.vm.box = "hashicorp/precise64"
    beta.vm.network :private_network, ip: "192.168.33.11"
  end
end
