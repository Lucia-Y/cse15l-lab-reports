# Lab Report 2

## 1. First Code Change
Screenshot for the code changes:
<img width="1243" alt="Screen Shot 2022-04-24 at 6 25 08 PM" src="https://user-images.githubusercontent.com/103156151/165006201-854e738c-1ec0-4ba6-897b-63965a58ce6d.png">
The link to the file that prompted me to make that change [TestFile2] (https://github.com/Mashyuf/markdown-parser/blob/main/test-file2.md)

The screenshot of failure-inducing input:
<img width="1221" alt="Screen Shot 2022-04-24 at 6 39 59 PM" src="https://user-images.githubusercontent.com/103156151/165007192-93189b7f-ac7c-41fa-a74d-df46e15a052a.png">

The screenshot of the symptom (output):

<img width="560" alt="Screen Shot 2022-04-24 at 6 30 08 PM" src="https://user-images.githubusercontent.com/103156151/165007901-d97cf0bf-a989-470f-aa7e-8e9e15b82c7c.png">

Relatiohsip among bug, symptom, and failure-inducing input: the code has the bug that when the text does not end with "]" or ")", the code can't recognize the ending of the text. So when using the failure-indcing input, the text does not end with "]" or ")", it causes a symptom that the output has a infinity loop. But after fixing the code, it gives the correct output.
