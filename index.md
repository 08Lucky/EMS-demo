```js
let name = "lucky";
```

```js
let Name = "harshita";
```

```js
let rahul = 1;
```

```js
let raj = 34;
```

```js
let add = 4 > 1;
```

```js
4 > 1;
```

```js
let top = null;
```

```js
let jump = null;
```

```js
let subs;
```

```js
let mixs;
```

```js
let a = "fgdfrvg" / 2;
```

```js
bb = "fgdfrvg" * 2;
```

```js
let object = {
  name: "Lucky",
  age: 19,
  lastName: "Singh",
};
```

```js
let ObJ = {
  education: "BE",
  yearOfPassing: 2023,
  college: "SIT",
};
```

```js
prompt("Please enter your name", "Lucky");
```

```js
confirm("Are you sure that you want t submit");
```

```js
alert("Do not switch the browser");
```

```js
9 + 8;
```

```js
a = prompt("enter the first value", 9);
b = prompt("enter the second value", 8);
Number(a) + Number(b);
```

```js
p = Number(prompt("enter the value", 8));
q = Number(prompt("enter the value", 8));
p + q;
```

```js
let value = 87;
let zero = "hell";
value + zero;
("87hell");
```

```js
9 - 8;
```

```js
pp = Number(prompt("enter the value", 8));
qq = Number(prompt("enter the value", 8));
pp + qq;
```

```js
2*3
```

```js
let first=34;
let second=4;
first*second;
```

```js
let first=34;
let second=4;
first/second;
```

```js
fiirst = Number(prompt("enter the value", 8));
secoond = Number(prompt("enter the value", 8));
fiirst/secoond;
```

```js
5%2;
```

```js
fine = Number(prompt("enter the value", 5));
dine = Number(prompt("enter the value", 7));
fine%dine;
```

```js
null==undefined;
```

```js
45=="45";
```

```js
null===undefined;
```

```js
45==="45";
```

```js
!true;
```

```js
!NaN;
```

```js
let a=2;
let b=2;
if(a=b) {
  console.log("equal")
}else{
   console.log("not equal")
}
```

```js
let per=prompt("enter the total percentage")
if(per>=75) {
  console.log("distinction")
}else if(per<75 && per>=55){
   console.log("first class")
}else {
    console.log("second class")
}
```

```js
let prepa=45;
prepa%2==0 ? "even" : prepa==0 ? "invalid" : "odd";
```

```js
let a=3;
let b=7;
a!=b ? "not equal" : 'equal';
```

```js
let name = "Hiee"
let fName = ""
let lName = "ME"
lName && fName && false && name || lName;
// output ME
```

```js
let name = ""
let fName = ""
let lName = "ME"
name || lName && false || lName && "Hello"
// output:- 'Hello'
```

```js
let name = ""
let fName = ""
let lName = "ME"
lName && fName || false || name && "Hello"
// output''
```

```js
let name = ""
let fName = " "
let lName = "ME"
lName && fName && name && "Hello"
// output:-''
```

```js
let name = ""
let fName = " "
let lName = "ME"
lName || fName || name || "Hello"
// output:- 'ME'
```
```js
// function declaration
function sub(n){
    return(n-1);
}
sub(7) //output 7
```

```js
// function expression
let sub=function(n){
    return(n-1)
}
sub(7) //output 7
```

```js
// arrow function without braces
const sub = (n) => n-1;
sub(7) //output 7
```

```js
// arrow function with braces
const sub=(n)=>{
    return(n-1);
}
sub(7) //output 7
```

```js
// function declaration
function mul(n){
    return(n*1)
}
mul(7) //output 7
```

```js
// function expression
let mul=function(n){
    return(n*1)
}
mul(7) //output 7
```

```js
// arrow function without braces
const mul=(n)=>n*1;
mul(7) //output 7
```

```js
// arrow function with braces
const mul=(n)=>{
    return(n*1);
}
mul(7) //output 7
```

```js
// function declaration
function div(n){
    return(n/1)
}
div(7) //output 7
```

```js
// function expression
let div=function(n){
    return(n/1)
}
div(7) //output 7
```

```js
// arrow function without braces
const div=(n)=>n/1;
div(7) //output 7
```

```js
// arrow function with braces
const div=(n)=>{
    return(n/1);
}
div(7) //output 7
```

```js
let score;
let maxPossibleScore =100;
function grades(score){
    if(score>=90 && score<=100){
    console.log("you have got A grade")
}else if(score>=80 && score<=89){
    console.log("you have got B grade")
}else if(score>=70 && score<=79){
    console.log("you have got C grade")
}else if(score>=60 && score<=69){
    console.log("you have got D grade")
}else if(score>=0 && score<=59){
    console.log("you have got F grade")
}else{
    console.log("Enter the score in the range of 0-100")
}
}
grades(58) // output you have got F grade
```

```js
function puppysAge(age, rate=7){
    let dogsAge = age*rate;
    console.log("Your Doggie is "+dogsAge +" years old in dog years!")
}
puppysAge(2) // output Your Doggie is 12 years old in dog years!
```