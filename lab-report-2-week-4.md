# Lab Report 2

## 1. First Code Change
Screenshot for the code changes:
<img width="1229" alt="Screen Shot 2022-04-24 at 7 08 06 PM" src="https://user-images.githubusercontent.com/103156151/165009186-8cace1a8-bc0a-4c64-be3a-62dff3da5fa3.png">
The link to the file that prompted me to make that change [TestFile2] (https://github.com/Mashyuf/markdown-parser/blob/main/test-file2.md)

The screenshot of failure-inducing input:
<img width="1221" alt="Screen Shot 2022-04-24 at 6 39 59 PM" src="https://user-images.githubusercontent.com/103156151/165007192-93189b7f-ac7c-41fa-a74d-df46e15a052a.png">

The screenshot of the symptom (output):

<img width="560" alt="Screen Shot 2022-04-24 at 6 30 08 PM" src="https://user-images.githubusercontent.com/103156151/165007901-d97cf0bf-a989-470f-aa7e-8e9e15b82c7c.png">

__Relatiohsip among bug, symptom, and failure-inducing input:__ the code has the bug that when the text does not end with "]" or ")", the code can't recognize the ending of the text. So when using the failure-indcing input, the text does not end with "]" or ")", it causes a symptom that the output has a infinity loop. But after fixing the code, it gives the correct output.


## 2. Second Code Change
Screenshot for the code changes:
