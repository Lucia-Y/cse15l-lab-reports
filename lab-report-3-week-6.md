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

Screenshot for using ```scp``` command copying a file to my account:
<img width="1298" alt="Screen Shot 2022-05-08 at 8 50 21 PM" src="https://user-images.githubusercontent.com/103156151/167337549-2f29d2de-d01d-4ca2-bffc-00a65de21509.png">

I created a new file in the ```~/.ssh``` directory, named ```newFile```, and then I used ```scp newFile ieng6:~/``` to move this ```newFile``` to my account.

## 2. Setup Github Access from ieng6


## 3. Copy whole directories with ```scp -r```

