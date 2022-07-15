# Assignment-05-js-solved

 console.log("\n\n1. Write a js program to print day of week name using switch case.?");

console.log("====OUTPUT_Q_NO_1====\n\n");

var day="thu";

switch (day) {

    case 'sun':

        console.log("today is sunday");

        break;

    case 'mon':

        console.log("today is monday");

        break;

    case 'tue':

        console.log("today is tuesday");

        break;

    case 'wed':

        console.log("today is wednesday")

        break;

    case 'thu':

        console.log("today is thursday");

        break;

    case 'sun':

        console.log("today is friday");

        break;

    case 'sat':

        console.log("today is saturday");

        break;

    default:

        console.log("you entered wrong name of day");

        break;

}



console.log("\n\n2. Write a js program to print total number of days in a month using switch case.?");

console.log("====OUTPUT_Q_NO_2====\n\n");

var month="feb";

switch (month) {

    case 'jan':

        console.log("january contain 31 days");

        break;

    case 'feb':

        console.log("february contain 28 days in formal_year and 29 days in leap_year");

        break;

    case 'mar':

        console.log("march contain 31 days");

        break;

    case 'apr':

        console.log("aprile contain 30 days");

        break;

    case 'may':

        console.log("may contain 31 days");

        break;

    case 'jun':

        console.log("june contain 30 days");

        break;

    case 'jul':

        console.log("july contain 31 days");

        break;

    case 'aug':

        console.log("august contain 31 days");

        break;

    case 'sep':

        console.log("september contain 30 days");

        break;

    case 'oct':

        console.log("october contain 31 days");

        break;

    case 'nov':

        console.log("november contain 30 days");

        break;

    case 'dec':

        console.log("december contain 31 days");

        break;

    default:

        console.log("Enter correct name of month");

        break;

}



console.log("\n\n3. Write a js program to check whether an alphabet is vowel or consonant using switch case.?");

console.log("====OUTPUT_Q_NO_3====\n\n");

var alphabet='d';

switch (alphabet) {

    case 'a':

        console.log("alphabet ",alphabet,"is vowel");

        break;

    case 'e':

        console.log("alphabet ",alphabet,"is vowel");

        break;

    case 'i':

        console.log("alphabet ",alphabet,"is vowel");

        break;

    case 'o':

        console.log("alphabet ",alphabet,"is vowel");

        break;

   case 'u':

        console.log("alphabet ",alphabet,"is vowel");

        break;

    case 'A':

        console.log("alphabet ",alphabet,"is vowel");

        break;

    case 'E':

        console.log("alphabet ",alphabet,"is vowel");

        break;

    case 'I':

        console.log("alphabet ",alphabet,"is vowel");

        break;

    case 'O':

        console.log("alphabet ",alphabet,"is vowel");

        break;

    case 'U':

        console.log("alphabet ",alphabet,"is vowel");

        break;   

                   

    default:

        console.log("alphabet ",alphabet,"is consonant");

        break;

}



console.log("\n\n4. Write a js program to find maximum between two numbers using switch case.?");

console.log("====OUTPUT_Q_NO_4====\n\n");

var num1=20,num2=10;

switch (num2>num1)

{

    case true:

        console.log("The greater number between ",num1," and ",num2," is ",num2);

        break;

    case false:

        console.log("The greater number between ",num1," and ",num2," is ",num1);

        break;

    default:

        break;

}



console.log("\n\n5. Write a js program to check whether a number is even or odd using switch case.?");

console.log("====OUTPUT_Q_NO_5====\n\n");

var numbar=90;

switch (numbar%2)

{

    case 0:

        console.log(numbar," is even");

        break;

    case 1:

        console.log(numbar," is odd");

        break;

    default:

        break;

}



console.log("\n\n6. Write a js program to check whether a number is positive, negative or zero using switch case.?");

console.log("====OUTPUT_Q_NO_6====\n\n");

var num=-50;

