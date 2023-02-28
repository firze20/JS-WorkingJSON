Exercise: Reading a JSON String

Now that we’ve shown you how to read a JSON string, let’s practice with a code challenge by writing some code yourself.

1. Create a variable called jsObject that is an object parsed from jsonData.

2. Print out the array of all the children property nested in jsObject. Be sure to use either bracket notation or dot notation to access the nested properties.

----------------//-----------------

Exercise: Writing a JSON String

As a developer, you receive some data in the form of a JSON string in the variable, jsonData. However, the content of jsonData is not completely correct. The age value of the parent property should be 35 instead of 45. Without changing the content of jsonData directly, update the age value and then log a new JSON string with the correct value in the console.

Here is a step-by-step guide to solve this challenge:

 1. Convert jsonData to a JavaScript object using JSON.parse() and save it as a const variable, for instance, jsObject.
 2. Use either the dot, .key, or bracket, ['key'], notation to access the parent property of jsObject followed by the age property and change its value from 45 to 35.
 3. Convert jsObject back to a JSON string using JSON.stringify() and save it as another const variable, for instance, jsObjectToJson.
 4. Log the jsObjectToJson string on the console.





