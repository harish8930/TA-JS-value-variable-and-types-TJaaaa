
number = prompt("what is your age?")
if(number %2==0) {alert("number is even");}
else{alert("number is odd");}*/

num1 = prompt("enter the first number")
num2 = prompt("enter the second number")

 if(num1>num2) {alert("The maximum value is" +num1)}
 else if (num2>num1){alert("The maximum value is" +num2)}
 else {alert("The number is equal");}*/

 
 let num1 = prompt("Enter the first number")
 let num2 = prompt("Enter the second number")

 let max = (num1>num2) ? num1: num2;

 alert("The maximum value is" +max);

   Housename = prompt("Enter your Housename")

if(Housename = "stark" ) {alert("Winter is coming")}


  if (Housename ="lannister") {alert("A lannister always pay his debt")}
  
 else {alert("All men must die");}


let monthNumber = prompt("Type the number of the month")

if(monthNumber==1||monthNumber==3||monthNumber==5||monthNumber==7||monthNumber==8||monthNumber==10||monthNumber==12)
{alert("31 days")}
else if (monthNumber==4||monthNumber==6||monthNumber==9||monthNumber==11)
{alert("30days")}
else if (monthNumber==2)
{alert("28 or 29 days")}
else{alert("invalid input. please type the number between 1 to 12")}
