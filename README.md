# More Ajax Practice!

### Part 1 - 10 min

Make a function called `makeCall` that will make an AJAX GET request to https://randomuser.me/api/ and console.log the response in the success function.


### Part 2 - 5 min

Write a click handler for the button that will call the makeCall function.


### Part 3 - 15 min

Write a function called `getData` that will parse the results from the ajax request and create an object with the user's first name, last name, email, dob, street, city, state, address, phone, password, and image. Call this function from the success method of your AJAX call.


### Part 4 - 20 min

Write a function called `manipulateDom` that will accept the object with the user's name, email, dob, address, phone, pw, and image as an argument. Assign these values as data attributes to the html elements as follows:
- the element with the id of `bigtext` should have the the user's name for its text
- the element with the id of `photo` should have the user's image for it's background-image
- the element witht he id of `name` should have the user's name for its data attribute
- the element with the id of `email` should have the user's email for its data attribute
- the element with the id of `birthdate` should have the user's birthdate for its data attribute
- the element with the id of `phone` should have the user's phone for its data attribute
- the element with the id of `password` should have the user's password for its data attribute

### Part 5 - 20 min

write a function called addEventListeners that will add the following hover listeners for the icons on the page

- when hovering over `#name`, the `#smalltext` should say 'My name is', and the `#bigtext` should use the `#name`'s data attribute for its text.
- when hovering over `#email`, the `#smalltext` should say 'My email is', and the `#bigtext` should use the `#email`'s data attribute for its text
- when hovering over `#birthdate`, the `#smalltext` should say 'My birthday is', and the `#bigtext` should use the `#birthdate`'s data attribute for its text
- when hovering over `#address`, the `#smalltext` should say 'My addresss is', and the `#bigtext` should use the `#address`'s data attribute for its text
- when hovering over `#phone`, the `#smalltext` should say 'My phone number is', and the `#bigtext` should use the `#phone`'s data attribute for its text
- when hovering over `#password`, the `#smalltext` should say 'My password is', and the `#bigtext` should use the `#password`'s data attribute for its text
