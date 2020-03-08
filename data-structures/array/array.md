 # Array (JavaScript)

Array is consecutive data structure
also traditionally an array is a consecutive segment of memory


![locker](array.img.locker.jpg)
> Image by <a href="https://pixabay.com/users/laterjay-1627906/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1037935">LaterJay Photography</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1037935">Pixabay</a>

locker is good example for explain array structure.
in here each element is locker. and consecutive lockers is in other words consecutive data

we can describe lockers something like this
```
Array<locker> lockers = [locker1, locker2, locker3]
```
 
 
 <br>
 <br>
 
 ## Number(integer) type array
 ```
 const integerArray = [1, 3, 5]
 
 console.log(integerArray[0]);
 // return 1
 
structure 
Index  | values 
0   |   [1]
1   |   [3]
2   |   [5]
 ```

#### why index start from 0(zero)?
> when we counting something we starting from 1 but why 0?
>
that's good question.  
imagine counting apples. 1, 2, 3 right?  
now imagine you measuring something use measure probably you string from 0.  
index is pointing start point. make sense?

wanna know more? 
* [zero-based numbering](https://en.wikipedia.org/wiki/Zero-based_numbering)
 
 <br>
 
 ## String type array
 ```  
 const stringArray = ['apple', 'banana', 'mango'];
 
 console.log(stringArray[0]);
 // return 'apple'
 
 Index   0      1       2
 values  [apple][banana][mango]
 ```
 
 <br>
 
 actually the example of above is kind of `Static Type language` style
 in JavaScript(JS) every element is reference.
 that means you can put any kind of things beyond data type.
 welcome to `Dynamic type language` world!
 
 here is a example
 
 ```
 const numberElement = 1;
 const stringElement = 'testString';
 const combinationArray = [numberElement, stringElement, 'mango'];
 
 console.log(combinationArray);
 // [ 1, 'testString', 'mango' ]
 ```
 
 <br>
 <br>
 
 # summary
 
 * array can initialize with any type of value or reference
 * array element reference real value
 
 <br>
 <br>
 
 # references (for deep dive)
 
 * [js-array.h](https://github.com/v8/v8/blob/master/src/objects/js-array.h)
 * [js-array.tq](https://github.com/v8/v8/blob/master/src/objects/js-array.tq)
 
