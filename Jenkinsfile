This file is for Jenkins Groovy script
We will install 
#Nexus Default Username: admin Password: admin123
As a good security practice, Nexus is not advised to run nexus service as a root user,
# so create a new user called nexus and grant sudo access to manage nexus services as follows.
# Nexus will run on 4G of RAM
sudo hostname nexus
sudo useradd nexus
# Grand sudo access to nexus user
sudo echo "nexus ALL=(ALL) NOPASSWD:ALL" | sudo tee /etc/sudoers.d/nexus
sudo su - nexus

