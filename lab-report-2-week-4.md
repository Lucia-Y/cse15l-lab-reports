# Lab Report 2

## 1. First Code Change
Screenshot for the code changes:

<img width="712" alt="Screen Shot 2022-04-24 at 7 49 50 PM" src="https://user-images.githubusercontent.com/103156151/165012693-79b028de-07cd-4b69-a252-3e8c93203dab.png">

The link to the file that prompted me to make that change [TestFile2] (https://github.com/Lucia-Y/markdown-parser/blob/main/test-file2.md)

The screenshot of failure-inducing input:

<img width="711" alt="Screen Shot 2022-04-24 at 7 50 46 PM" src="https://user-images.githubusercontent.com/103156151/165012750-b09bed6c-3244-4cca-aabe-6719623ffc95.png">

The screenshot of the symptom (output):

<img width="602" alt="Screen Shot 2022-04-24 at 7 58 25 PM" src="https://user-images.githubusercontent.com/103156151/165013642-6e8722cf-4dba-454d-a10a-5d78df66a8c4.png">

__Relatiohsip among bug, symptom, and failure-inducing input:__ the code has the bug that when the text does not end with ")", the code can't recognize the ending of the text. So when using the failure-indcing input, the text does not end with ")", it causes a symptom that the output has a infinity loop, which leads to the out of memeory error. But after fixing the code, it gives the correct output.


## 2. Second Code Change
Screenshot for the code changes:

<img width="710" alt="Screen Shot 2022-04-24 at 8 04 07 PM" src="https://user-images.githubusercontent.com/103156151/165014022-146473dc-712f-41f5-81d2-b4a81969d4bb.png">

The link to the file that prompted me to make that change [TestFile3] (https://github.com/Lucia-Y/markdown-parser/blob/main/test-file3.md)

The screenshot of failure-inducing input:

<img width="710" alt="Screen Shot 2022-04-24 at 8 06 23 PM" src="https://user-images.githubusercontent.com/103156151/165014176-1d619de3-ad51-424a-bacf-467a1c4158fa.png">

The screenshot of the symptom (output):

<img width="623" alt="Screen Shot 2022-04-24 at 8 00 18 PM" src="https://user-images.githubusercontent.com/103156151/165013708-b9627b98-b16b-404b-bda1-ee5376edea55.png">

__Relatiohsip among bug, symptom, and failure-inducing input:__ the code has the bug that when the text does not end with ")", the code can't recognize the ending of the text. So when using the failure-indcing input, the text does not end with ")", it causes a symptom that the output has a infinity loop. But after fixing the code, it gives the correct output.
