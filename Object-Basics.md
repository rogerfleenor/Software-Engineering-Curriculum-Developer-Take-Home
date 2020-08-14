
![Object](https://cdn.lynda.com/course/782146/782146-637286262547385310-16x9.jpg)

&nbsp;

# Object Basics

&nbsp;

## 1) What is an Object in Real World?

OOP offers us the ability to create objects in our JavaScript program that resembles things in the real world. If we imagine a delivery driver for Uber Eats or Amazon Prime, this can be represented programatically in an object with these contents:

  * Driver's personal information
  * Vehicle information
  * Time spent driving
  * Current delivery
  * Next delivery
  * And more!

### What is an example of an object you can resemble from the real world? 
Start thinking about it, we will put it in code at the end of this lesson!

&nbsp;

## 2) What is an Object in JavaScript?

A JavaScript object is an unordered collection of data organized by `key` and `value` pairs. An object can contain any data structure or data type including funtions! Objects can also be used to contain a group of relevant data.

### Key-values:
Below we have key `name` which has the value `['Laquisha', 'Bonflay']` which is a list.

```
const customer = {
  name: ['Laquisha', 'Bonflay'],
};
```

A key's value could be a list, integer, string, list, another key or even a function!

```
const customer = {
  
  name: ['Laquisha', 'Bonflay'],    <-- list

  age: 29,                          <--integer
  
  gender: 'female',                 <-- string
  
  favorites: {                      <-- another key

    home: 'kitchen'                 <-- and another key

  },
  
  getLastPurchase: function() {     <- function
    
    console.log('wow a function');
  
  }

};
```

### Accessing Objects

We can access each of these values by using dot notation! If we would like to obtain the gender female, we just need to reference the object and key name like this:

```
customer.gender
```
If we want the value of home which is part of a key inside of another key, we reference the key inside:
```
customer.favorites.home
```

Different data structures can be accessed as well, for a list we just need to specify the index!
```
customer.name[0]
```
Similar syntax for a function!
```
customer.getLastPurchase()
```

### Video on JavaScript Objects
To help clarify how objects work, check out this video! [YouTube](https://www.youtube.com/embed/8iXoWC9XcU8)

&nbsp;

## 3) Real World Meets JavaScript

Because Amazon collects a lot of shopping data, relevant customer data for a single customer can be stored in a JavaScript Object. A single customer's data could include:
* First Name
* Last name
* Age
* Gender
* Purchases
* Favorite Products
* A quick look at the last purchased item

### Let's Run Some Code

Run the below code and comment/uncomment the lines one at a time to see how data and functionality is accessed and outputted to the console! Or visit https://repl.it/join/lsaempyy-rogerfleenor

&nbsp;

<iframe height="600px" width="100%" src="https://repl.it/@RogerFleenor/awesomeCustomerObject?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>

&nbsp;

## 4) Let's make an Object!

Let's wrap up this lesson with our own JavaScript Object! Create an object based on something in the real world (Choose something you encounter daily). Use the previous example as reference if needed! Your object should contain:
* 5 different `keys`
* A `list`
* A `key` inside of a `key`
* A `function()`
* `Strings`, `Integers` or `Floats`

And lastly, `console.log()` each of the values in your object. Don't forget to save! Use the below repl.it editor to create an object or visit https://repl.it/@RogerFleenor/studentCode?lite=true

&nbsp;

<iframe height="400px" width="100%" src="https://repl.it/@RogerFleenor/studentCode?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>

Congrats! You have completed this lesson!

&nbsp;

---

### For more on Objects in JavaScript, visit:

[Mozilla](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object-oriented_JS#Object-oriented_programming_%E2%80%94_the_basics)

[w3schools](https://www.w3schools.com/js/js_objects.asp)

&nbsp;

[Roger Fleenor](https://www.linkedin.com/in/rogerfleenor/) 
