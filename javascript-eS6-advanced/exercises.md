Inheritance with prototype
----------------------------

1. Create a function/class Animal, whose objects has a method `speak`, which returns a value "poop". Create two class Dog and Cat that inherits from Animal. Calling speak on Dog should return "woof" and the Cat should return "meow"

    ```javascript

        function Animal() {
        }

        Animal.prototype.speak = function() {
        return "poop";
        }

        var animal = new Animal();

        function Dog() {  
        }

        var dog = new Dog();
        //make this test pass
        console.log(dog.speak() == "bark");
    ```

DOM and Events
------------------
1. Given this DOM:
    ```html
        <div id="div1"></div>
        
        <div class="test" id="div2">
            <p>Text1</p>
            <p>Text2</p>
        </div>
        <div class="test" id="div3">
            <p>Para
            <span id="span1">1</span>
            </p>
        </div>
    ```
    - Select all the elements with class "test"
    - Log the ids of the elements with class "test"
    - Select the span with id "span1", Log all the parent elements upto body
    - Assign a height and width to div with id "div1" and put a background color red
    - Change the color of the text "Para" to green and "1" to blue
    - Add another paragraph to div with id "div2" and add some text to it

    *(you can use javascript or jquery for the above)*

    Try here: http://jsbin.com/tuhuci/edit?html,js,console

2. Given this DOM:
    ```html
        <div id="products">
            <div class="content">
                <span class="product-name">Oranges</span>
                <span class="product-quantity" data-quantity="4">6</span>
                <span class="product-price" data-price="200">Rs.200.00 a dozen</span>
            </div>
            <div class="content">
                <span class="product-name">Pen</span>
                <span class="product-quantity" data-quantity="2">2</span>
                <span class="product-price" data-price="20">Rs.20.00 a piece</span>
            </div>
            <div class="content">
                <span class="product-name">Watch</span>
                <span class="product-quantity" data-quantity="1">1</span>
                <span class="product-price" data-price="2000">Rs.2000.00 a piece</span>
            </div>
        </div>

    ```
    - Write a program to calculate the total price using the values in the data attributes.
    - Show Amount: <calculated amount from the above> in the dom after the div with id `produtcs` 
    *(you can use javascript or jquery or both)*

3. Given an input field, show the difference between `change`, `input`, `focus` and `blur` events.


ES6
-------------------
1. Create an array that takes an array of functions, each function when called returns its index in the array.
    *Hint: `arrayOfFuncs.push(function() { console.log(i) })`*
2. Using es6 arrow syntax and an array of 5 numbers, create another functions with each elements doubled
3. Given this object
    ```javascript
        var Game = {
            bounceFactor: 1,
            bounced: 0,
            limit: 10,
            bounce: function() {

            }
        }
    ```
    Write the bounce method that increases the value of bounced from 0 upto the `limit` adding the `bounceFactor` each time, at an interval of 1 second(1000 ms). Clear the interval after the value of `bounced` has reached the `limit`.

    *(Use es6 arrow when necessary)*
    Excepted output: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10.
4. Show destructing of an array and object.
5. Write a method `formatDate` that takes `year`, `month`, `day` and an optional `separator` and formats the date like `year<separator>month<separator>day<separator>`, by default, the separator should be `/`;
6. What is Promise ? How to convert a value into a Promise ? What is the use of Promise.all and Promise.reject ?

ajax using jquery
-------------------------------

`github` gives us an api that helps to fetch user details. using this url `https://api.github.com/search/users?q=<user name from input field for say>`.

Now Given this dom:

```html
        <div id="error"></div>
        <div id="user">
            <p>Name: <span id="name"/></p>
            <img id="image"/>
        </div>
        <input type="text" id="users" placeholer="type user name"/>
        <button id="search" type="button">Search</button>
```

whenever the user hits Search, get the first user returned by the ajax request and show the names and image in proper place.