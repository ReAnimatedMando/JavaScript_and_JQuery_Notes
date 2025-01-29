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
    -   let msg = 'h2>browser window/h2>p>width: ' + window.innerWidth + '/p>';
    -   msg += 'p>height: ' + window.innerHeight + '/p>';
    -   msg += 'h2>history/h2>p>items: ' + window.history.length + '/p>';
    -   msg += 'h2>screen/h2>p>width: ' + window.screen.width + '/p>;
    -   msg += 'p>height: ' + window.screen.height + '/p>';
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
    -   let msg - 'p>b>page title: /b>' + document.title + 'br />';
    -   msg += 'b>page address: /b>' + document.URL + br />';
    -   msg += 'b>last modified: /b>' + document.lastModified + '/p>;
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
    -   let msg = 'h2>length/h2>p>' + saying.length + '/p>';
    -   msg += 'h2>uppercase/h2>p>' + saying.toUpperCase() + '/p>';
    -   msg += 'h2>lowercase/h2>p>' + saying.toLowerCase() + '/p>';
    -   msg += 'h2>character index: 12/h2>p>' + saying.charAt(12) + '/p>';
    -   msg += 'h2>first ee/h2>p>' + saying.indexOf('ee') + '/p>';
    -   msg += 'h2>last e/h2>p>' + saying.lastIndexOf('e') + '/p>';
    -   msg += 'h2>character index 8-14/h2>p>' + saying.substring(8, 14) + '/p>';
    -   msg += 'h2>replace/h2>p>' + saying.replace('me', 'w') + '/p>';
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
    -   let msg = 'h2>original number/h2>p>' + originalNumber + '/p>';
    -   msg += 'h2>3 decimal places/h2>p>' + originalNumber.toFixed(3); + '/p>';
    -   msg += 'h2>3 digits/h2>p>' + originalNumber.toPrecision(3) + '/p>';
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
    -   el.innerHTML = 'h2>random number/h2>p>' + randomNum + '/p>';
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
    -   el.innerHTML = 'p>Copyright &copy;' + year + '/p>;
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
*   Using Comparison Operators
    -   Example;
    -   let pass = 50; // Pass mark
    -   let score = 90; // Score
    -   
    -   // Check if the user has passed
    -   let hasPassed = Score >= pass;
    -   
    -   // Write the message into the page
    -   let el = document.getElementById('answer');
    -   el.textContent = 'Level passed: ' + hasPassed;
        *   At the most basic level, you can evaluate two variables using a comparison operator to return a true or false value.
        *   In this example, a user is taking a test, and the script tells the user whether they have passed this round of the test.
        *   First the two variables are set. pass and score. To see if the user has passed, a comparison operator checks whether score is greater than or equal to pass. The result will be true or false, and is stored in a variable called hasPassed. On the the next line(textContent), the result is written on the screen. The last two lines select the element whose id attribute has a value of answer, and then updates its contents.
*   Using Expressions with Comparison Operators
    -   The Operand does not have to be a single value or variable name. An operand can be an expression (because each expression evaluates into a single value).
    -   Example;
    -   ((score1 + score2) > (highScore1 + highScore2))
*   Comparing two Expressions
    -   Example;
    -   let score1 = 90; // Round 1 score
    -   let score2 = 95; // Round 2 score
    -   let highScore1 = 75; // Round 1 high score
    -   let highScore2 = 95; // Round 2 high score
    -   
    -   // Check if scores are higher than current high score
    -   let comparison = (score1 + score2) > (highScore1 + highScore2);
    -   
    -   // Write the message into the page
    -   let el = document.getElementById('answer');
    -   el.textContent = 'New high score: ' + comparison;
        *   In this example, there are two rounds to the test and the code will check if the user has achieved a new high score, beating the previous record.
        *   The script starts by storing the user's scores for each round in variables. Then the highest scores for each round are stored in two more variables. The comparison operator checks if the user's total score is greater than the highest score for the test and stores the results in a variable called comparison.
        *   In the comparison operator, the operand on the left calculates the user's total score. The operand on the right adds together the highest scores for each round. The result is then added to the page. 
        *   When you assign the result of the comparison to a variable, you  do not strictly need the containing parentheses.
        *   Some programmers use them anyway to indicate that the code evaluates into a single value. Others only use containing parentheses when they form part of a condition.
*   Logical Operators
    -   Comparison operators usually return single values of true or false. Logical operators allow you to compare the results of more than one comparison operator.
    -   Example;
    -   ((5 < 2) && (2 >= 3))
        *   Here in one line of code are three expressions, each of which will resolve to the value true or false.
        *   The expression on the left and the right both use comparison oeprators, and both return false.
        *   The third expression uses a logical operator rather than a comparison operator. The locical and operator checks to see whether both expressions on either side of it return true(in this case they don't), so it evaluates to false.
    -   && - Logical AND
        *   This operator tests more than one condition. If both expressions evaluate to true then the expression returns true. If just one of the expressions returns false, then the expression will return false.
    -   || - Logical OR
        *   This operator tests at least one condition. If either expression evaluates to true, then the expression returns true. If both return false, then the expression is false. 
    -   ! - Logical NOT
        *   This operator takes a single Boolean value and inverts it. This reverses the state of an expression. If it was false without the ! before, it would return true. If the statement was true, it would return false. 
    -   Short-Circuit Evaluation
        *   Logical expressions are evaluated left to right. If the first condition can provide enough information to get the answer, then there is no need to evaluate the second condition.
*   Using Logical And
    -   Example;
    -   let score1 = 8; // Round 1 score
    -   let score2 = 8; // Round 2 score
    -   let pass1 = 6; // Round 1 pass mark
    -   let pass2 = 6; // Round 2 pass mark
    -   
    -   // Check whether user passed both rounds, store result in variable
    -   let passBoth = (score1 >= pass1) && (score2 >= pass2);
    -   
    -   // Create message
    -   let msg = 'Both rounds passed: ' + passBoth;
    -   
    -   // Write the message into the page
    -   let el = document.getElementById('answer');
    -   el.textContent = msg;
        *   In this example, a math test has two rounds. For each round there are two variables: one holds the user's score for that round; the other holds the pass mark for that round. The logical AND is used to see if the user's score is greater than or equal to the pass mark in both of the rounds of the test. The result is stored in a varuable called passBoth. The example finishes off by letting the user know whether or not they have passed both rounds.
        *   It is rare that you would ever write the Boolean result into the page like we are doing here. As you will see later, it is more likely that you would check a condition, and if it is true, run other statements.
*   Using Logical OR & Logical NOT
    -   Example;
    -   let score1 = 8; // Round 1 score
    -   let score2 = 8; // Round 2 score
    -   let pass1 = 6; // Round 1 pass mark
    -   let pass2 = 6; // Round 2 pass mark
    -   
    -   // Check whether user passed both rounds, store result in variable
    -   let minPass = (score1 >= pass1) || (score2 >= pass2);
    -   
    -   // Create message
    -   let msg = 'Resit required' + !(minPass);
    -   
    -   // Write the message into the page
    -   let el = document.getElementById('answer');
    -   el.textContent = msg;
        *   Here is the same test but this time using the logical OR operator to find out if the user has passed at least one of the two rounds. If they pass just one round, they do not need to retake the test.
        *   Look at the numbers stored in the four variables at the start of the example. The user has passed both rounds, so the minPass variable will hold the Boolean value of true.
        *   Next, the message is stored in a variable called msg. At the end of the message, the logical NOT will invert the result of the Boolean variable so it is false. It is then written into the page.
*   If Statements - The if statement evaluates or checks a condition. If the condition evaluates to true, any statements in the subsequent code block are executed.
    -   Example;
    -   if (score >= 50) {
    -   congratulate();
    -   }
        *   If the condition evaluates to true, the following code block, the code in the next set of curly braces, is executed.
        *   If the condition resolves to false, the statement in that code block are not run. The script will continue to run from the end of the next code block.
*   Using IF Statements
    -   Example;
    -   let score = 75; // Score
    -   let msg;        // Message
    -   
    -   if (score >= 50) {  // if score is 50 or higher
    -       msg = 'Congratulations!';
    -       msg += ' Proceed to the next round. ';
    -   }
    -   let el = document.getElementById('answer');
    -   el.textContent = msg;
        *   In this example, the IF statement is checking if the value currently held in a variable called score is 50 or more. In this case, the statement evaluates to true. Therefore, the contents of the statement within the subsequent code block are run, creating a message that congratulates the user and tells them to proceed.
        *   After the code block, the message is written to the page.
        *   If the value of the score variable had been less, the statements in the code block would not have run, and the code would have continued on to the next line after the code block.
*   IF ELSE Statements
    -   The if... else statement checks a condition. If it resolves to true the first code block is executed. If the condition resolves to false the second code block is run instead.
*   Using IF... ELSE Statements
    -   Example;
    -   let pass = 50;  // Pass mark
    -   let score = 75; // Current score
    -   let msg =       // Message
    -   
    -   // Select message to write based on score
    -   if (score >= pass) {
    -   msg = 'Congratulations, you passed!';
    -   } else {
    -   msg = 'Have another go!';
    -   }
    -   
    -   let el = document.getElementById('answer');
    -   el.textContent = msg;
        *   Here you can see that an if... else statement allows you to provide two sets of code:
            -   1. one set if the condition evaluates to true.
            -   2. another set if the condtiion is false.
        *   In this test, there are two possible outcomes: a user can either get a score equal to or greater than the pass mark, or they can score less than the pass mark. One response is required for each eventuality. The response is then written to the page.
        *   Note that the statements inside an if statement should be followed by a semicolon, but there is no need to place one after the closing curly braces of the code blocks.
    -   An if statement only runs a set of statements if the condition is true.
    -   An if... else statement runs one set of code if the condition is true or a different set if it is false.
*   Switch Statements
    -   A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches the value.
    -   Example;
    -   switch (level) {
    -   case 'One':
    -       title = 'Level 1';
    -       break;
    -   
    -   case 'Two':
    -       title = 'Level 2';
    -       break;
    -   
    -   case 'Three':
    -       title = 'Level 3';
    -       break;
    -   
    -   default:
    -       title = 'Test';
    -       break;
    -   }
        *   Here, the variable named level is the switch value. If the value of the level variable is the string One, then the code for the first case is executed. If it is Two, the second case is executed. If it is Three, the third case is executed. If it is none of these, the code for the default case is executed.
        *   The entire statement lives in one code block, and a colon separates the option from the statements that are to be run if the case mathces the switch value.
    -   If... Else vs. Switch
        *   If... Else - There is no need to provide an else option, you can just use an if statement. With a series of if statements, they are all checked even if a match has been found so it performs more slowly than a switch.
        *   Switch - You have a default option that is run if none of the cases match. If a match is found, that code is run; then the break statement stops the rest of the switch statement running providing better performance than multiple if statements.
*   Using Switch Statements
    -   Example;
    -   let msg;    // Message
    -   let level = 2;  // Level
    -   
    -   // Determine message based on level
    -   switch (level) {
    -   case 1:
    -       msg = 'Good luck on the first test';
    -       break;
    -   
    -   case 2:
    -       msg = 'Second of three - keep going!';
    -       break;
    -   
    -   case 3:
    -       msg = 'Final round, almost there!';
    -       break;
    -   
    -   default:
    -       msg = 'Good luck!';
    -       break;
    -   }
        *   In this example, the purpose of the switch statement is to present the user with a different message depending on which level they are at. The message is stored in a variable called msg.
        *   The variable called level contains a number indicating which level the user is on. This is then used as the switch value. The switch value could also be an expression.
        *   In the following code block, there are three options for what the value of the level variable might be: the numbers 1, 2, or 3.
        *   If the value of the level variable is the number 1, the value of the msg variable is set to 'Good luck on the first test' and so on with each case.
        *   Each case ends with the break keyword which will tell the JavaScript interpreter to skip the rest of this code block and continue onto the next.
*   Type Coercion & Weak Typing
    -   If you use a data type JavaScript did not expect, it tries to make sense of the operation rather than report an error.
    -   JavaScript can convert data types behind the scenes to complete an operation. This is known as type coercion. For example, a string '1' could be converted to a number 1 in the following expression: ('1' > 0). As a result, the above expression would evaluate to true.
    -   JavaScript is said to use Weak Typing because the data type for a value can change. Some other languages require that you specify what data type each variable will be. They are said to use Strong Typing.
    -   Type coercion can lead to unexpected values in your code and also cause errors. Therefore, when checking if two values are equal, it is considered better to use strict equals operators === and !== rather than == and != as these strict operators check that the value and data types match.
*   Truthy & Falsy Values
    -   Due to type coercion, every value in JavaScript can be treated as if it were true or false; and this has some interesting side effects.
    -   Example - Falsy Values;
    -   let highScore = false;      //  The tradition Boolean false
    -   let highScore = 0;          //  The number zero
    -   let highScore = '';         //  Empty value
    -   let highScore = 10/'score'; //  NaN Not a Number
    -   let highScore;              //  A variable with no value assigned to it
    -   
    -   Example - Truthy Values;
    -   let highScore = true;       //  The traditional Boolean true
    -   let highScore = 1;          //  Numbers other than zero
    -   let highScore = 'carrot';   //  Strings with content
    -   let highScore = 10/5;       //  Number calculations
    -   let highScore = 'true';     //  true written as a string
    -   let highScore = '0';        //  Zero written as a string
    -   let highScore = 'false';    //  false written as a string
        *   falsy values are treated as if they are false. The table above shows a highScore variable with a series of values, all of which are falsy. Falsy values can also be treated as the number 0.
        *   Truthy values are treated as if they are true. Almost everything that is not in the falsy table can be treated as if it were true. Truthy values can also be treated as the number 1.
        *   In addition, the presence of an object or an array is usually considered truthy, too. This is commonly used when checking for the presence of an element in a page. 
*   Checking Equality & Existence
    -   Because the presence of an object or array can be considered truthy, it is often used to check for the existence of an element within a page.
    -   A unary operator returns a result with just one operand. Here you can see an if statement checking for the presence of an element. If the element is found, the result is truthy, so the first set of code is run. If it is not found, the second set is run instead.
        *   Example;
        *   if (document.getElementById('header')) {
        *       // Found: do something
        *   }   else {
        *       // Not Found: do something else
        *   }
            -   Those new to JavaScript often think the following would do the same: if (document.getElementById('header') == true) but the document.getElementById('header') would return an object which is a truthy value but it is not equal to a Boolean value of true.
    -   Because of type coercion, the strict equality operators === and !== result in fewer unexpected values than == and != do.
    -   If you use ==, the following values can be considered equal: false, 0, and ''. However, they are not equivalent when using the strict operators.
        *   false == 0 - true
        *   false === 0 - false
        *   false == '' - true
        *   false === '' - false
        *   0 == '' - true
        *   0 === '' - false
    -   Although null and undefined are both falsy, they are not equal to anything other than themselves. Again, they are not equivalent when using strict operators.
        *   undefined == null - true
        *   null == false - false
        *   undefined == false - false
        *   null == 0 - false
        *   undefined == 0 - false
        *   undefined === null - false
    -   Although NaN is considered falsy, it is not equivalent to anything; it is not even equivalent to itself since NaN is an undefinable number, two cannot be equal.
        *   NaN == null - false
        *   NaN == NaN - false
*   Short Circuit Values
    -   Logical operators are processed left to right. They short-circuit/stop as soon as they have a result - but they return the value that stopped the processing, not necessarily true or false.
    -   Logical operators will not always return true or false because:
        *   They return the value that stopped processing.
        *   That value might have been treated as truthy or falsy although it was not a Boolean.
    -   Programmers use this creatively, for example, to set values for variables or even create objects.
    -   Example;
    -   let artist = 'Rembrandt';
    -   let artistA = (artist || 'Unknown');
        *   On line 1, the variable artist is given a value.
        *   On line 2, if the variable artist has a value, then artistA will be given the same value as artist because a non-empty string is truthy.
    -   let artist = '';
    -   let artistA = (artist || 'Unknown');
        *   If the string is empty, artistA becomes a string 'Unknown'.
    -   let artist = '';
    -   let artistA = (artist || {});
        *   You could even create an empty object if artist does not have a value.
    -   valueA = 0;
    -   valueB = 1;
    -   valueC = 2;
    -   if (valueA || valueB || valueC) {
    -       // Do something here
    -   }
        *   Here there are three values. If any one of them is considered truthy, the code inside the if statement will execute. When the script encounters valueB in the logical operator, it will short circuit because the number 1 is considered truthy and the subsequent code block is executed.
        *   This technique could also by used to check for the existence of elements within a page.
    -   As soon as a truthy value is found, the remaining options are not checked. Therefore experienced programmers often:
        *   Put the code most likely to return true first in OR operations, and false answers first in AND operations.
        *   Place the options requiring the most processing power last, just in  case another value returns true and they do not need to be run.
*   Loops
    -   Loops check a condition. If it returns true, a code block will run. Then the condition will be checked again and if it still returns true, the code block will run again. It repeats until the condition returns false. There are three common types of loops:
        *   For - If you need to run code a specific number of times, use a for loop. it is the most common loop. In a for loop, the condition is usually a counter which is used to tell how many times the loop should run.
        *   While - If you do not know how many times the code should run, you can use a while loop. Here the condition can be something other than a counter, and the code will continue to loop for as long as the condition is true.
        *   Do While - the do... while loop is very similar to the while loop, but has one key difference: it will always run the statements inside the curly braces at least once, even if the condition evaluates to false. 
    -   for (let i = 0; i < 10; i++) {
    -   document.write(i);
    -   }
        *   This is a for loop. the condition is a counter that counts to ten. The result would write "0123456789" to the page.
        *   If the variable i is less than ten, the code inside the curly braces is executed. Then the counter is incremented.
        *   The condition is checked again, if i is less than ten it runs again.
*   Loop Counters
    -   A for loop uses a counter as a condition. This instructs the code to run a specified number of times. Here you can see the condition is made up of three statements:
        *   Initialization - Create a variable and set it to 0. This variable is commonly called i, and it acts as the counter.
            -   let i = 0;
            -   The variable is only created the first time the loop is run. You will sometimes see this variable declared before the condition. The following is the same and it is mainly a preference of the coder.
                *   let i;
                *   for (i = 0; i < 10; i++) {
                *       // code goes here
                *   }
        *   Condition - The loop should continue to run until the counter reaches a specified number.
            -   i < 10
            -   The value of i was initially set to 0, so in this case the loop will run 10 times before stopping. The condition may also use a variable that holds a number. If a variable called rounds held the number of rounds in a test and the loop ran once for each round, the condition would be:
                *   let rounds = 3;
                *   i < (rounds);
        *   Update - Every time the loop has run the statements in the curly braces, it addes one to the counter.
            -   i++
            -   One is added to the counter using the increment operator (++). Another way of reading this is that it says, "Take the variable i, and add one using the ++ operator." It is also possible for loops to count downwards using the decrement operator (--).
*   Looping
    -   Example;
    -   for (let i = 0; i < 10; i++) {
    -       document.write(i);
    -   }
        *   The first time the loop is run, the variable i (the counter) is assigned a value of zero.
        *   Every time the loop is run, the condition is checked. Is the variable i less than 10?
        *   Then the code inside the loop is run.
        *   The variable i can be used inside the loop. Here it is used to write a number to the page.
        *   When the statements have finished, the variable i is incremented by 1.
        *   When the condition is no longer true, the loop ends. The script moves to the next line of code.
*   Key Loop Concepts
    -   Here are three points to consider when you are working with loops. Each is illustrated in examples.
        * Keywords - You will commonly see these two keywords used withh loops:
            -   Break - This keyword causes the termination of the loop and tells the interpreter to go onto the next statement of code outside of the loop. This is also used in functions.
            -   Continue - This keyword tells the interpreter to stop the current iteration, and then check the condition again, if it is true the code runs again.
        *   Loops and Arrays - Loops are very helpful when dealing with arrays if you want to run the same code for each item in the array. 
            -   For example, you might want to write the value of each item stored in an array into the page. 
            -   You may not know how many items will be in an array when writing a script, but, when the code runs, it can ckeck the total number of items in a loop, That figure can then be used in the counter to control how many times a set of statements is run. Once the loop has run the right number of times, the loop stops.
        *   Performance Issues - It is important to remember that when a browser comes across JS, it will stop doing anything else until it has processed the script.
            -   If your loop is dealing with only a small number of items, this will not be an issue. If, however, your loop contains a lot of items, it can make the page slower to load.
            -   If the condition never returns false, you get what is commonly referred to as an infinite loop. The code will not stop running until your browser runs out of memory, breaking your script.
            -   Any variable you can define outside of the loop and that does not change within the loop should be defined outside of it. If it were declared inside the loop, it would be recalculated every time the loop ran, needlessly using resources.
*   Using For Loops
    -   Example;
    -   let scores  = [24, 32, 17];     // Array of scores
    -   let arrayLength = scores.length;    // Items in array
    -   let roundNumber = 0;            // Current round
    -   let msg = '';                   // Message
    -   let i;                          // Counter
    -   
    -   // Loop through the items in the array
    -   for (i = 0; i < arrayLength; i++) {
    -   // Arrays are zero based (so 0 is round 1)
    -   // Add 1 to the current round
    -   roundNumber = (i + 1);
    -   
    -   // Write the current round to message
    -   msg += 'Round' + roundNumber + ': ';
    -   
    -   // Get the score from the scores array
    -   msg += scoresi] + 'br />';
    -   }
    -   
    -   document.getElementById('answer').innerHTML = msg;
        *   A for loop is often used to loop throught the items in an array.
        *   In this example, the scores for each round of a test are stored in an array called scores.
        *   The total number of items in the array is stored in a variable called arrayLength. This number is obtained using the length property of the array.
        *   There are three more variables: roundNumber holds the round of the test; msg holds the message to display; i is the counter, declared outside the loop.
        *   The loop starts with the for keyword, then contains the condition inside the parentheses. As long as the counter is less than the total number of items in the array, the contents of the curly braces will continue to run. Each time the loop runs, the round number is increased by 1.
        *   Inside the curly braces are rules that write the round number and the score to the msg variable. The variables declared outside of the loop are used within the loop.
        *   The msg variable is then written into the page. It contains HTML so the innerHTML property is used to do this.
