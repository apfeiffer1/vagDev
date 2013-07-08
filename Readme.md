
# VagDev -- Developing using Vagrant 

A simple project to ease the setting up of development VMs for the
CMS conditions (and possible other environments) using vagrant. 

To get started (see also the *Note* below):

   git clone https://github.com/apfeiffer1/vagDev.git 
   cd slc6
   vagrant up
   vagrant ssh

should be all you need to set up a devbox and use it. 

Enjoy ! :)



*Note:* Until the certificate issue with cmssdt is fixed, 
please first run this:

	vagrant box add --insecure vag-slc6-jul13 https://cmssdt.cern.ch/SDT/slc6-base-jul13.box

in order to first download the bare box into your environment, after 
this the procedure as mentioned above should work. 

