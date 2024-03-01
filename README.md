# HARVESTIFY 🌿

#### A simple ML and DL based website which recommends the best crop to grow, fertilizers to use and the diseases caught by your crops.

# Learning to deploy ML project on EC2

1. connect to AWS instance
   `ssh -i /home/zohaib/deployonec.pem  ec2-user@54.237.196.63`
2. push entire app folder to AWS instance
   `sudo scp -i /home/zohaib/deployonec.pem -r /home/zohaib/deploy-in-ec2/app/ ec2-user@ec2-54-237-196-63.compute-1.amazonaws.com:~/`