*   Using While Loops
    -   Example;
    -   let i = 1;      // Set counter to 1
    -   let msg = '';   // Message
    -   
    -   // Store 5 times table in a variable
    -   while (i < 10) {
    -   msg += i + ' x 5 = ' + (i * 5) + 'br />';
    -   }
    -   
    -   document.getElementById('answer').innerHTML = msg;
        *   Here is an example of a while loop. It writes out the 5 times table. Each time the loop is run, another calculations is written into the variable called msg.
        *   This loop will continue to run for as long as the condition in the parentheses is true. That condition is a counter indicating that, as long as the variable i remains less than 10, the statements in the subsequent code block should run.
        *   Inside the code block there are two statements:
            -   The first statement uses the += operator, which is used to add new content to the msg variable. Each time the loop runs, a new calculation and line break is added to the end of the message being stored in it. So += works as a shorthand for writing: msg = msg + 'new msg'.
            -   The second statement increments the counter variable by one. This is done inside the loop rather than with the condition.
        *   When the loop has finished, the interpreter goes to the next line of code, which writes the msg variable to the page.
        *   In this example, the condition specifies that the code should run nine times. A more typical use of a while loop would by when you do not know how many times you want the code to run. it should continue to run as long as a condition is met.
*   Using Do While Loops
    -   Example;
    -   let i = 1;      // Set counter to 1
    -   let msg = '';   // Message
    -   
    -   // Store 5 times table in a variable
    -   do {
    -       msg += i + ' x 5 = ' + (i * 5) + '<br />';
    -       i++;
    -   }   while (i < 1);
    -   // Note how this is already 1 and it still runs
    -   
    -   document.getElementById('answer').innerHTML = msg;
        *   The key difference between a while loop and a do while loop is that the statements in the code block come before the condition. This means that those statements are run once whether or not the condtion is met.
        *   If you take a look at the condition, it is checking that the value of the variable called i is less than 1, but that variable has already been set to a value of 1. Therefore, in this example the result is that the 5 times table is written out once, even though the counter is not less than 1.
        *   Some people liek to write while on a separate line from the closing curly brace before it.
##  Document Object Model
*   Document Object Model
    -   The document object model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.
    -   The DOM is neither part of HTML, or part of JavaScript; it is a separate set of rules. It is implemented by all major browser makers, and covers two primary areas:
        *   Making a model of the HTML page - When the browser loads a web page, it creates a model of the page in memory.
            -   The DOM specifies the way in which the browser should structure this model using a DOM tree.
            -   The DOM is called an object model because the model (the DOM tree) is made of objects.
            -   Each object represents a different part of the page loaded in the browser window.
        *   Accessing and changing the HTML page - The DOM also defines mothods and properties to access and update each object in this model, which in turn updates what the user sees in the browser.
            -   You will hear people call the DOM an Application Programming Interface (API). User interfaces let humans interact with programs; APIs let programs and scripts talk to each other. The DOM states what your script can ask the browser about the current page, and how to tell the browser to update what is being shown to the user.
*   The DOM Tree is a Model of a Web Page
    -   As a browser loads a web page, it creates a model of that page. The model is called  a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes.
        *   The Document Node
            -   At the top of the DOM tree is the document node and it represents the entire page. It is the starting point for all visits to the DOM tree.
        *   Element Nodes
            -   HTML elements describe the structure of an HTML, i.e. the headings, paragraphs, divs, lists, and body. To access the DOM tree, you start looking for elements. Once you find the element you want, then you can access its text and attribute nodes if you want to. This is why you start by learning methods that allow you to access element nodes, before learning to access and alter text or attributes.
        *   Attribute Nodes
            -   The opening tags of HTML elements can carry attributes and these are represented by attribute nodes in the DOM tree. Attribute nodes are not children of the element that carries them; they are part of that element. Once you access an element, there are specific JS methods and properties to read or change that element's attributes. For example, it is common to change the values of class attributes to trigger new CSS rules that affect their presentation.
        *   Text Nodes
            -   Once you have accessed an element node, you can then reach the text within that element. THis is stored in its own text node. Text nodes cannot have children. If an element contains text and another child element, the child element is not a child of the text node but rather a child of the containing element. 
        *   Note: Each node is an object with methods and properties. Scripts access and wupdate this DOM tree (not the source HTML file). Any changes made to the DOM tree are reflects in the browser.
*   Working with the DOM Tree
    -   Accessing and updating the DOM tree involves two steps:
        *   1: Locate the node that represents the element you want to work with.
        *   2: Use its text content, child elements, and attributes.
    -   Access the Elements - Here is an overview of the methods and properties that access elements covered earlier.
        *   Select an individual element node.
            -   getElementById - Uses the value of an element's id attribute which should be unique within the page.
            -   querySelector - Uses a CSS selector, and returns the first matching element.
            -   You can also select individual elements by traversing from one element to another within the DOM tree.
        *   Select multiple elements (Nodelists) - There are three common ways to select multiple elements.
            -   getElementByClassName - Selects all elements that have a specific value for their class attribute
            -   getElementByTagName - Selects all elements that have the specified tag name.
            -   querySelectorAll - Uses a CSS selector to select all matching elements.
        *   Traversing between element nodes - You can move from one element node to a related element node.
            -   parentNode - Selects the parent of the current element node which will return just one element.
            -   previousSibling/nextSibling - Selects the previous or next sibling from the DOM tree.
            -   firstChild/lastChild - Select the first or last child of the current element.
    -   Work with those Elements - Here is an overview of methods and properties that work with the elements introduced earlier.
        *   Access/Update text nodes.
            -   The text inside any element is stored inside a text node. To access the text node above:
                *   1. select the li> element
                *   2. Use the firstChild property to get the text node
                *   3. Use the text node's only property (nodeValue) to get the text from the element
            -   nodeValue - this property lets you access or update contents of a text node, the text node does not include text inside any child elements.
        *   Work with HTML content
            -   One property allows access to child elements and text content: innerHTML
            -   Another just the text content: textContent
            -   Several methods let you create new nodes, add nodes to a tree, and remove nodes from a tree:
                *   createElement
                *   createTextNode
                *   appendChild/removeChild
                    -   This is called DOM manipulation
        *   Access or update attribute values
            -   Here are some of the properties and methods you can use to work with attributes.
            -   className/Id - Lets you get or update the value of the class and id attributes.
            -   hasAttribute, getAttribute, setAttribute, removeAttribute
                *   The first checks if an attribute exists, the second gets its value, the third updates the value, the fourth removes an attribute.
