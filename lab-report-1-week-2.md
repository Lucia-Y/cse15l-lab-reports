# Week 2 Lab Report

## Installing VScode

<img width="1019" alt="image 1" src="https://user-images.githubusercontent.com/103156151/162644905-5a490c83-8cc2-47a3-8ea0-89749223a1ab.png">

In order to download the Visual Studio Code application, we need to go the Visual Studio Code website https://code.visualstudio.com/ and follow the dowloading instructions here to download the application to our computers. After we sucessful download the Visual Studio Code application and open it, we can see the image above. 

## Remotely Connecting

<img width="511" alt="image7" src="https://user-images.githubusercontent.com/103156151/162646706-18993d5f-ba5a-4853-bf4f-34335d9c66cb.png">

Firstly, we need to find our course-specific accounts for CSE 15L course in the website https://sdacs.ucsd.edu/~icc/index.php. Secondly, we should connect to the remote computer using VSCode’s remote option. Then in the Visual Studio Code, we need to open a new terminal, and type "ssh cs15lsp22zz@ieng6.ucsd.edu" to the terminal, but remember to replace zz by letters in our course-specific accounts. Since it is our first time connect to the server, there will be a message "Are you sure you want to continue connecting (yes/no/[fingerprint])?", and we need to answer "yes" to make sure we give the permission to connect. Finally, we enter our passwords for our accounts, and we will connect it successfully.

## Trying Some Commands

Running comands on computer

<img width="614" alt="Screen Shot 2022-04-10 at 5 43 57 PM" src="https://user-images.githubusercontent.com/103156151/162647832-8024a610-73ef-4617-b3d5-767bc4026447.png">

Running comands on remote computer after ssh-ing

<img width="505" alt="Screen Shot 2022-04-10 at 5 42 15 PM" src="https://user-images.githubusercontent.com/103156151/162647687-ec6f2e89-7531-43f3-a635-71c97ab7930e.png">

Firstly, we need to type some commands in the terminal of Visual Studio Code, for example, "ls" and "pwd", and we can get the outputs. Secondly, we connect to the server by typing "ssh cs15lsp22zz@ieng6.ucsd.edu" to the terminal, but remember to replace zz by letters in our course-specific accounts. Finally, we try to type the commands in terminal, for example, "ls" and "pwd", and we can see the outputs are different than the output we get when running the commands in our computers before login.

## Moving Files with scp

<img width="843" alt="image14" src="https://user-images.githubusercontent.com/103156151/162648239-4b34d1aa-638f-4814-acda-dac04a460093.png">

Firstly, we need to create a new file named WhereAmI.java, and put the corresponding content into this file. Secondly, we should run this file by using javac and java on our computers. 
