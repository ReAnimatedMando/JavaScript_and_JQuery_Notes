##  The ABC of Programming
##  How Javascript makes web pages more interactive
*   Access Content
    -   You can use JavaScript to select any element, attribute, or text from an HTML page. For example;
        *   Select the text inside all of the h1> elements on a page
        *   Select any elements that have a class attribute with a value of note
        *   Find out what was entered into a text input whose id attribute has a value of email
    -   JavaScript allows you to make web pages more interactive by accessing and modifying the content and markup used in a web page while it is being viewed in the browser.
*   Modifying Content
    -   You can use JavaScript to add elements, attributes, and text to the page, or remove them. For example;
        *   Add a paragraph of text after the first h1> element
        *   Change the value of class attributes to trigger new CSS rules for those elements
        *   Change the size or position of an img> element
* Program Rules
    -   You can specify a set of steps for the browser to follow (like a recipe), which allows it to access or change the content of a page. For example;
        *   A gallery script could check which imagea user clicked on and display a larger version of that image
        *   A mortgage calculator could collect values from a form, perform a calculation, and display repayments
        *   An animation could check the dimensions of the browser window and move an image to the bottom of the viewable area (also known as the viewport)
    -   JavaScript encompasses many of the traditional rules of programming. It can make the web page feel interactive by responding to what the user does.
*   React to Events
    -   You can specify that a script should run when a specific event has occurred.
    For example;
        *   A button is pressed
        *   A link is clicked (or tapped) on
        *   A cursor hovers over an element
        *   Information is added to a form
        *   An interval of time has passed
        *   A web page has finished loading
*   Examples of JavaScript in the Browser
    -   Being able to change the content of an HTML page while it's loaded in the browser. These rely on the ability to...
        *   Access - Get each image or slide from a slideshow page, get values from a field on the page, access links users click on, access pages to be replaced when reloading specific areas of the page.
        *   Modify - Only show first slide and hide others, change slide or img shown, show requested slide, showing warnings is field isn't filled out correctly, replace old content with new content, show subset of imgs that use certain tags.
        *   Program - Set timers for when to show slides, determine which slides to show, chech that information in fields are long enough, load new content that is required from a link, collect keywords from imgs, find the relevant subset of imgs that should be shown.
        *   React - Script triggered when the page loads, when user clicks button for different slide, user presses the submit button when they have entered their name, script triggers when user clicks on link.
##  What Is A Script & How Do I Create One?
*   A script is a series of instructions that a computer can follow to achieve a goal. You could compare scripts to any of the following.
    -   Recipes - By following the istructions in a recipe, one-by-one in the order set out, cooks can create a dish they have never made before.
    -   Handbooks - Handbooks contain procedures to follow in certain situations.
    -   Manuals - Contain series of tests to check the key functions along with details of how to fix. 
*   Scripts are made up of instructions a computer can follow step by step.
*   A browser may use different parts of the script depending on how the user interacts with the web page.
*   Scripts can run different sections of the code in response to the situation around them.
*   Writing a script - to write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.
    -   Scripts may seem complicated at first but are really just a series of short instructions, each of which is performed in order to solve the problem at hand. This is how a script is like a recipe or manual, it allows a computer to solve a puzzle one step at a time.
        *   A computer doesn't learn how to perform tasks permanently and needs to follow instructions every time it performs the task so a program must give it enough detail to perform the task everytime as if it were its first time.
    -   Always start with the big picture of what you want to achieve, and break that down into smaller steps.
        *   1. Define the goal - First, define the task you want to achieve like a puzzle you want the computer to solve.
        *   2. Design the script - Split the goal out into a series of tasks that are going to be involved in solving this puzzle. Can be represented using a flow chart. You can write down individual steps the computer needs to perform in order to complete each task as well as any information it needs to perform the task, again like a recipe it needs to follow.
        *   3. Code each step - Each of the steps needs to be written in a programming language that the computer understands, in our case JavaScript. 
            - It pays to spend time designing your script before you start writing it.
*   Designing a script: Tasks
    -   Once you know the goal of your script, you can work out the individual tasks needed to achive it. This high-level view of the tasks can be represented using a flowchart.
*   Designing a script: Steps
    -   Each individual task may be broken down into a sequence of steps. When you are ready to code the script, these steps can then be translated into individual lines of code.
        *   The steps that a computer needs to follow in order to perform a task are often very different from those that you or I might take.
*   From steps to Code - Every step for every task shown in a flowchart needs to be written in a language the computer can understand and follow.
    -   We will be learning JavaScript and in doing so we will learn the VOCABULARY & SYNTAX. We will also learn how a computer  uses a programmatic approach to problem-solving.
    -   Computers are very logical and obedient so they need to be told every detail of what they are expected to do, and they will do it without question.
    -   We will need to learn to think like a computer because they solve tasks different than we would. i.e.
        *   If a computer wanted to determine who the tallest person of a group was it would have to look at each person in turn, one by one. It would also have to designate the first person looked at as the tallest. then, when going through each person it would compare them to the designated tallest person and determine if the new/current person it was looking at was now the tallest and then designate it as so, moving on to the next person and repeating the process until it has gone through everyone in the room and can deliver a definitive answer.
*   Defining a goal & designing the script - Consider how you might approach a different type of script.
    -   Detail your goals for the script, what you want it to achieve.
    -   Break it into a series of tasks that have to be performed in order to achieve the goals:
        *   1. Script is triggered when the button is clicked
        *   2. It collects the name entered into the form field
        *   3. It checks that the user has entered a value
        *   4. If the user has not entered anything, a message will appear telling them to enter a name
        *   5. If a name has been entered, calculate the cost of the sign by multiplying the number of letters by the cost per letter
        *   6. Show how much the plaque costs
    -   Flowcharts are used to work out how the tasks fit together
        *   Arrows show how the script moves from one task to the next and some different decisions/interactions can cause the code to follow different paths.
##  Computers & The World Around Them
*   Computers create models of the world using data
    -   A computer has no predefined concept of what things in the world are and doesn't know what they are used for.
    -   Programmers make models using data as instructions for computers to follow and this is all that the computer needs to carry out its' tasks.
*   Objects - Are things, in computer programming, each physical thing in the world can be represented as an object.
    -   If your objects are a hotel and two cars, programmers would say that there are one instance of a hotel and two of a car.
        *   Each object has its own...
            -   Properties
            -   Events
            -   Methods
        *   Together these make up the working model of that object. 
            -   Name/Value pairs are used alot in programming. Same for JS as in HTML & CSS
*   Properties - Are characteristics, such as color, model, speed, size. The characteristics work in name/value pairs.
*   Events - Simply put an event is the users interaction with an object that triggers a functionality. It's a computers way of raising its hand and saying, "Hey, this just happened".
    -   Programmers choose which events they respond to. When a specific event happens, that event can be used to trigger a specific section of the code.
    -   Scripts often use different events to trigger different types of functionality.
    -   So, a script will state which events the programmer wants to respond to, and what part of the script should be run when each of those events occur.
*   Methods - Methods represent things people need to do with objects. They can retrieve or update the values of an object's properties.
    -   Methods represent how people interact with an object in the real world. They are like questions and instructions that:
        *   Tell you something about that object (using information stored in its properties)
        *   Change the value of one or more of that object's properties
    -   The code for a method can contain lots of instructions that together represent one task.
        *   When you use a method, you do not always need to know how it achieves its task; you just need to know how to ask the question and how to interpret any answers it gives you.
*   Putting it all together
    -   Computers use data to create models of things in the real world. The events, methods, and properties of an object all relate to each other: Events can trigger methods, and methods can retrieve or update an objects properties.
    -   Hotel Object;
        *   1. When a reservation is made, the book event fires.
            2. The book event triggers the makeBooking() method, which increases the value of the bookings property.
            3. The value of the bookings property is changed to reflect how many rooms the hotel has available.
    -   Car Objects;
        *   1. As a driver speeds up, the accelerate event fires.
            2. The accelerate event calls the changeSpeed() method, which in turn increases the value of the currentSpeed property.
            3. The value of the currentSpeed property reflects how fast the car is traveling.
    -   Web browsers are programs built using objects
        *   Window object - A browser represents each window or tab using a window object.
        *   Document object - The current web page loaded into each window is a document object.
            -   Just like the hotel, the document object has properties, methods, and events.
                *   Properties;
                    -   URL
                    -   lastModified
                    -   title
                *   Event;
                    -   load
                    -   click
                    -   keypress
                *   Method;
                    -   write()
                    -   getElementByld()
*   How a Browser sees a Web Page
    -   1. Recieve a page as HTML - each page seen as a separate document
    -   2. Create a model (like a family tree) and store it in memory - The HTML is the document object and beneath it each other box/element is called a node and each is another document object.
    -   3. Use a rendering engine to show the page on the screen - With or without CSS, the rendering engine processes all folders associate with the HTML document object and displays it on the page using an interpreter. A JS one to be exact.
##  How to Write a Script for a Web Page
*   How HTML, CSS, & JAVASCRIPT Fit Together
    -   HTML - Is the content layer. This is where the content of the page lives. It adds structure and semantics. HTML will contain links to the folders for the CSS and JS.
    -   CSS - The presentation layer. This is the styling of the page.
    -   JS - Behavior layer. Adds interactivity. Each language forms a separate layer with a different purpose.
