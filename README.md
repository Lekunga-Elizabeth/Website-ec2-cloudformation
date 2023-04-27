# Website-ec2-cloudformation
step by step solution for this project 
-create a repo and clone
-put in your index.html
- push to github
- create-a keypair in your console under ec2 use .pem and not .ppk since will be using the cli to ssh in to it
-create-security group or used the default security group, make sure you edit the inbound role. to add ssh and everywhere as the port 22
-create a file call ec2-cloudformation.yaml
-copy and past the  code edit the comments, the keypair, the security group, and the Aim you will see this on your console under ec2, once you open the ec2 take lauch template then look at the right you will see your aim and you copy it 
-Deploy the stack used this command : aws cloudformation deploy --template-file ec2-cloudformation.yaml --stack-name elizabethstack
- Descript the stack used this command : 
- ssh in the instance, but befor you do that you have to cd .. untill you are in the part of your name, then you can now cd to you Downloads where your keypair is found. to ssh go your ec2 instance and connect then take ssh client copy it from there 
- once you are done with your ssh your virtual machine is then created 
- you need to install git in this machine. use this command. sudo yum install git -y
-Do git clone with the url of your project
- Test the website by doing sudo cp -R put your repository name

BELOW IS THE IMAGE OF MY WEBSITE CREATED WITH MY EC2 USING CLOUD FORMATION
![Screenshot 2023-04-27 012508](https://user-images.githubusercontent.com/116527791/234767176-f926dce2-56d5-49de-8e4d-e3c5c8af7869.jpg)



