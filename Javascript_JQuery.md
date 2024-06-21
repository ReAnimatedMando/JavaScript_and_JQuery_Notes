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