*   Progressive Enhancement - the 3 layers form the basis of progressive enhancement. Progressive meaning that starting with HTML, then moving to CSS, and lastly JS, a programmer can enhance there page without losing the usability of its lowest functions. HTML is the content and most important part, without the others it still gets a point across albeit in a boring way. Building from there a programmer just makes there page more appealing with CSS and JS. 
*   Creating a Basic JavaScript - JS, like HTML & CSS, is written in plain text.
    -   1.A JavaScript file is just a text file with an extension of .js. Create a folder to put the example in called c01, then start up your favorite code editor, and enter the text as follows;
        *   var today = new Date();
            var hourNow = today.getHours();
            var greeting;

            if (hourNow > 18) {
                greeting = 'Good evening!';
            } else if (hourNow > 12) {
                greeting = 'Good afternoon!';
            } else if (hourNow > 0) {
                greeting = 'Good morning!';
            } else {
                greeting = 'Welcome!';
            }

            document.write('h3>' + greeting + '/h3>');
    -   2.Get CSS images from www.javascriptbook.com
    -   3.Enter HTML from book example pg. 47. Link JS with a script> src="">/script>
    -   4.Test in browser
    -    The source code is not amended in this example and the HTML for your page remains the same.
    -   Placing the script in the page. You may see JS in the HTML between opening script> and closing /script> but it's better to put scripts in their own files.
*   How to use Objects & Methods
    -   document.write('Good afternoon!');
        *   document object represents the entire page. Use by giving its name.
        *   member operator is a dot between the object name and object member you want to access.
        *   write method of the document allows new content to be written into the page wherever the script> element sits.
        *   parameters are pieces of information inside parentheses. In the above example the parameter is what needs to be written into the page.
            -    So you know your object and method and how to tell it what information it needs to do the job you want.
            -   Also, JS runs where it is found in the HTML (the script> element)
##  Basic JavaScript Instructions
*   Statements - A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon.
    -   Statements are instructions and each one starts on a new line and ends with a semicolon. The semicolon tells that JS interpreter when a step is over, indicating it should move on to the next step.
    -   Some statements are surrounded by curly braces and are known as code blocks, the curly brace does not end with a semicolon. 
*   Comments - You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code. 
    -   Multi-line comments
        *   To write a comment that stretches over more than one line, you use a multi-line comment starting with /* and ending with */. Anything between these characters is not processed by the JS interpreter. They are used by the author as descriptions of how the script works or to prevent section of the script from running during testing.
    -   Single-line comments
        *   In a single-line comment, anything that follows // on that line will not be processed by the JS interpreter. These should be short descriptions of what the code is doing. 
*   What Is A Variable? - A script will have to temporarily store the bits of information it needs to do its job. It can store this data into variables.
    -   When writing JS you must tell the interpreter every individual step that you want it to perform. This involves alot of data.
    -   Variable is a good name for this concept because the data stored can change/vary each time the script runs.
*   Variables - How to declare them
    -   Before you can use a variable, you need to announce that you want to use it. This involves creating the variable and giving it a name. Programmers say that you declare the variable. i.e... var is the variable keyword, quantity is the variable name. JS knows that var is used to declare/create a variable. The second name, quantity, is the identifier. If a variable name is more than one word, it is usually written in camelCase. Meaning the first letter of the first word is lower case and the first letter of the second word is uppercase. 
*   Variables - How to assign them value
    -   Once you have created a variable, you can tell it what information you would like it to store for you. Programmers say that you assign a value to the variable. 
    -    Here you can use the variable name, quantity, as it should represent the kind of data that the variable holds. Here the = sign is the assignment operator. This assigns a value to the variable, until you assign a value to the quantity variable it will be said to be undefined.
*   Data Types - JS distinguishes between numbers, strings, and true or false values known as Booleans
    -   Numeric Data Type
        *   The numeric data type handles numbers. Numbers are used for calculators, determining sizes, moving position of elements, or setting an amount of time for a command. 
            -   uses numbers 0-9
            -   there are no commas in between hundreds and thousandths
            -   numbers can be negative
            -   numbers can be decimals
    -   String Data Type
        *   The string data type consists of letters and other characters.
            -   string data is enclosed in '' or "" but must match
            -   can be used with any kind of text
            -   used to add new content and can contain HTML
    -   Boolean Data Type
        *   Boolean data types can have one of two values: true or false.
            -   boolean may seem abstract but is actually very helpful
            -   think of boolean as a light switch, it is either on or off
            -   helpful when determining which part of a script should run
*   Using a Variable to Store a Number
    -   i.e.
        *   var price;
            var quantity;
            var total;

            price = 5;
            quantity = 14;
            total = price * quantity;

            var el = document.getElementById('cost');
            el.textContent = '$' + total;
        *   Note that the numbers are not written inside quotation marks. Once a value has been assigned to a variable, you can use the variable name to represent that value(like in algebra). Here, the total cost is calculated by multiplying the price of a single tile by the number of tiles the user wants.
            -   The result is then written into the page on the final two lines. The first two lines finds the element whose id attribute has a value of cost, and the final line replaces the content of that element with the new cost.
                *   Note there are many ways to write content into a page, and several places you can place your script.
*   Using a Variable to Store a String
    -   i.e.
        *   var username;
            var message;
            username = 'Molly';
            message = 'See our upcoming range';

            var elName = document.getElementById('name');
            elName.textContent = username;
            var elNote = document.getElementById('note');
            elNote.textContent = message;
        *   Note in the first four lines, the two variables are declared, username and message, and they are used to hold strings the users' name and a message for that user. The last four lines is the code to update the page. This code selects two elements using the values of their id attributes. The text in those elements is updated using the values stored in these variables.
            -   Remember that...
                *   text needs quotes, single or double, "" ''
                *   quotes should be straight
                *   quotes must match "" '' not '" "'
                *   strings must always be written on one line
*   Using Quotes Inside a String
    -   Sometimes you will want to use a double or single quote mark within a string.
        *   Because strings can live in single or double quotes, if you just want to use double quotes in the string, you could surround the entire string in single quotes.
        *   If you just want to use single quotes in the string, you could surround the string in double quotes... title = "Molly's Special Offers";
        *   You can also use a technique called escaping the quotation characters. This is done by using a backwards slash before any type of quote mark that appears within a string... message = '<a href=\"sale.html\">25% off!<a/>';
        The backslash tells the interpreter that the following character is part of the string, rather than the end of it. 
*   Using a Variable to Store a Boolean
    -   i.e.
        *   var inStock;
            var shipping;
            inStock = true;
            shipping = false;

            var elStock = document.getElementById('stock');
            elStock.className = inStock;

            var elShip = document.getElementById('shipping');
            elShip.className = shipping;
            -   Booleans are only used when the value can be true or false, or 0/1. 0 being false and 1 being true.
            -   Booleans are used when your code can take more than one path. Remember, different code may run in different circumstances. The path the code takes depends on a test or a condition.
*   Shorthand for Creating Variables
    -   Variables are declared and values assigned in the same statement.
        *   var price = 5;
            var quantity = 14;
            var total = price * quantity;
    -   Three variables are declared on the same line, then values assigned to each.
        *   var price, quantity, total;
            price = 5;
            quantity = 14;
            total = price * quantity;
    -   Two variables are declared and assigned values on the same line. Then one is declared and assigned a value on the next line.
        *   var price = 5, quantity = 14;
            var total = price * quantity;
    -   Here, a variable is used to hold a reference to an element in the HTML page. This allows you to work directly with the element stored in that variable.
        *   // Write total into the element with id of cost
            var el = document.getElementById('cost');
            el.textContent = '$' + total;
            -   Note that shorthand, while convenient to write can make your code harder to follow.
*   Changing the Value of a Variable
    -   Once you have assigned a value to a variable, you can then change what is stored in the variable later in the same script. Once the variable has been created, you do not need to use the var keyword to assign it a new value. You just use the variable name, the equals sign also known as the assignment operator, and the new value for that attribute. 
        *   i.e.
            var inStock;
            var shipping;

            inStock = true;
            shipping = false;

            inStock = false;
            shipping = true;
*   Rules for Naming Variables - Here are 6 rules you must always follow when giving a variable a name:
    -   1 - The name must begin with a letter, dollar sign, or an underscore. It must NOT start with a number
    -   2 - The name can contain letters, numbers, $, _. Note that must not use a dash or a period in a variable name
    -   3 - You cannot use keywords or reserved words. Keywords are special words that tell the interpreter to do something. For example, var is a keyword used to declare a variable. Reserved words are ones that may be used in a future version of JS
    -   4 - All variables are case sensitive, so score and Score would be different variable names, but it is bad practice to create two variables that have the same name using different cases
    -   5 - Use a name that describes the kind of information that the variable stores. For example, firstName might be used to store a person's first name, lastName for their last name, and age for their age.
    -   6 - If your variable name is made up of more than one word, use a capital letter for the first letter of every word AFTER the first word. For example, firstName rather than firstname, this is referred to as camel case. You can also use an underscore between each word(you cannot use a dash)
*   Arrays - An array is a special type of variable. It doesn't just store one value; it stores a list of values. 
    -   You should use an array whenever you are working with a LIST or a set of values that are RELATED to each other. 
        *   You do not need to specify how many values it will hold
        *   Using an array is better than creating enough variables for a long list. 
        *   A good example of an array is storing individual items for a shopping list because all of the items are related, and each time you write a new list, the number of items may differ.
        *   Values in an array are separated by a comma.
