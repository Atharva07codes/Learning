# Learning
It is the 1 st day of learning git and github . I am new to this vcs.
https://www.perplexity.ai/search/go-throgh-js-mdn-docs-and-expl-UJSg9a_.S2qdwbztl6sdwg
// // function declartion
// // hoisting
// add(5, 3);
// function add(a, b) {
//   let c = a + b;
//   console.log(c);
// }

// //named function expression
// const a = function greet(name) {
//   console.log("Hello " + name);
//   // return "Hello" + name;
// };
// a("Atharva");

// //anonymous function
// const greet = function (name) {
//   console.log("Good Morning:" + name);
// };
// greet("Pawan");

// //function expression they can be name or anonymous
// const exp = function (a, b) {
//   console.log(a + b);
// };
// exp(4, 2);
// //arrow with no return and no {}
// const arrow = (a, b) => a + b;
// console.log(arrow(3, 2));
// //arrow with no return and no{} without ()
// const arrow1 = (a) => a * 4;
// console.log(arrow1(3));
// //arrow with no parameter no return and no{} withou ()
// const arrow2 = (_) => console.log("hello");
// arrow2();
// //another way arrow with no parameter no return and no{} without ()
// const arrow3 = ($) => console.log("bye");
// arrow3();

// const arrow4 = (name1) => {
//   name1 = "Atharva";
//   console.log("Hello" + name1);
// };
// arrow4();
// // higher order function
// // callback function
// function greetUser(name) {
//   console.log("hello Mr." + name);
// }
// //higher order funct
// function user(caller) {
//   const name = "Pawan";
//   caller(name);
// }
// // debugger;
// document.getElementById("higher").addEventListener("click", function () {
//   user(greetUser);
// });
// user(greetUser);

// array literal
// let arr = [1, 2, 3, 4, 5, 6, 6, 4, 5];
// console.log(arr);
// //array constructor new keyword
// let arr1 = new Array(1, 3, 32, 56575, 75);
// // let arr22=new Array(5);
// console.log(arr1);
// //array using of()
// let arr2 = Array.of("helo", "bye");
// console.log(arr2);
// //array using from()
// let arr3 = Array.from("Hello" + "Ram" + "Good" + "Afternoon");
// console.log(arr3);

//push()
// //Appends new elements to the end of an array, and returns the new length of the array
// let array = Array.of(22, 45, 453, 232, 1, 23, 542, 42, 522, 32);
// console.log("Before Adding: " + array);
// array.push(111);
// console.log("After Adding: " + array);

// pop()
////Removes the last element from an array and returns it. If the array is empty, undefined is returned and the array is not modified.
// let array = Array.of(22, 45, 453, 232, 1, 23, 542, 42, 522, 32);
// console.log("Before pop: " + array);
// array.pop();
// console.log("After Pop: " + array);

//reverse()
////Reverses the elements in an array in place. This method mutates the array and returns a reference to the same array.
// let array = Array.of(22, 45, 453, 232, 1, 23, 542, 42, 522, 32);
// console.log("Before Reverse:" + array);
// array.reverse();
// console.log("After Reversed: " + array);

//shift()
////Removes the first element from an array and returns it. If the array is empty, undefined is returned and the array is not modified.
// let array = Array.of(22, 45, 453, 232, 1, 23, 542, 42, 522, 32);
// console.log("Before Shift: " + array);
// array.shift();
// console.log("After Shift: " + array);

// unshift()
////Inserts new elements at the start of an array, and returns the new length of the array.
// let array = Array.of(22, 45, 453, 232, 1, 23, 542, 42, 522, 32);
// console.log("Before Unshift: " + array);
// array.unshift(34, 44, 1111111);
// console.log("After Unshift: " + array);

//sort()
////Sorts an array in place. This method mutates the array and returns a reference to the same array.
//// @param compareFn
//// Function used to determine the order of the elements. It is expected to return a negative value if the first argument is less than the second argument, zero if they're equal, and a positive value otherwise. If omitted, the elements are sorted in ascending, UTF-16 code unit order.
// let array = Array.of(22, 45, 453, 232, 1, 23, 542, 42, 522, 32);
// console.log("Before Sort: " + array);
// array.sort();
// console.log("After Sort:" + array);

//fill()
////Changes all array elements from start to end index to a static value and returns the modified array
// let array = Array.of(22, 45, 453, 232, 1, 23, 542, 42, 522, 32);
// console.log("Before Fill: " + array);
// array.fill(7,2,6);
// console.log(array);

//slice()
////The beginning index of the specified portion of the array. If start is undefined, then the slice begins at index 0.
////Returns a copy of a section of an array. For both start and end, a negative index can be used to indicate an offset from the end of the array. For example, -2 refers to the second to last element of the array.
// let array = Array.of(22, 45, 453, 232, 1, 23, 542, 42, 522, 32);
// console.log("Before Slice: " + array);
// let slice = array.slice(2, 6);
// console.log("Sliced Array: " + slice);
// console.log("After Slice: " + array);

//splice()
////Removes elements from an array and, if necessary, inserts new elements in their place, returning the deleted elements.
// let array = Array.of(22, 45, 453, 232, 1, 23, 542, 42, 522, 32);
// console.log("Before Splice: " + array);
// array.splice(2, 3);
// console.log("After Splice: " + array);

//copyWithin()
////If target is negative, it is treated as length+target where length is the length of the array.
//// Returns the this object after copying a section of the array identified by start and end to the same array starting at position target
// let array = Array.of(22, 45, 453, 232, 1, 23, 542, 42, 522, 32);
// console.log("Before CopyWithIn: " + array);
// array.copyWithin(1, 2, 9);
// console.log("After CopyWithIn: " + array);

//concat()
////Combines two or more arrays. This method returns a new array without modifying any existing arrays.
// let a = Array.of(1, 2, 3);
// let b = Array.of(4, 5, 6);
// let c = a.concat(b);
// console.log("a[] +b[] =" + c);

//- indexing
// const animals = ["ant", "bison", "camel", "duck", "elephant"];
// console.log(animals);
// console.log(animals.slice(2, -1));

//map() Calls a defined callback function on each element of an array, and returns an array that contains the results.
let map = Array.of(1, 2, 3, 4, 5, 6, 7, 8, 9, 10);
const explain = map.map((x) => x * 4);
console.log(explain);

//filter() Returns the elements of an array that meet the condition specified in a callback function.
// debugger;
let filter = Array.of(1, 2, 3, 4, 5, 6, 7, 8, 9, 10);
const ex = filter.filter((x) => x % 2 === 0);
console.log("Even Nos:" + ex);

//
let reduce = Array.of(1, 2, 3, 4, 5, 6, 7, 8, 9, 10);
const etc = reduce.reduce((x, y) => x + y);
console.log(etc);

