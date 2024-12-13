# MY STEP TO STEP GUIDE ON LAUNCHING MY EC2 INSTANCES TO INSTALL APACHE WEBSERVER ON IT
I started by signing into my AWS account using my IAM login details.
After signing in, I typed EC2 on the searach bar aand scroll down on the left side of my page to click security Group.
On the security group page i typed AtinukeAkinyemi_litaSG on the security group name aand select the VPC created by Lita.
I then added Inbound rule for my SSH and HTTP traffic and seet the source as Anywhere IP4 Address to alloww traffic anywhere While I left the outbound rule as it is by allowing all traffic.
After adding rule, I click on create Security Group.
### Below is the Image of the security Group created
! [SECURITY_GROUP PICTURE] (/(https://github.com/Atinuke-Akinyemi/LITA-PROJECT-/blob/main/SECURITY_GROUP%20PICTURE.png))

