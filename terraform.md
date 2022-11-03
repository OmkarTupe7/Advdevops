installation

'''
sudo mkdir -p /opt/terraform
'''

'''
cd /opt/terraform
'''
'''
sudo wget https://releases.hashicorp.com/terraform/0.15.3/terraform_0.15.3_linux_amd64.zip
'''

'''
sudo apt-get install unzip -y
'''

'''
sudo unzip terraform_0.15.3_linux_amd64.zip
'''

'''
sudo mv /opt/terraform/terraform /usr/bin/
'''

'''
terraform -version
'''