*   Creating an Array
    -   You create an array and give it a name just like you would any other variable. The values are assigned to the array inside a pair of square brackets, and each value is separated by a comma. You can store a string, a number, and a boolean all in the same array.
        *   Example;
            -   var colors;
                colors = ['white', 'black', 'custom'];
                -   Here the variable is colors and the colors = an array in square brackets
        *   Example 2; an array constructor
            -   var colors = new Array('white',
                                        'black',
                                        'custom');
                -   Here the var = is followed by the var name, then =, then the words new Array, and are listed inside of a parenthesis and separated by a comma.
*   Values in Arrays
    -   Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero(not one).
        *   Each item in an array is given a number called an index. This is used to access items in the array.
            -   i.e.
                var colors;
                colors = ['white',
                            'black',
                            'custom'];
                *   The index for these would be assigned as follows...
                    INDEX   VALUE
                    0       'white'
                    1       'black'
                    2       'custom'
        *   You access items in the array as follows
            var itemThree;
            itemThree = colors[2];
            -   Here you have declared a new var of itemThree, and then identified itemThree using brackets to pick the color with the index of [2]
        *   Each array has a property called length, which holds the number of items in the array. Next we can declare a var of numColors and retrieve the length of our array.
            var numColors;
            numColors = colors.length;
*   Accessing & Changing Values in an Array
    -   Example
        //Create the array
        var colors = ['white',
                       'black',
                       'custom'];

        //Update the third item in the array
        colors[2] = 'beige';

        //Get the element with an id of colors
        var el = document.getElementById('colors');

        //Replace with third item from array
        el.textContent = colors[2];
            *   The first lines of code create an array of colors
            *   The 3rd item on the list is changed from 'custom' to 'beige'
            *   To access a value from an array, after the array name you specify the index number for that value inside square brackets
            *   You can change the value of an item in an array by selecting it and assigning it a new value just as you would any other variable. Using the = sign and the new value for that item
            *   In the last two statements, the newly updated third item in the array is added to the page
            *   If you wanted to write out all of the items in an array, you would use a loop
*   Expressions
    -   An EXPRESSION evaluates into (results in) a single value. Broadly speaking there are two types of expressions.
        *   Expressions that just assign a value to a variable
            -   In order for a variable to be useful, it needs to be given a value. As you have seen, this is done using the assignment operator = (var color = 'beige';)
        *   Expressions that use two or more values to return a single value
            -   You can perform operations on any number of individual values to determine a single value (var area = 3 * 2;) < the value area of this var is 6
*   Operators
    -   Expressions rely on things called operators; they allow programmers to create a single value from one or more values.
        *   Assignment operators - assign a value to a variable
            -   color = 'beige';
            -   the value of color is now beige
        *   Arithmetic operators - Perform basic math
            -   area = 3 * 2;
            -   the value of the area is now 6
        *   String operators - Combine two strings
            -   greeting = 'HI' + 'Molly';
            -   The value of greeting is now Hi Molly
        *   Comparison operators - Compare two values and return true or false
            -   buy = 3 > 5;
            -   The value of buy is false
        *   Logical operators - Combine expressions and return true or false
            -   buy = (5 > 3) && (2 < 4>);
            -   The value of buy is now true
*   Arithmetic Operators
    -   JS contains the following mathematical operators, which you can use with numbers. You may remember some from math class.
        *   Addition + adds one value to another
        *   Subtraction - Subtracts one value from another
        *   Division / Divides two values
        *   Multiplication * Multiplies two values using an asterisk(not the letter x)
        *   Increment ++ Adds one to the current number
        *   Decrement -- Subracts one from the current number
        *   Modulus % Divides two values and returns the remainder
    -   Order of Execution - Several arithmetic operations can be performed in one expression, but it is important to understand how the result will be calculated. Multiplication and division are performed before addition or subtraction. This can affect the number that you expect to see.
        *   i.e
            total = 2 + 4 + 10; the result is left to right... 16!
            total = 2 + 4 * 10; the result is * and / before + and - so.... 42!
        *   To change the order of which the operation occurs, place the operation you want to happen first inside of (). total = (2 + 4) * 10; Now the answer is 60!
*   Using Arithmetic Operators
    -   Example;
        var subtotal = (13 + 1) * 5;    //Subtotal is 70
        var shipping = 0.5 * (13 + 1);  //Shipping is 7
        *   The first couple of lines create two variables: one to store the subtotal of the order, the other to hold the cost of shipping the order; so the variables are named accordingly: subtotal and shipping.
        var total = subtotal + shipping; //Total is 77
        *   On the third line, the total is calculated by adding together these two values.
        var elSub = document.getElementById('subtotal');
        elSub.textContent = subtotal;

        var elShip = document.getElementById('shipping');
        elShip.textContent = shipping;

        var elTotal = document.getElementById('total');
        elTotal.textContent = total;
        *   The remaining six lines of code write the results to the screen.
            -   Notice how the variables represent the numbers so that the numbers did not need to be written into the code.
*   String Operators
    -   There is only one string operator: the + symbol and it is used to join the strings on either side of it.
        *   There are many occasions when you may need to join two or more strings to create a single value. Programmers call the process of joining together two or more strings to create one new string CONCATENATION.
            -   Example;
                *   var firstName = 'Ivy';
                *   var lastName = 'Stone';
                *   var fullName = firstName + lastName; Result is Ivy Stone!
        *   Mixing Numbers and strings together
            -   When you place quotes around a number, it is a string(not a numeric data type), and you cannot perform addition operations on strings.
                *   var cost1 = '7';
                *   var cost2 = '9';
                *   var total = cost1 + cost2;
                    -   The result is a string saying '79'
            -   If you try to add a numeric data type to a string, then the number becomes part of the string, e.g., adding a house number to a street name.
                *   var number = 12;
                *   var street = 'Ivy Road';
                *   var add = number + street;
                    -   The resulting string is '12Ivy Road'
            -   If you try to use any of the other arithmetic operators on  a string, then the value that results is usually a value called NaN. This means not a number.
                *   var score = 'seven';
                *   var score2 = 'nine';
                *   var total = score * score2;
                    -   You would end up with the value NaN.
*   Using String Operators
    -   Example;
        *   var greeting = 'Howdy ';
        *   var name = 'Molly';
            -   The first line creates the variable 'greeting' to store a message for the user, the second line creates the variable 'name', storing the name of the user.
        *   var welcomeMessage = greeting + name + '!';

        *   var el = document.getElementById('greeting');
        *   el.textContent = welcomeMessage;
            -   The personal message is created by concatenating(or joining) these two variables, adding an exclamation mark, and storing them in a new variable called welcomeMessage.
            -   Notice in the greeting variable Howdy, there is a space after Howdy. If the space is omitted, the value of the welcomeMessage would be HowdyMolly!
##  Functions, Methods & Objects
*   Browsers require very detailed instructions about what we want them to do. Therefore, complex scripts can run to hundreds(even thousands) of lines. Programmers use functions, methods, and objects to organize their code.
    -   Functions & Methods - Functions consist of a series of statements that have been grouped together because they perform a specific task. A method is the same as a function, except methods are created inside(and are part of) an object.
    -   Objects - Programmers use objects to create models of the world using data, and that objects are made up of properties and methods. You will learn how to create your own objects using JS.
    -   Built-in Objects - The browser comes with a set of objects that act like a toolkit for creating interactive web pages. You will be introduced to a number of built-in objects, which you will then see used throughout.
*   What is a Function?
    -   Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function(rather than repeating the same set of statements).
        *   Grouping statements that are required to answer a question or to perform a task together helps to organize your code.
        *   Statements in a function aren't always executed when a page loads. Functions offer a way to store steps needed to achieve a task. The script can ask the function to perform all of those tasks as and when they are required. Such as a user clicking on a specific element in the page.
        *   If requiring a function to perform a task later, you need to name your function such as it describes the task being performed when CALLED. Known as CALLING the function.
        *   The steps that the function needs to perform in order to perform its task are packaged in a code block. A code block consists of one or more statements contained within curly braces. There is no semi-colon after closing the curly braces.
        *   Some functions require parameters to achieve a given task, such as height and width when calculating the area of a box.
        *   A RETURN VALUE is the response you get when a function is meant to provide an answer to a question.
        *   Remember that programming languages rely on name/value pairs. The function will have a name followed by a code block containing statements.
        *   You can also have anonumous functions. They do not have a name, so they cannot by called. Instead, they are executed as soon as the interpreter comes across them.
*   Declaring a Function
    -   To create a function, you give it a name and then write the statements nedded to achieve its task inside the curly braces. This is known as a FUNCTION DECLARATION.
        *   Declare a function using the function keyword
        *   Give the function a name(identifier), followed by ()
        *   The statements that perform the task sit in a code block. Inside curly braces.
        *   Example;
            -   function sayHello() {
            -    document.write('Hello');
            -   }
        *   Remember that functions store the code required to perform a specific task, and that the script can ask the function to perform that task whenever needed.
        *   If different parts of a script need to perform the same task, you don't need to repeat the same statements multiple times - you use a function to do it(and reuse the same code).