switch (num>=0) {

    case true:

        console.log(num," is positive.");

        break;

    case false:

        console.log(num," is negative.");

        break;

    default:

        break;

}



console.log("\n\n7. Write a js program to find roots of a quadratic equation using switch case.?");

console.log("====OUTPUT_Q_NO_7====\n\n");

var a=3,b=1,c=-2,x,y;

x=(-b+Math.sqrt(b*b-4*a*c))/(2*a);

y=(-b-Math.sqrt(b*b-4*a*c))/(2*a);

console.log("a=",a,"b=",b,"c=",c);

console.log("Roots of quadratic equations are ",x," and ",y);

console.log("\n\n8. Write a js program to create Simple Calculator using switch case.?");

console.log("====OUTPUT_Q_NO_8====\n\n");

var x=25,y=5,op='%';

console.log("x=",x,"y=",y);

switch (op) {

    case '+':

        console.log("x",op,"y=",x+y);

        break;

    case '-':

        console.log("x",op,"y=",x-y);

         break;

    case '*':

        console.log("x",op,"y=",x*y);

        break;

    case '/':

        console.log("x",op,"y=",x/y);

        break;

    case '%':

        console.log("x",op,"y=",x%y);

        break;



    default:

        console.log("enter correct arithmatic operator");

        break;

}



console.log("\n\n9. Write a js program to input any character and check whether it is alphabet, digit or special character.?");

console.log("====OUTPUT_Q_NO_9====\n\n");

var character=prompt("enter any character:");

console.log(character);

if (character==='a'||character==='b'||character==='c'||character==='d'||character==='e'||character==='f'||character==='g'||character==='h'||character==='i'||character==='j'||character==='k'||character==='l'||character==='m'||character==='n'||character==='o'||character==='p'||character==='q'||character==='r'||character==='s'||character==='t'||character==='u'||character==='v'||character==='w'||character==='x'||character==='y'||character==='z'||character==='A'||character==='B'||character==='C'||character==='D'||character==='E'||character==='F'||character==='G'||character==='H'||character==='I'||character==='J'||character==='K'||character==='L'||character==='M'||character==='N'||character==='O'||character==='P'||character==='Q'||character==='R'||character==='S'||character==='T'||character==='U'||character==='V'||character==='W'||character==='X'||character==='Y'||character==='Z') {

    console.log(character," is an Alphabet");

}else if (character==='1'||character==='2'||character==='3'||character==='4'||character==='5'||character==='6'||character==='7'||character==='8'||character==='9') {

    console.log(character," is a digit");

} else {

    console.log(character," is a special character");

}

console.log("\n\n10. Write a js program to check whether a character is uppercase or lowercase alphabet.?");

console.log("====OUTPUT_Q_NO_10====\n\n");

var character;

character=prompt("enter any alphabet character");

if (character==='a'||character==='b'||character==='c'||character==='d'||character==='e'||character==='f'||character==='g'||character==='h'||character==='i'||character==='j'||character==='k'||character==='l'||character==='m'||character==='n'||character==='o'||character==='p'||character==='q'||character==='r'||character==='s'||character==='t'||character==='u'||character==='v'||character==='w'||character==='x'||character==='y'||character==='z') {

    console.log(character," is lower case.");

} else if (character==='A'||character==='B'||character==='C'||character==='D'||character==='E'||character==='F'||character==='G'||character==='H'||character==='I'||character==='J'||character==='K'||character==='L'||character==='M'||character==='N'||character==='O'||character==='P'||character==='Q'||character==='R'||character==='S'||character==='T'||character==='U'||character==='V'||character==='W'||character==='X'||character==='Y'||character==='Z') {

    console.log(character," is upper case.");

} else {

    console.log("wrong input!");

}



console.log("\n\n11. Write a js program to input week number and print week day?");

console.log("====OUTPUT_Q_NO_11====\n\n");

var dayNo=prompt("enter any day number");

