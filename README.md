## Fill your feedback form ASAP. (Only for IITG Students)- 2021

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
  var but = document.querySelectorAll('input[type="radio"]')
  for(var i=0;i<but.length;i++){
  if(but[i].value=="6")
    but[i].checked=true;
 }

```

  
## How to do - STEPS

- Open the feedback page![s1](https://user-images.githubusercontent.com/78336837/141949795-e6db1264-d055-4260-8f3d-53da2ada5f8b.png)


- Right click and press inspect![s2](https://user-images.githubusercontent.com/78336837/141949932-cb52b702-1596-4c99-865e-b7ce94dcd3ba.png)


- Open the console panel![s4](https://user-images.githubusercontent.com/78336837/141950018-2995773c-302e-402c-9e67-935d459a0ff5.png)


- Enter the above given code


- Change the value as per your requirement

- And press Enter ![ss5](https://user-images.githubusercontent.com/78336837/141950083-10ff1577-50c3-48b6-a215-633f5f945c42.png)
- After that all checboxes will be selected respective to the values you entered ![s6](https://user-images.githubusercontent.com/78336837/141950177-9fb29872-d73d-477a-aa99-938e4b05d50f.png)

- Then press Submit

- Khatam 😉


  
#### Note - This code will select all same checkboxes only. Means if you enter value 6 all strongly agree checkboxes will be selected at once.
