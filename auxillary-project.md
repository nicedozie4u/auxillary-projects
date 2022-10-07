## In this project, i will onboard 20 new Linux users onto a server using shell scripting.


Lunch EC2 Instnce 

![EC2 Image](./images/EC2_shell_script.PNG)

Create the project folder

`mkdir Shell`

Move into the Shell folder

`cd Shell`

Create a csv file name 

`touch names.csv`

Open the names.csv file

`vim names.csv`

Insert some random names into it. (One name per line)

![Random names](./images/names.csv)

Open and populate the id_rsa.pub file the public key then Save and exit.

![id_rsa.pub](./images/publickey.PNG)

Add shell script to automate the onboarding of 20 users then Save and exit.

![shell script](./images/shell%20script.PNG)

Create the developers group then
Make the shell script executable

`sudo groupadd developers`

`sudo chmod +x onboarding_users.sh`

![create group](./images/create%20group.PNG)

Change user to super and run script.

`sudo su`

![change mode](./images/change%20user%20mode.PNG)


User are created successfully


![change mode](./images/20users_created.PNG)

Verify the new users

`cd ../..`

`ls -la`

![change mode](./images/users_verified.PNG)

Testing one of the created users from putty

![testing user](./images/Testing_user.PNG)

## Congratulations.