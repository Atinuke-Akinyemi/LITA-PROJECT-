# MY STEP TO STEP GUIDE ON LAUNCHING MY EC2 INSTANCES TO INSTALL APACHE WEBSERVER ON IT
I started by signing into my AWS account using my IAM login details.
After signing in, I typed EC2 on the searach bar aand scroll down on the left side of my page to click security Group.
On the security group page i typed AtinukeAkinyemi_litaSG on the security group name aand select the VPC created by Lita.
I then added Inbound rule for my SSH and HTTP traffic and seet the source as Anywhere IP4 Address to alloww traffic anywhere While I left the outbound rule as it is by allowing all traffic.
After adding rule, I click on create Security Group.
### The Image of my security Group created is uploaded above on my Github.com page due to the fact that my laptop is window 7 and couldn't download the github desktop
## NEXT STEP: WHICH IS LAUNCHING MY INSSTANCES 
I click on Launch Insstances and enter AtinukeAkinyemi_lita as my Name and tags Info and hoose AWS as Application and OS Images.
I then Choose Amazon Linux 2 AMI for Amazon Machine Image and t2 Micro as my instance type.
After which i created my keypair by clicking New keypair and entering my keypair name AtinukeAkinyemi_Kp
I then edited my Network setting by choosing the VPC created by LITA and set my EC2 to be on the public subnet created by Lita so as to access via Internet and enable Auto-assign public IP Info and then select the existing security group created by me.
Then I lauch my Instances and Refresh the page to see if it has be check.
### The Image of my instances running is also uploaded above on my Github.com page



