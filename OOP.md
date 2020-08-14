
# Working with Objects

---

### What is an Object?

A JavaScript object is an unordered collection of data organized by key and value pairs. An object can contain any data structure or data type including funtions! Objects can be used to contain a group of relevant data.

#### Key-values:
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

We can access each of these individual values by their key from the 

### Real World Example

Because Amazon.com collects a lot of shopping data, relevant customer data for a single customer can be stored in a JavaScript Object. A single customer's data could include:
* First Name
* Last name
* Age
* Gender
* Purchases
* Favorite Products
* A quick look at the last purchased item

### Code

Run the below code and comment/uncomment the lines below to understand 

&nbsp;

<iframe height="600px" width="100%" src="https://repl.it/@RogerFleenor/awesomeCustomerObject?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>

Or visit https://repl.it/join/lsaempyy-rogerfleenor

<details>
  <summary><strong> Abstraction</strong></summary>

* details

</details>


<details>
  <summary><strong> Inheritance</strong></summary>

* details

</details>


<details>
  <summary><strong> Polymorphism</strong></summary>

* details

</details>


<details>
  <summary><strong> Encapsulation</strong></summary>

* details

</details>
