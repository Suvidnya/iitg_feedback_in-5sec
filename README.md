## Fill your feedback form in 5 sec. (Only for IITG Students)

Edit the code (value) as per your requirement.


 ##

| Value             | no.                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Strongly agree | 6 |
| Agree| 5 |
| ....| ...|
|Strongly disagree | 1|




#### Run this code in console of the feedback page



```bash
  var btns = document.querySelectorAll('input[type="radio"]')
  for(var i=0;i<btns.length;i++){
  if(btns[i].value=="6")
    btns[i].checked=true;
 }

```

  
## How to do - STEPS

- Open the feedback page![s1](https://user-images.githubusercontent.com/78336837/141948246-ce03249f-f5c0-4437-bde6-a47f65fbabd8.png)


- Right click and press inspect![s2](https://user-images.githubusercontent.com/78336837/141948266-96648948-ec09-4805-9dbc-a0273410c1bf.png)

- Open the console panel![s3](https://user-images.githubusercontent.com/78336837/141948281-94a97fae-05a7-4000-87a4-54f457f63631.png)

- Enter the above given code![s4](https://user-images.githubusercontent.com/78336837/141948299-64dcd204-d948-4e4b-87f2-fa4c5ab4c1a8.png)

- Change the values as per your requirement![s5](https://user-images.githubusercontent.com/78336837/141948316-88ef1bee-cdb7-460f-89df-ea91f77f0a3a.png)

- And press Enter 
- After that all checboxes will be selected respective to the values you entered![s6](https://user-images.githubusercontent.com/78336837/141948341-2a3b4b1b-3da2-4cf7-8a5f-1914fefc0861.png)

- Then press Submit
- Khatam 😉


  
#### Note - This code will select all same checkboxes only. Means if you enter value 6 all strongly agree checkboxes will be selected at once.
