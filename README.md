## User Input Mini App
Now that we know about `prompt` and `alert`, let's build a simple input/output app. The main objective is to create an application that _takes in user input, does something with that input, and then displays an output_.

### Gets
The first thing we need to do is take in user input with the `prompt` method. Remember, when an executed JavaScript program hits the method `prompt`, the program is going to pause and wait for the user to enter text into the text box.

The way `prompt` takes in input is important to remember. First, it always takes in input as strings. If a user enters `10`, gets interprets that as `"10"`, not as an integer. The second thing to remember is that `gets` also takes in the newline character. 

### The Challenge: A Visit to NYC

You're going to build an application to plan a tourist's visit to NYC. You'll code your solution in `js/trip.js` Open `trip.js` with your editor to start writing your program.

You'll want to ask the user where they would like to stay, what sites they want to visit, what food they want to eat, and how many nights they want to stay. For each question, you'll take in input from the user and store each piece in a variable. <img src="https://s3.amazonaws.com/after-school-assets/greetings.jpg" align="right" width="300" hspace="20">

Once you have that input stored, you'll want to use string methods (like toUpperCase, toLowerCase, etc) to put the input in a proper format. You can always take a look at the JavaScript documentation [here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) to learn more about string methods you can use. 

Your final output should use *string concatenation* to output the data in a full summary of their NYC itinerary. 

Remember, you'll need to link your JavaScript file to `index.html` for your code to run in the browser.

#### Bonus

See if you can make suggestions for them based on the type of food they'd like to eat, the types of places they'd like to visit, etc. You'll need to use if-statements to trigger events based on their input. 