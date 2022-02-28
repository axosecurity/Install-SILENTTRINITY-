# Install-SILENTTRINITY-
in this repository i had share some comand for installing SILENTTRINITY in your linux system

# <h1>Install useing Apt <h1>
# sudo apt-cache search silenttrinity    
  
  # sudo apt install silenttrinity -y
  
  
  
 #<h1>Install from Git<h1>
  
git clone https://github.com/byt3bl33d3r/SILENTTRINITY

apt update && apt upgrade  

apt install python3.7 python3.7-dev python3-pip

sudo -H pip3 install -U pipenv

cd SILENTTRINITY  

pip3 install -r requirements.txt

pipenv install && pipenv shell 
  
  
  
# Silenttrinity Comands
  
  silenttrinity teamserver --port 81 127.0.0.1 password

  silenttrinity client wss://username:password@127.0.0.1:81     
  
