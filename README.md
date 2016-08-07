## user for ec2 user data  
sudo yum install -y python  

cd /etc/init.d  

[[ ! -f heartbeat-server ]] && sudo wget https://raw.githubusercontent.com/fliuheyan/heartbeat/master/heartbeat -o heartbeat-server && sudo chmod +x heartbeat-server 

sudo service heartbeat-server start  
