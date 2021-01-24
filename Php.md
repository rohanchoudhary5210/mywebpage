PHP: Hypertext Preprocessor (PHP) is a free, highly popular, open source scripting language. PHP scripts are executed on the server.

Just a short list of what PHP is capable of:
- Generating dynamic page content
- Creating, opening, reading, writing, deleting, and closing files on the server
- Collecting form data
- Adding, deleting, and modifying information stored in your database
- controlling user-access
- encrypting data
- and much more!


PHP runs on numerous, varying platforms, including Windows, Linux, Unix, Mac OS X, and so on.
PHP is compatible with almost any modern server, such as Apache, IIS, and more.
PHP supports a wide range of databases.
PHP is free!

A PHP script starts with <?php and ends with ?>:
Here is an example of a simple PHP file. The PHP script uses a built in function called "echo" to output the text "Hello World!" to a web page.
<html>
    <head>
        <title>My First PHP Page</title>
    </head>
    <body>
    <?php   
        echo "Hello World!";
    ?>
    </body>
</html>

PHP statements end with semicolons (;).


Alternatively ,php can also be used in script
<html>
  <head>
    <title>My First PHP Page</title>
  </head>
  <body>
  <script language="php">
    echo "Hello World!";
  </script>
  </body>
</html>

However, the latest version of PHP removes support for <script language="php"> tags. As such, we recommend using <?php ?> exclusively.
You can also use the shorthand PHP tags, <? ?>, as long as they're supported by the server.


PHP has a built-in "echo" function, which is used to output text. 
In actuality, it's not a function; it's a language construct. As such, it does not require parentheses.
.The text should be in single or double quotation marks.
Each PHP statement must end with a semicolon.



<?php
    echo "<strong>This is a bold text.</strong>";
?>

In PHP code, a comment is a line that is not executed as part of the program. You can use comments to communicate to others so they understand what you're doing, or as a reminder to yourself of what you did.

A single-line comment starts with //:
Multi-line comments are used for composing comments that take more than a single line. 
A multi-line comment begins with /* and ends with */.

NOTE- Adding comments as you write your code is a good practice. It helps others understand your thinking and makes it easier for you to recall your thought processes when you refer to your code later on.

