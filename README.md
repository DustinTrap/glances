# glances
#Simple script to install glances on a RHEL 7 server

sudo yum install python-devel -y
export PATH="/opt/rh/python27/root/usr/bin/:$PATH"
pip install glances
