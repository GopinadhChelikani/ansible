# Ansible
sudo amazon-linux-extras install epel
sudo yum update -y
sudo yum install epel-release telnet bind-utils nano git -y
sudo yum -y install wget net-tools python3 daemonize java-1.8.0-openjdk
sudo yum update -y
curl -O https://bootstrap.pypa.io/get-pip.py
python3 get-pip.py --user
ls -a ~
export PATH=~/.local/bin:$PATH
source ~/.bash_profile
pip3 --version
pip3 install awscli --upgrade --user
sudo pip install boto
