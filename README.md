## user for ec2 user data  
sudo yum install -y python  
cd /etc/init.d  
sudo wget https://raw.githubusercontent.com/fliuheyan/heartbeat/master/hearbeat -o server8080  
sudo chkconfig server8080 on  
sudo service server8080 start  

