# Find the culprit
```
<!DOCTYPE html>
<html>
<body>
 <script>
 alert( "I’m JavaScript!");
 </script>
 Whats the error in this ?
</body>
</html>
```

# Find the culprit and invoke the alert
```
<!DOCTYPE html>
<html>
<body>
 <script src="script.js"></script>
</body>
</html>
alert("I’m invoked!");
```

#Explain the below how it works
```
alert("I'm JavaScript!");
alert('Hello') // this line is not having semicolon
alert(`Wor
 ld`)
alert(3 +
1
+ 2); // this is multiple line code and its working
```

Explanantion: As Javascript it interpreted adds or forgives if semi colon is not added and exceutes the code

# Fix the below to alert Guvi geek
```
let admin=9, fname=10.5; 
fname = "Guvi";
lname = "geek"
admin = `${fname} ${lname}`;
alert( admin ); // "Guvi geek"
```

# Fix the below to alert hello Guvi geek
```
let fname=10.5; 
fname = "Guvi";
lname = "geek"
let name = `${fname} ${lname}`;
alert( `hello ${name}` );
```

# Fix the below to alert sum of two numbers
```
let a = 6;
let b = 10;
alert(a + b);
```

# If you run the below scritpt you will get “Code is Blasted”
```
Explain Why the Code is blasted and how to diffuse it and get “Diffused”.
var a = 2 > 12;
//Don't touch below this
if (a) {
  console.log("Code is Blasted")
}
else
{
  console.log("Diffused") 
}
```
Explanation : Code is blasted because it is compared as string literals

# How to get the success in console.
```
let a = prompt("Enter a number?");
//Don't modify any code below this
if (a) {
 console.log( 'OMG it works for any number inc 0' );
}
else
{
 console.log( "Success" );
}
```

Answer : If there is no input in the prompt, console success will be printed because a will be true if any input is provided.

# How to get the correct score in console.
```
let value = prompt('How many runs you scored in this ball');
if (value == 4) {
      console.log("You hit a Four");
} else if (value == 6) {
      console.log("You hit a Six");
} else {
       console.log("I couldn't figure out");
}
```

Answer : From the prompt the value is in string === compares the value and the data type so changing it to == or parsing the string into int 

# Fix the code to welcome the Employee
```
let login = 'Employee';
let message = (login === 'Employee') ? 'Welcome employee'  :(login == '') ? 'No login' :'';
console.log(message);
```

#Fix the code to welcome the boss
```
let message;
if (message===undefined)
{
 message = "welcome boss";
}
else
{
 message = "Go away";
}
console.log(message);
```

# Fix the code to welcome the boss
```
let message;
let lock = false;
//Dont change any code below this 
if (null || lock || undefined )
{
  message = "Go away";
}
else
{
 message = "welcome";
}
console.log(message);
```

# Fix the code to welcome the boss
```
let message;
let lock = false;
//Dont change any code below this
if (lock && " " || undefined )
{
  message = "Go away";
}
else
{
 message = "welcome";
}
console.log(message);
```

# Change the code to print 321
```
//You can change only 2 characters
let i = 3;
while (i) {
  console.log( i-- );
}
```

# Change the code to print 1 to 10 in 4 lines
```
for(let i=1;i<=10;i++){
    console.log(i);
}
```
                       
# Change the code to print even numbers
```
for (let num = 2; num <= 20; num += 2) {
    console.log(num)
  }
```

# Change the code to print all the gifts
```
let gifts = ["teddy bear", "drone", "doll"];
for (let i = 0; i < gifts.length; i++) {
  console.log(`Wrapped ${gifts[i]} and added a bow!`);
}
```
                                 
# Fix the code to disarm the bomb.
```
let countdown = -1;
while (countdown > 0) {
  countdown--;
  if(countdown == 0)
  {
   console.log("bomb triggered");
  }
}
```

# Whats the msg printed and why?
  hi is printed because string literals if present are considered as truthy and if in integer or number 0 is present it is considered as falsy so only hi is printed.                                                                  
