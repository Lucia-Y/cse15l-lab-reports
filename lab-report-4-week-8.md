# Lab Report 4

Link for my group's markdown-parse repository: [my group's repo](https://github.com/Mashyuf/markdown-parser)

Link for the markdown-parse repository my group reviewed: [repo my group reviewed](https://github.com/cmy0357/markdown-parser)

## 1. Snippet 1

__Screenshot for the expect output:__
<img width="1203" alt="Screen Shot 2022-05-22 at 10 19 07 PM" src="https://user-images.githubusercontent.com/103156151/169748769-0e5408a5-4849-4435-9846-702d152429cd.png">

__Screenshot for code in ``MarkdownParseTest.java``:__
<img width="834" alt="Screen Shot 2022-05-22 at 10 22 34 PM" src="https://user-images.githubusercontent.com/103156151/169748942-a10270ae-1222-4505-b4fd-3071b379606f.png">

__Screenshot for my implementation:__ The test did not pass.
<img width="904" alt="Screen Shot 2022-05-22 at 10 24 05 PM" src="https://user-images.githubusercontent.com/103156151/169749088-b1ae50af-a0b7-4fc6-87a3-f655cdaa7d8a.png">

__Sreenshot for the implementation I reviewed:__ The test did not pass.
<img width="950" alt="Screen Shot 2022-05-23 at 12 07 40 AM" src="https://user-images.githubusercontent.com/103156151/169763423-87c589a3-4fbc-49ba-b765-434eb131d92c.png">

__Code Change:__ I think there is a small code change that will make my program work for snippet 1 and all related cases that use inline code with backticks. We should ``break`` the while loop when there is a `` ` `` outside the ``[]`` for the link. Also, we should still consider and return the link when the `` ` `` is inside the ``[]`` for the link, and there is an extra ``]`` inside the ``[]`` for the link as well.


## 2. Snippet 2

__Screenshot for the expect output:__
<img width="1170" alt="Screen Shot 2022-05-22 at 10 35 39 PM" src="https://user-images.githubusercontent.com/103156151/169750517-41c08b5a-b36c-4691-ba89-fb548786a4e8.png">

__Screenshot for code in ``MarkdownParseTest.java``:__
<img width="808" alt="Screen Shot 2022-05-23 at 12 03 38 AM" src="https://user-images.githubusercontent.com/103156151/169762364-46948b8d-5e7e-4643-a36d-4963900ec7fe.png">

__Screenshot for my implementation:__ The test did not pass.
<img width="897" alt="Screen Shot 2022-05-23 at 12 05 37 AM" src="https://user-images.githubusercontent.com/103156151/169762659-0f0ca1b5-a585-4de3-85c4-571ac2da5c65.png">

__Sreenshot for the implementation I reviewed:__ The test did not pass.
<img width="857" alt="Screen Shot 2022-05-23 at 12 04 44 AM" src="https://user-images.githubusercontent.com/103156151/169763522-2c5059e5-bb01-41ca-bb60-ee361dfef44c.png">

__Code Change:__ I think there is a small code change that will make my program work for snippet 2 and all related cases that use inline code with backticks. We should still consider and return the link when the `` \ `` is inside the ``[]`` for the link, and there is an extra ``[]`` inside the ``[]`` for the link as well.


## 3. Snippet 3

__Screenshot for the expect output:__
<img width="1258" alt="Screen Shot 2022-05-22 at 10 44 05 PM" src="https://user-images.githubusercontent.com/103156151/169752353-52f43878-2e3b-4b11-b569-cb15397e6374.png">

__Screenshot for code in ``MarkdownParseTest.java``:__
<img width="1084" alt="Screen Shot 2022-05-23 at 12 25 42 AM" src="https://user-images.githubusercontent.com/103156151/169765979-148bcfe7-5ab0-4567-87fc-194b7d86b661.png">

__Screenshot for my implementation:__ The test did not pass.
<img width="910" alt="Screen Shot 2022-05-23 at 12 26 45 AM" src="https://user-images.githubusercontent.com/103156151/169766175-26e50823-47bc-4080-a302-3389a47cc5e4.png">

__Sreenshot for the implementation I reviewed:__ The test did not pass.
<img width="903" alt="Screen Shot 2022-05-23 at 12 23 27 AM" src="https://user-images.githubusercontent.com/103156151/169765723-eabb2bb4-4636-45b5-8a92-ac06d95a5add.png">

__Code Change:__ I think there is a small code change that will make my program work for snippet 3 and all related cases that use inline code with backticks. We should still consider and return the link when we press the ``return`` key on the keyborad after the ``[](`` and put the link on the next line, and then, press the ``return`` key on the keyborad after the link, and put ``)`` on the next line.
