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

//array literal
// let arr = [1, 2, 3, 4, 5, 6, 6, 4, 5];
// console.log(arr);
// //array constructor new keyword
// let arr1 = new Array(1, 3, 32, 56575, 75);
// console.log(arr1);
// //array using of()
// let arr2 = Array.of("helo", "bye");
// console.log(arr2);
// //array using from()
// let arr3 = Array.from("Hello");
// console.log(arr3);

let array = Array.of(22, 45, 453, 232, 1, 23, 542, 42, 522, 32);
console.log(array);
array.push(111);
