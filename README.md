# HARVESTIFY 🌿

#### A simple ML and DL based website which recommends the best crop to grow, fertilizers to use and the diseases caught by your crops.

# Learning to deploy ML project on EC2

1. connect to AWS instance
   `ssh -i /home/zohaib/deployonec.pem  ec2-user@54.237.196.63`
2. push entire app folder to AWS instance
   `sudo scp -i /home/zohaib/deployonec.pem -r /home/zohaib/deploy-in-ec2/app/ ec2-user@ec2-54-237-196-63.compute-1.amazonaws.com:~/`

3. To make site accessible to publicgot to `security group`> make one> inbpund rule: ALL traffic> attatch it with EC@ instance

python3 app.py

4. `ec2-54-237-196-63.compute-1.amazonaws.com:8080` in url to access it
