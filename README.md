# Project-1
For project1
 I learnt what LAMP is (Linux Apache MysQl PhP). This is a web-stack in aws  that is set up to develop a software product
 A technology web-stacks are set of frameworks and  tools. There are other webstacks which includes LEMP, MEAN, MERN stacks
 I created a server in the internet using amazon web instance, I created an EC2 instance on aws using the aws console
 For LAMP; I downloaded a Linux os named  ubuntu, I ssh into the ec2 instance I created so as to download the rest of the
stacks in my instance, next I downloaded the Apache2 in my instance using sudo apt install apache2, to serve my content. After that I checked the status
of my apache2 using sudo systemctl apache2 status, and if it is not running one can use sudo systemctl apache2 start.
 After Apache2 was downloaded, I downloaded and installed the MysQl in the server I created on my aws instance; this is to store and  manage my data, I downloaded MysQl using the command sudo apt install Mysql-server.After installation, logged into Mysql using sudo     mysql, then after I went ahead to create the password for mysql following the steps.
 The last tool is the php; this is the component of the stack setup that will process code to display dynamic content to the end user.
there are 3 packages that came with the php tool to interact with one another,php-mysql is a PHP module that allows PHP to communicatewith MySQL-based databases. libapache2-mod-php is to enable Apache to handle PHP files. Core PHP packages will automatically be installed as dependencies.

