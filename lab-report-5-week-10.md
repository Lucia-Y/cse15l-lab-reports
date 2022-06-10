# Lab Report 5

__How you found the tests with different results:__ I used ``vimdiff`` on the results of running a bash for loop to find the tests with different results.

<img width="1440" alt="Screen Shot 2022-06-10 at 3 09 57 PM" src="https://user-images.githubusercontent.com/103156151/173157199-cd5f6ee5-8fc8-4e8d-a2d5-29240d37963f.png">


__link to the test-file with different-results:__ [Test 571](https://github.com/xzrRyan/markdown-parser/blob/main/test-files/571.md)
[Test 578](https://github.com/xzrRyan/markdown-parser/blob/main/test-files/578.md)


## 1. Test 571

__Actual outputs:__  
<img width="1220" alt="Screen Shot 2022-06-10 at 4 08 07 PM" src="https://user-images.githubusercontent.com/103156151/173161205-1d1493eb-6971-4ed6-8a2c-0f782ff8617c.png">

__Expected outputs:__ 
<img width="1187" alt="Screen Shot 2022-06-10 at 3 27 48 PM" src="https://user-images.githubusercontent.com/103156151/173161298-03c83b3f-51d7-451e-8325-edd64dd3ffa2.png">
Since it is an image reference, it is not a link, the expected output should be ``[]``.

__Describe which implementation is correct:__ The output from the lab 9 version is correct, since the ouput is ``[]``.

__Describe the bug:__ 

<img width="857" alt="Screen Shot 2022-06-10 at 4 24 46 PM" src="https://user-images.githubusercontent.com/103156151/173162130-feb6aa45-316b-4731-96bd-54098c73faf6.png">
The problem for the code is that it still considers it as a link when there is ``!`` in front of the ``[]``. In order to fix the code, we need to add another condition that when there is ``!`` in front of the ``[]``, the while loop should be ``break``.

## 2. Test 578
__Actual outputs:__ 
<img width="1162" alt="Screen Shot 2022-06-10 at 4 08 26 PM" src="https://user-images.githubusercontent.com/103156151/173161237-c287a431-d94b-4e72-a186-947e82ec1ca4.png">

__Expected outputs:__ 
<img width="1187" alt="Screen Shot 2022-06-10 at 3 28 53 PM" src="https://user-images.githubusercontent.com/103156151/173161312-d54a1107-6928-4a78-aab0-5e6c337dcf17.png">
Since it is an image reference, it is not a link, the expected output should be ``[]``.

__Describe which implementation is correct:__ The output from the lab 9 version is correct, since the ouput is ``[]``.

__Describe the bug:__ 

<img width="857" alt="Screen Shot 2022-06-10 at 4 24 46 PM" src="https://user-images.githubusercontent.com/103156151/173162246-005c9c46-79d0-4ae8-a988-a9b5ade30c82.png">
The problem for the code is the same as the problem for test 571, which is that it still considers it as a link when there is ``!`` in front of the ``[]``. In order to fix the code, we need to add another condition that when there is ``!`` in front of the ``[]``, the while loop should be ``break``.
