# Lab Report 2

## 1. First Code Change
Screenshot for the code changes:

<img width="712" alt="Screen Shot 2022-04-24 at 7 49 50 PM" src="https://user-images.githubusercontent.com/103156151/165012693-79b028de-07cd-4b69-a252-3e8c93203dab.png">

The link to the file that prompted me to make that change [TestFile2] (https://github.com/Lucia-Y/markdown-parser/blob/main/test-file2.md)

The screenshot of failure-inducing input:

<img width="711" alt="Screen Shot 2022-04-24 at 7 50 46 PM" src="https://user-images.githubusercontent.com/103156151/165012750-b09bed6c-3244-4cca-aabe-6719623ffc95.png">

The screenshot of the symptom (output):

<img width="560" alt="Screen Shot 2022-04-24 at 6 30 08 PM" src="https://user-images.githubusercontent.com/103156151/165007901-d97cf0bf-a989-470f-aa7e-8e9e15b82c7c.png">

__Relatiohsip among bug, symptom, and failure-inducing input:__ the code has the bug that when the text does not end with ")", the code can't recognize the ending of the text. So when using the failure-indcing input, the text does not end with ")", it causes a symptom that the output has a infinity loop. But after fixing the code, it gives the correct output.


## 2. Second Code Change
Screenshot for the code changes:
