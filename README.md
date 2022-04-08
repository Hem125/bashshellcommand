# bashshellcommand
## *Create, copy, move, delete, and organize files from the bash shell*
- #### create a folder 
![image](https://user-images.githubusercontent.com/103022040/162363931-296c6bc6-85d8-47af-93d7-85ab06cbf35e.png)
- #### create two file inside folder 1 name file1 and file2
 ![image](https://user-images.githubusercontent.com/103022040/162364155-c38901d3-0a1f-4efc-ab04-227e30de7684.png)
- #### create another folder for moving or copying files
![image](https://user-images.githubusercontent.com/103022040/162364833-363ea779-ff7f-415c-bc00-fca7816f7ac3.png)
- #### copy file 1 from folder1 to folder2 using cp command
![image](https://user-images.githubusercontent.com/103022040/162367516-8c4853b4-eb93-4a1c-bea9-9e2f0a47fb7f.png)
- #### now we have to move file2 from folder1 to folder2 
![image](https://user-images.githubusercontent.com/103022040/162368450-ec7c84c5-ca69-4517-ada0-4f097be1b2af.png)
- #### we can move using mv command 
![image](https://user-images.githubusercontent.com/103022040/162368680-9ce276b8-56a0-4861-ad04-e92eeb951b45.png)
- #### remove file1 from folder2 using rm command
![image](https://user-images.githubusercontent.com/103022040/162369358-b3e2cb93-5001-4dfe-8d87-09680bc65040.png)
- #### remove folder1 from list using rmdir command
![image](https://user-images.githubusercontent.com/103022040/162369755-c8bf6f0b-b31d-4472-a898-41ad7ab06004.png)
## *Create, view, and edit text files from command output or in an editor*
- #### create file using cat command and touch command, redirecrt command,nano command
![image](https://user-images.githubusercontent.com/103022040/162371244-863b3fa1-231f-4432-85aa-913b6601890a.png)
- #### edit file using nano command
![image](https://user-images.githubusercontent.com/103022040/162371741-18ea444a-6d9b-423c-a849-f8cb0bd05dd0.png)
- #### edit using vi command
![image](https://user-images.githubusercontent.com/103022040/162373336-e0a9f750-ebd0-4f5a-96e4-56af4594c423.png)
- #### view content of file using cat command 
![image](https://user-images.githubusercontent.com/103022040/162376405-f38f2688-cbb5-4235-b51c-b08b970c68b6.png)
## *Manage local Linux users and groups*
- #### list out all user in linux
![image](https://user-images.githubusercontent.com/103022040/162375905-88f9e70e-4f01-419c-b922-d0039618c198.png)
- #### id command to get id of username
![image](https://user-images.githubusercontent.com/103022040/162376772-5caad2b3-a000-4c5d-a9a9-a28fbd4c3092.png)
- #### useradd command to create a user 
![image](https://user-images.githubusercontent.com/103022040/162378221-2c37e360-2477-4c81-ab5b-8f55d62ff33f.png)
- #### Using passwd command to assign a password to a user
![image](https://user-images.githubusercontent.com/103022040/162378585-76fbd997-1516-4fd7-ac91-cd73cb9d26ea.png)
- #### This commands prints the data of the configuration file. This file contains information about the user in the format.  
 username : x : user id : user group id : : /home/username : /bin/bash 
![image](https://user-images.githubusercontent.com/103022040/162379726-671080fa-ceb5-46ef-8195-b7d87afbd1ca.png)
- #### command to change the user id of user
![image](https://user-images.githubusercontent.com/103022040/162380278-8d309534-23ff-4266-91ed-3b9057001849.png)
- #### delete a user name 
![image](https://user-images.githubusercontent.com/103022040/162381045-3b14b233-3434-4361-8328-df5b4e36967c.png)
## *Set Linux file system permissions on files*
- #### we can see the permission of file  using long list command
![image](https://user-images.githubusercontent.com/103022040/162383493-dd8a1be8-bb7f-4211-8239-96fdded704a9.png)
- #### give all permission to group user and other in file3.txt 
![image](https://user-images.githubusercontent.com/103022040/162383077-46bd4164-3a0d-45a5-8690-bd1aaa441511.png)
- #### removing all permission from group user and other in file4.txt
![image](https://user-images.githubusercontent.com/103022040/162384140-7026e2c7-f6a9-459f-89c2-62e07c3af6d4.png)
- #### giving all permission to user, read write permission to group and read permission to other in file4.txt
![image](https://user-images.githubusercontent.com/103022040/162385009-298514e2-ef38-4101-8055-8824230aef8b.png)
 ## *Obtain information about the system*
- #### display information of active process by ps command
![image](https://user-images.githubusercontent.com/103022040/162397664-7bfb49f1-bf4c-4448-b955-8136e9fa8fd2.png)
- #### offer dynamic view of running system using top command acts as a system monitoring tool
![image](https://user-images.githubusercontent.com/103022040/162398266-10dcb6b3-fca2-44ed-8221-e66c60493432.png)
 ## *control processes running on it.*
 - #### killing process using kill command
 ![image](https://user-images.githubusercontent.com/103022040/162401888-c11f9294-e62e-4cde-9a92-4cb01150bad3.png)
 - #### sending signal to process using kill -l
 ![image](https://user-images.githubusercontent.com/103022040/162402422-8bd1f31f-57c4-4653-8079-16ffac081470.png)
- #### use pkill or killall to kill an application
![image](https://user-images.githubusercontent.com/103022040/162403367-99a7c96b-890a-4141-b1bb-7bb6f599d952.png)
 ## *Configure and secure OpenSSH service*
- #### using scp command to copy a file from one operating system to another
![image](https://user-images.githubusercontent.com/103022040/162409333-b35e5526-313c-4ce8-9577-d3a07c8f132e.png)
- #### file transferred using ip address of another operating system 
![image](https://user-images.githubusercontent.com/103022040/162409664-615427e4-7671-4a6f-9441-1de707a76764.png)
## *Installation of Apache2*
- #### We can install using following command
![image](https://user-images.githubusercontent.com/103022040/162413196-69bc6859-a40a-4f71-9760-eaf77b93c226.png)
- #### update apache2 using following command
![image](https://user-images.githubusercontent.com/103022040/162413426-482d1cf7-4ee4-437d-b2f8-b1aec6276e72.png)
- #### we can test it out by typing in our IP address for the web server.
![image](https://user-images.githubusercontent.com/103022040/162413985-64cd01f5-82a0-4144-8335-4e5ec8a2be42.png)
## *Installation of nginx*
- #### we can install using following command 
![image](https://user-images.githubusercontent.com/103022040/162415036-8dc944aa-ea39-4ff2-b913-144568b5fabe.png)
