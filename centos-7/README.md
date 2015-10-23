From the installation from the Centos7 minimal, choose the install option and hit "tab", then remove the "quiet" and append the following lines below for an automated install

  noverifyssl ks=https://raw.githubusercontent.com/abedwardsw/build/master/centos-7/kickstart.txt
