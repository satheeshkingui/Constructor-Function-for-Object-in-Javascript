<b>About Constructor</b> </br>
A constructor is special type subroutine called to create object. It prepares the new object for use, often accepting arguments that the constructor uses to set required member variables.</br>

<b>Constructor Function for Object in Javascript</b> </br>

Fist create a function use parameters </br>


Ex: </br>

function studentInfo(id, rollno, name, class){     // constructor function</br>
     //assign variable to parameters</br>
}</br>

Inside the constructor function declare variables and assign parameters</br>

function studentInfo(id, rollno, name, section){ //constructor function</br>
    this.studId = id;      // studId is variable, id studentInfo parameter</br>
    this.studRollno=rollno;</br>
    this.studName=name;</br>
    this.studSection=section;</br>
}</br>


//Create object declare the values</br>
var studentOne = new studentInfo(1, 10001, "Raj", "Xth-B");  // studentOne is variable, studentInfo is object</br>


// check result in console</br>
console.log(studentOne.studName);</br>
Output</br>
Raj</br>


studentOne is single record can create multiple records using studentInfo() function </br>

var studentTwo = new studentInfo(2, 10002, "Ravi", "Xth-B");  </br>
var studentThree = new studentInfo(3, 10003, "Revathi", "Xth-B");  </br>

// check result in console </br>
console.log(studentOne); //StudentOne record </br>
console.log(studentTwo); //StudentTwo record </br>
console.log(studentThree); //StudentThree record </br>