*   Calling a Function
    -   Having declared the Function, you can then execute all of the statements between the curly braces with just one line of code. This is known as calling the function.
    -   To run the code you use the function name followed by parentheses. You can call the code as many times as you want within the same JS.
    -   The function can store instructions for a specific task.
    -   When you need the script to perform that task, you call the function.
    -   The function executes the code in that code block.
    -   When it has finished, the code continues to run from the point where it was initially called. 
        *   Example
        *   function sayHello() {
            document.write('Hello!');
        }
        // Code before Hello...
        sayHello();
        // Code after hello....
*   Declaring Functions that need information
    -   Sometimes a function needs specific information to perform its task. In such cases, when you declare the function you give it parameters. Inside the function, the parameters act like variables.
    -   If a function needs information to work, you indicate what it needs to know in the parentheses after the function name.
    -   Items that appear inside these parentheses are known as the parameters of the function. Inside the function those words act like variable names.
        *   Example
            -   function getArea(width, height) {
            -       return width * height;
            -   }
        *   This function will calculate and return the area of a rectangle. To do this, it needs the rectangle's width and height. Each time you call the function these values should be different. So when you write a script, you need to note the information the function will require in order to perform its task.
        *   If you look inside the function, the parameter names are used just as you would use variables. Here, the parameter names width and height represent the width and height of the wall. 
        *   This demonstrates how the code can perform a task without knowing the exact details in advance, as long as it has rules it can follow to achieve the task.
*   Calling Functions that need information
    -   When you call a function that has parameters, you specify the values it should use in the parameters that follow its name. The values are called arguments, and they can be provided as values or variables.
        *   Arguments as values - using above example...
            -   getArea(3, 5);
            -   When this function is called, the number 3 will be used for the width and 5 will be used for its height.
        *   Arguments as variables
            -   wallWidth = 3;
            -   wallHeight = 5;
            -   getArea(wallWidth, wallHeight);
            -   You do not have to specify actual values when calling a function - you can use variables in their place. So the above does the same thing.
        *   Parameters vs. Arguments
            -   People often use the terms parameter and argument interchangeably, but there is a subtle difference.
                *   When declaring the function, the width and height given in curly braces act as variables and are PARAMETERS.
                *   When calling the function, the code in curly braces given are real numbers and will be used to perform the calculation. These are ARGUMENTS.
*   Getting a single value out of a Function
    -   Some functions return information to the code that called them. For example, when they perform a calculation, they return the result.
        *   Example;
            -   function calculateArea(width, height) {
            -       let area = width * height;
            -       return area;
            -   }
            -   let wallOne = calculateArea(3, 5);
            -   let wallTwo = calculateArea(8, 5);
                *   This calculateArea() function returns the area of a rectangle to the code that called it. Inside the function, a variable called area is created. It holds the calculated area of the box. The return keyword is used to return a value to the code that called the function.
                *   This also demonstrates how the same function can be used to perform the same steps with different values.
*   Getting multiple values out of a Function
    -   Functions can return more than one value using an array. For example, this function calculates the area and volume of a box.
        *   Example;
            -   function getSize(width, height, depth) {
            -       let area = width * height;
            -       let volume = width * height * depth;
            -       let sizes = [area, volume];
            -       return sizes;
            -   }
            -   let areaOne = getSize(3, 2, 3)[0];
            -   let volumeOne = getSize(3, 2, 3)[1];
                *   First, getSize function is declared, the area of the box is calculated and stored inside area variable. The volume is calculated and stored inside volume variable. Both are then placed inside the array sizes. The array is then returned to the code that called the getSizes( function, allowing the values to be used)
                *   The areaOne variable holds the area of a box that is 3 * 2. The area is the first value in the sizes array. The volumeOne variable holds the volume of a box that is 3 * 2 * 3. The volume is the second variable in the sizes array.
*   Anonymous Functions & Function Expressions
    -   Expressions produce a value. They can be used where values are expected. If a function is placed where a browser expects to see an expression, or as an argument to a function, then it  gets treated as an expression.
    -   Function Declaration - A function declaration creates a function that you can call later in your code. It is the type of function you have seen so far in these examples.
        *   Example
        *   function area(width, height) {
        *       return width * height;
        *   };
        *   let size = area(3, 4);
            -   The function above is named area() and can be called using its name
        *   Interpreters always look for variables and function declarations before going through each section of the script, line-by-line. This means that a function created with a Function declaration can be called before is has even been declared.
    -   Function Expression - If you put a function where the interpreter would wxpect to see an expression, then it is treated as an expression, and it is known as a functino expression. In function expressions, the name is usually omitted. A function with no name is called an anonymous function.
        *   Example
        *   let area = function(width, height) {
        *       return width * height;
        *   };
        *   let size = area(3, 4);
            -   This function is stored in a variable named area. It can be called like any function, with a function declaration
        *   In a function expression, the function is not processed until the interpreter gets to that statement. This means you cannot call this function before the interpreter has discovered it. It also means that any code that appears up to that point could potentially alter what goes on inside this function.
*   Immediately invoked Function Expressions
    -   This way of writing a functino is used in several different situations. Often functions are used to ensure that the variable names do not conflict with each other (especially if the page uses more than one script).
    -   Immediately Invoked Function Expressions(IIFE) - Pronounced "iffy", these functions are not given a name. Instead, they are executed once as the interpreter comes across them.
        *   Example
        *    let area = (function() {
        *    let width = 3;
        *    let height = 2;
        *    return width * height;
        *   }())
            -   Above, the variable called area will hold the value returned from the function(rather than storing the function itself so that it can be called later)
            -   The final parentheses after the closing curly brace of the bode block tell the interpreter to call the function immediately. The grouping operators are parentheses there to ensure the interpreter treats this as an expression
    -   When to use anonymous functions and IIFES - You will see many ways in which anonymous functino expressions and IIFEs are used throughout these notes.
    -   They are used for code that only needs to run code within a task, rather than repeatedly being called by other parts of the script. i.e...
        *   As an argument when a function is called (to calculate a value for that function)
        *   To assign the value of a property to an object
        *   In event handlers and listeners to perform a task when an event occurs
        *   To prevent conflicts between two scripts that might use the same variable names
    -   IFFEs are commonly used as a wrapper around a set of code. Any variables declared within that anonymous function are effectively protected from variables in other scripts that might have the same name. This is due to a concept called scope, which you meet on the next seciont. It is also a very popular technique with jQuery.
*   Variable Scope
    -   The location where you declare a variable will affect where it can be used within your code. If you declare it within a function, it can only be used within that function. This is known as the variable's scope.
    -   Local Variables - When a variable is created inside a function using the let keyword, it can only be used in that function. It is called a local variable or function-level variable. It is said to have local scope or function-level scope. It cannot be accessed outside of the function in which it was declared.
        *   The interpreter creates local variables when the function is run, and removes them as soon as the function has finished its task. This means...
            -   If the function runs twice, the variable can have different values each time
            -   Two different functions can use variables with the same name without any kind of conflict
    -   Global Variables - If you create a variable outside of a function, then it can be used anywhere within the script. It is called a global variable and has global scope.
        *   Global variables are stored in memory for as long as the web page is loaded into the web browser. This means they take up more memory than local variables, and it also increases the risk of naming conflicts. For these reasons you should use local variables wherever possible.
            -   If you forget to declare a variable using the let keyword, the variable will work, but it will be treated as a global variable(this is considered bad practice).
    -   Example
    -   function getArea(width, height) {
    -       let area = width * height;
    -       return area;
    -   }
    -   let wallSize = getArea(3, 2);
    -   document.write(wallSize);
        *   area = Local or Function-level scope
        *   wallSize = Global scope
*   How Memory & Variables work
    -   Global variables use more memory. The browser has to remember them for as long as the web page using them is loaded. Loval variables are only remembered during the period of time that a function is being executed.
    -   Creating the variables in code - Each variable that you declare takes up memory. The more variables a browser has to remember, the more memory your script requires to run. Scripts that require a lot of memory can perform slower, which in turn makes your web page take longer to respond to the user.
    -   Naming Collisions - You might think you would avoid naming collisions; after all you know which variables you are using. But many sites use scripts written by several people. If an HTML page uses two JS files, and both have a global variable with the same name, it can cause errors.
        *   Remember, variables in global scope that share a name will have conflicts, while variables in local scope that share a name will not.
*   What is an Object?
    -   Objects group together a set of variables and functions to create a model of something you would recognize from the real world. In an object, variables and functions take on new names.
        *   In an object: variables become known as properties. If a variable is part of an object, it is called a property. Properties tell us about the object, such as the name of a hotel or the number of rooms it has. Each individual hotel might have a different name and a different number of rooms.
        *   In an object: functions become known as methods. If a function is part of an object, it is called a method. Methods represent tasks that are associated with the object. For example, you can check how many rooms are available by subtracting the number of booked rooms from the total number of rooms.
    -   Example
    -   let hotel = {
    -   name: 'Quay',
    -   rooms: 40,
    -   booked: 25,
    -   gym: true,
    -   roomTypes: ['twin', 'double', 'suite'],
    -   checkAvailability: function() {
    -       return this.rooms - this.booked;
    -       }
    -   };
        *   This object represents a hotel. It has five properties and one method. The object is in curly braces. It is stored in a variable called hotel.
    -   Like variables and named functions, properties and methods have a name and a value. In an object, that name is called a KEY.
    -   An object cannot have two keys with the same name. This is because keys are used to access their corresponding values.
    -   The value of a property can be a string, nember, Boolean, array, or even another object. The value of a mehtod is always a function.
    -   In the example above the hotel object contains the following key/value pairs:
        *   Properties:
            -   Key;
                *   name
                *   rooms
                *   booked
                *   gym
                *   roomTypes
            -   Value;
                *   string
                *   number
                *   number
                *   Boolean
                *   array
        *   Methods:
            -   Key;
                *   chechAvailability
            -   Value;
                *   function
                    -   This is just one of the ways you can create an object
    -   Programmers use a lot of name/value pairs:
        *   HTML uses attributes names and values.
        *   CSS uses property names and values.
        *   In JS
            -   Variables have a name and you can assign them a value of a string, number, or Boolean
            -   Arrays have a name and a group of values. (Each item in an array is a name/value pair because it has an index number and a value.)
            -   Named functions have a name and value that is a set of statements to run if the function is called.
            -   Objects consist of a set of name/value pairs(but the names are referred to as keys).
