# JSON
 
##  Context
 
   - Overview
  
   - What is JSON?
  
   - Why use JSON?
  
   - JSON Syntax and Rules
  
   - JSON Values
 
   - Example

   - Reference
  

## Overview
- JSON (JavaScript Object Notation) is a `lightweight`, `text-based data interchange format`. 
- It is easy for humans to read and write and easy for machines to parse and generate. JSON is a common format for `sending and receiving` data between web services and applications.
- JSON is composed of `key-value pairs`, where the keys are always strings and the values can be a variety of data types, including `strings`, `numbers`, `booleans`, `arrays`, and other JSON objects.


## What is JSON?

 - JSON stands for `JavaScript Object Notation`.
 
 - JSON is a `lightweight data-interchange format`.
 
 - JSON is plain text written in JavaScript object notation.
 
 - JSON is used to send data between computers.
 
 - JSON is language independent *.



## Why use JSON?

 The JSON formate is syntactically similar to the code for creating JavaScript objects. Because of this, a JavaScript program can easily convert JSON data into JavaScript objects.
 
 Since the formate is text only, JSON data can easily be sent between computers, and used by any programming language.
 
 JavaScript has a built in function for converting JSON string into JavaScript objects:
          
          JSON.parse()

 JavaScript also has a built in function for converting an object into a JSON string
 
          JSON.stringify()
 
 

## JSON Syntax and Rules

The syntax is a subset of the JavaScript syntax. Code for reading and generating JSON exists in many programming languages

### rules

JSON syntex is derived from JavaScript object notation, but the JSON formate is text only.

  - Data is in name/value pairs
  - Data is separated by commas
  - Curly braces hold objects
  - Square brackets hold arrays
 

## JSON Values

In JSON   values must be one of the following data types:

  - a string
  - a number
  - an object
  - an array
  - a boolean
  - null

In JavaScript values can be all of the above,plus any other valid JavaScript expression,including:

  - a function
  - a date
  - undefined

In JSON, string values must be written with `double quotes`.

         
         JSON 
         {"name":"vivek"}
         


## Example


              {
                "name": "vivek",
                "age": 20,
                "isMarried": false,
                "hobbies": ["reading", "traveling","cooking"]
              }


"C:\Users\Rajya Lakshmi\OneDrive\Pictures\Screenshots\Screenshot (20).png"

JSON arrays are ordered lists of values enclosed in square brackets, separated by commas. For example:

              ["apple", "banana", "orange"]


JSON data can be used in a wide range of applications, including web APIs, databases, and configuration files. It is a popular format for representing structured data in web development, and many programming languages provide built-in support for parsing and generating JSON.


## Reference

[ CHATGTP SERVICE ](https://chat.openai.com/chat)

[ W3SCHOOL SERVICE ](https://www.w3schools.com)









