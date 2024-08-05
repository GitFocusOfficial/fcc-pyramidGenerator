# Learn Introductory JavaScript by Building a Pyramid Generator

JavaScript is a powerful scripting language that you can use to make web pages interactive. It's one of the core technologies of the web, along with HTML and CSS. All modern browsers support JavaScript.

In this practice project, you'll learn fundamental programming concepts in JavaScript by coding your own Pyramid Generator. You'll learn how to work with arrays, strings, functions, loops, `if/else` statements, and more.

## Step 1

JavaScript is the programming language that powers the web. Unlike the HTML and CSS you have learned previously, JavaScript is most commonly used to write logic instead of markup.

In this project, you will learn the basics of Javascript and apply those concepts to building a pyramid generator.

A pyramid generator is a program where you can set the type of character, the count for the pyramid, and the direction of the pyramid. The program will then generate a pyramid based on those inputs.

Click on the `"Check your code"` button to proceed to the next step and start the project.

## Step 2

One of the most important concepts in programming is variables. A *variable* points to a specific memory address that stores a value. Variables are given a name which can be used throughout your code to access that value.

Declaring a variable means giving it a name. In JavaScript, this is often done with the `let` keyword. For example, here is how you would declare a `hello` variable:

>Example Code
>
>```let
>let hello;
>```

Variable naming follows specific rules: names can include letters, numbers, dollar signs, and underscores, but cannot contain spaces and must not begin with a number.

>Use the `let` keyword to declare a variable called `character`.

Note: It is common practice to end statements in JavaScript with a semicolon. `;`

## Step 3

Your `character` variable currently does not have a value. You can assign a value using the assignment operator `=`. For example:

>Example Code
>
>```let
>let hello = "Hello";
>```

Assigning a value to a variable at the moment of its declaration is known as *initialization*.

Initialize your `character` variable by assigning it the value `"Hello"` during its declaration.

## Step 4

JavaScript has seven primitive data types, with `String` being one of them. In JavaScript, a *string* represents a sequence of characters and can be enclosed in either single (`'`) or double (`"`) quotes.

Note that strings are *immutable*, which means once they are created, they cannot be changed. The variable can still be reassigned another value.

Change your `"Hello"` string to use `single quotes`.

## Step 5

The console allows you to print and view JavaScript output. You can send information to the console using `console.log()`. For example, this code will print `"Naomi"` to the console:

>Example Code
>
>```let
>let developer = "Naomi";
>console.log(developer);
>```

The code above accesses the `developer` variable with its name in the `console.log()`. Note that the value between the parentheses is the value that will be printed.

Print the value of the `character` variable to the console. Then, click the "Console" button to view the JavaScript console.

## Step 6

When a variable is declared with the `let` keyword, you can *reassign* (or change the value of) that variable later on. In this example, the value of `programmer` is changed from `"Naomi"` to `"CamperChan"`.

>Example Code
>
>```let
>let programmer = "Naomi";
>programmer = "CamperChan";
>```

Note that when reassigning a variable, you do **not** use the `let` keyword again.

After your `console.log`, assign the value `"World"` to your `character` variable.

## Step 7

Now log your `character` variable to the console again. You should see the string `"Hello"`, then the string `"World"`, in the console.

## Step 8

When variable names are more than one word, there are specific naming conventions for how you capitalize the words. In JavaScript, the convention to use is *camel* case.

Camel case means that the first word in the name is entirely lowercase, but the following words are all title-cased. Here are some examples of camel case:

>Example Code
>
>```let
>let variableOne;
>let secondVariable;
>let yetAnotherVariable;
>let thisIsAnAbsurdlyLongName;
>```

Use camel case to declare a new `secondCharacter` variable.

## Step 9

When you declare a variable without initializing it, it is considered *uninitialized*. Currently, your `secondCharacter` variable is uninitialized.

Add a `console.log()` to see what the value of your `secondCharacter` variable is.

## Step 10

The default value of an uninitialized variable is `undefined`. This is a special data type that represents a value that does not have a definition yet.

You can still assign a value to an uninitialized variable. Here is an example:

>Example Code
>
>```let
>let uninitialized;
>uninitialized = "assigned";
>```

Assign the string `"Test"` to your `secondCharacter` variable below your declaration. Open the console to see how your log has changed.