console.log(dayNo);

switch (dayNo) {

    case '1':

        console.log("today is monday");

        break;

    case '2':

        console.log("today is tuesday");

        break;

    case '3':

        console.log("today is wednesday");

        break;

        

    case '4':

        console.log("today is thursday");

        break;

    case '5':

        console.log("today is friday");

        break;

    case '6':

        console.log("today is saturday");

        break;

    case '7':

        console.log("today is sunday");

        break;



    default:

        console.log("invalid input!");

        break;

}



console.log("\n\n12. Write a js program to input month number and print number of days in that month.?");

console.log("====OUTPUT_Q_NO_12====\n\n");

var monthNo=prompt("enter any month number");

console.log(monthNo);

switch (monthNo) {

    case '1':

        console.log("january contain 31 days");

        break;

    case '2':

        console.log("february contain 28 days in formal year and 29 days in leap year");

        break;

    case '3':

        console.log("march contain 31 days");

        break;

        

    case '4':

        console.log("aprile contain 30 days");

        break;

    case '5':

        console.log("may contain 31 days");

        break;

    case '6':

        console.log("june contain 30 days");

        break;

    case '7':

        console.log("july contain 31 days");

        break;

    case '8':

        console.log("august contain 31 days");

        break;

    case '9':

        console.log("september contain 30 days");

        break;

    case '10':

        console.log("october contain 31 days");

        break;

    case '11':

        console.log("november contain 30 days");

        break;

    case '12':

        console.log("december contain 31 days");

        break;



    default:

        console.log("invalid input!");

        break;

}

console.log("\n\n13. Write a js program to count total number of notes in given amount.?");

console.log("====OUTPUT_Q_NO_13====\n\n");

var notes=prompt("how many notes you want to buy"),pricePerNotes=prompt("enter price per notes"),totalPrice=pricePerNotes*notes;

console.log("total notes=",notes);

console.log("pricePerNotes=",notes,"rupees");

console.log("totalPrice is ",totalPrice);



console.log("\n\n14. Write a js program to input angles of a triangle and check whether triangle is valid or not.?");

console.log("====OUTPUT_Q_NO_14====\n\n");

var angle1=prompt("enter First angle"),angle2=prompt("enter Second angle"),angle3=prompt("enter Third angle"),sum;

angle1=parseInt(angle1);

angle2=parseInt(angle2);

angle3=parseInt(angle3);

console.log("angle1=",angle1);

console.log("angle2=",angle2);

console.log("angle3=",angle3);

sum=angle1+angle2+angle3;

console.log("sum=",sum);

if (sum==180) {

    console.log("Triangle is valid!");

} else {

    console.log("Triangle is invalid!");

}



console.log("\n\n15. Write a js program to input all sides of a triangle and check whether triangle is valid or not.?");

console.log("====OUTPUT_Q_NO_15====\n\n");

var a=prompt("enter First side"),b=prompt("enter Second side"),c=prompt("enter Third side");

a=parseInt(a);

b=parseInt(b);

c=parseInt(c);

console.log("a=",a);

console.log("b=",b);

console.log("c=",c);

if (a+b>c&&b+c>a&&c+a>b) {

    console.log("Triangle is valid!");

} else {

    console.log("Triangle is invalid!");

}



console.log("\n\n16. Write a js program to check whether the triangle is equilateral, isosceles or scalene triangle.?");

console.log("====OUTPUT_Q_NO_16====\n\n");

var a=prompt("enter First side"),b=prompt("enter Second side"),c=prompt("enter Third side");

a=parseInt(a);

b=parseInt(b);

c=parseInt(c);

console.log("a=",a);

console.log("b=",b);

console.log("c=",c);

if (a==b&&a==c) {

    console.log("Triangle is equilateral");

} else if (a==b||b==c||c==a) {

    console.log("Triangle is isosceles");

} else if (a!=b&&b!=c&&c!=a) {

    console.log("Triangle is scalene");

}



