## user for ec2 user data  
yum install -y python  
cd /etc/init.d  
wget https://raw.githubusercontent.com/fliuheyan/heartbeat/master/hearbeat -o server8080  
sudo chkconfig server8080 on  
sudo service server8080 start  

