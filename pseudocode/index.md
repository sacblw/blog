---
layout: layouts/post.njk
title: Pseudocode
templateClass: tmpl-post
eleventyNavigation:
  key: Pseudocode
  order: 7
---


<code>
LOOP through numbers 0 - 100
  IF number is a mulitiple of 3 
    THEN output "fizz"
  ELSE IF the number is a mulitiple of 5 
    THEN output "buzz"
  ELSE IF the number is a multiple of 3 and 5
    THEN output "fizzbuzz"
  ELSE 
    THEN output number 

LOOP through numbers 0 - 100
  IF the number is a multiple of 3 and 5 
    THEN output "fizzbuzz"
  ELSE IF the number is a mulitiple of 5 
    THEN output "buzz"
  ELSE IF number is a mulitiple of 3 
    THEN output "fizz"
  ELSE 
    THEN output number 
</code>












<script>
//LOOP through numbers 0 - 100
for (counter=1; couster<=100; counter++){
  var message = '';
//ELSE IF number is a mulitiple of 3 
  if(counter % 3 == 0){
    //THEN output "fizz"
    message += 'fizz';
  }
//ELSE IF the number is a mulitiple of 5 
  if(counter % 5 == 0){
    //THEN output "buzz"
    message += 'buzz';
  }
//ELSE 
  if(!message){
    //THEN output number
    message = counter;
  }

  console.log(message);
}
</script>