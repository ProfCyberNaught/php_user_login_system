# Variable, Function, and Class Naming Policy

## Why have a Naming Policy for Variables, Functions, and Classes?

Having a naming policy for variables, functions, and classes in PHP is important for several reasons:

- Readability: Consistent and meaningful names can make the code more readable and easier to understand. By following a naming policy, developers can quickly identify the intended use and meaning of variables, functions, and classes, which can reduce the time and effort needed to read and understand the code.
- Maintainability: Consistent and meaningful names can also make the code more maintainable. If the names are descriptive and convey the intended use and meaning of the code, it can be easier to modify or extend the code in the future.
- Collaboration: A naming policy can also facilitate collaboration among developers. By using consistent naming conventions, developers can more easily understand each other's code and work together more effectively.
- Self-documentation: Consistent and meaningful names can also make the code more self-documenting. If the names are descriptive and convey the intended use and meaning of the code, it may be less necessary to provide additional comments or documentation.

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

#### IMPORTANT NOTICE

Please note that ```$route-name``` is not a valid variable name in PHP as the hyphen character is not allowed in variable names. If you want to use kebab-case in your variable names, you can either replace hyphens with underscores or use camelCase instead. Here are the examples for both:

```php
// Using snake_case for kebab-case variable names
$route_name = "example-route";

// Using camelCase for kebab-case variable names
$routeName = "example-route";
```

## Official Naming Policy

A good naming policy for variables, functions, and classes in PHP should follow some basic principles that can make the code more readable, maintainable, and self-documenting. Here are the general guidelines for this project:
- Use descriptive and meaningful names: Names should reflect the intended use and meaning of the variable, function, or class. Avoid using abbreviations or acronyms that are not widely known or easily understood.
- Use camelCase for variables and functions: In camelCase, the first letter of the first word is lowercase, and the first letter of each subsequent word is capitalised. For example, ```$customerName``` or ```getCustomerName()```. This convention is widely used in PHP and other programming languages.
- Use PascalCase for classes: In PascalCase, the first letter of each word is capitalised. For example, ```Customer``` or ```OrderManager```. This convention is also widely used in PHP and other programming languages.
- Use nouns for classes: Classes should represent objects or concepts in the problem domain, and their names should be nouns. For example, ```Customer```, ```Order```, or ```Product```.
- Use verbs for functions: Functions should represent actions or operations on objects or concepts in the problem domain, and their names should be verbs or verb phrases. For example, ```getCustomer()```, ```saveOrder()```, or ```calculateTotal()```.
- Use nouns or noun phrases for variables: Variables should represent values or attributes of objects or concepts in the problem domain, and their names should be nouns or noun phrases. For example, ```$customerName```, ```$orderDate```, or ```$productPrice```.
- Avoid using reserved keywords: Avoid using reserved keywords as names for variables, functions, or classes in PHP.

In summary, a good naming policy should use descriptive and meaningful names, follow consistent conventions for casing and naming, and convey the intended use and meaning of variables, functions, and classes.

## Examples of Reserved Keywords

Here are some examples of reserved keywords in PHP:

- ```array``` - Used to define an array.
- ```callable``` - Used to define a callable variable or function.
- ```class``` - Used to define a class.
- ```const``` - Used to define a constant.
- ```declare``` - Used to set execution directives.
- ```die``` - Used to terminate the current script.
- ```echo``` - Used to output one or more strings.
- ```elseif``` - Used to specify an alternative conditional statement.
- ```empty``` - Used to determine whether a variable is empty.
- ```final``` - Used to prevent a class from being inherited or a method from being overridden.
- ```function``` - Used to define a function.
- ```global``` - Used to access a global variable from within a function or method.
- ```if``` - Used to specify a conditional statement.
- ```implements``` - Used to declare that a class implements one or more interfaces.
- ```include``` - Used to include a file.
- ```include_once``` - Used to include a file once only.
- ```instanceof``` - Used to determine whether an object is an instance of a specified class.
- ```insteadof``` - Used to resolve naming conflicts in traits.
- ```interface``` - Used to define an interface.
- ```namespace``` - Used to declare a namespace.
- ```new``` - Used to create a new instance of a class.
- ```or``` - Used to specify an alternative conditional statement.
- ```private``` - Used to define a private property or method.
- ```protected``` - Used to define a protected property or method.
- ```public``` - Used to define a public property or method.
- ```require``` - Used to require a file.
- ```require_once``` - Used to require a file once only.
- ```return``` - Used to return a value from a function or method.
- ```static``` - Used to declare a static property or method.
- ```switch``` - Used to specify a multi-way conditional statement.
- ```throw``` - Used to throw an exception.
- ```trait``` - Used to define a trait.
- ```try``` - Used to specify a block of code to try, and to handle exceptions that may be thrown from that code.
- ```use``` - Used to import namespaces or traits.
- ```var``` - Used to declare a property in a class.
- ```while``` - Used to specify a loop that executes as long as a specified condition is true.
- ```yield``` - Used to return a value from a generator function.

Note that these keywords are reserved, which means they cannot be used as identifiers (such as variable names, function names, or class names) in PHP code.