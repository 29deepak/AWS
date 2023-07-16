# AWS
#Step1
<p>how to configure AWS <br/>
1--to create a new instances of EC2(instances)<br/>
   --to right side click launch instances
   --inside the launch instances
       ---Name-- You enter
       ---Amazon Linux(Free Tier)
       ----to create key,value pairs or existing 
       ----to create folder where you use these things that folder you store aws Credentials
       ----create Security group (for New user)
       ----at the right side launch instances click on that.
       ----you create new instances successfully <br/>
2--Go to EC2 Dashboard ,where you see your created instances is there.
 --click on the instances Id 
---After that new page is open 
---At the right top side connect option is there just click on that.
---in that go to SSH Client 
----At the bottom there is Some url (copy that) like that it shows....ssh -i "kunal.pem" ec2-user@ec2-44-204-61-222.compute-1.amazonaws.com <br/>

3---created that folder where aws credentials is there ,which we use command prompt
 ---open terminal
 ----cd your folder name (location of the folder)
 ---After that you copy that url from aws paste it here (this one ->ssh -i "kunal.pem" ec2-user@ec2-44-204-61-222.compute-1.amazonaws.com)
 ---After that you are in EC2 user .<br/>
4--congrats you are done till here.
</p>
<br/>
#step2
<p>
   step2---
 you are in the linux user
that is Ec2 User<br/>
1----------------------------------------------------------------------------------------------------------------
it showm like that [ec2-user@ip-44-204-61-222]$
 ----you should change in to parent user that is root user , you write the commmand (sudo su) after that it changes in to parent user
that is shown like that [root@ip-44-204-61-222]#
step1-------------Installation of Node---------------------------------------------------------------------------------

After that you write the command (curl --silent --location https://rpm.nodesource.com/setup_14.x | bash -) in the root user

after thatyou write the command (sudo yum install -y nodejs) <br/>

step2 -----------------Installation of Git--------------------------------------------------------------------------------------
command you writethat
sudo yum install git -y  or sudo yum install git ~y^C
check the version

node -v
npm -v
git -v
 after that write the command
  (git clone repository_url)
   

after that check that write the commmand (ls) - it is there or not


after that go to that repository
just example (example_tracker is my repo)


write the command

(cd example_tracker/)

Cd(ls -la) ---check the private which is started .env


after that you write the command for dot env file

vi .env

just keyboard i , after thatyou write it.


after that save the file (:qa)


after that installl with the command (npm install)
</p>
