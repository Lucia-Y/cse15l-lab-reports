# Lab Report 3

## 1. Streamlining ssh Configuration

Screenshot for ```.ssh/config``` file:
<img width="1303" alt="Screen Shot 2022-05-08 at 7 18 49 PM" src="https://user-images.githubusercontent.com/103156151/167329750-71120e51-a51e-4f45-bc2e-165fa89449b3.png">

I went to the terminal in my computer,and then I created the ```~/.ssh``` directory by using ```mkdir -p ~/.ssh```. After that, I used ```cd ~/.ssh``` to go into the ```~/.ssh``` directory, and then I used ```open -t config``` to open my ```config``` file.

Screenshot for editing the file in the terminal of the computer:
<img width="699" alt="Screen Shot 2022-05-08 at 7 26 37 PM" src="https://user-images.githubusercontent.com/103156151/167330381-ba2c0c0c-e713-4e10-be4d-e1739a87a3f5.png">

I copied these three important lines to my ```config``` file, and I replaced the ```zzz``` of the ```cs15lsp22zzz``` to my account, which is ```ahp```.

Screenshot for using ```ssh``` command to login into my account:
<img width="570" alt="Screen Shot 2022-05-08 at 7 28 02 PM" src="https://user-images.githubusercontent.com/103156151/167330547-b4acfa54-2953-4f8f-a580-2cfadf303ef2.png">

I only typed ```ssh ieng6``` to login to my account.

Screenshot for using ```scp``` command to copy a file to my account:
<img width="1298" alt="Screen Shot 2022-05-08 at 8 50 21 PM" src="https://user-images.githubusercontent.com/103156151/167337549-2f29d2de-d01d-4ca2-bffc-00a65de21509.png">

I created a new file in the ```~/.ssh``` directory, named ```newFile```, and then I used ```scp newFile ieng6:~/``` to copy this ```newFile``` to my account.

## 2. Setup Github Access from ieng6

Screenshot for public key storing on Github:
<img width="786" alt="Screen Shot 2022-05-08 at 9 36 29 PM" src="https://user-images.githubusercontent.com/103156151/167341499-3fb3ae1e-72ad-4602-82c2-1c6883cb4bb0.png">

I created a new SSH key in my terminal and then, I followed the (tutorial)[https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account] for adding the new SSH key to the Github.

## 3. Copy whole directories with ```scp -r```

