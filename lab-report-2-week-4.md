# Lab Report 2

## 1. First Code Change
Screenshot for the code changes:

<img width="1232" alt="Screen Shot 2022-04-24 at 10 02 08 PM" src="https://user-images.githubusercontent.com/103156151/165023865-f587dea5-6753-4f50-85bf-7f85baa8e541.png">
 
 The link to the file that prompted me to make that change [TestFile2](https://github.com/Mashyuf/markdown-parser/blob/main/test-file2.md)
 
 The screenshot of failure-inducing input:
 
 <img width="1221" alt="Screen Shot 2022-04-24 at 6 39 59 PM" src="https://user-images.githubusercontent.com/103156151/165007192-93189b7f-ac7c-41fa-a74d-df46e15a052a.png">
 
 The screenshot of the symptom (output):
 
<img width="602" alt="Screen Shot 2022-04-24 at 7 58 25 PM" src="https://user-images.githubusercontent.com/103156151/165023915-0d65fb1e-48a3-4887-a6a3-cc548ba4173e.png">

__Relatiohsip among bug, symptom, and failure-inducing input:__ the code has the bug that when the text does not end with ")" or "]", the code can't recognize the ending of the text. So when using the failure-indcing input, the text does not end with ")"or "]", it causes a symptom that the output has a infinity loop, which leads to the out of memeory error. But after fixing the code, it gives the correct output, which is the links.


## 2. Second Code Change
Screenshot for the code changes:

<img width="710" alt="Screen Shot 2022-04-24 at 10 20 26 PM" src="https://user-images.githubusercontent.com/103156151/165026574-8ebedd66-fb5e-412f-bd7b-b82dc25f38e8.png">

The link to the file that prompted me to make that change [TestFile3](https://github.com/Mashyuf/markdown-parser/blob/main/test-file3.md)

The screenshot of failure-inducing input:

<img width="711" alt="Screen Shot 2022-04-24 at 10 20 39 PM" src="https://user-images.githubusercontent.com/103156151/165026608-dca5ba35-ecda-4030-a436-773739e8bacb.png">

The screenshot of the symptom (output):

<img width="650" alt="Screen Shot 2022-04-24 at 10 13 55 PM" src="https://user-images.githubusercontent.com/103156151/165026674-018eed0a-4168-49b0-a18d-4f6a38b95e1a.png">

__Relatiohsip among bug, symptom, and failure-inducing input:__ the code has the bug that when the file contains image reference, since the image reference has "[", "]", "(", and ")", the code will recognize it as a link and return the image reference, however, it is not a link, it should return a bracket with nothing in it. So when using the failure-indcing input, the image reference causes a symptom that the output is the image reference, which is wrong. But after fixing the code, it gives the correct output, which is a bracket with nothing inside.


## 3. Third Code Change
Screenshot for the code changes:

<img width="712" alt="Screen Shot 2022-04-24 at 11 05 11 PM" src="https://user-images.githubusercontent.com/103156151/165030524-11dc2e98-0636-427b-bc51-3253d59ccb56.png">

The link to the file that prompted me to make that change [TestFile4](https://github.com/Lucia-Y/markdown-parser/blob/main/test-file4.md)

The screenshot of failure-inducing input:

<img width="713" alt="Screen Shot 2022-04-24 at 11 12 51 PM" src="https://user-images.githubusercontent.com/103156151/165030645-1a51b28f-f181-46a9-8850-eb9906374ec2.png">

The screenshot of the symptom (output):

<img width="593" alt="Screen Shot 2022-04-24 at 11 02 16 PM" src="https://user-images.githubusercontent.com/103156151/165030488-3a930528-1ef6-434e-ac6b-7d10977c11e7.png">

__Relatiohsip among bug, symptom, and failure-inducing input:__ the code has the bug that when there is a space between the link name and the link, since the link with this wrong format still has "[", "]", "(", and ")", the code will recognize the link with wrong format as a link and return the link, however, it is not a link because of its format, it should return a bracket with nothing in it. So when using the failure-indcing input, the link with worng format causes a symptom that the output is the link, which is wrong. But after fixing the code, it gives the correct output, which is a bracket with nothing inside.

