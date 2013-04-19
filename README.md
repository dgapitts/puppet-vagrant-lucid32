*** THIS PROJECT IS STILL UNDER DEVELOPMENT ***

1) Install vagrant, VirtualBox  and download lucid32 base box

This project is a simple Vagrant lucid32 server, so before you start you will need to install vagrant and VirtualBox. These are both very popular software and the latest version can installed in a couple of minutes ... just google it!
Next download the lucid32.box:

  vagrant box add lucid32 http://files.vagrantup.com/lucid32.box

FYI ... vagrant will save the 249M box file in a hidden directory:

  $ cd ~/.vagrant.d/boxes
  $ ls -ltr
  drwxr-xr-x  5 dpitts  660531311  170 Apr  9 22:43 lucid32
  $ du -h
  249M  ./lucid32

2) Clone this repo

3) Go to the repo and launch the box

  cd [repo]
  vagrant up
