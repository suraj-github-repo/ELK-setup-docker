# ELK-setup-docker

# Step 1] For the setup of ELK  on your server need 
-->	Docker and docker compose  Installation
-->	Open require port 
-->	Create a ELK folder on your server and inside this folder crate all the following files 

# Step 2] clone the repository to your server
--> git clone and http path of the repo.
# step 3] then run following command for creating a containers 
--> docker compose up -d
--> docker ps -a  {for checking a containers list}

# Step 4] To check the  kibana and elasticsearch are running or not 
     Please check at browser like
For kibana - ip@address of server:5601
For elastiseach – ip@address of server:9201
Hit at browser.

#Step 5] When kibana running please do following configuration for setup kibana dashboard
-->	Go to the management 
--> In management , click at Index pattern 
--> Create Index Pattern


 








--> AT Index patter 
--> Search logstash and click on a Next step
 
--> Select @timestamp  and click on Create index pattern
 







--> Your index pattern now ready 
--> Then at the left hand side select Discover (mark by red box) for showing logs of your server in the form of graph 
 

--> Final out put
 


