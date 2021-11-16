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

- Open the feedback page

- Right click and press inspect
- Open the console panel
- Enter the above given code
- Change the values as per your requirement
- And press Enter 
- After that all checboxes will be selected respective to the values you entered
- Then press Submit
- Khatam 😉


  
#### Note - This code will select all same checkboxes only. Means if you enter value 6 all strongly agree checkboxes will be selected at once.
