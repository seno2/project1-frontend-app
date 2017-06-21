# 第1回Webアプリ制作課題（テクノロジー・藤原）

5/17pushの練習

function hello(name) {
    return 'こんにちは、' +name + 'さん';
}
undefined
hello('藤原')
"こんにちは、藤原さん"
var myFunction = hello;
undefined
myFunction
function hello(name) {
    return 'こんにちは、' +name + 'さん';
}
myFunction('藤原')
"こんにちは、藤原さん"
function double(x) {
return x * 2; // 因数を2倍にして返す関数
}
undefined
double(1)
2
double(2)
4
var numbers = [1,2,3,4,5
               ]
undefined

function foo() {
return "hello";
}
undefined
numbers. map(double)
(5) [2, 4, 6, 8, 10]
var a = function() {
return "hello";
}

undefined
var a = () => {
   return "hello";
}
undefined
var numbers = [1,2,3,4,5];
undefined
numbers.map(function(x) {
    return 2 * x;
})
(5) [2, 4, 6, 8, 10]
//アロー関数式　(正式)
numbers.map((x) => {
return 2 * x ;
})
(5) [2, 4, 6, 8, 10]
function f(n) {
if (n <= 0) {
  return 1;
}
return n * f(n-1);
}
undefined
f(3)  // 3*2*1
6
f(5) //5*4*3*2*1
120
f(1)
1
function newCounter() {
var count = 1;
return () => 1;
}
undefined
function newCounter() {
var count = 1;
return () => count++;
}
undefined
var counter1 = newCounter();
undefined
var counter2 = newCounter();
undefined
counter1()
1
counter1()
2
counter2()
1
counter2()
2
counter2()
3
counter1()
3
counter1()
4
window.alert === alert;
true
window.innerwidth === innerwidth;
VM2726:1 Uncaught ReferenceError: innerwidth is not defined
    at <anonymous>:1:23
(anonymous) @ VM2726:1
window.innerWidth === innerWidth;
true
samplevalue = 5;
5
window.sampleValue;
undefined
window.samplevalue;
5

誤字・脱字が多かった

function sum() {
 var total = 0;
for (var counter =1; counter <= 10; counter++) {
total += counter;
}
window.alert(total);
}
undefined
sum();
undefined
function sum(rangeTo) {
 var total =0;
for (var counter = 1; counter <= rangeTo; counter++) {
total += counter;
}                                                     }
window.alert(total);

VM436:6 Uncaught ReferenceError: total is not defined
    at <anonymous>:6:14
(anonymous) @ VM436:6
function sum(rangeTo) {
 var total =0;
for (var counter = 1; counter <= rangeTo; counter++) {
total += counter;
}                                                     
window.alert(total);
}   
undefined
sum();
undefined
function sum(rangeFrom, rangeTo) {
var total = 0;
for (var counter =rangeFrom; counter <= rangeTo; counter++) {
total += counter;
}
window.alert(total);
}
undefined
sum(1,10);
undefined