console.log("\n\n18. Write a js program to calculate profit or loss.?");

console.log("====OUTPUT_Q_NO_18====\n\n");

var purchasePrice=prompt("purchase price of gold per tola for user"),soldPrice=prompt("sold price of gold per tola for customer"),noOfquantity=prompt("how many tolas you want to buy?"),profitLoss,totalPrice;

purchasePrice=parseInt(purchasePrice);

soldPrice=parseInt(soldPrice);

noOfquantity=parseInt(noOfquantity);

totalPrice=soldPrice*noOfquantity;

profitLoss=(soldPrice*100)/purchasePrice;

console.log("purchasePrice=",purchasePrice);

console.log("soldPrice=",soldPrice);

console.log("noOfTola=",noOfquantity);

console.log("Total price=",totalPrice);

if (profitLoss>100) {

    console.log("profit is ",profitLoss-100,"%");

} else if (profitLoss<100){

    console.log("loss is ",100-profitLoss,"%");

}else{

    console.log("profit_loss is neutral");

}



console.log("\n\n19. Write a js program to input marks of five subjects Physics, Chemistry, Biology, Mathematics and Computer. Calculate percentage and grade?");

console.log("====OUTPUT_Q_NO_19====\n\n");

var math=prompt("enter marks in math out of 100"),phy=prompt("enter marks in physics out of 100"),Bio=prompt("enter marks in BioLogy out of 100"),chem=prompt("enter marks in chemistry out of 100"),cs=prompt("enter marks in Computer sience out 0f 100"),percentage,sum,total=500;

math=parseInt(math);

phy=parseInt(phy);

chem=parseInt(chem);

cs=parseInt(cs);

Bio=parseInt(Bio);

sum=math+chem+cs+Bio+phy;

percentage=(sum*100)/total;

console.log("math=",math,"marks");

console.log("Computer science=",cs,"marks");

console.log("physics=",phy,"marks");

console.log("chemistry=",chem,"marks");

console.log("BioLogy=",Bio,"marks");

console.log("percentage=",percentage,"%");

if (percentage >= 90) {

    console.log("Grade=A");

} else if (percentage >= 80) {

    console.log("Grade=B");

}else if (percentage >= 70) {

    console.log("Grade=C");

}else if (percentage >= 60) {

    console.log("Grade=D");

} else if (percentage >= 40) {

    console.log("Grade=E");

} else if (percentage < 40) {

    console.log("Grade=F");

}



console.log("\n\n20. Write a js program to input basic salary of an employee and calculate its Gross salary ");

console.log("====OUTPUT_Q_NO_20====\n\n");

var basicSalary=prompt("Enter basic salary:"),grossSalary;

basicSalary=parseInt(basicSalary);

console.log("basicSalary=",basicSalary);

grossSalary=basicSalary+(basicSalary/20)+(basicSalary/80);

console.log("grossSalary=",grossSalary);



console.log("\n\n21. Write a js program to input marks of five subjects Physics, Chemistry, Biology, Mathematics and Computer. Calculate percentage and grade?");

console.log("====OUTPUT_Q_NO_21====\n\n");

var un,bill;

    un=prompt("Enter units of electricity:");

    un=parseInt(un);

    console.log("Unit=",un);

    if(un<=50){

        bill=un*0.50;

        console.log("electricity bill of consumer is:",bill,"rupees");

    }else if(un<=100){

        bill=un*0.75; 

        console.log("electricity bill of consumer is:",bill,"rupees"); 

    }else if(un<=200){

        bill=un*1.20;

        console.log("electricity bill of consumer is:",bill,"rupees");

    }else if(un<=250){

        bill=un*1.50;

        console.log("electricity bill of consumer is:",bill,"rupees");

    }else{

        bill=un*1.50+(un*1.50)/20;

        console.log("electricity bill of consumer is:",bill,"rupees");

    }