*   Caching DOM Queries
    -   Methods that find elements in the DOM tree are called DOM queries. When you need to work with an element more than once, you should use a variable to store the result of this query.
    -   When a script selects an element to access or update, the interpreter must find the element(s) in the DOM tree.
    -   getElementById('one') - The interpreter is told to look through the DOM tree for an element whose id attribute has a value of one. Once it has found the node that represents the element(s), you can work with that node, its parent, or any children.
    -   When people talk about storing elements in variables, they are really storing the location of the element(s) within the DOM tree in a variable. The properties and methods of that element node work on the variable.
    -   If your script needs to use the same element(s) more than once, you can store the location of the element(s) in a variable.
    -   This saves the browser looking through the DOM tree to find the same element(s) again. It is known as caching the selection.
    -   Programmers would say that the variable stores a reference to the object in the DOM tree. It is storing the location of the node. 
    -   let itemOne = getElementById('one');
        *   itemOne does not store the li> element, it stores a reference to where that node is in the DOM tree. To access the text content of this element, you might use the variable name: itemOne.textContent
*   Accessing Elements
    -   DOM inqueries may return on element, or they may return a NodeList, which is a collection of nodes.
    -   Sometimes you will want to access one individual element or a fragment of the page that is stored within that one element. Other times you may want to select a group of elements, for example, every h1 element in the page or every li element within a particular list.
    -   Groups of element nodes - if a method can return more than one node, it will always return a NodeList. You then need to select the element you want from this list using an index number starting with 0 like any array.
    -   Fastest Route - Finding the quickest way to access an element within your web page will make the page seem faster and or more responsive. This usually means evaluating the minimum number of nodes on the way to the element you want to work with. For example, getElementById() will quickly return one element because no two elements on the same page should have the same value for an id attribute, but it can only be used when the element you to access has an id attribute.
*   Methods that select individual Elements
    -   getElementById() and querySelector() can both search an entire documnet and return individual elements. Both use a similar syntax.
    -   getElementById() is the quickest and most efficient way to access an element because no two elements can share the same value for their id attributes. The syntax for this method is shown below.
        *   document.getElementById('one')
            -   document refers to the document object. You always have to access individual elements via the document object.
            -   The getElementById() method indicates that you want to find an element based upon the value of its id attribute.
            -   Member Operator - The dot notation indicates that the method on the right is being applied to the node on the left of the period.
            -   The parameter ('one'), the method needs to know the value of the id attribute on the element you want. It is the parameter of the method.
            -   This code will return the element node for the element whose id attribute has a value of one. You often see element nodes stored in a variable for use later in the script.
            -   Here the method is used on the document object so it looks for that element anywhere within the page. DOM methods can also by used on element nodes within the page to find descendants of that node.
    -   querySelector - is a more recent addition to the DOM, so it is not supported in older browsers. But it is very flexible because its parameter is a CSS selector, which means it can be used to accurately target many more elements.
*   Selecting Elements using ID Attributes
    -   Example;
    -   HTML
    -   h1 id="header">List King/h1>
    -   h2>Buy groceries/h2>
    -   ul>
    -       <li id="one" class="hot">fresh</em>
    -           figs</li>
    -       <li id="two" class="hot">pine nuts</li>
    -       <li id="three" class="hot">honey</li>
    -       <li id="four">balsamic vinegar</li>
    -   /ul>
    -   JavaScript
    -   //  Select the element and store it in a variable
    -   let el = document.getElementById('one');
    -   
    -   //  Change the value of the class attribute
    -   el.className = 'cool';
        *   getElementById() allows you to select a single element node by specifying the value of its id attribute
        *   This method has one parameter: the value of the id attribute on the element you want to select. This value is placed inside quote marks because it is a string. The quotes can be single or double, but they must match.
        *   In the example, the first line of JS code finds the element whose id attribute has a value of one, and stores a reference to that node in a variable called el.
        *   The code then uses a property called className to update the value of the class attribute of the element stored in this variable. Its value is cool, and this triggers a new rule in the CSS that sets the background color of the element to aqua.
        *   Note how the className property is used on the variable that stores the reference to the element.
            -   getElementByTagName('h1') - returns the one h1 element from the html doc.
            -   getElementByTagName('li') - returns four li> elements, they appear in same order as they are entered into the html page.
            -   getElementByClassName('hot') - returns only the li> elements that have a class of 'hot', not a tag name.
            -   querySelectorAll('li[id]') - returns four elements, one for each of the li> elements on the page that have an id attribute, regardless of the values of the id attributes. (all)
*   NodeLists: DOM Queries that return more than one Element
    -   When a DOM method can return more than one element, it returns a NodeList, even if it only finds one matching element.
    -   A NodeList is a collection of element nodes. Each node is given an index number, just like an array.
    -   The order in which the element nodes are stored in a NodeList is the same order that they appeared in the HTML page.
    -   When a DOM query returns a NodeList, you may want to:
        *   Select one element from the NodeList.
        *   Loop through each item in the NodeList and perform the same statements on each of the element nodes.
    -   NodeLists look like arrays and are numbered like arrays, but they are not actually arrays; they are a type of object called a COLLECTION.
    -   Like any other object, a NodeList has properties and methods, notably:
        *   The length property tells you how many items are in the NodeList
        *   The item() method returns a specific node from the NodeList when you tell it the index number of the item that you want in the parentheses. However, it is more common to use array syntax with square brackets to retrieve an item from a NodeList.
*   Live & Static NodeLists
    -   There are times when you will want to work with the same selection of elements several times, so the NodeList can be stored in a variable and re-used rather than collecting the same elements again.
    -   In a live NodeList when your script updates the page, the NodeList is updated at the same time. The methods beginning getElementBy... return live NodeLists. They are also typically faster to generate than static NodeLists.
    -   In a Static NodeList when your script updates the page, the NodeList is not updated to reflect the changes made by the script.
    -   The new methods that begin querySelector... return static NodeLists. They reflect the document when the query was made. If the script changes the content of the page, the NodeList is not updated to reflect those changes.
*   Selecting an Element from a NodeList
    -   There are two ways to select an element from a NodeList: the item() method and array syntax. Both require the index number of the element you want.
    -   The Item() Method
        *   NodeLists have a method called item() which will return an individual node from the NodeList. You specify the index number of the element you want as a parameter of the method.
        *   Executing code when there are no elements to work with wastes resources. So programmers often check that there is at least one item in the NodeList before running any code. To do this, use the length property of the NodeList - it tells you how many items the NodeList contains.
        *   Look at this if statement, the condition is whether the length property of the NodeList is greater than zero. If it is, then the statements inside the if statement are executed. If not, the code continues to run after the second curly brace.
        *   Example;
        *   1. let elements = document.getElementByClassName('hot')
        *   2. if (elements.length >= 1) {
        *   3. let firstItem = elements.item(0);
        *      }
            -   1. Select elements that have a class attribute whose value is hot and store the NodeList in a variable called elements.
            -   2. Use the length property to check how many elements were found. If 1 or more are found, run the code in the if statement.
            -   3. Store the first element from the NodeList in a variable called firstItem, it says 0 because index numbers start at zero.
    -   Array Syntax - Array syntax is preferred over the item() method because it is faster. Before selecting a node from a NodeList, check that it contains nodes. If you repeatedly use the NodeList, store it in a variable.
        *   You can access individual nodes using a square bracket syntax similar to that used to access individual items from an array. You specify the index number of the element you want inside square brackets that follow the NodeList.
        *   As with all DOM queries, if you need to access the same NodeList several times, store the result of the DOM query in a variable. In this example, the NodeList is stored in a variable called elements.
        *   If you create a variable to hold a NodeList but there are not matching elements, the variable will be an empty NodeList. When you check the length property of the variable, it will return the number 0 because it does not contain any elements.
        *   Example;
        *   1. let elements = document.getElementByClassName('hot')
        *   2. if (elements.length >= 1) {
        *   3. let firstItem = elements(0);
        *      }
            -   1. Create a NodeList containing elements that have a class attribute whose value is hot, and store it in the variable elements.
            -   2. If that number is greater than or equal to 1, run the code inside the if statement.
            -   3. Get the first element from the NodeList, 0 because thats where index's start.
*   Selecing Elements Using Class Attributes
    -   Example;
    -   let elements =  document.getElementByClass('hot');       // find hot items
    -   if (elements.length > 2) {                               // if 3 or more are found
    -   let el = elements[2];                                    // select the third one from the NodeList
    -   el.className = 'cool';                                   // change the value of its class attribute
    -   }
        *   The getElementByClassName () method allows you to select elements whose class attribute contains a specific value. The method has one parameter: the class name which is given in quotes within the parentheses after the method name. Because several elements can have the same value for their class attribute, this method always returns a NodeList.
        *   This example starts by looking for elements whose class attribute contains hot. The value of class attributes can contain several class names, each separated by a space. The result of this DOM query is stored in a variable called elements because it is used more than once in the example.
        *   An if statement checks if the query found more than two elements. If so, the third one is selected and stored in a variable called el. The class attribute of that element is then updated to say class. In turn, this triggers a new CSS style, changing the presentation of that element.
*   Selecting Elements By Tag Name
    -   Example;
    -   let elements = document.getElementByTagName('li');          // Find li> elements
    -   if (elements.length > 0) {                                    // If 1 or more are found
    -   let el = elements[0];                                       // Select the first one using array syntax
    -   el.className = 'cool';                                      // Change the value of the class attribute
    -   }
        *   The getElementByTagName() method allows you to select elements using their tag names. The element name is specified as a parameter, so it is placed inside the parentheses and is contained by quote marks. Note that you do not include the angled brackets that surround the tag name in the HTML, just the letters inside the brackets.
        *   This example looks for any li> elements in the document. It stores the result in a variable called elements because the result is used more than once in this example.
        *   An if statement checks if any li> elements were found. As with any element that can return a NodeList, you check that there will be a suitable element before you try to work with it.
        *   If matching elements were found, the first one is selected and its class attribute is updated. This changes the color of the list item to make it aqua.
*   Selecting Elements Using CSS Selectors
    -   Example;
    -   // querySelector() only returns the first match
    -   let el = document.querySelector('li.hot');
    -   el.className = 'cool';
    -   // querySelectorAll returns a NodeList
    -   // The second matching element, the third list item, is selected and changed
    -   let els = document.querySelectorAll('li.hot');
    -   els[1].className = 'cool';
        *   querySelector() returns the first element node that matches the CSS-style selector. querySelectorAll() returns a NodeList of all the matches. Both methods take a CSS selector as their only parameter. The CSS selector syntax offers more flexibility and accuracy when selecting an element than just specifying a class name or a tag name, and should also be familiar to front-end web devs who are used to targeting elements using CSS.
        *   These two methods were introduced by browser manufacturers because a lot of devs were including scripts like jQuery in their pages so that they could select elements using CSS selectors. If you look at the final line of code, array syntax is used to select the second item from the NodeList, even though that NodeList is stored in a variable.
        *   JS code runs one line at a time, and statements affect the content of a page as the interpreter processes them.
        *   If a DOM query runs when a page leads, the same query could return different elements if it is used again later in the page. See the changes the JS makes in the HTML below.
            -   Example;
            -   ul> 
            -       li id = "one" class="hot">
            -           em>fresh/em> figs/li>
            -       li id="two" class="hot">pine nuts/li>
            -       li id="three" class="hot">honey/li>
            -       li id="four">balsamic vinegar/li>
            -   /ul>
                *   1. This is how the page starts. There are three li elements that have a class attribute whose value is hot. The querySelector() method finds the first one, and updates the value of its class from hot to cool. This also updates the DOM tree stored in memory so - after this line has run - only the second and third li elements have a class with a value of hot.
            -   ul> 
            -       li id = "one" class="COOL">
            -           em>fresh/em> figs/li>
            -       li id="two" class="hot">pine nuts/li>
            -       li id="three" class="hot">honey/li>
            -       li id="four">balsamic vinegar/li>
            -   /ul>
                * 2. When the second selector runs, there are now only two li elements whose class have a value of hot so it just selects these two. This time, array syntax is used to work with the second of the matching elements which is the third list item. Again the value of its class is changed from hot to cool.
            -   ul> 
            -       li id = "one" class="COOL">
            -           em>fresh/em> figs/li>
            -       li id="two" class="hot">pine nuts/li>
            -       li id="three" class="COOL">honey/li>
            -       li id="four">balsamic vinegar/li>
            -   /ul>
                *   3. When the second selector has done its job, the DOM tree now only holds one li element whose class has a value of hot. Any further code looking for li elements whose class value is hot would find only this one. However, if they were looking for li elements whose class value is cool, they would find two matching element nodes.
*   Repeating Actions For an Entire NodeList
    -   When you have a NodeList, you can loop through each node in the collection and apply the same statements to each.
    -   Example;
    -   let hotItems = document.querySelectorAll('li.hot');
    -   for (let i = 0; i < hotItems.length; i++) {
    -       hotItems[i].className = 'cool';
    -   }
        *   In this example, once a NodeList has been created, a for loop is used to go through each element in the NodeList. All of the statements inside the for loops curly braces are applied to each element in the NodeList one by one. To indicate which item of the NodeList is currently being worked with, the counter i is used in the array-style syntax.
        *   1. The variable hotItems contains a NodeList. It contains all list items whose class attribute has a value of hot. They are collected using the querySelectorAll() method.
        *   2. The length property of the NodeList indicates how many elements are in the NodeList. The number of elements dictates how many times the loop should run.
        *   3. Array syntax is used to indicate which item in the NodeList is currently being worked with: hotItems[i] it uses the counter variable inside the square brackets.
