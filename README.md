## CS438 Vagrant Box

### Prerequisites
- VirtualBox
- [Vagrant](https://www.vagrantup.com/)

### Usage and Practices
1. Checkout this repo into your svn directory. i.e. `git clone git@github.com:xiaoyao1991/CS438-Vagrant.git /path/to/your/svn/<netid>/`
2. Run `vagrant up`. It will create 2 VMs: alpha and beta.
3. To ssh into alpha, run `vagrant ssh alpha`. You will find your svn directory at `/vagrant` directory. 
