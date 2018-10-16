Vagrant.configure("2") do |config|
  config.vm.box = "vatman/xenial64"
  config.vm.provision :shell, :path => "install_ruby.sh", :privileged => true
  config.vm.provision :shell, :path => "hello.rb", :privileged => false
end