*   Looping through a NodeList
    -   Example;
    -   let hotItems = document.querySelectorAll('li.hot');     // Store NodeList in an array
    -   if (hotItems.length > 0) {                              // if it contains items
    -       for (let i = 0; i < hotItems.length; i++) {         // Loop through each item
    -           hotItems[i].className = 'cool';                 // Change value of class attribute
    -       }
    -   }
        *   If you want to apply the same code to numberous elements, looping through a NodeList is a powerful technique. It involves finding out how many items are in the NodeList, and then setting a counter to loop through them, one-by-one. Each time the loop runs, the script checks that the counter is less than the total number of items in the NodeList.
        *   In this example, the NodeList is generated using querySelectorAll(), and it is looking for any li> elements that have a class value of 'hot'
        *   The NodeList is stored in a variable called hotItems, and the number of elements in the list is found using the length property.
        *   For each of the elements in the NodeList, the value of the class attribute is changed to 'cool'
    -   Play-by-play
        *   for (let i = 0; i < hotItems.length; i++) {         // Loop through each item
        *       hotItems[i].className = 'cool';                 // Change value of class attribute
        *   }
            -   At the start of this example, there are three list items with a class attribute whose value is hot so the value of hotItems.length is 3
            -   At first, the value of the counter is set to 0, so the first item from the NodeList, which has an index of 0, is targeted and the value of its class attribute is set to cool.
            -   When the value of the counter is 1, the second item from the NodeList, whose index is 1, is targeted and the class is changed to cool.
            -   When the value of the counter is 2, the third item from the NodeList, whose index is 2, is targeted and the class is changed to cool.
            -   When the value of the counter is 3, the condition no longer returns true, so the loop ends. The script then continues to the first line of code after the loop.
*   Traversing the DOM
    -   When you have an element node, you can select another element in relation to it using these five properties. This is known as traversing the DOM
        *   parentNode - This property finds the element node for the containing, or parent, element in the HTML. If you started with the first li> element, then its parent node would be the one representing the ul> element.
        *   previousSibling/nextSibling - These properties find the previous or next sibling of a node if there are siblings. If you started with the first li> element, it would not have a previous sibling. However, its next sibling would be the node representing the second li>.
        *   firstChild/lastChild - These properties find the first or last child of the current element. If you started with the ul> element, the first child would be the node representing the first li> element, and the last child would be the last li>.
            -   These are properties of the current node not methods to select an element; therefore they do not end in parentheses.
            -   If you use these properties and they do not have a previous/next sibling or a last/first child, the result will be null.
            -   These properties are read-only; they can only be used to select a new node, not to update a parent, sibling, or child.
*   Whitespace nodes
    -   Traversing the DOM can be difficult because some browsers add a text node whenever they come across whitespace between elements. Most browsers, except IE, treat whitespaces between elements, such as spaces or carriage returns, as a text node, so the properties, previous/next sibling, and first/last child, return different elements in different browsers.
    -   One of the most popular ways to address this kind of problem is to use a JS library such as jQuery, which helps deal with such problems. These types of browser inconsistencies were a big factor in jQuery's popularity.
*   Previous & Next Sibling
    -   Example;
    -   HTML
    -   ul>li id="one" class="hot">em>fresh/em> figs/li>li> id="two" class="hot">pine nuts/li>li id="three" class="hot">honey/li>li> id="four">balsamic vinegar/li>/ul>
    -   JS
    -   // Select the starting point and find its siblings
    -   let startItem = document.getElementById('two');
    -   let prevItem = startItem.previousSibling;
    -   let nextItem = startItem.nextSibling;
    -   // Change the values of the siblings' class
    -   prevItem.className = 'complete';
    -   nextItem.className = 'cool';
        *   You have just seen that these properties can return inconsistent results in different browsers. However, it is safe to use them when there is no whitespace between elements. 
        *   For this example, all spaces between the HTML elements have been removed. In order to demonstrate these properties, the second list item is selected using getElementById().
        *   From this element node, the previousSibling property will return the first li> element, and the nextSibling property will return the third li> element.
        *   Note how references to sibling nodes are stored in new variables. This means properties such as className can be used on that node by adding the dot notation between the variable name and the property.
*   First & Last Child
    -   Example;
    -   HTML
    -   ul>
    -       li> id="one" class="hot">em>fresh/em> figs/li>
    -       li> id="two" class="hot">pine nuts/li>
    -       li> id="three" class="hot">honey/li>
    -       li> id="four">balsamic vinegar/li>
    -   ul>
    -   JavaScript
    -   //  Select the starting point and find its children
    -   let startItem = document.getElementByTagName('ul')[0];
    -   let firstItem = startItem.firstChild;
    -   let lastItem = startItem.lastChild;
    -   
    -   //  Change the values of the children's class attributes
    -   firstItem.setAttributes('class', 'complete');
    -   lastItem.setAttributes('class', 'cool');
        *   These properties also return inconsistent results if there is whitespace between elements. In this example, a slightly different solution is used in the HTML - the closing tags are put next to the opening tags of the next element, making it a little more readable. The example starts by using the getElementsByTagName() method to select the ul> element from the page. From this element node, the firstChild property will return the first li> element, and the lastChild property will return the last li> element.
*   How to get/update Element Content
    -   So far this chapter has focused on finding elements in the DOM tree. The rest of this chapter shows how to access/update element content. Your choice of techniques depends upon what the element contains.
    -   To work with the content of elements you can;
        *   Navigate to the text nodes. This works best when the element contains only text, no other elements.
        *   Work with the containing element. This allows you to access its text nodes and child elements. It works better when an element has text nodes and child elements that are siblings.
    -   Text Nodes - Once you have navigated from an element to its text node, there is one property that you will commonly find yourself using:
        *   property = node value, description = Accesses text from node
    -   Containing Element - When you are working with an element node, rather than its text node, that element can contain markup. You have to choose whether you want to retrieve (get) or update (set) the markup as well as the text.
        *   When you use these properties to update the content of an element, the new content will overwrite the entire contents of the element, both text and markup. For example, if you used any of these properties to update the content of the body> element, it would update the entire web page.
        *   property = innerHTML, description = Gets/sets text and markup
        *   property = textContent, description = Gets/sets text only
        *   property = innerText, description = Gets/sets text only
*   Access & Update a Text Node with NodeValue
    -   When you select a text node, you can retrieve or amend the content of it using the nodeValue property.
    -   In order to use nodeValue, you must be on a text node, not the element that contains the text.
    -   example;
    -   li id="one">em>fresh/em> figs/li>
    -   document.getElementById('one').firstChild.nextSibling.nodeValue
        *   getElementById selects the li> element
        *   em> element is the first child of li>
        *   the text node is the next sibling of the em> element
        *   now that you have the text node you can get its value with nodeValue
*   Accessing & Changing a Text Node
    -   example;
    -   let itemTwo = document.getElementById('two');       // Get second list item
    -   let elText = itemTwo.firstChild.nodeValue;          // Get its text content
    -   elText = elText.replace('pine nuts', 'kale');       // Change pine nuts to kale
    -   itemTwo.firstChild.nodeValue = elText;              // Update the list item
        *   To work with text in an element, first the element node is accessed and then its text node. The text node has a property called nodeValue which returns the text in that text node. You can also use the nodeValue property to update the content of a text node.
        *   This example takes the text content of the second list item and changes it from pine nuts to kale.
        *   The fist line collects the second list item.. It is stored in a variable called itemTwo.
        *   Next the text content of that element is stored in a variable called elText.
        *   The third line of the text replaces the words 'pine nuts' with 'kale' using the String object's replace() method.
        *   The last line uses the nodeValue property to update the content of the text node with the updated value.
*   Access & Update Text with textContent and innerText
    -   The textContent property allows you to collect or update just the text that is in the containing element and its children
    -   textContent
        *   To collect the text from the li> elements in our example and ignore any markup inside the element, you can use the textContent property on the containing li> element. In this case it would return the value: fresh figs
        *   You can also use this property to update the content of the element; it replaces the entire content of it, including any markup.
        *   One issue with textContent property is that IE did not support until IE9
    -   innerText - should be avoided...
        *   Support - Although most browser manufacturers adopted the property, firefox does not because innerText is not part of any standard.
        *   Obeys CSS - It will not show any content that has been hidden by CSS. For example, if there were a CSS rule that hid the em> elements, the innerText would return only the word figs.
        *   Performance - Because the innerText property takes into account layout rules that specify whether the element is visible or not, it can be slower to retrieve the content than the textContent property.
*   Accessing Text Only
    -   example;
    -   let firstItem = document.getElementById('one');         // Find first list item
    -   let showTextContent = firstItem.textContent;            // Get Value of textContent
    -   let showInnerText = fisrtItem.innerText;                // Get value of innerText
    -   
    -   // Show the content of these two properties at the end of the list
    -   let msg = 'p>textContent: ' + showTextContent + ' /p>';
    -       msg += 'p>innerText: ' + showInnerText + '/p>';
    -   let el = document.getElementById('scriptResults');
    -   el.innerHTML = msg;
    -   firstItem.textContent = 'sourdough bread';              // Update the first list item
        *   In order to demonstrate the difference between textContent and innerText, this example features a CSS rule to hide the contents of em>.
        *   In most browsers, the textContent collects the words fresh figs, innerText just shows figs because fresh (em) was hidden by CSS
*   Adding or Removing HTML Content
    -   There are two very different approaches to adding and removing content from a DOM tree: the innerHTML property and DOM manipulation.
    -   The innerHTML Property
        *   Note: there are security risks associated with using innerHTML
    -   Approach
        *   innerHTML can be used on any element node. It is used both to retrieve and replace content. To update an element, new content is provided as a string. It can contain markup for descendant elements.
    -   Adding Content
        *   To add new content:
            -   1. Store new content, including markup, as a string in a variable.
            -   2. Select the element whose content you want to replace.
            -   3. Set the element's innerHTML property to be the new string.
    -   Removing Content
        *   To remove all content from an element, you set innerHTML to an empty string. To remove one element from a DOM fragment, you need to provide the entire fragment minus that element.
    -   Example; Changing a list item
        *   1. Create variable holding markup
        *   let item;
        *   item = 'em>Fresh/em> figs';
        *   You can have as much or as little markup in the variable as you want. It is a quick way to add a lot of markup to the DOM tree.
        *   2. Select element whose content you want to update. i.e. the li> element.
        *   3. Update content of selected element with new markup.
    -   DOM Manipulation Methods - DOM manipulation easily targets individual nodes in the DOM tree, whereas innerHTML is better suited to updating entire fragments.
    -   Approach
        *   DOM manipulation refers to a set of DOM methods that allow you to create element and text nodes, and then attach them to the DOM tree or remove them from the DOM tree.
    -   Adding content
        *   To add content, you use a DOM method to create new content one node at a time and store it in a variable. Then another DOM method is used to attach it to the right place in the DOM tree.
    -   Removing content
        *   You can remove an element, along with any contents and child elements it may contain, from the DOM tree using a single method.
    -   Example; Adding a list item
        *   1. Create a new text node
        *   2. Create new element node
        *   3. Add text node to element node
        *   4. Select element you want to add the new fragment to
        *   5. Append the new fragment to the selected element
*   Access & Update Text & Markup with innerHTML
    -   Using innerHTML, you can access and amend the contents of an element, including any child elements.
    -   When getting HTML from an element, the innerHTML property will get the content of an element and return it as one long string, including any markup that the element contains.
    -   When used to set new content for an element, it will take a string that can contain markup and process that string, adding any elements within it to the markup.
    -   Get content
        *   let elContent = document.getElementById('one').innerHTML
            -   Collects the content of the list item and adds it to a variable elContent.
        *   'em>fresh/em> figs'
            -   The elContent variable now holds this string.
        *   document.getElementById('one').innerHTML = elContent;
            -   Adds content of the elContent variable, including markup, to the first li> item
                *   Note: When adding new content using innerHTML, be aware that one missing closing tag could throw out the design of the entire page. Even worse, if innerHTML is used to add content that your users created to a page, they could add malicious content.
*   Update Text & Markup
    -   Example;
    -   //  Store the first list item in a variable
    -   let firstItem = document.getElementById('one');
    -   //  Get the content of the first list item
    -   let itemContent = firstItem.innerHTML;
    -   //  Update the content of the first list item so it is a link
    -   firstItem.innerHTML = 'a href=\"http://example.org\">' + itemContent + '/a>';
        *   This example starts by storing the first list item in a variable called firstItem
        *   It then retrieves the content of this list item and stores it in a variable called itemContent.
        *   Finally, the content of the list item is placed inside a link. Note how the quotes are escaped.
        *   As the content of the string is added to the element using the innerHTML property, the browser will add any elements in the string to the DOM. In this example, an a> element has been added to the page. 
        *   If you see attributes in your HTML code, escaping the quotation using backslash character can make it clearer that those characters are not part of the script.
*   Adding Elements Using DOM Manipulation
    -   DOM manipulation offers another technique to add new content to a page. It involves 3 steps.
        *   Create the element - createElement()
            -   Use this method to create a new node and store it in a variable, it is not yet added to the DOM tree.
        *   Give it content - createTextNode()
            -   Creates new text node and stores it in a variable. It can be added to the element node using appendChild() method. This provides the content for the element, although you can skip if you want to attach empty element to the DOM tree.
        *   Add it to the DOM - appendChild()
            -   This adds it to the DOM tree. Allows you to specify which element you want this node added to as a child of it.
*   Adding An Element to the DOM Tree
    -   Example;
    -   //  Create a new element and store it in a variable
    -   let newEl = document.createElement('li');
    -   //  Create a text node and store it in a variable\
    -   let newText = document.createTextNode('quinoa');
    -   //  Attach the new text node to the new element
    -   newEl.appendChild(newText);
    -   //  Find the position where the new element should be added
    -   let position = document.getElementByTagName('ul')[0];
    -   //  Insert the new element into its position
    -   position.appendChild(newEl)
*   Removing Elements via DOM Manipulation
    -   DOM manipulation can be used to remove elements from the DOM tree.
        *   1. Store the element to be removed in a variable
            -   You start by selecting the element that is going to be removed and store that element node in a variable
            -   You can use any of the methods you saw in the section on DOM queries to select the element
        *   2. Store the parent of that element in a variable
            -   Next, you find the parent element that contains the element you want to remove and store that element node in a variable
            -   The simplest way to get this element is to use the parentNode property of this element
        *   3. Remove the element from its containing element
            -   The removeChild() method takes one parameter: the reference to the element that you no longer want
    -   When you remove an element from the DOM, it will also remove any child elements.
    -   Removing elements from the DOM will affect the index number of siblings in a NodeList
