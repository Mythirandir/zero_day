*I have been able to succesfully install vagrant and VirtualBox*
** Here's how its done **
1. Download and Install Vagrant
2. Download and install VirtualBox
** Next you will install Ubuntu Focal64**
*Let's do this*
`vagrant box add ubuntu/focal64`
`vagrant init ubuntu/focal64`
`vagrant plugin install vagrant-vbguest`
`vagrant up`
`vagrant ssh`