*   Creating an Object: Literal Notation
    -   Literal notation is the easiest and most popular way to create objects. Though there are several.
        *   Example
        *   let hotel = {
        *   name: 'Quay',
        *   rooms: 40,
        *   booked: 25,
        *   checkAvailability: function() {
        *       return this.rooms - this.bookd;
        *       }
        *   }
            -   The object is the curly braces and their contents. The object is stored in a variable called hotel, so you would refer to it as the hotel object.
            -   Separate each key from its value using a colon. Separate each property and method with a comma(but not after the last value).
            -   In the checkAvailability() method, the this keyword is used to indicate that it is using the rooms and booked properties of this object.
            -   When setting properties, treat the values like you would do for variables: strings live in quotes and arrays live in square brackets.
*   Accessing an Object & Dot Notation
    -   You access the properties or methods of an object using dot notation. You can also access properties using square brackets.
        *   Example
        *   let hotelName = hotel.name;
        *   let roomsFree = hotel.checkAvailability();
            -   To access a property or method of an object you use the name of the object, followed by a period, then the name of the property or method you want to access. This is known as dot notation.
            -   The period is known as the member operator. The property or method on its right is a member of the object on its left. Here, two variables are created to hold the hotel name and number of vacant rooms.
        *   You can also access the properties of an object (but not its methods) using square bracket syntax. This time the object name is followed by square brackets, and the property name is inside them.
        *   let hotelName = hotel['name'];
            -   This notation is most commonly used when:
                *   The name of the property is a number (technically allowed, but should generally be avoided)
                *   A variable is being used in place of the property name (you will see this technique used later)
* Example - Creating Objects using Literal Notation
    -   let hotel = {
    -   name: 'Quay',
    -   rooms: 40,
    -   booked: 25,
    -   checkAvailability: function() {
    -       return this.rooms - this.booked;
    -       }
    -   };
    -   let elName = document.getElementById('hotelName');
    -   elName.textContent = hotel.name;
    -   let elRooms = document.getElementById('rooms');
    -   elRooms.textContent = hotel.checkAvailability();
        *   This example starts by creating an object using literal notation.
        *   This object is called hotel which represents a hotel called Quay with 40 rooms, 25 of which have been booked.
        *   Next, the content of the page is updated with data from this object. It shows the name of the hotel by accessing the object's name property and the number of vacant rooms using the checkAvailability() method.
        *   To access a property of this object, the object name is followed by a dot (the period symbol) and the name of the property that you want.
        *   Similarly, to use the method, you can use the object name followed by the method name. hotel.checkAvailability().
        *   If the method needs parameters, you can supply them in the parentheses just like you can pass arguments to a function.
*   Creating an Object: Constructor Notation
    -   The new keyword and the object constructor create a blank object. You can then add properties and methods to the object.
    -   Example
    -   let hotel = new Object();
    -   hotel.name = 'Quay';
    -   hotel.rooms = 40;
    -   hotel.booked = 25;
    -   hotel.checkAvailability = function() {
    -       return this.rooms - this.booked;
    -   };
        *   First, you create a new object using a combination of the new keyword and the object() constructor function. This function is part of the JS language and is used to create objects.
        *   Next, having created the blank object, you can add properties and methods to it using dot notation. Each statement that adds a property or method should end with a semicolon.
        *   You can use this syntax to add properties and methods to any object you have created, no matter which notation you used to create it.
        *   To create an empty object using literal notation you use: let hotel = {}. The curly brackets create an empty object.
*   Updating an Object
    -   To update the value of properties, use dot notation or square brackets. They work on objects created using literal or constructor notation. To delete a property, use the delete keyword.
        *   Dot notation;
            -   hotel.name = 'park';
                *   Same method as adding properties to any object but just give it a different value. From 'Quay' to 'Park'
        *   Square bracket;
            -   hotel['name'] = 'Park';
                *   Surrounding property with square brackets indicates the property you are changing.
        *   Deleting a property;
            -   delete hotel.name;
                *   To delete a property just use the keyword delete followed by the object name and property name.
                *   If you just want to clear the value of a property, you could set it to a blank string
                    -   hotel.name = '';
*   Creating many Objects: Constructor Notation
    -   Sometimes you will want several objects to represent similar things. Object Constructors can use a function as a template for creating Objects. First, create the template with the object's properties and methods.
    -   Example
    -   function Hotel(name, rooms, booked) {
    -   this.name = name;
    -   this.rooms = rooms;
    -   this.booked = booked;
    -   this.checkAvailability = function() {
            return this.rooms - this.booked;
    -       };
    -   }
        *   A function called Hotel will be ised as a template for creating new objects that represent hotels. Like all functions, it contains statements. In this case, they add properties or methods to the object.
        *   The function has three parameters. Each one sets the value of a property in the object. The methods will be the same for each object created using this function.
        *   The THIS keyword is used instead of the object name to indicate that the property or method belongs to the object that THIS function creates.
        *   Each statement that creates a new property or method for this object ends in a semicolon, not a comma, which is used in the literal syntax.
        *   The name of a constructor function usually begins with a capital letter, unlike other functions, which tend to begin with a lowercase character.
        *   The uppercase letter is supposed to help remind developers to use the new keyword when they create an object using that function.
    -   You create instances of the object using the constructor function. The new keyword followed by a call to the function creates a new object. The properties of each object are given as arguments to the function.
    -   Example;
    -   let quayHotel = new Hotel('Quay', 40, 25);
    -   let parkHotel = new Hotel('Park', 120, 77);
        *   The first object is called quatHotel. Its name is 'Quay', has 40 rooms, 25 of which are booked.
        *   The second object is called parkHotel. Its name is 'Park', has 120 rooms, 77 of which are booked.
        *   Even when many objects are created using the same constructor function, the methods stay the same because they access, update, or perform a calculation on the data stored in the properties.
        *   You might use this technique if your script contains a very complex object that needs to be available but might not be used. The object is defined in the function, but it is only created if it is needed.
*   Creating Objects using Constructor Syntax
    -   Example;
    -   let hotel = new Object();
    -   hotel.name = 'Park';
    -   hotel.rooms = 120;
    -   hotel.booked = 77;
    -   hotel.checkAvailability = function() {
    -       return this.rooms - this.booked;
    -       };
    -   let elName = document.getElementById('hotelName');
    -   elName.textContent = hotel.name;
    -   let elRooms = document.getElementById('rooms');
    -   elRooms.textContent = hotel.checkAvailability();
        *   Here an empty object called hotel is created using the constructor function
        *   Once it has been created, three properties and a method are then assigned to the object
        *   If the object already had any of these properties, this would overwrite the values in those properties
        *   To access a property of this object, you can use dot notation, just as you can with any object
        *   For example, to get the hotel's name you could use hotel.name
        *   Similarly, to use the method, you can use the object name followed by the method name: hotel.checkAvailability()
*   Create & Access Objects Constructor Notation
    -   Example
    -   function Hotel(name, rooms, booked) {
    -       this.name = name;
    -       this.rooms = rooms;
    -       this.booked = booked;
    -       this.checkAvailability = function() {
    -           return this.rooms - this.booked;
    -       };
    -   }
    -   let quayHotel = new Hotel('Quay', 40, 25);
    -   let parkHotel = new Hotel('Park', 120, 77);
    -   let details1 = quayHotel.name + ' rooms: ';
    -       details1 += quayHotel.checkAvailability();
    -   let elHotel1 = document.getElementById(Hotel1);
    -   elHotel1.textContent = details1;
    -   let details2 = parkHotel.name + ' rooms: ';
    -       details2 += parkHotel.checkAvailability();
    -   let elHotel2 = document.getElementById('hotel2');
    -   elHotel2.textContent = details2;
        *   To get a better idea of why you might want to create multiple objects on the same page, here is an example that shows room availability in two hotels
        *   First, a constructor function defines a template for the hotels. Next, two different instances of this type of hotel object are created. The first represents a hotel called Quay and the second a hotel called Park.
        *   Having created instances of these objects, you can then access their properties and methods using the same dot notation that you use with all other objects.
        *   In this example, data from both objects is accessed and written into the page. The HTML for this example changes to accommodate the extra hotel. 
        *   For each hotel, a variable is created to hold the hotel name, followed by space, and the word rooms.
        *   The line after it adds to that variable with the number of available rooms in that hotel.
        *   The += operator is used to add content to an existing variable.