*   Removing an Element from the DOM Tree
    -   Example;
    -   let removeEl = document.getElementByTagName('li)[3];        // The element to remove
    -   let containEl = removeEl.parentNode;                        // Its containing element
    -   containerEl.removeChild(removeEl);                          // Remove the element
        *   This example uses the removeChild() method to remove the fourth item from the list, along with its contents.
        *   The first variable, removeEl, stores the actual element you want to remove from the page, the fourth list item.
        *   The second variable, containerEl, stores the ul> element that contains the element you want to remove.
        *   The removeChild() method is used on the variable that holds the container node.
        *   It requires one parameter: the element you want to remove, which is stored in the second variable.
*   Comparing Techniques: Updating HTML Content
    -   So far, you have seen three techniques for adding HTML to a web page...
    -   document.write()
        *   The document object's write() method is a simple way to add content that was not in the original source code to the page, but its use is rarely advised.
        *   Advantages;
            -   It is a quick and easy way to show beginners how content can be added to a page.
        *   Disadvantages;
            -   It only works when the page initially loads
            -   If you use it after the page has loaded it can...
                *   overwrite the whole page
                *   not add the content to the page
                *   create a new page
            -   It can cause problems with XHTML pages that are strictly validated
            -   This method is very rarely used by programmers these days and is generally frowned upon
    -   element.innerHTML
        *   The innerHTML property lets you get/update the entire content of any element, including markup, as a string.
        *   Advantages;
            -   You can use it to add a lot of new markup using less code than DOM manipulation methods
            -   It can be faster than DOM manipulation when adding a lot of new element to a web page
            -   It is a simple way to remove all of the content from one element, by assigning it a blank string
        *   Disadvantages;
            -   It should not be used to add content that has come from a user, such as a username or blog comment, as it can pose a significant security risk which is discussed later
            -   It can be difficult to isolate single elements that you want to update within a larger DOM fragment
            -   Event handlers may no longer work as intended
    -   DOM Manipulation
        *   DOM manipulation refers to using a set of methods and properties to access, create and update elements and text nodes.
        *   Advantages;
            -   It is suited to changing one element from a DOM fragment where there are many siblings.
            -   It does not affect event handlers
            -   It easily allows a script to add elements incrementally, when you do not want to alter a lot of code at once.
        *   Disadvantages;
            -   If you have to make a lot of changes to the content of a page, it is slower than innerHTML
            -   You need to write more code to achieve the same thing compared with innerHTML
*   Cross-site Scripting (XSS) Attacks
    -   If you add HTML to a page using innerHTML, or several jQuery methods, and attacker could gain access to your users' accounts.
    -   How XSS happens;
        *   XSS involves an attacker placing malicious code into a site. Websites often feature content created by many different people. i.e.
            -   Users can create profiles or add comments
            -   Multiple authors may contribute articles
            -   Data can come from third-party sites such as Facebook, Twitter, news tickers, and other feeds
            -   Files such as images and video may be uploaded
        *   Data you do not have complete control over is known as untrusted data; it must be handled with care.
        *   What can these attacks do?
            -   XSS can give the attacker access to information in:
                *   The DOM, including form data
                *   That websites cookies
                *   Session tokens: information that identifies you from other users when you log into a site
            -   This could let the attacker access a user account and:
                *   Make purchases with that account
                *   Post defamatory content
                *   Spread their malicious code further/faster
    -   Even simple code can cause problems - malicious code often mixes HTML and JS, although URLs and CSS can be used to trigger XSS attacks.
*   Defending Against Cross-site Scripting
    -   Validate Input Going to the Server
        *   1. Only let visitors input the kind of characters they need to when supplying information. This is known as validation. Do not allow untrested users to submit HTML markup or JS.
        *   2. Double-check validation on the server before displaying user content/storing it in a database. This is important because users could bypass validation in the browser by turning JS off.
        *   3. The database may safely contain markup and script from trusted sources, i.e. your content management system. This is because it does not try to process the code; it just stores it.
        *   4. As your data leaves the database, all potentially dangerous characters should be escaped.
        *   5. Make sure that you are only inserting content generated by users into certain parts of the template files.
        *   6. Do not create DOM fragments containing HTML from untrusted sources. It should only be added as text once it has been escaped.
*   XSS: Validation & Templates
    -   Make sure your users can only input characters they need to use and limit where this content will be shown on the page.
    -   Filter or validate input
        *   The most basic defense is to prevent users from entering characters into form fields that they don't need to use when providing that kind of information.
        *   For example, users' names and email addresses will not contain angled brackets, ampersands, or parentheses, so you can validate data to prevent characters like this being used.
        *   This can be done in the browser, but must also be done on the server, in case the user has JS turned off. 
    -   Limit where content user goes
        *   Malicious users will not just use script tags to try and create an XSS attack. Malicious code can live in an event handler attribute without being wrapped in script tags. XSS can also be triggered by malicious code in CSS or URLs.
        *   Browsers process HTML, CSS, and JavaScript in different ways, or execution contexts, and in each language different characters can cause problems. Therefore, you should only add content from untrusted sources as text, not markup, and place that text in elements that are visible in the viewport.
    -   You have seen that the comment sections on websites rarely allow you to enter a lot of markup, sometimes they allow a limited subset of HTML. This is to prevent people from entering malicious code such as script tags, or any other character with an event handling attribute.
    -   Even HTML editors used in many content management systems will limit the code that you are allowed to use within them, and will automatically try to correct any markup that looks malicious.
    -   NEVER place any user's content in the following places without detailed experience of the issues involved.
        *   Script tags: script>not here/script>
        *   HTML comments: !-- note here-->
        *   Tag names: notHere href="/test" />
        *   Attributes: div notHere="norHere" />
        *   CSS values: {color: not here}4
*   XSS: Escaping & Controlling Markup
    -   Any content generated by users that contain characters that are used in code should be escaped on the server. You must control any markup added to the page.
    -   Escaping User Content
        *   All data from untrusted sources should be escaped on the server before it is shown on the page. Most sever-side languages offer helper functions that will strip-out or escape malicious code.
    -   HTML - Escape these characters so that they are displayed as characters, not processed as code
        *   &   &amp;   '   &#x27; (not &apos;)
        *   <   &lt;    "   &quot;
        *   >   &gt;    /   &#x2f;
        *   `   &#x60;
    -   JavaScript
        *   Never include data from untrusted sources in JavaScript. It involves escaping all ASCII characters with a value less than 256 that are not alphanumeric characters, and can be a security risk.
    -   URLs
        *   If you have links containing user input, i.e. links to a user profile or search queries, use the JS encodeURIComponent() method to encode the user input. It encodes the following characters: , / ? : @ & = + $ #
    -   Adding user content
        *   When you add user content to an HTML page, once it has been escaped on the server, it should still be added to the page as text. JS and JQuery both offer tools for doing this:
        *   JS
            -   Do use: textContent or innerText
            -   Do Not use: innerHTML
        *   JQuery
            -   Do use: .text()
            -   Do Not use: .html()
        *   You can still use innerHTML property and jQuery.html() method to add HTML to the DOM, but you must make sure that:
            -   You control all of the markup being generated, do not allow user content that could contain markup.
            -   The user's content is escaped and added as text using the approaches noted above, rather than adding the user's content as HTML.
*   Attribute Nodes
    -   Once you have an element node, you can use other properties and methods on that element node to access and change its attributes.
        *   There are two steps to accessing and updating attributes. 
            -   First, select the element node that carries the attribute and follow it with a period symbol
            -   Then, use one of the methods or properties below to work with that elemetn's attribute
                *   Example;
                *   document.getElementById('one').getAttribute('class');
        *   Method                  Description
        *   getAttribute()          gets the value of an attribute
        *   hasAttribute()          checks if element node has a specified attribute
        *   setAttribute()          sets the value of an attribute
        *   removeAttribute()       removes an attribute from an element node
        *   
        *   Property                Description
        *   className               gets or sets the value of the class attribute
        *   id                      gets or sets the value of the id attribute
            -   You have seen that the DOM treats each HTML element as its own object in the DOM tree. The properties of the object correspond to the attributes that type of element can carry. 
*   Check for an Attribute and get its Values
    -   Example;
    -   let firstItem = document.getElementById('one');     // Get first list item
    -   if (firstItem.hasAttribute('class')) {              // If it has class attribute
    -       let attr = firstItem.getAttribute('class');     // Get the attribute
    -       // Add the value of the attribute after the list
    -       let el = document.getElementById('scriptResults);
    -       el.innerHTML = 'p>The first item has a class name: ' + attr + '/p>;
    -   }
        *   Before you work with an attribute, it is good practice to check whether it exists. This will save resources if the attribute cannot be found. The hasAttribute() method of any element node lets you check if an attribute exists. The attribute name is given as an argument in the parentheses. Using hasAttribute() in an if statement like this means that the code inside the curly braces will run only if the attribute exists on the given element.
        *   In this example, the DOM query getElementById() returns the element whose id attribute has a value of one.
        *   the hasAttribute() method is used to check whether this element has a class attribute, and returns a Boolean. This is used with an if statement so that the code in the curly braces will run only if the class attribute does exist.
        *   The getAttribute() method returns the value of the class attribute, which is then written to the page.
*   Creating Attributes & Changing their Values
    -   Example;
    -   let firstItem = document.getElementById('one')      // Get the first item
    -   firstItem.className = 'complete';                   // Change its class attribute
    -   
    -   let fourthItem = document.getElementByTagName('li').item(3);    // Get fourth item
    -   fourthItem.setAttribute('class', 'cool');           // Add an attribute to it
        *   The classname property allows you to change the value of the class attribute. If the attribute does not exist, it will be created and given the specified value.
        *   You have seen this property used throughout the chapter to update the status of the list items. Here, you see another way to achieve this task.
        *   The setAttribute() method allows you to update the value of any attribute. It takes two parameters: the attribute name, and the value for the attribute.
        *   When there is a property, like the className or id properties, it is generally considered better to update the properties rather than use a method because behind the scenes, the method would just be setting the properties anyway.
        *   When you update the value of an attribute, especially the class attribute, it can be used to trigger new CSS rules, and therefore change the appearance of the elements.
        *   NOTE: These techniques override the entire value of the class attribute. They do not add a new value to the existing value of the class attribute.
        *   If you wanted to add a new value onto the existing value of the class attribute, you would need to read the content of the attribute first, then add the new text to that existing value of the attribute, or use the jQuery.addClass() method covered on pg320.
*   Removing Attributes
    -   Example;
    -   let firstItem = document.getElementById('one');         // Get the first item
    -   if (firstItem.hasAttribute('class')) {                  // If it has a class attribute
    -       firstItem.removeAttribute('class');                 // Remove its class attribute
    -   }
        *   To remove an attribute from an element, first select the element, then call removeAttribute(). It has one parameter: the name of the attribute to remove.
        *   Trying to remove an attribute that does not exist will not cause an error, but it is good practice to check for its existence before attempting to remove it.
        *   In this example, the getElementById() method is used to retrieve the first item from this list, which has an id attribute with a value of one.
        *   The script checks to see if the selected element has a class attribute and, if so, it is removed.
*   Examing the DOM in Chrome
    -   Modern browsers come with tools that help you inspect the page loaded in the browser and understand the structure of the DOM tree.
        *   To get the developer tools in Chrome on a mac, go to the view menu, select developer and then developer tools. On a PC, go to tools or more tools and select developer tools. Or right-click on any element and select inspect element.
        *   Select Elements from the menu that runs across the top of this tool. The source of the page will be shown on the left and several other options to the right. Any element that has child elements has an arrow next to it that lets you expand and collapse the item to show and hide its content.
        *   The properties panel tells you the type of object the selected element is, in some versions of Chrome this is shown as a tab. When you highlight different elements in the main left-hand window, you can see the values in the properties panel on the right reflect that element.
*   Examining DOM in FireFox
    -   FireFox has similar built-in-tools, but you can also download a DOM inspector tool that shows the text nodes.
        *   If you search online for DOM inspector, you will find the tool designed for FireFox shown on the left. In the screen shot, you can see a similar tree view to the one shown in Chrome, but it also shows you where there are whitespace nodes, they are shown as text. In the panel to the right, you can see the value in the nodes; whitespace nodes have no value in this panel.
        *   FireFox also has a 3d view of the DOM, where a box is drawn around each element, and you can change the angle of the page to show which parts of it stick out more than others. The further they protrude the further into child elements they appear.
        *   This can give you an interesting and quick glimpse into the compexity of the markup used on a page and the depth to which elements are nested.
##  Events
*   Events
    -   When you browse the web, your browser registers different types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events.
        *   Scripts often respond to these events by updating the content of the web page (via the DOM) which makes the page feel more interactive. In this section, you will learn how.
        *   Interactions Create Events
            -   Events occur when users click or tap on a link, hover or swipe over an element, type on the keyboard, resize the window, or when the page they requested has loaded. 
        *   Events Trigger Code
            -   When an event occurs, or fires, it can be used to trigger a particular function. Different code can be triggered when users interact with different parts of the page.
        *   Code Responds to Users
            -   In the last chapter, you saw how the DOM can be used to update a page. The events can trigger the kinds of changes the DOM is capable of. This is how a web page reacts to users.
*   Different Event Types
    -   Here is a selection of the events that occur in the browser while you are browsing the web. Any of these events can be used to trigger a function in your JS code. 
    -   UI Events
        *   Event           Description
        *   
        *   load            Web page has finished loading
        *   unload          Web page is unloading(usually because a new page was requested)
        *   error           Browser encounters a JS error or an asset doesn't exist
        *   resize          Browser window has been resized
        *   scroll          User has scrolled up or down the page
    -   Keyboard Events
        *   keydown         User first presses a key(repeats while a key is depressed)
        *   keyup           User releases a key
        *   keypress        Character is being inserted(repeats while key is depressed)
    -   Mouse Events
        *   click           User presses and releases a button over the same element
        *   dblclick        User presses and releases a button twice over the same element
        *   mousedown       User presses a mouse button while over an element
        *   mouseup         User releases a mouse button while over an element
        *   mousemove       User moves the mouse(not a touchscreen)
        *   mouseover       User moves the mouse over an element(not touchscreen)
        *   mouseout        User moves the mouse off an element(not touchscreen)
    -   Focus Events
        *   focus/focusin   Element gains focus
        *   blur/focusout   Element loses focus
    -   Form Events
        *   input           Value in any input> or textarea> has changed, or any element with contenteditable attribute
        *   change          Value in select box, checkbox, or radio button changes
        *   submit          User submits a form using button or key
        *   reset           User clicks on a form's reset button, rare these days
        *   cut             User cuts content from a form field
        *   copy            User copies content from a form field
        *   paste           User pastes content into a form field
        *   select          User selects some text in a form field
    -   Mutation Events
        *   DOMSubtreeModified  Change has been made to document
        *   DOMNodeInserted     Node has been inserted as a direct child of another node
        *   DOMNodeRemoved      Node has been removed from another node
        *   DOMNodeInsertedIntoDocument Node has been inserted as a descendant of another node
        *   DOMNodeRemovedFromDocument  Node has been removed as a descendant of another node
            -   Events fire or are raised
                *   When an event has occurred, it is often described as having fired or been raised.
            -   Events trigger scripts
                *   Events are said to trigger a function or script.
*   How Events Trigger JS Code
    -   When the user interacts with the HTML on a web page, there are three steps involved in getting it to trigger some JS code. Together these steps are known as event handling.
        *   1. Select the element node(s) you want the script to respond to.
            -   For example, if you want to trigger a function when a user clicks on a specific link, you need to get the DOM node for that link element. You do this using a DOM query.
        *   2. Indicate which event on the selected node(s) will trigger the response.
            -   Programmers call this binding and event to a DOM node. The previous two pages showed a selection of the popular events that you can monitor for. 
        *   3. State the code you want to run when the event occurs.
            -   When the event occurs, on a specified element, it will trigger a function. This may be a named or an anonymous function.
                *   The UI events that relate to the browser window, rather than the HTML page loaded in it, work with the window object rather than an element node. Examples include the events that occur when a requested page has finished loading, or when the user scrolls. Some events work with most element nodes, such as the mouseover event, which is triggered when the user rolls over any element. Other events only work with specific element nodes, such as the submit event, which only works with a form.
    -   Here you can see how event handling can be used to provide feedback to users filling in a registration form. It will how an error message if their username is too short.
        *   1. Select Element
            -   The element that users are interacting with is the text input where they inter the username
        *   2. Specify Event
            -   When users move out of the text input, it loses focus, and the blur event fires on this element.
        *   3. Call Code
            -   When the blur event fires on the username input, it will trigger a function called checkUsername(). This function checks if the username is less than 5 characters.
            -   If there are not enough characters, it shows an error message that prompts the user to enter a longer username.
            -   If there are enough characters, the element that holds the error message should be cleared.
            -   This is because an error message may have been shown to the user already and they subsequently corrected their mistake. If the error message was still visible when they had filled in the form correctly, it would be confusing.
*   Three Ways to Bind an Event to an Element
    -   Event handlers let you indicate which event you are waiting for on any particular element. There are three types of event handlers.
    -   HTML Event Handlers
        *   This is bad practice but you need to be aware of it because you may see it in older code.
        *   Early versions of HTML included a set of attributes that could respond to events on the element they were added to. The attribute names matched the event names. their values called the functions that were to run when that event occured. 
        *   For example, a onclick="hide()"> indicated that when a user clicked on this a> element, the hide() function would be called.
        *   This method of event handling is no longer used because it is better to separate the JS from the HTML. You should use one of the other approaches shown now.
    -   Traditional DOM Event Handlers
        *   DOM event handlers were introduced in the original specification for the DOM. They are considered better than HTML event handlers because they let you separate the JS from the HTML.
        *   Support in all major browsers is very strong for this approach. The main drawback is that you can only attach a single function to any event. For example, the submit event of a form cannot trigger one function that checks the contents of a form, and a second to submit the form data if it passes the check.
        *   As a result of this limitation, if more than one script is used on the same page, and both scripts respond to the same event, then one or both of the scripts may not work as intended.
    -   DOM Level 2 Event Listeners
        *   Event listeners were introduced in an update to the DOM specification, they are now the favored way of handling events.
        *   The syntax is quite different and, unlike traditional event handlers, these newer event listeners allow one event to trigger multiple functions. As a result, there are less likely to be conflicts between different scripts that run on the same page.
        *   This approach does not work with IE8 or earlier. Differences in browser support for the DOM and events helped speed adoption of jQuery.
*   HTML Event Handler Attributes (DO NOT USE)
    -   In the HTML, the first input> element has an attribute called onblur, triggered when the user leaves the element. The value of the attribute is the name of the function that it should trigger. The value of the event handler attribute would be JS. Often it would call a function that was written either in the head> element or a separate JS file.
    -   a> elements can have onclick, onmouseover, onmouseout, form> elements can have onsubmit, input> elements for text can have onkeypress, onfocus, onblur.
*   Traditional DOM Event Handlers
    -   All modern browsers understand this way of creating an event handler, but you can only attach one function to each event handler.
    -   Example;
    -   element.onevent = functionName;
    -   This is the syntax to bind an event to an element using an event handler, and to indicate which function should execute when that event fires.
    -   Example 2;
    -   function checkUsername() {
    -   // code to check the length of username
    -   }
    -   let el = document.getElementById('username');
    -   el.onblur = checkUsername;
        *   Here, the event handler is on the last line, after the function has been defined and the DOM element node selected.
        *   When a function is called, the parentheses that follow its name tell the JS interpreter to "run this code now"
        *   We don't want the code to run until the event fires, so the parentheses are omitted from the event handler on the last line.
*   Using DOM Event Handlers
    -   Example;
    -   function checkUsername() {                                              // Declare function
    -       let elMsg = document.getElementById('feedback');                    // Get feedback element
    -       if (this.value.length < 5) {                                        // If username too short
    -       elMsg.textContent = 'Username must be 5 characters or more';        // Set message
    -       } else {                                                            // Otherwise
    -       elMsg.textContent = '';                                             // Clear message
    -       }
    -   }
    -   let elUsername = document.getElementById('username');                   // Get username input
    -   elUsername.onblur = checkUsername;                                      // When it loses focus call checkUsername()
        *   In this example, the event handler appears on the last line of the JS. Before the DOM event handler, two things are put in place:
            -   If you use a named function when the event fires on your chosen DOM node, write that function first.
            -   The DOM element node is stored in a variable. Here the text input, whose id attribute has a value of username, is placed into a variable called elUsername.
        *   When using event handlers, the event name is preceded by the word "on"... onsubmit, onchange, onfocus, onblur...
            -   On the last line of the code, the event handler elUsername.onblur indicates that the code is waiting for the blur event to fire on the element stored in the variable called elUsername.
            -   This is followed by an = sign, then the name of the function that will run when the event fires on that element. Note that there are no parentheses on the function name. This means you cannot pass arguments to this function.
            -   Browser support: on line 3, the checkUsername() function uses the this keyword in the conditional statement to check the number of characters the user entered. It works in most browsers because they know this refers to the element the event happened on.
*   Event Listeners
    -   Event listeners are a more recent approach to handling events. They can deal with more than one function at a time but they are not supported in older browsers.
    -   Example;
    -   Syntax: element.addEventListener('event', functionName, [boolean])
    -   function checkUsername() {
    -       // code to check the length of username
    -   }
    -   let el = document.getElementById('username');
    -   el.addEventListener('blur', checkUsername, false);
        *   A reference to the DOM element node is often stored in a variable
        *   The code starts by defining the named function. 
        *   The Function is called by the event listener on the last line, but the parentheses are omitted.
*   Using Event Listeners
    -   Example;
    -   function checkUsername() {                                              // Declare function
    -       let elMsg = document.getElementById('feedback');                    // Get feedback element
    -       if (this.value.length < 5) {                                        // If username too short
    -       elMsg.textContent = 'Username must be 5 characters or more';        // Set message
    -       } else {                                                            // Otherwise
    -       elMsg.textContent = '';                                             // Clear message
    -       }
    -   }
    -   let elUsername = document.getElementById('username');                   // Get username input
                  
    -   elUsername.addEventListener('blur', checkUsername, false)               // When it loses focus call checkUsername()
        *   The event listener appears on the last line, before you write an event listener...
            -   If you use a named function when the event fires on your chosen DOM node, write that function first.
            -   The DOM element node is stored in a variable. Here the text input, whose id attribute has a value of username, is placed into a variable called elUsername.
            -   The addEventListener() method takes 3 properties
                *   The event you want it to listen for. blur
                *   The code that you want it to run when the event fires. checkUsername() Function. Parantheses omitted since it can't take an argument.
                *   A Boolean indicating how events flow.
*   Using Parameters with Event Handlers & Listeners
    -   Because you cannot have parentheses after the function names in event handlers or listeners, passing arguments requires a workaround
        *   Usually, when a function needs some information to do its job, you pass arguments within the parentheses that follow the function name. When the interpreter sees the parentheses after a function call, it runs the code straight away. In an event handler, you want it to wait until the event triggers it. Therefore, if you need to pass arguments to a function that is called by an event handler or listener, you wrap the function call in an anonymous function.
            -   el.addEventListener('blur', function() {
            -   checkUsername(5);
            -   }, false);
                *   The named function (checkUsername) includes parentheses containing the parameter after the function name.
                *   The anonymous function (function()) is used as the second argument. It "wraps around" the named function.
            -   The named function that requires the arguments lives inside the anonymous function. Although the anonymous function has parentheses, it only runs when the even is triggered. The named function can use arguments as it only runs if the anonymous function is called.
*   Using Parameters with Event Listeners
    -   Example:
    -   let elUsername = document.getElementById('username');               // Get username input
    -   let elMsh = document.getElementById('feedback');                    // Get feedback element
    -   function checkUsername(minLenght) {                                 //  Declare function
    -       if (elUsername.value.length < minLength) {                      // If username too short
    -       // Set the error message
    -       elMsg.textContent = 'Username must be ' + minLength + ' characters or more';
    -     } else {                                                          // Otherwise
    -       elMsg.innerHTML = '';                                           // Clear message
    -     }
    -   }
    -   elUsername.addEventListener('blur', function() {                    // When it loses focus
    -       checkUsername(5);                                               // Pass argument here
    -   }, false);
        *   The first line of this example shows the updated checkUsername() function. The minLength parameter specifies the minimum number of characters that the username should be.
        *   The value that is passed into checkUsername() function is used in the conditional statement to check if the name is long enough, and provide feedback if the username name is too short.
        *   The Event Listener on the last three lines is longer than the previous example because the call to the checkUsername() function needs to include the value for the minLength parameter.
        *   To recieve this information, the event listener uses an anonymous function, which acts like a wrapper. Inside that wrapper the checkUsername() function is called, and passed an argument.
*   Browser Support IE5-8
    -   IE 5-8 did not support addEventListener(). Instead it used its own method called attachEvent(). Use conditional statement below in its stead for IE 5-8.
        *   if (el.addEventListener) {
        *     el.addEventListener('blur', function(){
        *       checkUsername(5);
        *       }, false );
        *   } else {
        *       el.attachEvent('onblur', function() {
        *           checkUsername(5);
        *       });
        *   }
            -   Using an if...else statement, you can check if the browser supports the addEvenListener() method. The condition in the if statement will return true if the browser supports the addEventListener, and you can use it. If the browser down not support the method, it returns false, and the code will try to use the attachEvent method.
*   Event Flow
    -   HTML elements nest inside other elements. If you hover or click on a link, you will also be hovering or clicking on its parent elements.
    -   Imagine a list item contains a link. When you hover over the link or click on it, JS can trigger events on the a> element, and also any elements the a> element sits inside.
    -   Event handlers/listeners can be bound to the containing li>, ul>, and html> elements, plus the document object, and the window object. The order in which the events fire is known as event flow, and events flow in two directions.
        *   Event Bubbling - The event starts at the most-specific node and flows outwards to the least specific one. This is the default type of event flow with very wide browser support.
        *   Event Capturing - The event starts at the least specific node and flows inwards to the most specific one. This is not supported in IE 8 and earlier.
*   Why Flow Matters?!
    -   The flow of events only really matter when your code has event handlers on an element and one of its ancestor or descendant elements.
*   The Event Object
    -   When an event occurs, the event object tells you information about the event, and the element it happened upon.
        *   Everytime an event fires, the event object contains helpful data about the event such as;
            -   Which element the event happened on
            -   Which key was pressed for a keypress event
            -   What part of the viewport the user clicked for a click event
        *   The event object is passed to any function that is the event handler or listener. If you need to pass arguments to a named function, the event object will first be passed to the anonymous wrapper function (automatically), then you must specify it as a parameter of the named function. When the event object is passed into a function, it is often given the parameter name e for event. It is a widely used shorthand.
            -   Note, however, that some programmers also use the parameter name e to refer to the error object; so e may mean event or error.
    -   Examples;
    -   property;   Purpose;
    -   target      The target of the event, most specific element intaracted with
    -   type        Type of event that was fired
    -   cancelable  Whether you can cancel the default behavior of an element
    -
    -   Method;     Purpose
    -   preventDefault()    Cancel default behavior of the event if it can be canceled
    -   stopPropagation()   Stops the event from bubbling or capturing any further
*   Event Delegation
    -   Creating event listeners for a lot of elements can slow down a page, but event flow allows you to listen for an event on a parent element. 
        *   If users can interact with a lot of elements on the page, such as; a lot of buttons in the UI, a long list, every cell of a table.... adding event listeners to each element can use a lot of memory and slow down performance.
        *   Because events affect containing or ancestor elements, you can place event handlers on a containing element and use the event object's target property to find which of its children the event happened on. By attaching an event listener to a containing element, you are only responding to one element, rather than having an event handler for each child element. You are delegating the job of the event listener to a parent of the elements.
        *   other benefits include;
            -   Works with new elements; If you add new elements to the DOM tree, you do not have to add event handlers to the new elements because the job has been delegated to an ancestor.
            -   Solves limitations with THIS keyword; the THIS keyword is used to identify an event's target, but that technique did not work when the function needed parameters.
            -   Simplifies your code; It requires fewer functions to be written, and there are fewer ties between the DOM and your code, which helps maintainability.
*   Changing Default Behavior
    -   The event object has methods that change: the default behavior of and element and how the element's ancestors respond to the event.
        *   preventDefault();
            -   Some events, such as clicking on links and submitting forms, take the user to another page. To prevent the default behavior of such elements, you can use the event object's preventDefault() method.
        *   stopPropagation();
            -   Once you have handled an event using one element, you may want to stop that event from bubbling up to its ancestor elements, especially if there are separate event handlers responding to the same events on the containing elements. To stop the event bubbling up, you can use the event object's stopPropagation() method.
        *   Using Both Methods;
            -   You will sometimes see the following used in similar situations that are in a function: return false; It prevents the default behavior of the element, and prevents the event from bubbling up or capturing further. It also works in all browsers. Note, however, when the interpreter comes across the return false statement, it stops processing any subsequent code within that function and moves to the next statement after the function was called. Since this blocks any further code within the function, it is often better to use the preventDefault() method rather than return false.
*   What Element did an Event Occur on?
    -   When calling a function, the event object's target property is the best way to determine which element the event occurred on. But you see the approach below used; it relies on the this keyword.
        *   The this keyword refers to the owner of a function. This works when no parameters are being passed to the function and therefore it is not called from an anonymous function.
        *   If you pass parameters to the function, the this keyword no longer works because the owner of the function is no longer the element that the event listener was bound to, it is an anonymous function. You could pass the element the event was called on as another parameter of the function. 
        *   In both cases the event object is the preferred approach.
*   Different Types of Events
    -   Events are defined in;
        *   The W3C DOM specification
        *   The HTML5 specification
        *   In Browser Object Models
            -   W3C DOM Events
                *   The DOM events specification is managed by the W3C which also looks after specifications including HTML5, CSS, and XML. Most of the events you will meet are a part of this DOM specification.
                *   Browsers implement all the events using the same event object that you already met. If also provides feedback such as which element the event occurred on, which key a user pressed, or where the cursor is positioned.
            -   HTML5 Events
                *   The HTML5 specification details events that browsers are expected to support that are specifically used with HTML. For example, events that are fired when a form is submitted or form elements are changed... submit, input, change. There are also new events introduced with the HTML5 specification that are only supported by more recent browsers.... readystatechange, DOMContentLoaded, hashchange.
            -   BOM Events
                *   Browser manufacturers also implement some events as part of their browser object model. Typically these are events not yet covered by W3C specification. Several of these dealt with touchscreen devices... touchstart, touchend, touchmove, orientationchange.
            -    Other events are being added to capture gestures and take advantage of accelerometers. Care is needed using such features, as different browsers often create different implementations of similar functionality.
*   User Interface Events
    -   UI events occur as a result of interaction with the browser window rather than the HTML page contained within it, ex, a page having loaded or the browser window being resized.
    -   Event                   Trigger                     
    -   load                    Fires when the web page has finished loading. It can also fire on nodes of other elements that load, such as images, scripts, or objects.
    -   unload                  Fires when the web page is unloading, usually because a new page has been requested. See also beforeunload event.
    -   error                   Fires when the web page encounters a JavaScript error or an asset doesn't exist.
    -   resize                  Fires when the browser window has been resized.
    -   scroll                  Fires when user scrolls up or down the page. It can relate to the entire page or a specific element.
*   Load
    -   The load event is commonly used to trigger scripts that access the contents of a page. The event is automatically raised by the window object when a page has finished loading the HTML and all of its resources: images, CSS, scripts, as well as 3rd party content such as ad banners.
    -   Because the load event only fires when everything else on the page has loaded, images, scripts, and ads, the user already have started to use the page before the script has started to run. Users particularly notice when a script changes the appearance of the page, changes focus, or selects form elements after they have started to use it, this can make the site look slower to load, and shift user focus becoming distracting.
*   Focus & Blur Events
    -   The HTML elements you can interact with, such as links and form elements, can gain focus. These events fire when they gain or lose focus.
    -   The focus and blur events are most commonly used on forms. They can particularly helpful when:
        * You want to show tips or feedback to users as they interact with an individual element within a form (tips are usually shown in other elements and not the one they are interacting with)
        * You need to trigger form validation as a user moves from one control to the next rather than waiting for them to submit the entire form first
    -   Event
        focus - trigger, when an element gains focus, the focus event fires for that DOM node.
        blur - trigger, when an element loses focus, the blur event fires for that DOM node.
*   Focus & Blur
    -   Ex.
        *   function checkUsername() {                                       // Declare function
                -   var username = el.value;                                         // Store username in variable 
                -   if (username.length < 5) {                                       // If username < 5 characters
                -       elMsg.className = 'warning';                                 // Change class on message 
                -       elMsg.textContent = 'Not long enough, yet...'                // Update message    
                -   } else {                                                         // Otherwise    
                -       elMsg.textContent = '';                                      // Clear message    
                -   }
            -   }
            -   function tipUsername() {                                             // Declare function    
                -   elMsg.className = 'tip';                                         // Change class for message    
                -   elMsg.innerHTML = 'Username must be at least 5 characters';      // Add message 
            -   }
            -   var el = document.getElementById('username');                        // Username input 
            -   var elMsg = document.getElementById('feedback');                     // Element to hold message 
            -   // When the username input gains/loses focus call functions above 
            -   el.addEvenListener('focus', tipUsername, false);                     // Focus call tipUsername()
            -   el.addEvenListener('blur', checkUsername, false);                    // Blur call checkUsername()
*   Mouse Events
    -   The mouse events are fired when the mouse is moved and also when its buttons are clicked.
        *   All of the elements on a page support the mouse events, and all of these bubble. Note that actions are different on touchscreen devices.
    -   Event               Trigger                                             Touch 
    -   
    -   Click               Fires when user clicks on primary mouse btn         A tap on the touchscreen will be treated like a single left click 
    -   dblClick            Fires when user clicks primary btn twice            A dbl tap will be treated as a dbl left click 
    -   mousedwn            User clicks down on any btn                         Can use touchstart event 
    -   mouseup             User releases btn                                   Can use touchend event 
    -   mouseover           Cursor is outside element then moved inside         cursor moved over an element 
    -   mouseout            Cursor outside element then moved inside another    cursor moved off an element
    -   mousemove           Cursor moved around an element                      cursor moved                // fires repeatedly 
        *   CSS uses :hover pseudo-class to change appearance of cursor at specified instances.
        *   mousedown and mouseup are used to add drag and drop functionality 
*   Where Events Occur 
    -   The event object can tell you where the cursor was positioned when an event was triggered.
        *   Screen - The screenX and screenY properties indicate the position of the cursor within the entire screen on your monitor, measuring from top left corner of the screen, rather than the browser.
        *   Page - The pageX and pageY properties indicate the position of the cursor within the entire page. The top of the page may be outside of the viewport so even if the cursor is in the same position, page and client coordinates can be different.
        *   Client - The clientX and clientY properties indicate the position of the cursor within the browser's viewport. If the user has scrolled down and the top of the page is no longer in view, it will not affect the client coordinates.
*   Determining Position 
    -   variable and function example of how to get event occurances
        *   let sx = document.getElementById('sx');                 // Element to hold screenX 
        *   let sy = document.getElementById('sy');                 // Element to hold screenY 
        *   let px = document.getElementById('px');                 // Element to hold pageX 
        *   let py = document.getElementById('py');                 // Element to hold pageY 
        *   let cx = document.getElementById('cx');                 // Element to hold clientX 
        *   let cy = document.getElementById('cy');                 // Element to hold clientY 
        *   function showPosition(event) {}                         // Declare function that will update element with position elements 
        *   sx.value = event.screenX;                               // Update element with screenX. do that same for all other element positions 
        *   let el = document.getElementById('body');               // Get body element 
        *   el.addEvenListener('mousemove', showPosition, false)    // Move updates position 
*   Keyboard Events 
    -   The keyboard events are fired when a user interacts with the keyboard, they fire on any kind of device with a keyboard.
        *   Event - input > Trigger - Fires when the value of an input> or textarea> element changes.
        *   Event - keydown > Trigger - Fires when the user presses any key on the keyboard. If the key is held down the event fires repeatedly.
        *   Event - keypress > Trigger - Fires when the user presses a key that would result in a character being shown on the screen.
        *   Event - keyup > Trigger - Fires when the user releases a key on the keyboard. Keyup fires after a character shows on screen.
            -   Events fire in this order... keydown, keypress, keyup.
        *   Which key was pressed? - The property keyCode returns ASCII code that represents the character for that key. Corresponding characters are on a ASCII table.
* Form Events
    -   There are two events that are commonly used with forms. In particular you are likely to see submit used in form validation.
        *   Event - submit > Trigger - When a form is submitted, the submit event fires on the node representing the form> element. It is most commonly used when checking the values a user has entered into a form before sending it to the server.
        *   Event - change > Trigger - Fires when the status fo several form elements change. Examples are dropdown boxes, radio buttons, checkboxes etc...
        *   Event - input > Trigger - The input event, which you saw earlier is commonly used with input> and textarea> elements.
    -   Focus and blur events are often used with forms, but can also be used in conjunction with other elements.
    -   Validation aka checking form values. If users miss required information or enter incorrect information, checking it using JS is faster than sending the data to the server for it to be checked.
*   Mutation Events and Observers
    -   Whenever elements are added to or removed from the DOM, its structure changes. This change triggers a mutation event.
    -   When your script adds or removes content from a page it is updating the DOM tree. There are many reasons why you might want to respond to the DOM tree being updated, you might want to tell the user that the page has changed.
        *   Event > DOMNodeInserted - Trigger > Fires when a node is inserted into the DOM tree.
        *   Event > DOMNodeRemoved - Trigger > Fires when a node is removed from the DOM tree.
        *   Event > DOMSubtreeModified - Trigger > Fires when the DOM structure changes.
        *   Event > DOMNodeInsertedIntoDocument - Trigger > Fires when a node is inserted into the DOM tree as a descendant of another node that is already in the document.
        *   Event > DOMNodeRemovedFromDocument - Trigger > Fires when a node is removed from the DOM tree as a descendant of another node that is already in the document.
    -   Problems with mutation events...
        *   If your script makes a lot of changes to a page, you end up with a lot of mutation events firing. This can also trigger other event listeners as they propagate through the DOM, which modify other parts of the DOM, triggering more mutation events. Therefore being replaced by mutation observers.
*   HTML 5 Events
    -   Here are three page level that have been included in versions of the HTML5 spec that have become popular very quickly.
        *   Event > DOMContentLoaded - Trigger > Event fires when the DOM tree is formed. Scripts start to run earlier than using the load event which waits for other resources such as images and ads to load.
        *   Event > hashchange - Trigger > Event fires when the URL hash changes without the window refreshing. 
        *   Event > beforeunload - Trigger > Event fires on window object before page is unloaded. Only used to help the user. Letting user know if changes haven't been saved.
*   JQuery 
    -   Offers a simple way to achieve a variety of common JavaScript tasks quickly and consistently, acrss all major browsers and without any fallback code needed.
    -   Select Elements - It is simpler to access elements using jQuery's CSS-style selecors than it is using DOM queries. The selectors are also more powerful and flexible.
    -   Perform Tasks - jQuery methods let you update the DOM tree, animate elements into and out of view, and loop through a set of elements, all in one line of code.
    -   Handle Events - jQuery includes methods that allow you to attach event listeners to selected elements without having to write any fallback code to support older browsers.
    -   jQuery is a JavaScript file that you include in your web pages. It lets you find elements using CSS-style selectors and then do something with the elements using jQuery methods.
        *   A function called jQuery() lets you find one or more elements in the page. $() is often used as shorthand.
        *   The jQuery() function has one parameter. $('li.hot') finds li elements with the class hot.
        *   The jQuery object has many methods that you can use to work with the elements you select. The methods represent tasks that you commonly need to perform with elements.
        *   $('li.hot').addClass('complete'), adds new value to the class attribute of li element selected.
*   Why use jQuery?
    -   jQuery doesn't do anything you cannot achieve with pure javascript. It is just a JavaScript file but estimates show it has been used on over a quarter of the sites on the web, because it makes coding simpler.
        *   Simple selectors;
            -   it's not always easy to select elements you want using the DOM tree.
            -   Uses language that you're already familiar with.
            -   Offers additional functionality through extra CSS style selectors.
        *   Common tasks in less code;
            -   loop through items, add/remove elements from the DOM tree, handle events, fade elements into/out of view, handle Ajax requests.
            -   jQuery Simplifies these tasks and allows you to write less code in achieving them. 
        *   Cross-browser compatibility;
            -   jQuery automatically handles the inconsistent ways which browsers select and handle elements and events.
            -   jQuery uses conditional statements to check if browsers support it. If not, it checks the next best option and uses that instead.
*   Finding elements in jQuery
    -   Basic Selectors
        *   * - All elements
        *   element - All elements with that element name
        *   #id - Elements whose id attribute has the value specified
        *   .class - Elements whose class attribute has the value specified
        *   selector1, selector2 - Elements that match more than one selector
    -   Hierarchy
        *   ancestor descendant - An element that is a descendant of another element
        *   parent > child - An element that is a direct child of another element
        *   previous + next - Adjacent sibling selector only selects elements that are immediately followed by the previous element
        *   previous - sibling - Sibling selector will select any elements that are a sibling of the previous element
    -   Basic Filters
        *   :not(selector) - All elements except the one in the selector
        *   :first - The first element from the selection
        *   :last - The last element from the selection
        *   :even - Elements with an even number index from the selection
        *   :odd - Elements with an odd number index from the selection
        *   :eq(index) - Elements with an index number equal to the one in the parameter
        *   :gt(index) - Elements with an index number greater than the parameter
        *   :lt(index) - Elements with an index number less than the parameter
        *   :header - All h1-h6 elements
        *   :animated - Elements that are currently being animated
        *   :focus - The element that currently has focus
    -   Content Filters
        *   :contains('text') - Elements that contain the specified text as a parameter
        *   :empty - All elements that have no children
        *   :parent - All elements that have a child node
        *   :has(selector) - Elements that contain at least one element that matches the selector
    -   Visibility Filters
        *   :hidden - All elements that are hidden
        *   :visible - All elements that consume space in the layout of the page
    -   Child Filters
        *   :nth-child(expr) - The value here is not zero-based
        *   :first-child - First child from the current selection
        *   :last-child - Last child from the current selection
        *   :only-child - When there is only one child of the element
    -   Attribute Filters
        *   [attribute] - Elements that carry the specified attribute with any value
        *   [attribute='value'] - Elements that carry the specified attribute with the specified value
        *   [attribute!='value'] - Elements that carry the specified attribute but not the specified value
        *   [attribute^='value'] - The value of the attribute begins with this value
        *   [attribute='value'] - The value of this attribute ends with this value
        *   [attribute*='value'] - The value should appear somewhere in the attribute
        *   [attribute|='value'] - Equal to given string, or starting with the string and followed by a hyphen
        *   [attribute~='value'] - The value should be one of the values in a space separated list
        *   [attribute] [attribute2] - Elements that match all of the selectors
    -   Form
        *   :input - All input Elements
        *   :text - All text inputs
        *   :password - All password inputs
        *   :radio - All radio buttons
        *   :checkbox - All checkboxes
        *   :submit - All submit buttons
        *   :image - All img> elements
        *   :reset - All reset buttons
        *   :button - All button> elements
        *   :file - All file inputs
        *   :selected - All selected items from dropdown lists
        *   :enabled - All enabled form elements
        *   :disabled - All disabled form elements
        *   :checked - All checked radio buttons or checkboxes
*   Doing Things with Your selection        
    -   Content Filters 
        *   Get/Change Content
            -   .html(), .text(), .replaceWith(),remove()
        *   Elements    
            -   .before(), .after(), .prepend(), .append(), .remove(), .clone(), .unwrap(), .detach(), .empty(), .add()
        *   Attributes  
            -   .attr(), .removeAttr(), .addClass(), .removeClass(), .css()
        *   Form Values
            -   .val(), .isNumeric()
    -   Finding Elements
        *   General 
            -   .find(), .closest(), .parent(), .parents(), .children(), .siblings(), .next(), .nextAll(), .prev(), .prevAll()
        *   Filter/Test
            -   .filter(), .not(), .has(), .is(), :contains()
        *   Order selection
            -   .eq(), .lt(), .gt()
    -   Dimension/Position
        *   Dimension
            -   .height(), .width(), .innerHeight(), .innerWidth(), .outerHeight(), .outerWidth(), $(document).height(), $(document).width(), $(window).height(), $(window).width()
        *   Position
            -   .offest(), .position(), .scrollLeft(), .scrollTop()
    -   Effects & animation
        *   Basic   
            -   .show(), .hide(), .toggle()
        *   Fading
            -   .fadeIn(), .fadeOut(), .fadeTo(), .fadeToggle
        *   Sliding
            -   .slideDown(), .slideUp(), .slideToggle()
        *   Custom 
            -   .delay(), .stop(), .animate()
    -   Events
        *   Document/Files
            -   .ready(), .load()
        *   User Interaction 
            -   .on()
*   jQuery Objects Store References to Elements
    -   When you create a selection with jQuery, it stores a reference to the corresponding nodes in the DOM tree. It does not create copies of them.
    -   When programmers say that a variable or object is storing a reference to something, what it is doing is storing the location a piece of information in the browser's memory.
*   Caching jQuery Selections in Variables 
    -   A jQuery object stores references to elements. Caching a jQuery object stores a reference to it in a variable.
    -   To create a jQuery object the interpreter must...
        *   find the matching nodes in the DOM tree
        *   Create the jQuery object
        *   Store references to the nodes in the jQuery object 
            -   This takes time, processing resources, and memory.
            -   So instead of repeating the process over, you store a reference to the jQuery object in a variable.
*   Looping
    -   Instead of looping like in javascript, you can update all returned elements using just one method, using the selector.
*   Chaining
    -   You can also use several methods at a time using dot notation to separate each method. This is referred to as chaining.
*   Checking a Page is Ready to Work With
    -   the .ready() method checks that the page is ready for your code to work with.
    -   The load event - fires after the page and all its resources ie. images, css, and scripts have loaded. Use when your script relies on assets to have loaded.
    -   The ready method - fires as soon as the DOM has loaded, does not wait for assets, and makes the page look as if it is loading faster.
*   Getting Element Content
    -   The .html() and .text() methods both retrieve and update the content of elements.
    -   .html() is used to retrieve information from a jQuery selection, it retrieves only the HTML inside the first element in the matched set, along with any of its descendants.
    -   .text() is used to retrieve the text from a jQuery selection, it returns the content from every element in the jQuery selection, along with the text from any descendants.
*   Updating Elements
    -   .html() - This method gives every element in the matched set the same new content. The new content may include html.
    -   .text() - This method gives every element in the matched set the same new text content. Any markup would be shown as text.
    -   .replaceWith() - This method replaces every element in a matched set with new content. It also returns the replaced elements.
    -   .remove() - This method removes all of the elements in the matched set.
*   Inserting Elements
    -   Inserting new elements involves two steps: Create the new elements in a jQuery object; Use a method to insert the content into the page.
    -   Creating new elements in jQuery object, var $newFragment = $('<li>'); creates a variable called newFragment and stores a jQuery object in it, in this case an empty li element.
    -   Adding new elements to the page, once the object is created, you use a method to add the content to the DOM tree.
        *   .before() - inserts before selected elements.
        *   .after() - inserts after selected elements.
        *   .prepend() - inserts content inside the selected element after the opening tag.
        *   .append() - inserts contents inside the selected element before the closing tag.
*   Getting & Setting Attribute Values
    -   You can create attributes, or access and update their contents, using the following four methods...
        *   .attr() - Get or set a specified attribute and its value. $(li#one).attr('id', 'hot') - first argument is the attribute, second is the new value.
        *   .removeAttr() - Removes specified attribute.
        *   .addClass - adds new value to the existing value of the class attribute.
        *   .removeClass() - Removes a value from the class attribute, leaving others intact.
*   Getting & Setting CSS Properties
    -   .css() method lets you retrieve and set values of CSS properties.
        *   To get the value of a CSS property, you indicate which property you want to retrieve in parenthese. $('li').css('background-color')...css('background-color', '#2727272'), the second value is the new css property...
        *   You can set multiple properties using object literal notation. Remember key value pairs in objects..css({'background-color': '#272727'})
*   Working with Each Element in a Selections   
    -   jQuery allows you to recreate the functionality of a loop on a selection of elements, using .each() method.
        *   .each() - like a loop, allows you to perform one or more statements on each of the items in the selection of elements that is returned by a selector.
        *   $('li').each(function() {let ids = this.id; $(this).append(' <em class="order">' + ids + '<em>');});
            -   ^ contains all of the li elements, .each applies same code to each element selection, an anonymous function is run for each of the items in the list.
*   Event Methods
    -   The .on() method is used to handle all events. Behind the scenes, jQuery handles all of the cross-browser issues you saw in the last chapter.
    -   Using the .on() method is no different than using any other jQuery method...
        *   You use a selector to create a jQuery selection
        *   Use .on() to indicate which event you want to respond to. It adds an event listener to each element in the selection
    -   Some of the most popular .on() events are...
        *   UI - focus, blur, change
        *   Keyboard - input, keydown, keyup, keypress
        *   Mouse - click, dblclick, mouseup, mousedown, mouseover, mousemove, mouseout, hover
        *   Form - submit, select, change
        *   Document - ready, load, unload
        *   Browser - error, resize, scroll
*   The Event Object    
    -   Every event handling function recieves an event object. It has methods and properties related to the event that occured.
        *   Type - type of event.... click, mouseover....
        *   Which - button or key that was pressed
        *   Data - An object literal containing extra information passed to the function when the event fires
        *   Target - DOM element that initiated the event
        *   pageX - Mouse position from left edge of viewport
        *   pageY - Mouse position from top of viewport
        *   timeStamp - Number of milliseconds from Jan 1st 1970 to when the event was triggered... known as Unix Time
        *   .preventDefault() - Prevents the default
        *   .stopPropagation() - Stops the event bubbling up to ancestors
*   Additional Parameters For Event Handlers
    -   The .on() method has two optional properties that let you: Filter the initial jQuery selection to respond to a subset of the elements; Pass extra information into the event handler using object literal notation
    -   .on(events[, selector][, data] function(e));
        *   Here you can see two additional properties that can be used with the .on() method
        *   When square brackets are used inside a method, they signify that the parameter is optional
        *   Leaving out a parameter written in square brackets will not stop the method working
        *   You can leave a space separating events if there are more than one. 'focus click'...
*   Effects
    -   When you start using jQuery, the effects methods can enhance your web page with transitions and movement.
        *   Basic Effects   
            -   .show() - Displays selected elements
            -   .hide() - Hides selected elements
            -   .toggle() - Toggles between showing and hiding seleceted elements
        *   Fading Effects
            -   .fadeIn() - Fades in selected elements making them opaque
            -   .fadeOut() - Fades out selected elements making them transparent
            -   .fadeTo() - Changes opacity of selected elements
            -   .fadeToggle() - Hides or shows selected elements by changing their opacity
        *   Sliding Effects 
            -   .slideUp() - Shows selected elements with a sliding motion
            -   .slideDown() - Hides selected elements with a sliding down motion
            -   .slideToggle() - Hides or shows selected elements with a sliding motion
        *   Custom Effects
            -   .delay() - Delays execution of subsequent items in queue
            -   .stop() - Stops an animation if it is currently running
            -   .animate() - Creates custom animations
*   Animation CSS Properties
    -   The .animate() method allows you to create some of your own effects and animations by changing CSS properties
        *   You can animate any CSS property whose value can be represented as a number such as height, width, and font-size. Not a string value such as font-family or text-transform.
        *   CSS properties are written in camel case.
        *   CSS properties are specified using object literal notation and can take three optional parameters.
*   Traversing the DOM
    -   When you have a jQuery selection, you can use these methods to access other element nodes relative to the initial selection
        *   .find() - All elements within current selection that match selector
        *   .closest() - Nearest ancestor that matches selector
        *   .parent() - Direct parent of current selection
        *   .parents() - All parents of current selection
        *   .children() - All children ....
        *   .siblings() - All siblings....
        *   .next() - Next sibling of current ....
        *   .nextAll() - All subsequent siblings of current ...
        *   .prev() - Previous sibling of current element
        *   .prevAll() - All previous siblings ....
            -   If the original selection contains multiple elements, these methods will work on all of the elements in the selection.
*   Add & Filter Elements in a Selections
    -   Once you have a jQuery selection, you can add more elements to it, or you can filter the selection to work with a subset of the elements.
        *   Adding Elements to a selection
            -   .add() - Selects all elements that contain the text specified, parameter is case sensitive
        *   Filtering with a second selector
            -   .filter() - Finds elements in matched that in turn match a second selector
            -   .find() - Finds descendants of elements in matched set that match the selector
            -   .not()/:not() - Finds elements that do not match the selector
            -   .has()/:has() - Finds elements from the matched set that have a descendant that matches the selector
            -   :contains() - Selects all elements that contain the text specified, parameter is case sensitive
*   Finding Items by Order
    -   Each item returned by a jQuery selector is given an index number, which can be used to filter the selection
        *   Finding elements by index number
            -   .eq() - The element that matches the index number
            -   :lt() - Elements with an index less than the number specified
            -   :gt() - Elements with an index greater than the number specified
*   Selecting Form Elements
    -   :button - button and input elements whose type attribute has a value of button
    -   :checkbox - input elements with type attribute of checkbox
    -   :checked - checked elements from checkboxes and radio buttons
    -   :disabled - all disabled elements
    -   :enabled - all enabled elements
    -   :focus - Element that currently has focus
    -   :file - all file input elements
    -   :image - all image inputs
    -   :input - all button, input, select, and textarea elements
    -   :password - all password inputs
    -   :radio - all radio inputs
    -   :reset - all inputs that are reset buttons
    -   :selected - all elements that are seleceted
    -   :submit - button and input elements with type attribute submit
    -   :text - input elements with a type attribute of text
*   Form Methods & Events
    -   Retrieve the value of elements
        *   .val() - Primarily used with input, select, and textarea elements. Used to get first element in a matched set or update the value of all of them
    -   Other methods
        *   .filter() - used to filter jQuery selections using a second selector
        *   .is() - Often used with filters to check whether a form input is selected/checked
        *   .isNumeric() - checks whether the value represents a numeric value and returns a boolean
    -   Events
        *   .on() - used to handle all events
            -   blur - when an element loses focus
            -   change - when the value of an input changes
            -   focus - an element gains focus
            -   select - when option for a select element is changed
            -   submit - when a form is submitted
*   Working with forms
    -   New jQuery objects can be created to hold new item button elements, the form to add new button items, and the add button.
    -   jQuery methods can show the button and hide the form. If users click the new item button the button is hidden and the form shown.
    -   The new item is then added to the list.
*   Cutting & Copying Elements
    -   Once you have a jQuery selection, you can use these methods to remove those elements or make a copy of them.
        *   Cut
            -   .remove() - Removes matched elements from DOM tree including any descendants and text nodes
            -   .detach() - Same as .remove() but keeps a copy of them in memory.
            -   .empty() - Removes child nodes and descendants from any elements in matched set.
            -   .unwrap() - Removes parents of matched set, leaving matched elements.
        *   Copy
            -   .clone() - Creates a copy of the matched set including descendants and text nodes.
*   Box Dimensions 
    -   These methods allow you to discover or update the width and height of all boxes on the page.
        *   Retrieve or set box dimensions 
            -   .height() - Height of box, no margin, border, or padding.
            -   .width() - Width of box, no margin, border, or padding.
        *   Retrieve box dimensions only 
            -   .innerHeight() - height of box plus padding.
            -   .innerWidth() - width of box plus padding.
            -   .outerHeight() - Height of box plus padding and border.
            -   .outerWidth() - Width of box plus padding and border.
            -   .outerHeight(true) - height of box plus padding, border, and margin.
            -   .outerWidth(true) - width of box plus padding, border, and margin.
*   Windows & Page Dimensions
    -   The .height() and .width() methods can be used to determine the dimensions of both the browser window and the HTML document. There are also methods to get and set the position of the scroll bars.
        *   .scrollLeft() - Gets the horizontal position of the scroll bar for the first element in the jQuery selection, or sets the horizontal scroll bar position for matched nodes.
        *   .scrollTop() - Gets the vertical position of the scroll bar for the first element in the jQuery selection, or sets the vertical scroll bar position for matched nodes.
*   Position of Elements on the Page
    -   .offset() and .position() methods can be used to determine the position of elements on the page.
        *   .offset() - Gets or sets coordinates of the element relative to the top left hand corner of the document object.
        *   .position() - Gets or sets coordinates of the element relative to any ancestor that has been taken out of normal flow. if none it will return same as .offset().
*   

