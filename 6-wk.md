### Term 1
### Week 6
---
1. ### Switch
   ```
   switch(){
       case 1:
       case 2:
       case 3:
            result = answer;
            break;
       case 3:
            return result;
            break;
    }
* In switch statement more than one case can be used.
* If we don't used the break after outputting the result, we have to use to `break` to get off the loop.

2. ### Single line - return with if else condition
    ```
    return i > 6 ? a + b : a - b; 
  * The above statement is read as:
    ```
    if ( i > 6){
        return a + b;
    } else {
        return a - b;
    }

3. ### Methods
* Splice
  ```
  1. Splice is used to `remove` or `remove and add` an element from an array.
  2. Syntax------`Array.splice(begin, deleteCount, add1, add2, ..)`
  3. or just 'Array.splice(begin, deleteCount)
  4. begin--it is from where deleting begins.
  5. deleteCount--it is count of how many elements to be deleted.
  6. add1, add2,..--number of elements to be added.

* Join
  ```
  1. Join is used to add elements of an array.
  2. Syntax-----`array.join(separator to be used to join)`
  3. array.join('+')--elements of array will be joined with +.

* IndexOf
  ```
  1. string.indexOf(searchValue [, fromIndex] ).
  2. indexOf will search for `searchValue` in the string or an array.
  3. if the `searchValue` is not there, it will return `-1`.

* Includes
  ```
  1. string.includes(searchString[, position]).
  2. it looks inside the string to see if the _searchString_ is there or not and returns a boolean value
  3.the position is where it will start the search.

* Math.pow(base, exponent)
  ```
  Math.pow(2,3)//8

4. ### For loops.
    ```
    for loops is generally used while indices are involved.

5. ### String interpolation.
* '`hello ${variables}, good to see you`'
* here in a regular string `${ }` can be used to add variable.

6. ### While-loop tips.
* as soon you write the while loop , write the variable increment too.
    ```
    while (n < 5){

        n++;
    }