*   Adding & Removing Properties
    -   Once you've created an object using literal or constructor notation, you can add new properties to it. You do this using the dot notation.
    -   In the following example we use dot notation to add details on the hotel facilities using Booleans.
        *   let hotel = {
        *   name: 'Park',
        *   rooms: 120,
        *   booked: 77
        *   };
        *   hotel.gym = true;
        *   hotel.pool = false;
        *   delete hotel.booked;
    -   Having added these properties to the object, you can access them just like any of the objects other properties. Here, they update the value of the class attribute on their respective elements to show either a check mark or a cross mark.
    -   To delete a property, you use the keyword delete, and then use dot notation to identify the property or method you want to remove from the object.
    -   In this case, the booked Property is removed from the object.
        *   If an object is created using a constructor function, this syntax only adds or removes the properties from the one instance of the object, not all objects created with that function.
*   Recap: PG 113.
*   The keyword THIS
    -   The keyword this is commonly used inside functions and objects. Where the function is declared alters what this means. It always refers to one object, usually the object in which the function operates.
    -   A Function in global scope - when a function is created at the top level of a script, that is, not inside another object or function, then it is in the global scope/context.
        *   The default object in this context is the window object, so when this is used inside a function in the global context it refers to the window object.
        *   example;
        *   function windowSize() {
        *   let width = this.innerWidth;
        *   let height = this.innerHeight;
        *   return [height, width];
        *   }
            -   Under the hood, the this keyword is a reference to the object that the function is created inside.
    -   Global Variables - all global variables also become properties of the window object, so when a function is in the global context, you can access global variables using the window object, as well as its other properties.
        *   example;
        *   let width = 600;
        *   let shape = {width: 300};
        *   
        *   let showWidth = function() {
        *   document.write(this.width);
        *   };
        *   
        *   showWidth();
            -   Here, the showWidth() function is in global scope, and this.width refers to the width variable.
            -   Here, the function would write a value of 600 into the page, using the document object's write() method.
    -   A Method of an Object - When a function is defined inside an object, it becomes a method. In a method, this refers to the containing object.
        *   example;
        *   let shape = {
        *   width: 600,
        *   height: 400,
        *   getArea: function() {
        *       return this.width * this.height;
        *       }
        *   };
            -   here, the getArea() method appears inside the shape object, so this refers to the shape object it is contained in.
            -   because the this keyword here refers to the shape object, it would be the same as writing:
                *   return shape.width * shape.height;
            -   if you were creating several objects using an object constructor and each shape had different dimensions, this would refer to the individual instance of the new object you are creating. When you called getArea(), it would calculate the dimensions of that particular instance of the object.
    -   Function Expressions as Method - If a named functino has been defined in global scope, and it is then used as a method of an object, this refers to the object it is contained within.
        *   example;
        *   let width = 600;
        *   let shape = {width: 300};
        *   
        *   let showWidth = function() {
        *       document.write(this.width) ;
        *   };
        *   
        *   shape.getWidth = showWidth;
        *   shape.getWidth();
            -   here, shows the same showWidth() function expression as the one above it, but its assigned as a method of an object.
            -   The last but one line indicates that the showWidth() function is used as a method of the shape object. THe method is given a different anem: getWidth().
            -   When the getWidth() method is called, even though it uses the showWidth() function, this now refers to the shape object, not the global context and this.width refers to the width property of the shape object. So it writes a value of 300 to the page.
*   Recap - storing data on PG 116-117
*   Arrays are Objects
    -   Arrays are actually a special type of object. They hold a related set of key/value pairs(like all objects), but the key for each value is its index number.
        *   so an object holds its values in properties and arrays hold theirs in index numbers.
*   Arrays of Objets & Objects in Arrays
    -   You can combine arrays and objects to create complex data structures: Arrays can store a series of objects and remember their order. Objects can also hold arrays as values of their properties.
        *   Arrays in an Object - the property of any object can hold an array. 
        *   Objects in Arrays - The value of any element in an array can be an object written using the object literal syntax.
*   What are Built in Objects?
    -   Browsers come with a set of built-in objects that represent things like the browser window and the current web page shown in that window. These built-in objects act like a toolkit for creating interactive web pages.
        *   Browser Object Model - Contains objects that represent the current browser window or tab. It contains objects that model things like browser history and the device's screen.
        *   Document Object Model - Uses objects to create a representation of the current page. It creates a new object for each element and each individual section of text within the page.
        *   Global Javascript Objects - Represent things that the JS language needs to create a model of. i.e. There is an object that deals only with dates and time.
    -   Built in objects contain functionality commonly needed by many scripts. These objects are available as soon as a web page is loaded into your browser and help you get a wide range of information.
    -   An object model is a group of objects, each of which represent related things from the real world. Together they form a model of something larger.
    -   It is possible for the property of an object to be another object, also known as child object.
*   3 Groups of Built-In Objects
    -   Browser Object Model - The browser object model creates a model of the browser tab or window.
        *   The window objects print() method will cause the browser's print dialogue box to be shown: window.print();
        *   The screen object's width property will let you find the width of the device's screen in pixels: window.screen.width;
    -   Document Object Model - The document object model creates a model of the current web page.
        *   The document object's getElementById() method gets an element by the value of its id attribute: document.getElementById('one');
        *   The document object's lastModified property will tell you the date that the page was last updated: document.lastModified;
    -   Global JavaScript Objects - The global objects do not form a single model. They are a groupd of individual objects that relate to different parts of the JavaScript language.
        *   The String object's toUpperCase() method makes all letters in the following variable uppercase: hotel.toUpperCase();
        *   The Math object's PI property will return the value of pi: Math.PI();
    -   Using built-in objects: The 3 sets of built-in objects each offer a different range of tools that help you write scripts for web pages.
*   The Browser Object Model: The Window Object
    -   The window object represents the current browser window or tab. It is the topmost object in the browser object model, and it contains other objects that tell you about the browser.
    -   Here are selections of the window object's properties and methods. You can also see some properties of the screen and history objects which are children of the window object.
        *   window.innerHeight - Height of window in px
        *   window.innerWidth - Width of window in px
        *   window.pageXOffset - Distance document has been scrolled horizontally in px
        *   window.screenX - x-coordinate of pointer, relative to top left corner of screen in px
        *   window.screenY - y-coordinate of pointer, relative to top left corner of screen
        *   window.location - Current URL of window object or local file path
        *   window.document - Reference to document object, which is used to represent the current page contained in window
        *   window.history - Reference to history object for browser window or tab, which contains details of the pages that have been viewed in that window or tab
        *   window.history.length - Number of items in history object for browser window or tab
        *   window.screen - Reference to screen object
        *   window.screen.width - Accesses screen object and finds value of its width property in px
        *   window.screen.height - Accesses screen object and finds calue of its height property in px
        *   window.alert() - Creates dialog box with message
        *   window.open() - Opens new browser window with URL specified as parameter. Won't work if browser has pop-up blocking software
        *   window.print() - Tells browser that user wants to print contents of current page, acts like user has clicked a print option in the browser's user interface
*   Using the Browser Object Model
    -   Example
    -   let msg = '<h2>browser window</h2><p>width: ' + window.innerWidth + '</p>';
    -   msg += '<p>height: ' + window.innerHeight + '</p>';
    -   msg += '<h2>history</h2><p>items: ' + window.history.length + '</p>';
    -   msg += '<h2>screen</h2><p>width: ' + window.screen.width + '</p>;
    -   msg += '<p>height: ' + window.screen.height + '</p>';
    -   let el = document.getElementById('info');
    -   el.innerHTML = msg;
    -   alert('Current page: ' + window.location);
        *   Here, data about the browser is collected from the window object and its children, stored in the msg variable, and shown in the page. The += operator adds data onto the end of the msg variable.
        *   1. Two of the window object's properties, innerWidth and innerHeight, show width and height of the browser window. 
        *   2. Child objects are stored as properties of their parents objects. So dot notation is used to access them, like you access any other property of that object. In turn, to access the properties of the cheld object, another dot is used between the cheld object's name and its properties, i.e. window.history.length
        *   3. The element whose id attribute has a value of info is selected, and the message that has been built up to this point is written into the page. 
        *   4. The window object's alert() method is used to create a dialog box shown on top of the page. It is known as an alert box. Although this is a mehtod of the window object, you may see it used on its own as shown here because the window object is treated as the default object if none is specified. Historically the alert() method was used to display warnings to users. These days there are better ways to provide feedback
*   The Document Object Model: The Document Object
    -   The topmost object in the DOM is the document object. It represents the web page loaded into the current browser window or tab. You meet its child objects later.
    -   Here are some properties of the document object which tell you about the current page.
        *   document.title - title of current doc
        *   document.lastModified - last time doc was updated
        *   document.URL - returns string containing URL of doc
        *   document.domain - returns domain of current doc
    -   The DOM is vital to accessing and amending the contents of the current page. Following are the methods used to select or update content of a page.
        *   document.write() - Writes text to document
        *   document.getElementById() - returns element, if there is an element with the value of the id attribute that matches
        *   document.querySelectorA() - returns list of elements that match CSS selector, which is specified as a parameter
        *   document.createElement() - Creates new element
        *   document.createTextNode() - Creates new text node
*   Using the DOM
    -   example
    -   let msg - '<p><b>page title: </b>' + document.title + '<br />';
    -   msg += '<b>page address: </b>' + document.URL + <br />';
    -   msg += '<b>last modified: </b>' + document.lastModified + '</p>;
    -   
    -   let el = document.getElementById('footer');
    -   el.innerHTML = msg;
        *   This example gets information about the page, and then adds that information to the footer.
        *   1. The details about the page are collected from properties of the document object. These details are stored inside a variable called msg, along with HTML markup to display the information. Again, the += operator adds the new value onto the existing content of the msg variable.
        *   2. You have seen the document object's getElementById() method in several examples so far. It selects an element from the page using the value of its id attribute. 
