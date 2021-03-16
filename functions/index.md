---
layout: layouts/post.njk
title: Functions
templateClass: tmpl-post
eleventyNavigation:
  key: Functions
  order: 6
---


<script>
/*
function outputMessage() {
    console.log('Output Message');
};

console.log('Task 1 Start');
console.log('-------------');


outputMessage();

console.log('-------------');
console.log('Task 1 End');


console.log('--------------------------------------------------------');



function combineStrings(string1, string2) {
    console.log(string1 + " " + string2);
}

console.log('Task 2 Start');
console.log('-------------');

var fName = 'Hello'; 
var lName = 'World';

//This is how we pass arguments to a function
combineStrings(fName, lName);


console.log('-------------');
console.log('Task 2 End');

console.log('--------------------------------------------------------');



function combineStringsAndReturn(string1, string2) {
    var combinedStrings = string1 + " " + string2;
    return combinedStrings;
}

console.log('Task 3 Start');
console.log('-------------');

var fName = 'Sarah'; 
var lName = 'Carr';

var names = combineStringsAndReturn(fName, lName);

//console.log(combinedStrings);

console.log('-------------');
console.log('Task 3 End');

*/

// Both comparisons have to be true && 
// One comparisons have to be true || 

function shouldIPutOnACoat(temp) {

    console.log(temp < 30);

    if (temp <= 50 && temp > 30) { //temp less than or equal to 50 && temp greater than 30 
        var message = "Put On A Coat";
    } else if (temp <= 30 && temp != 0) {
        var message = "Put On A Coat & Hat";
    } else if (temp === 0 ) { 
        var message = "Stay Inside";
    } else {
        var message = "Pants & Vest is fine";
    }

    return message;
};

var temp = 0;

console.log(shouldIPutOnACoat(temp));

</script>