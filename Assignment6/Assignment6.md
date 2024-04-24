                         JavaScript
                         Assignment 6

## Q1.Write short notes on Array methods with code example?
### push()
### pop()
### shift()
### unshift()
### includes()
### toString()
### reverse()
### join()
### concat()
### flat()
### slice()
### splice()

## Ans. 

## push()-Adds an elememt at the end of an array

```js 
 let arr=[0,1,2,3,4,5]
 let newArr=arr.push("one")
 console.log(arr)
```

## pop()-Deletes the last element of the array

```js 
 let arr=[0,1,2,3,4,5,6]
 arr.pop()
 console.log(arr);
```

## shift()-Eleminates the first element of the array it modifies the orginal array

```js 
let arr=[1,2,3,4,5,6]
 console.log(arr.shift());
 console.log(arr);
```

## unshift()-Adds a new element at the first of an array

 ```js 
 let arr=[1,2,3,4,5,6]
 arr.unshift(0)
 console.log(arr);
 ```

## includes()- Checks the array contains the value

```js 
 let arr=[1,2,3,4,5]
 console.log(arr.includes(7));
 ```

## toString()- Converts a Array to string

```js
 let arr=[1,2,3,4,5,6]
 console.log(arr.toString());
 ```


## reverse()- Changing the position of each number of the given array to its opposite position from end   

```js
 let arr=[6,5,4,3,2,1]
 console.log(arr.reverse());
```



## join()-  takes all items in an iterable and joins them into one string

```js
 let arr=[1,2,3,4,6,8]
 console.log(arr.join("_"));
```

## concat()-  combines the text from multiple ranges and/or strings

```js  let arr=[1,2,3]
 let arr2=[4,5,3]
 let arr3=[84,85,44]
 console.log(arr.concat(arr2,arr3));
```

## flat()- Flattens the input array into a new array

```js
 let arr=[
 [1,2,3],[4,5,6], [7,8,9],[2,4,4], [13,14,[15,16]]]
 console.log(arr.flat(5));
 ```

## slice()- Returns selected elements in an array, as a new array

```js
 let arr=[5,4,6,5,8,4]
 let slicedArray=arr.slice(0,4)
 console.log(slicedArray);
 ```

## splice()- Used to add or remove elements of an existing array

```js
 let arr=[5,4,8,79,32,41]
 arr.splice("sreejith", 0, 5)
 console.log(arr);
 ```

 ### Q2.
 ![screenshot](./Screenshot(1).png)

### Q3. Write a JavaScript function to check whether an `input` is an array.
## Ans. 
 ```js
 let array=[1,2,3,4,5,6,]
 let isArr=(arr)=>{
    return Array.isArray(arr)
 }
 console.log(isArr(array))
 ```

### Q4. Write a JavaScript function that takes an array as an argument and returns the first element of the array.
## Ans
 ```js
 let arr=[1,2,3,4,5,6,7,8,9]
 let firstE=(array)=>{
   return array.shift()
 }
 let result=firstE(arr)
 console.log(result);
 ```

### Q5. Write a JavaScript function that takes an array as an argument and returns the last element of the array
## Ans
```js
let arr=[1,2,3,4,5,6,7,8,9]
 let firstE=(array)=>{
   return array.pop()
 }
 let result=firstE(arr)
 console.log(result);
 ```

### Q6. Write a simple JavaScript function to join all elements of the following array into a string.   sample array : myColor = ["Red", "Green", "White", "Black"];
## Ans 
 ```js
 let arr=["Red", "Green", "White", "Black"]
 let joinedElemets=(array)=>{
   return arr.join("")
 }
 let result=joinedElemets(arr)
 console.log(result);
 ```

### Q7. Write a JavaScript program that accepts a number as input and inserts dashes (-) between each. For example, if you accept 025468 the output should be 0-2-5-4-6-8
## Ans 
```js
let arr=[0,2,5,4,6,8]
let dashedArray=(array)=>{
  return arr.join("-")
}
let result=dashedArray(arr)
console.log(result);
```

### Q8. Write a JavaScript function that checks if the given number is even or odd then returns a Boolean value (use: arrow function, return keyword, ternary operator)
## Ans

```js
let isEven=(num)=>{
  return num%2===0? console.log("true"):console.log("false");
}
isEven(99)
```

### Q9. Create an array of guestlist. Write a javascript function that takes the user’s name as an argument and checks if it is there in the guestlist. If yes, return the string “Welcome” else, return “Sorry, good luck next time”.
## Ans 

```js

let checkGuestList = (name) =>{
    let guestList =["sreejith","arun","ajith","akash","eswar"]
    return guestList.includes(name)? console.log("welcome"):console.log("Sorry, good luck next time");
}
 checkGuestList("sreejith")
 // welcome
```

### Q10.Write a javascript function that reverses a given number example: 123456789 => 987654321 (split(), reverse (), join())
## Ans 
```js
let num = 123456789
let toReverse= (number) => {
    let outPut = String(number).split("").reverse().join("")
    return Number(outPut)

}
console.log(toReverse(num));
```

### Q11.Write a JavaScript function that accepts a string as a parameter and converts the first letter into upper case. Example: “Javascript” => “Javascript”
## Ans 
```js
let wrd = "javascript"
let firstLetter = wrd.slice(0,1)
let upperCaseLetter = firstLetter.toUpperCase();
let restOfTheLetters = wrd.slice(1,  wrd.length)
let lowerCaseLetters = restOfTheLetters.toLowerCase()
let nameToDisplay = upperCaseLetter+lowerCaseLetters
console.log(nameToDisplay);
 ```












 




