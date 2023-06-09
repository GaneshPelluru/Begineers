# JSON
 
##  Context
 
   - Overview

   - History
  
   - What is JSON ?
  
   - Why use JSON ?
  
   - JSON Syntax and Rules
  
   - JSON Values
 
   - Example

   - Merirts and Demerits

   - Reference
  

## Overview:
- JSON (JavaScript Object Notation) is a `lightweight`, `text-based data interchange format`. 
- It is easy for humans to read and write and easy for machines to parse and generate. JSON is a common format for `sending and receiving` data between web services and applications.
- JSON is composed of `key-value pairs`, where the keys are always strings and the values can be a variety of data types, including `strings`, `numbers`, `booleans`, `arrays`, and other JSON objects.


## History:

JSON, which stands for `JavaScript Object Notation`, is a `lightweight data` interchange format that has gained widespread use in web applications and APIs. It was created by `Douglas Crockford` in the early `2000s` as an alternative to the more complex XML format.

JSON was designed to be easy to "read and write for both humans and machines", and to be easily parsed and generated by software. It is based on a subset of the JavaScript language, but is also `language-independent`, meaning it can be used with any programming language.

The initial specification for JSON was released in `2001`, and it quickly gained popularity as a data exchange format for web applications. It was embraced by many companies, including "Yahoo, Google, and Amazon", and became a key part of the web development ecosystem.

JSON has continued to evolve over the years, with new features and updates being added to the specification. In `2013`, the `JSON-LD` specification was released, which added support for linking data in JSON documents. In `2017`, the JSON Schema specification was released, which provided a way to describe the structure and validation rules for JSON data.


## What is JSON ?

 - JSON stands for `JavaScript Object Notation`.
 
 - JSON is a `lightweight data-interchange format`.
 
 - JSON is plain text written in JavaScript object notation.
 
 - JSON is used to send data between computers.
 
 - JSON is language independent *.



## Why use JSON ?

 The JSON formate is syntactically similar to the code for creating JavaScript objects. Because of this, a JavaScript program can easily convert JSON data into JavaScript objects.
 
 Since the formate is text only, JSON data can easily be sent between computers, and used by any programming language.
 
 JavaScript has a built in function for converting JSON string into JavaScript objects:
          
          JSON.parse()

 JavaScript also has a built in function for converting an object into a JSON string
 
          JSON.stringify()
 
 

## JSON Syntax and Rules:

The syntax is a subset of the JavaScript syntax. Code for reading and generating JSON exists in many programming languages

### Rules:

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
         


## Example:


              {
                "name": "vivek",
                "age": 20,
                "isMarried": false,
                "hobbies": ["reading", "traveling","cooking"]
              }



![Screenshot (20)](https://github.com/GaneshPelluru/Begineers/assets/129501298/93c6395a-79df-4f30-b29c-b8b26443db87)

JSON arrays are ordered lists of values enclosed in square brackets, separated by commas. For example:

              ["apple", "banana", "orange"]


JSON data can be used in a wide range of applications, including web APIs, databases, and configuration files. It is a popular format for representing structured data in web development, and many programming languages provide built-in support for parsing and generating JSON.


## Merits and Demerits

### Merits of JSON:

JSON (JavaScript Object Notation) is a lightweight and easy-to-parse format for exchanging data between applications. Some of the merits of JSON include:

- `_Simple syntax_` : JSON has a simple syntax that is easy for both humans and machines to read and write. This makes it a popular choice for data exchange between web applications and services.

- `_Small file size_`: JSON files are typically smaller than XML files, which can be an advantage in applications that require frequent data transfer, particularly over networks with limited bandwidth.

- `_Wide language support_`: JSON is supported by many programming languages, including JavaScript, Python, Ruby, and PHP, among others. This makes it a versatile and widely adopted technology.

- `_Easy to convert to objects_`: JSON data can be easily converted to native objects in most programming languages, making it easy to work with and integrate into applications.

- `_Support for arrays_`: JSON supports arrays, which can be useful for representing lists of data or for storing multiple values with the same name.

- `_Human-readable_`: Like XML, JSON is human-readable, meaning that it can be easily understood and edited by humans using a simple text editor. This makes it easy to view and modify data, and also facilitates collaboration between developers and other stakeholders.

Overall, JSON offers a lightweight, efficient, and widely supported format for exchanging data between applications, particularly in the web development space.


### `Demerits of JSON`:

While JSON (JavaScript Object Notation) has many merits, it also has some potential demerits

- `Limited data typing`: JSON is a loosely typed language, which means that it does not provide explicit data typing. This can make it difficult to ensure the integrity of data and to enforce constraints on the data, particularly in large or complex applications.

- `Limited support for comments`: JSON does not support comments, which can make it difficult to document and annotate code or data. This can be a problem for larger or more complex applications where documentation is critical.

- `No schema enforcement`: Unlike XML, JSON does not enforce schema validation, which means that there is no way to ensure that the data conforms to a specific schema or structure. This can be problematic for applications that require strict validation or that rely on consistent data structures.

- `No support for binary data`: Like XML, JSON is primarily designed for text-based data, which means that it may not be the best choice for applications that require efficient handling of binary data, such as images, audio files, or video.

- `Limited extensibility`: JSON has limited extensibility compared to XML, which means that it may not be the best choice for applications that require a high degree of customization or flexibility in data representation.

- `No support for namespaces`: Unlike XML, JSON does not support namespaces, which can make it difficult to differentiate between data from different sources or to ensure consistency across different data sources.

Overall, while JSON is a popular and widely used data exchange format, it has some limitations that may make it less suitable for certain applications or use cases.



## Reference:

[ CHATGTP SERVICE ](https://chat.openai.com/chat)

[ W3SCHOOL SERVICE ](https://www.w3schools.com)









