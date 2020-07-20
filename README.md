# Stress-your-CPU-Instance


- select your instance > actions > connect > i am using windows, so connecting using putty


- now i am inside the instance which running the website



- let's install the utility called "stress", add the repo

sudo amazon-linux-extras install epel -y

sudo yum install stress -y


- stress the cpu

sudo stress --cpu 2 --timeout 30000           

(2 == number of cpu i have, 30000 == timeout seconds)













