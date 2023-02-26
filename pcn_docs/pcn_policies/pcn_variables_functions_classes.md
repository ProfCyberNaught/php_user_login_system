# Variable, Function, and Class Naming Policy

## Naming Conventions

The practice of using a naming policy or convention for variables, functions, and classes in programming has been around for a long time and has been widely adopted in many programming languages, including PHP. The use of consistent and meaningful names for variables, functions, and classes can make the code more readable and easier to understand, which can save time and effort for developers and improve the quality of the code.

One of the earliest and most influential naming conventions was the Hungarian notation, which was developed by Charles Simonyi at Microsoft in the 1980s. The Hungarian notation involved adding a prefix to variable names to indicate their data type, such as i for integer or sz for string. Although the Hungarian notation fell out of favor in the 2000s, its influence can still be seen in some naming conventions today.

Other naming conventions have emerged over time, including camelCase, PascalCase, snake_case, and kebab-case, among others. These conventions vary in their specifics but generally follow the principle of using consistent and meaningful names for variables, functions, and classes.

In PHP, several naming conventions have been proposed and widely adopted, including the PSR-1 and PSR-12 standards developed by the PHP Framework Interoperability Group (PHP-FIG). These standards provide guidelines for naming variables, functions, and classes, among other aspects of PHP coding style.

## PSR-1 and PSR-12 Conventions

**PSR-1 and PSR-12** are standards developed by the _PHP Framework Interoperability Group (PHP-FIG)_ that provide guidelines for coding style and naming conventions in PHP.

PSR-1 provides basic coding standards for PHP, including guidelines for file names, line endings, and class and method names. Here are some examples of the guidelines provided by PSR-1:


- File names should be in all-lowercase and use underscores to separate words, e.g. my_file.php.
- Files should use the Unix LF (linefeed) line ending.
- Class names should be declared in StudlyCaps (also known as PascalCase), e.g. MyClass.
- Method names should be declared in camelCase, e.g. myMethod.


PSR-12 provides additional guidelines for coding style and naming conventions in PHP, building on the foundations established by PSR-1. Here are some examples of the guidelines provided by PSR-12:


- Code should be indented using 4 spaces.
- Logical blocks of code should be separated by a single blank line.
- Short array syntax ([]) should be used instead of the older array syntax (array()).
- Visibility (public, protected, or private) should be declared first when declaring class properties and methods.
- Type declarations should be used where appropriate, e.g. function myFunction(string $myParam).



Overall, the guidelines provided by PSR-1 and PSR-12 are designed to make PHP code more consistent, readable, and maintainable. By following these guidelines, developers can produce code that is easier to understand, modify, and extend, and can collaborate more effectively with other developers.

## camelCase, PascalCase, snake_case, and kebab-case Conventions

Here are some explanations and examples of these naming conventions:

### camelCase Convention

**camelCase:** This naming convention is commonly used in many programming languages, including PHP. In camelCase, the first letter of the first word is lowercase and the first letter of subsequent words is uppercase. There are no spaces or underscores between words. Here's an example:

```php
$myVariableName = "this is an example of camelCase";
```


### PascalCase Convention

**PascalCase:** This naming convention is also known as _UpperCamelCase_ or _StudlyCaps_. In PascalCase, the first letter of every word is capitalised, and there are no spaces or underscores between words. This convention is commonly used for naming classes and interfaces in PHP. Here's an example:

```php
class MyClassName {
  // class definition goes here
}
```

### snake_case Convention

**snake_case:** In snake_case, all letters are lowercase, and words are separated by underscores. This naming convention is often used in languages such as Python and Ruby. In PHP, snake_case is commonly used for naming variables and functions. Here's an example:

```php
$my_variable_name = "this is an example of snake_case";
```


### kebab-case Convention

**kebab-case:** This naming convention is also known as spinal-case or lisp-case. In kebab-case, all letters are lowercase, and words are separated by hyphens. This convention is often used in CSS and HTML for naming classes and IDs. In PHP, kebab-case is not commonly used for naming variables, functions, or classes, but it may be used for naming URLs or routes in a web application. Here's an example:

```php
$url = "example-route";
```

Please note that ```$route-name``` is not a valid variable name in PHP as the hyphen character is not allowed in variable names. If you want to use kebab-case in your variable names, you can either replace hyphens with underscores or use camelCase instead. Here are the examples for both:

```php
// Using snake_case for kebab-case variable names
$route_name = "example-route";

// Using camelCase for kebab-case variable names
$routeName = "example-route";
```

## Official Naming Policy