*   Global Objects: String Object
    -   Whenever you have a value that is a string, you can use the properties and mehtods of the string object on that value. This example stores the phrase "Home sweet home" in a variable
    -   Example;
    -   let saying = 'Home sweet home';
    -   The following properties and methods are often used to work with text stored in variables or objects.
    -   Property:   Descripting:    Example:    Result:
    -   length - Returns number of characters in the string - saying.length; - 16
    -   toUpperCase() - Changes strings to uppercase characters - saying.toUpperCase(); - 'HOME SWEET HOME'
    -   toLowerCase() - Changes strings to lowercase characters - saying.toLowerCase(); - 'home sweet home'
    -   charAt() - Takes an index number as a parameter, and returns the character found at that position - saying.charAt(12); - 'o'
    -   indexOf() - Returns index number of the first time a character or set of characters is found in a string - saying.indexOf('ee'); - 7
    -   lastIndexOf() - Returns index number of last time a character or set of characters is found within a string - saying.lastIndexOf('e'); - 14
    -   substring() - Returns characters found between two index #'s where the character for the first index # is included & the character for the last index # is not included - saying.substring(8,14); - 'et hom'
    -   split() - When a character is specified, it splits the string each time it is found, then stores each individual part in an array - saying.split(' '); - ['Home', 'sweet', 'home', '']
    -   trim() - Removes whitespace from start and end of string - saying.trim(); - 'Home sweet home'
    -   replace() - Takes one value that should be found, and another to replace it, only replaces the first match it finds - saying.replace('me','w'); - 'How sweet home'
        *   Each character in a string is automatically given a number, called an index number. Index numbers always start at zero and not one, just like items in an array.
*   Working with strings
    -   Example;
    -   let saying = 'Home sweet home ';
    -   let msg = '<h2>length</h2><p>' + saying.length + '</p>';
    -   msg += '<h2>uppercase</h2><p>' + saying.toUpperCase() + '</p>';
    -   msg += '<h2>lowercase</h2><p>' + saying.toLowerCase() + '</p>';
    -   msg += '<h2>character index: 12</h2><p>' + saying.charAt(12) + '</p>';
    -   msg += '<h2>first ee</h2><p>' + saying.indexOf('ee') + '</p>';
    -   msg += '<h2>last e</h2><p>' + saying.lastIndexOf('e') + '</p>';
    -   msg += '<h2>character index 8-14</h2><p>' + saying.substring(8, 14) + '</p>';
    -   msg += '<h2>replace</h2><p>' + saying.replace('me', 'w') + '</p>';
    -   
    -   let el = document.getElementById('info');
    -   el.innerHTML = msg;
        *   This example demonstrates the length property and many of the string object's methods shown above.
        *   1. This example starts by storing the phrase "Home sweet home " in a variable called saying.
        *   2. The next line tells you how many characters are in the string using the length property of the string object and stores the result in a variable called msg.
        *   3. This is followed by examples showing several of the string object's methods. The name of the variable saying is followed by a dot, then the property or method that is being demonstrated in the same way that the other objects in this chapter used the dot notation to indicate a property or method of an object.
        *   4. The final two lines select the element with an id attribute whose value is info and then add the value of the msg variable inside that element.
*   Data Types Revisited
    -   In JavaScript there are six data types: Five of them are described as simple or primitive data types. The sixth is the object and is referred to as a complex data type.
    -   Simple or Primitive Data Types;
        *   String
        *   Number
        *   Boolean
        *   Undefined - a variable that has been declared, but no value has been assigned to it yet
        *   Null - a variable with no value - it may have had one at some point, but no longer has a value
            -   As you have seen, both the web browser and the current document can be modeled using objects and objects can have methods and properties. But it can be confusing to discover that a simple value like a string or a number or a Boolean can have methods and properties. Under the hood, JS treats every variable as an object in its own right.
            -   String: if a variable, or the property of an object contains a string, you can use the properties and methods of the string object on it.
            -   Number: If a variable, or property of an object stores a number, you can use the properties and methods of the number object on it.
            -   Boolean: There is a Boolean object. It is rarely used.
                *   Undefined and null values do note have objects
    -   Complex Data Types;
        *   Object
            -   Under the hood, arrays and functions are considered types of objects.
            -   Arrays are Objects; an array is a set of key/value pairs just like any other object. But you do not specify the name in the key/value pair of an array - it is an index number. Like other objects, arrays have properties and methods. Arrays have a property called length, which tells you how many items are in that array. There is also a set of methods you can use with any array to add items to it, remove items from it, or reorder its contents.
            -   Functions are Objects; Technically, but they have an additional feature: they are callable, which means you can tell the interpreter when you want to execute the statements that it contains.
*   Global Objects: Number Objects - Whenever you have a value that is a number, you can use the methods and properties of the Number object on it. 
    -   These methods are helpful when dealing with a range of applications from financial calculations to animations. Many calculations involving currency such as tax rates will need to be rounded to a specific number of decimal places. Or, in an animation, you might want to specify that cerain elements should be evenly spaced out across the page.
        *   Method  -   Description
        *   isNaN() - Checks if the value is not a number
        *   toFixed() - Rounds to specified number of decimal places, returns a string
        *   toPrecision() - Rounds to total number of places, returns a string
        *   toExponential() - Returns a string representing the number in exponential notation
    -   Commonly used terms;
        *   An INTEGER is a whole number not a fraction.
        *   A REAL NUMBER is a number that can contain a fractional part.
        *   A FLOATING POINT NUMBER is a real number that uses decimals to represent a fraction. The term floating point refers to the decimal point.
        *   SCIENTIFIC NOTATION is a way of writing numbers that are too big or too small to be conveniently written in decimal form. For example: 3,750,000,000 can be represented as 3.75 * 10 to the 9th power or 3.75e+12.
*   Working with Decimal Numbers
    -   Example;
    -   let originalNumber = 10.23456;
    -   let msg = '<h2>original number</h2><p>' + originalNumber + '</p>';
    -   msg += '<h2>3 decimal places</h2><p>' + originalNumber.toFixed(3); + '</p>';
    -   msg += '<h2>3 digits</h2><p>' + originalNumber.toPrecision(3) + '</p>';
    -   let el = document.getElementById('info');
    -   el.innerHTML = msg;
        *   As with string object, the properties and methods of the Number object can be used with any value that is a number.
        *   1. In this example, a number is stored in a variable valled originalNumber, and it is then rounded up or down using two different techniques. In both cases, you need to indicate how many digits you want to round to. This is provided as a parameter in the parentheses for that method.
        *   2. originalNumber.toFixed(3) will round the number stored in the variable originalNumber to three decimals places. The number of decimal places is specified in the parentheses. It will return the number as a string. It returns a string because fractions cannot always be accurately represented using floating point numbers.
        *   3. toPrecision(3) uses the number in parantheses to indicate the total number of digits the number should have. It will also return the number as a string. It may return a scientific notation if there are more digits than the specified number of positions.
*   Global Objects: Math Object - The Math Object has properties and mehtods for mathematical constants and functions.
    -   Method - Description
    -   Math.PI - Returns pi, appx; 3.14159265359
    -   Math.round() - Rounds number to the nearest integer
    -   Math.sqrt(n) - Returns square root of positive number, e.g., Math.sqrt(9) returns 3
    -   Math.ceil() - Rounds number up to the nearest integer
    -   Math.floor() - Rounds number down to the nearest integer
    -   Math.random() - Generates a random number between 0, inclusive, and 1, not inclusive
        *   Because it is known as a global object, you can just use the name of the Math object followed by the property or method you want to access.
        *   Typically you will then store the resulting number in a variable. This object also has many trigonometric functions such as sin(), cos(), and tan().
        *   The trigonometric functions return angles in radians which can then be converted into degrees if you divide the number by (pi/180).
