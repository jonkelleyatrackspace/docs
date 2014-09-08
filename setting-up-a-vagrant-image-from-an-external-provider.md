Setting up a CENTOS 7 vagrant image from opscode.
=========
By Jon Kelley

NOTE: Tested on host OS of Ubuntu 14.04 LTS


1) Download and install VirtualBox

2) Add the .box CENTOS 7 image from opscode. I happened to find it at the github readme.md for https://github.com/opscode/bento. We will save it as **opscode-centos-7.0**.

``` vagrant box add opscode-centos-7.0 http://opscode-vm-bento.s3.amazonaws.com/vagrant/virtualbox/opscode_centos-7.0_chef-provisionerless.box ```

3) Go to your working directory where you want to start vagrant work.

4) Initialize your first Vagrantfile

``` vagrant init opscode-centos-7.0 ```

5) Try to bring it up

``` vagrant up```

