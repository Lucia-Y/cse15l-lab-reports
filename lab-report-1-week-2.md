# Week 2 Lab Report

## Installing VScode

<img width="1019" alt="image 1" src="https://user-images.githubusercontent.com/103156151/162644905-5a490c83-8cc2-47a3-8ea0-89749223a1ab.png">

In order to download the Visual Studio Code application, we need to go the Visual Studio Code website [VS Code](https://code.visualstudio.com/) and follow the dowloading instructions there to download the application to our computers. After we sucessful download the Visual Studio Code application and open it, we can see the image above. 

## Remotely Connecting

<img width="511" alt="image7" src="https://user-images.githubusercontent.com/103156151/162646706-18993d5f-ba5a-4853-bf4f-34335d9c66cb.png">

Firstly, we need to find our course-specific accounts for CSE 15L course in the website [CSE 15L account](https://sdacs.ucsd.edu/~icc/index.php). Secondly, we should connect to the remote computer using VSCode’s remote option. Then in the Visual Studio Code, we need to open a new terminal, and type "ssh cs15lsp22zz@ieng6.ucsd.edu" to the terminal, but remember to replace "zz" by letters in our course-specific accounts. Since it is our first time connect to the server, there will be a message "Are you sure you want to continue connecting (yes/no/[fingerprint])?", and we need to answer "yes" to make sure we give the permission to connect. Finally, we enter our passwords for our accounts, and we will connect it successfully.

## Trying Some Commands

Running comands on computer

<img width="614" alt="Screen Shot 2022-04-10 at 5 43 57 PM" src="https://user-images.githubusercontent.com/103156151/162647832-8024a610-73ef-4617-b3d5-767bc4026447.png">

Running comands on remote computer after ssh-ing

<img width="505" alt="Screen Shot 2022-04-10 at 5 42 15 PM" src="https://user-images.githubusercontent.com/103156151/162647687-ec6f2e89-7531-43f3-a635-71c97ab7930e.png">

Firstly, we need to type some commands in the terminal of Visual Studio Code, for example, "ls" and "pwd", and we can get the outputs. Secondly, we connect to the server by typing "ssh cs15lsp22zz@ieng6.ucsd.edu" to the terminal, and replace "zz" by letters in our course-specific accounts. Finally, we try to type the commands in terminal, for example, "ls" and "pwd", and we can see the outputs are different than the outputs we get when running the commands in our computers before login.

## Moving Files with scp

<img width="843" alt="image14" src="https://user-images.githubusercontent.com/103156151/162648239-4b34d1aa-638f-4814-acda-dac04a460093.png">

Firstly, we need to create a new file named WhereAmI.java, and put the corresponding content into this file. And becasue we do not have java installed, we do not need to use "javac" and "java" on our computers to run this file. Secondly, we need to run this file by typing "scp WhereAmI.java cs15lsp22zz@ieng6.ucsd.edu:~/" to the terminal, and replace "zz" by letters in our course-specific accounts. Then, it will ask us to enter our passwords for our accounts. After logging into the accounts, we should use the command "ls" and run the file by using "javac" and "java", and we can see the output. Finally, we need to logging into our accounts by typing "ssh cs15lsp22zz@ieng6.ucsd.edu" to the terminal, and replace "zz" by letters in our course-specific accounts, and then follow the steps above to enter the passwords and use the command "ls" and run the file by using "javac" and "java", and we can see the output. 

## Setting an SSH Key

<img width="1252" alt="Screen Shot 2022-04-10 at 7 07 17 PM" src="https://user-images.githubusercontent.com/103156151/162653748-a06468dd-8ad0-4b6c-bf2c-ffe0dfc6ee32.png">

Firstly, we type "ssh-keygen" in the terminal, and when it says "Enter passphrase (empty for no passphrase):", we only need to click "return" until it does not ask for "enter passphrase" anymore, and then you can see the output. Secondly, we need to type "ssh cs15lsp22zz@ieng6.ucsd.edu", and replace "zz" by letters in our course-specific accounts, then, enter the passowrds for the accounts. After than, we should type "mkdir .ssh" in the terminal, and then type "<logout>". Then, we type "scp /Users/<user-name>/.ssh/id_rsa.pub cs15lsp22zz@ieng6.ucsd.edu:~/.ssh/authorized_keys", and replace "<user-name>" with our usernames, and replace "zz" by letters in our course-specific accounts.
  
## Optimizing Remote Running
  
<img width="440" alt="Screen Shot 2022-04-10 at 10 14 38 PM" src="https://user-images.githubusercontent.com/103156151/162669521-890c9b14-c494-4297-ac25-75174a0cfd73.png">

<img width="850" alt="Screen Shot 2022-04-10 at 10 15 08 PM" src="https://user-images.githubusercontent.com/103156151/162669540-1b0d7171-e88e-44ec-8b9f-256f6fa48aa5.png">

In order to make the running time become faster, we should use up arrow on our keyboard to call the last command we used again in the terminal. It can help us to reduce the time of typing all the commands.