*   Math Object to create random numbers
    -   Example;
    -   let randomNum = Math.floor((Math.random() * 10) + 1;
    -   
    -   let el = document.getElementById('info');
    -   el.innerHTML = '<h2>random number</h2><p>' + randomNum + '</p>';
        *   This example is designed to generate a random whole number between 1 and 10
        *   The Math objects random() method generates a random number between 0 and 1 with many decimal places
        *   To get a random whole number between 1 and 10, you need to multiply the randomly generated number by 10.
        *   This number will still have many decimal places, so you can round it down to the nearest integer.
        *   The floor() method is used to specifically round a number down rather than up or down.
        *   This will give you a value between 0 and 9. You then add 1 to make it a number between 1 and 10.
        *   If you used the round() method instead of the floor() method, the numbers 1 and 10 would be chosen around half of the number of times that 2-9 would be chosen.
        *   Anything between 1.5 and 1.999 would get rounded up to 2, and anything between 9 and 9.5 would be rounded down to 9.
        *   Using the floor() method ensures that the number is always rounded down to the neaerest integer, and you can then add 1 to ensure the number is between 1 and 10.
*   Creating an Instance of the Date Object
    -   In order to work with dates, you create an instance of the date object. You can then specify the time and date that you want it to represent.
    -   To create a date object, use the Date() object constructor. The syntax is the same for creating any object with a constructor function. You can use it to create more than one Date object.
    -   By default, when you create a date object it will hold today's date and the current time. If you want it to store another date, you must explicitly specify the date and time you want it to hold.
        *   let today = new Date();
    -   You can think of the above as creating a variable called today that holds a number. This is because in JS, dates are stored as a number: specifically the number of milliseconds since midnight on january 1, 1970.
    -   Note that the current date/time is determined by the computer's clock. If the user is in a different time zone than you, their day may start earlier or later than yours. Also, if the internal clock on their computer has the wrong date or time, the Date object could reflect this by holding the wrong date.
    -   The Date() object constructor tells the JS interpreter that this variable is a date, and this in turn allows you to use the Date object's methods to set and retrieve dates and times from this Date object.
    -   You can set the date and/or time using any of the following formats or methods shown on the right.
        *   examples;
        *   let dob = new Date(1996, 11, 26, 15, 45, 55);
        *   let dob = new Date('Dec 26, 1996 15:45:55');
        *   let dob = new Date(1996, 11, 26);
*   Global Objects: Date Object & Time - Once you have created a date object, the following methods let you set and retrieve the time and date that it represents.
    -   Method - Description
    -   getDate() setDate() - Returns/sets the day of the month(1-31)
    -   getDay() - Returns the day of the week(0-6)
    -   getFullYear() setFullYear() - Returns/sets the year(4digits)
    -   getHours() setHours() - Returns/sets the hour(0-23)
    -   getMilliseconds() setMilliseconds() - Returns/sets the milliseconds(0-99)
    -   getMinutes() setMinutes() - Returns/sets the minutes(0-59)
    -   getMonth() setMonth() - Returns/sets the month(0-11)
    -   getSeconds() setSeconds() - Returns/sets the seconds(0-59)
    -   getTime() setTime() - Number of milliseconds since january 1, 1970, 00:00:00 UTC, coordinated universal time, and a negative number for any time before
    -   getTimeZoneOffset() - Returns time zone offset in mins for locale
    -   toDateString() - Returns "date" as a human-readable string
    -   toTimeString() - Returns "time" as a human-readable string
    -   toString() - Returns a string representing the specified date
        *   The toDateString() method will display the date in the following format: Wed Apr 16 1975.
        *   If you want to display the date in another way, you can construct a different date format using the individual methods listed above to represent the individual parts: day, date, month, year.
        *   toTimeString() shows the time. Several programming languages specify dates in milliseconds since midnight on Jan 1, 1970. This is known as Unix time.
        *   A visitor's location may affect time zones and language spoken. Programmers use the term locale to refer to this kind of location-based information.
        *   The Date object does not store the names of days or months as they vary between languages. Instead, it uses a number from 0 to 6 for the days of the week and 0 to 11 for the months.
        *   To show their names, you need to create an array to hold them.
*   Creating a Date Object
    -   Example;
    -   let today = new Date();
    -   let year = today.getFullYear();
    -   
    -   let el = document.getElementById('footer');
    -   el.innerHTML = '<p>Copyright &copy;' + year + '</p>;
        *   1. In this example, a new Date object is created using Date() object constructor it is called today. If you do not specify a date when creating a Date object, it will contain the date and time when the JS interpreter encounters that line of code. Once you have an instance of the Date object holding the current date and time, you can use any of its properties or methods.
        *   2. In this example, you can see that getFullYear() is used to return the year of the date being stored in the Date object.
        *   3. In this case, it is being used to write the current year in a copyright statement.
*   Working with Date and Times
    -   To specify a date and time, you can use this format:
        *   YYYY, MM, DD, HH, MM, SS
        *   1996, 03, 16, 15, 45, 55
    -   This represents 3:45pm and 55 seconds on April 06, 1996
    -   The order and syntax for this is;
        *   Year    four digits
        *   Month   0-11(Jan is 0)
        *   Day     1-31
        *   Hour    0-23
        *   Minutes 0-59
        *   Seconds 0-59
        *   Milliseconds    0-999
    -   Another way to format the date and time is;
        *   MMM DD, YYYY HH:MM:SS
        *   Apr 16, 1996 15:45:55
            -   You can omit the time portion if you don't need it
    -   Example;
    -   let today = new Date();
    -   let year = today.getFullYear();
    -   let est = new Date('Apr 16, 1996 15:45:55');
    -   let difference = today.getTime() - est.getTime();
    -   difference = (difference / 31556900000);
    -   
    -   let elMsg = document.getElementById('message');
    -   elMsg.textContent = Math.floor(difference) + 'years of online travel advice';
        *   1. In this example, you can see a date being set in the past.
        *   2. If you try to find the difference between two dates, you will end up with a result in milliseconds.
        *   3. To get the difference in days/weeks/years, you divide this number by the number of milliseconds in a day/week/year.
        *   Here the number is divided by 31,556,900,000 - the number of milliseconds in a year that is not a leap year.
##  Decisions & Loops
*   Decisions & Loops
*   Looking at a flowchart (for all but the most basic scripts), the code can take more than one path, which means the browser runs different code in different situations. In this section, you will learn how to create and control the flow of data in your scripts to handle different situations.
*   Scripts often need to behave differently depending upon how the user interacts with the web page and/or the browser window itself. To determine which path to take, programmers often rely upon the following 3 concepts.
    -   Evaluations - You can analyze values in your scripts to determine whether or not they match expected results.
    -   Decsision - Using the results of evaluations, you can decide which path your script should go down.
    -   Loops - There are also many occassions where you will want to perform the same set of steps repeatedly.
*   Decision Making
    -   There are often several places in  a script where decisions are made that determine which lines of code should be run next. Flowcharts can help you plan for these occassions.
    -   In a flowchart, the diamond shape represents a point where a decision must be made and the code can take one of two different paths. Each path is made up of a different set of tasks, which means you have to write different code for each situation.
    -   In order to determine which path to take, you set a condition. For example, you can check that one value is equal to another, greater than another, or less than another. If the condition returns true, you take one path; if it is false, you take another path. Such as pass or fail depending on the score being greater than or less than 50.
    -   In the same way that there are operators to do basic math, or to join two strings, there are comparison operators that allow you to compare values and test whether a condition is met or not.
    -   Examples of comparison operators include the greater than (>) and less than (<) symbols, and double equals sign (==) which checks whether two values are the same.
*   Evaluation Conditions & Conditional Statements
    -   There are two components to a decision
        *   1: An expression is evaluated, which returns a value
        *   2: A conditional statement says what to do in a given situation
    -   Evaluation of a Condition
        *   In order to make a decision, your code checks the current status of the script. This is commonly done by comparing two values using a comparison operator which returns a value of true or false.
    -   Conditional Statements
        *   A conditional statement is based on a concept of if/then/else; if a condition is met, then your code executes one or more statements, else your code does something different or just skips the step.
    -   example
    -   if (score > 50) {
    -     document.write('You passed!');
    -   } else {
    -   document.write('Try again...');
    -   }
        *   What This is saying:
        *   if the condition returns true, execute the statement between the first set of curly brackets, otherwise, execute the statements between the second set of curly brackets.
    -   You can also have multiple conditions by combining two or more comparision operators. For example, you can check whether two conditions are both met, or if just one of several condtions is met. 
*   Comparison Operators: Evaluation Conditions
    -   You can evaluate a situation by comparing one value in the script to what you expect it might be. The result will be a Boolean: true or false.
    -   == Is equal to
        *   This operator compares two values, numbers, strings or Booleans, to see if they are the same. 'Hello' == 'Goodbye' returns false. 'Hello' == 'Hello' returns true.
    -   != is not equal to
        *   This operator compares two values to see if they are not the same. 'Hello' != 'Goodbye' returns true. 'Hello' != 'Hello' returns false.
    -   === Strict equal to
        *   This operator compares two values to check that both the data type and value are the same. '3' === 3 returns false. '3' === '3' returns true (both are a string).
    -   !== Strict not equal to
        *   This operator compares two values to check that both the data type and value are not the same. '3' !== 3 returns true. '3' !== '3' returns false.
    -   > Greater than
        *   This operator checks if the number on the left is greater than the number on the right. 4 > 3 returns true. 3 > 4 returns false.
    -   < Less than
        *   This operator checks if the number on the left is less than the number on the right. 4 < 3 returns false. 3 < 4 returns true.
    -   >= Greater than or equal to
        *   This operator checks if the number on the left is greater than or equal to the number on the right. 4 >= 3 returns true. 3 >= 4 returns false. 3 >= 3 returns true.
    -   <= Less than or equal to
        *   This operator checks if the number on the left is less than or equal to the number on the right. 4 <= 3 returns false. 3 <= 4 returns true. 3 <= 3 returns true.
    -   Programmers refer to the testing or checking of a condition as evaluating the condition. Conditions can be much more complex than those shown here, but they usually result in a value of true or false. There are a couple of notable exeptions: i) Every value can be treated as true or false even if it is not a Boolean true or false value. ii) In short-circuit evaluation, a condition might not need to run.
*   Structuring Comparison Operators
    -   In any condition, there is usually one operator and two operands. The operands are placed on each side of the operator. They can be values or variables. You often see expressions enclosed in brackets.
    -   Example;
    -   (score >= pass)
        *   score is the operand. >= is the operator. pass is the second operand. This will result in a single value, either true or false.
