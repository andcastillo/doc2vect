# doc2vect
Install jypeter on fedora 

##Install the notebook
sudo dnf install -y python3-devel redhat-rpm-config gcc-c++ @'Development Tools'
sudo pip3 install --upgrade setuptools pip
sudo pip3 install pyzmq
sudo pip3 install jupyter

##Run the notebook
jupyter notebook
