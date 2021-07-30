# Azure-manager
Manage your VM in Azure using cookies.

Default VM infomation:

USERNAME : defaultuser<br>
PASSWORD : Thisisyour.password1

## 1.Install Python3.9.6

apt update && sudo apt upgrade 

apt install wget build-essential libreadline-gplv2-dev libncursesw5-dev \
     libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev libffi-dev zlib1g-dev  


wget https://www.python.org/ftp/python/3.9.6/Python-3.9.6.tgz 

tar xzf Python-3.9.6.tgz 

cd Python-3.9.6 

./configure --enable-optimizations 


## 2.Install Python Library

pip3.9 install -r requirements.txt


## 4.RUN!!
python3.9 app.py

Visit 127.0.0.1:8888 and enjoy yourself.


