# Fix the code to get the largest of three
```
aa = (f,s,t) => {
    if(f>s &&f>t){
    console.log(f)}
    else if(s>f && s>t){
    console.log(s)}
    else{
    console.log(t)}
   }
   aa(1,2,3);
```
# Fix the code to Sum of the digits present in the number
```
let n = 123;
console.log(add(n));
function add(n)
{
let sum = 0;
let m=n.toString().split('');
for(var i=0;i<m.length;i++){
 sum+= parseInt(m[i]);
 }
 return sum;
}
```
# Fix the code to Sum of all numbers using IIFE function
```
const arr = [9,8,5,6,4,3,2,1];
(function() {
 let sum = 0;
 for (var i = 0; i < arr.length; i++){
    sum += arr[i];
 }
 console.log(sum);
})(arr);
```
# Fix the code to gen Title caps
```
var arro = ['guvi', 'geek', 'zen', 'fullstack'];
var ano = function(arro) {
 for (var i = 0; i < arro.length; i++) {
 console.log(arro[i][0].toUpperCase() + arro[i].substr(1));
 }
}
ano(arro);
```
# Fix the code to return the Prime numbers
```
const newArray=[1,3,2,5,10];
const myPrime=newArray.filter(num=>{
 for(let i=2;i<=num;i++){
    if(num<=2) return true;    
    if(num%i!==0) {
        return true;
    } else return false;
 }
return num===1;
});
console.log(myPrime);
```
# Fix the code to sum the number in that array
```
const num = [10, 20, 30, 40,50,60,70,80,90,100] 
const sum = (a, b) =>a + b;
const sumNum = num.reduce(sum)
console.log(sumNum);
```
# Fix the code to rotate an array by k times and return rotated array using IIFE function
```
var arr = [1, 2, 3, 6, 8, 6, 1, 9, 10, 12, 13];
var k = 3;
(function() {
 out = arr.slice(k + 1, arr.length);
 var count = out.length;
 for (var i = 0; i < k + 1; i++) {
 out[count] = arr[i];
 count += 1;
 }
 console.log(out);
})(arr);
```
# Fix the code to gen Title caps
```
var arr = ['guvi', 'geek', 'zen', 'fullstack'];
(function() {
 for (var i = 0; i < arr.length; i++) {
 console.log(arr[i][0].toUpperCase() + arr[i].slice(1));
 }
})(arr);
```
# print all odd numbers in an array using IIFE function
```
var arr = [1, 2, 3, 5, 7, 79, 7, 2, 6, 9, 4];
(function() {
 for (var i = 0; i < arr.length; i++) {
 if (arr[i] % 2 !== 0) {
    console.log(arr[i]);
 }}
})();
```
# Fix the code to reverse
```
(function(str){
    str1 = str.split('').reverse().join('');
    console.log(str1); 
   })('abcd')
```
# Fix the code to remove duplicates
```
var res = function(arr){
    const newArr = [];
    for(var i=0; i < arr.length; i++){
        if(!(newArr.includes(arr[i]))) {
            newArr.push(arr[i]);
        } 
    }
    console.log(newArr);
   }
   res(['guvi','geek','guvi','duplicate','geek']);
```
# Fix the code to give the below output: Expected Output:[{firstName: “Vasanth”, lastName: “Raja”, age: 24, role: “JSWizard”},
{firstName: “Sri”, lastName: “Devi”, age: 28, role: “Coder”}]
```
var array =[[['firstname','vasanth'],['lastname','Raja'],['age',24],['role','JSWizard']],[['firstname','Sri'],['lastname','Devi'],['age',28],['role', 'Coder']]];
var final=[];
let new_object={};
while(array.length!=0)
{
 var outer_remove = array.shift();
 while(outer_remove.length!=0)
 {
 var inner_remove = outer_remove.shift()
 var key = inner_remove[0];
 var value =inner_remove[1];
 new_object[key]=value;
 }
 final.push(new_object);
 new_object={};
}
console.log(final);
```
# Fix the code to give the below output: Sum of odd numbers in an array
```
var as=[12,34,5,6,2,56,6,2,1];
var sum=0;
var s=as.reduce(function(a,c){
 if(c%2!=0) return sum+=c;
});
console.log(s);
```
# Fix the code to give the below output: Swap the odd and even digits
```
aa = data=>{
    var a=data;
    var l='';
   for(i=0;i<a.length-1;i++){
    var s=a[i+1];
    var b=a[i];
    l+=s;
    l+=b;
    i=i+1;
   }
   if((a.length%2)!=0){
    l+=a[a.length-1];
   }
   console.log(l);
   }
   aa('1234');
   ```
