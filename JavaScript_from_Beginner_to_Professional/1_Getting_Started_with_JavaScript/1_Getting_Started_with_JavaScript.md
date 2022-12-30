# 1. Getting Started with JavaScript

## Using the browser console

* On a browser right-click -> click on ```Inspect``` -> click on ```Console```, start typing following commands.
* Hello World!
```JavaScript
console.log("Hello World!");

// Output
Hello World!
```

* Other console methods
```JavaScript
console.table();
console.error();
console.clear();
```

### Practice exercise 1.1
Working with the console:

1. Open the browser console, type ```4 + 10```, and press ```Enter```. What do you see as the response?
    ```JavaScript
    4 + 10;

    // Output
    14
    ```
2. Use the ```console.log()``` syntax, placing a value within the rounded brackets. Try entering your name with quotes around it.
    ```JavaScript
    console.log("Sinku Kumar");

    // Output
    Sinku Kumar
    ```

## Adding JavaScript to a web page

### Directly in HTML
```HTML
<!DOCTYPE html>
<html>
    <head>
        <title>The title of page</title>
    </head>
    <body>
        The content of the webpage
        <script>
            console.log("Hi there!");
        </script>
    </body>
</html>
```
[Directly in HTML](./1_Directly_in_HTML.html)

#### Practice exercise 1.2
JavaScript in an HTML page:
1. Open your code editor and create an HTML file.
2. Within your HTML file, set up the HTML tags, doctype, HTML, head and body, and then add the script tags.
3. Place some JavaScript code within the script tags. You can use ```console.log("hello world!")```.

    [Practice exercise 1.2 Solution](./Practice_exercise_1.2.html)

### Linking an external file to our webpage
```javascript
alert("Saying hi from a different file!");
```

```html
<html>
    <script type="text/javascript" src="1_alert.js"></script>
</html>
```
[Linking external file](./1_Linking_external_file.html)

#### Practice exercise 1.3
Linking to a JS JavaScript file:
1. Create a separate file called ```app``` with the extension ```.js```.
2. Withing the ```.js``` file, some JavaScript code.
3. Link to the separate ```.js``` file within the HTML file you created in Practice exercise 1.2.
4. Open the HTML file within your browser and check to see whether the JavaScript code ran properly.

    [Practice exercise 1.3 Solution](./Practice_exercise_1.2.html)

## Writing JavaScript code

### Formatting code
* Use indentation and whitespaces.
* Use semicolon after every statement wherever applicable
* Use code comments to add file description, metadata such as Author
* Add comments to specific parts of the code to explain what is happening or why a certain choice is made.
```JavaScript
// Single line comment
/* Multi
line 
comment
*/
```

#### Practice exercise 1.4
Adding comments:

1. Add a new statement to your JavaScript code by setting a variable value.
```JavaScript
let a = 10;
```
2. Add a comment at the end of the statement indicating that you set a value of 10.
3. Print the value using console.log(). Add a comment explaining what this will do.
4. At the end of your JavaScript code, use a multiple-line comment. In a real production script, you might use this space to add a brief outline of the purpose of the file.

### Prompt
* Takes input from the user
```JavaScript
prompt("Hi! How are you?");
```

### Random numbers
* Generate a random number between 0 and 1
```JavaScript
Math.random();
```

* See the result in console
```JavaScript
console.log(Math.random());
```

* Generates a random number between 0 and 100
```JavaScipt
console.log(Math.random() * 100);
```

* If you don't want to have a decimal result use ```Math.floor()``` function, roundin down to the nearest integer.
```JavaScript
console.log(Math.floor(Math.random() * 100));
```

## Chapter Project

### Create an HTML file and linked JavaScript file
Create an HTML file and create a separate JavaScript file. Then, connect to the JavaScript file from the HTML file.
1. In the JavaScript file, output your name into the console and add a multiple-line comment to your code.
2. Try commenting out the console message in your JavaScript file so that nothing shows in the console.

## Self-check quiz
1. What is the HTML syntax to add an external JavaScript file?
2. Can you run JavaScript in a file with a JS extension in your browser?
3. How do you write a multiple-line comment in JavaScript?
4. What is the best way to remove a line of code from running that you might want to keep as you debug?