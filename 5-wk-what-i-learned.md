#### Term 1
#### Week 5
---
* **Different conditional types.**
1. If - if else - else.
   ````
   if (condition){ 
       result;
   }else if (condition){
       result;
   }
   ````

2. Nest if - if else -else.<br>
   ```
   if (condition){
    if (condition){
       result;
       }
    result
   } else if (condition){
       result;
   } else {
       result;
   }
   ````

3. Switch.
   ````
   Switch(parameter){
    case parameter:
      condition;
      result;
      break;
    case parameter:
      condition;
      result ;
      break;
   }
   ````
   * This can't be used to compare with `>` or `<`.
   * This can only be used when `===` is used is condition.


4. By using a variable.
    ````
    const answer = '';

    if (!condition){  //if false  
        answer = ''; //or
        
    }
    if (condition){
        answer = '';
    }

    console.log('the result is '+ answer);
    
    //  If / if-else condition can also be solved this way.
    ````


---




* **Linking front-end javascript page with the back-end page.**<br>
Linking front-end to the back-end is how information can be passed to the back, get it processed and get back the refined result at the front end.

* To link the front-end and back-end:

>1. In the front-end page, in the beginning:
   * `const functionName = require('./path to back-end page');`<br>
   *  This is how request is made to the back-end to get the outcome of the back-end. 
>2. In the back-end page, in the end:
   * `module.exports = functionName;`
   * Back-end does all the calculation and then passes the value requested by the front-end.

---
* 
  
