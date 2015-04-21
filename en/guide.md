##How to Use 
####Manual 
-----
#####How to use AMIMOTO AMI
Easy! You don’t need to see the terminal! This movie clip is a comprehensive guide on how to use and how you can fully enjoy AMIMOTO AMI.

-----
#####Starts AWS EC2 with AMIMOTO AMI 
1. Open AWS Marketplace 
*WordPress Powered by AMIMOTO (HVM) on AWS Markeplace.*
Open WordPress powered by AMIMOTO (HVM) on AWS Marketplace.

-----
2. Select a region.
Select a region which you think your site is accessed from. For example, if your site is for Japan, please select “Asia Pacific (Tokyo)”.

-----
3. Click “Continue”
Click “Continue” to move to the next page.

-----
4. Log in to Amazon Web Services.
Log in to AWS.

-----
5. Select an instance type.
* T2 instance type only has VPS. Sometimes you may need to create a new VPC.
When you can’t find T2 family in the instance type, please look at “VPC Settings”.

-----
6. Security-Group
Select a security group.
Select “WordPress powered by AMIMOTO -HVM ***” from the security group menu.
* The security group “WordPress powered by AMIMOTO -HVM ***” is the setting which opens 80 for HTTP and 22 for SSH.

-----
7. Create “Key Pair”
Click “Visit the Amazon EC2 Console” in the “Key Pair” menu.

-----
8. Generate a new key at “Create Key Pair”
Click “Create Key Pair”.

-----
9. Enter “Key Pair name”
Enter “Key Pair Name” as you like.

-----
10. Created “Key Pair”
When the “Key Pair” is created, the pem file is downloaded automatically.
* DO NOT LOSE IT.

-----
11. Select the “Key Pair”
Back to Launch on EC2: AMIMOTO, reload the page and select the Key Pair just you created.


-----
12. Launch with 1-Click
Click “Launch with 1-Click”.

-----
13. Finish.
When you see “An instance of this software is now deploying on EC2″, that’s it.

-----
14. Confirm the running instance.
Open the EC2 dashboard and click “Instances”.
The URL appeared in “Public DNS” is the site URL.

-----
15. Install WordPress.
Open the URL of “Public DNS”.
And you will see your favorite WordPress installer window!

-----
#####AMIMOTO Hands-on Seminar 
This SlideShare is a comprehensive guide on how to use and how you can fully enjoy AMIMOTO AMI.
