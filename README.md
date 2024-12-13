# MY STEP TO STEP GUIDE ON LAUNCHING MY EC2 INSTANCES TO INSTALL APACHE WEBSERVER ON IT
I started by signing into my AWS account using my IAM login details.
After signing in, I typed EC2 on the searach bar aand scroll down on the left side of my page to click security Group.
On the security group page i typed AtinukeAkinyemi_litaSG on the security group name and select the VPC created by Lita.
I then added Inbound rule for my SSH and HTTP traffic and seet the source as Anywhere IP4 Address to alloww traffic anywhere While I left the outbound rule as it is by allowing all traffic.
After adding rule, I click on create Security Group.
### The Image of my security Group created is uploaded above on my Github.com page
![SECURITY GROUP IMAGE](/SECURITYGROUP.png)
## NEXT STEP: WHICH IS LAUNCHING MY INSTANCES 
I click on Launch Insstances and enter AtinukeAkinyemi_lita as my Name and tags Info and hoose AWS as Application and OS Images.
I then Choose Amazon Linux 2 AMI for Amazon Machine Image and t2 Micro as my instance type.
After which i created my keypair by clicking New keypair and entering my keypair name AtinukeAkinyemi_lita_Kp.pem
I then edited my Network setting by choosing the VPC created by LITA and set my EC2 to be on the public subnet created by Lita so as to access via Internet and enable Auto-assign public IP Info and then select the existing security group created by me.
Then I lauch my Instances and Refresh the page to see if it has be checked.
### The Image of my instances running is also uploaded above on my Github.com page
![EC2INSTANCESIMAGE](/EC2RUNNING.png)
## NEXT STEP: WHICH IS CONNECTING TO MY EC2 INSTANCES TO INSTALL APACHE WEBSERVER ON IT.
I click on my EC2 instance and go to connect.
I then move to the SSH client and copied the document under key not publicly viewable and paste it on gitbash where my keypair is downloaded.
### The image of my SSH Client is uploaded above on my Github.com page
![SSHCLIENT](/SSHClient.png)
Then i connect to my EC2 instance by copying the example the example in SSH client, the example already has my keypair name and my EC2 instance and i pasted it on the gitbash and it ask if i want to continue and i typed yes.
### The image of where my EC2 instance is sitting on is uploaded above on my Github.com page
## NEXT STEP IS INSTALLING APACHE 
I install the Apache webserver by typing the code on my project documents on the gitbash command page
### The two images of my Gitbash page running while trying to install my Apache  webserver is above on my Github.com page
##  NEXT STEP IS THE COPYING OF MY IP ADDRESS ON MY WEB BROWSER TO VIEW THE TEST PAGE
I copied my IP Address from my EC2 Instance and pasted it on my browser search bar and it displayed the test page cconfirming i have successfully insstall my Apache webserver on my EC2 inatance and then i exited from my gitbash command page.
### The image of my testpage displaying is uploaded above on my github.com
Below is my IP Address to the Test page of my Apache Webserver:
http://18.232.122.138/

#### Thanks LITA Team
#### God Bless you all


