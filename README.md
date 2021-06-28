This is a useful bash script that will let you save time creating vhosts for you.

It supports both ubuntu and centos (be careful to write ubuntu or centos in lowercase).

Instructions:

mkdir ~/scripts && cd $_
wget https://raw.githubusercontent.com/mattmezza/vhost-creator/master/vhost-creator.sh
chmod +x vhost-creator.sh
sudo ./vhost-creator.sh
follow Instructions
or for the most adventurous just run curl -s https://raw.githubusercontent.com/mattmezza/vhost-creator/master/install.sh | sh to install it globally for your user (you can use the script afterwards with sudo vhost-creator)

Don't forget to add a A record from your DNS pointing to your web server IP address.

You can also mv the script to a system wide bin folder or add it to your bash profile.

The original idea was this one

Thanks to:
alexnogard for his original version
