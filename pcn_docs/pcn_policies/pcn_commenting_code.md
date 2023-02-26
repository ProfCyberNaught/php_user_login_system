# Code Commenting Policy

Commenting code involves adding text annotations or notes within the source code to explain what the code does, how it works, and why it was written in a particular way. Comments are not executed by the computer, and they are ignored by the compiler or interpreter, which means they do not affect the behavior of the code.

There are several types of comments that can be used in code:

- **Single-line comments:** These are comments that start with two forward slashes // and continue to the end of the line. They are often used to provide brief explanations or context for a single line of code.
- **Multi-line comments:** These are comments that start with /* and end with */. They are often used to provide more detailed explanations for blocks of code, such as functions or classes.
- **Inline comments:** These are comments that are added after a line of code, separated by at least one space. They are often used to provide additional context or to clarify the purpose of a particular line of code.

## Why Comment Our Code?

There are several reasons why we should comment our code:

**Improve code readability:** Comments help to make code more readable by providing context and explanations for what the code is doing. This can help other developers who are working on the same codebase, as well as our future selves, to understand what the code does and why it was written in a particular way.

**Facilitate code maintenance:** Comments can make it easier to maintain code by making it clear how different parts of the code are related to each other and how they work together. This can save time and effort when trying to debug or modify code.

**Enhance code collaboration:** Comments can help to facilitate collaboration among team members by providing a common language for discussing code. They can also help to clarify expectations about how code should be written and structured.

**Document design decisions:** Comments can serve as a record of the design decisions that went into the code. This can be useful for future developers who may need to modify or extend the code, as well as for compliance and regulatory purposes.

**Increase code reliability:** Comments can help to increase the reliability of code by making it easier to identify potential errors and issues. This can lead to more robust and stable code that is less likely to fail or produce unexpected results.

## Code Commenting Policy

Here is our code commenting policy:

- **Comment all functions and methods:** Each function or method should have a brief description of what it does, along with a list of parameters and their expected types. Additionally, any preconditions or postconditions should be mentioned.
- **Comment complex code blocks:** Any block of code that is difficult to understand or may not be immediately clear to other developers should have a comment explaining what it does and why it is necessary.
- **Use descriptive variable names:** Variables should be named in a way that makes their purpose clear. If a variable is used in a complex way or has an unusual purpose, it should be explained in a comment.
- **Comment tricky or non-obvious parts of code:** Any parts of the code that may be difficult to understand or that were implemented in a non-obvious way should be commented to help other developers understand the thought process behind the implementation.
- **Update comments during code changes:** Any time code is modified, any relevant comments should be updated to reflect the changes.
- **Use a consistent commenting style:** All comments should use the same style throughout the project. This includes the use of punctuation, capitalization, and formatting.
- **Keep comments concise and to the point:** Comments should be clear and concise, without unnecessary detail or irrelevant information.
- **Use comments to provide context:** Comments should be used to provide context for the code, including any relevant information about the project, requirements, or design decisions.
- **Use comments to document bugs or issues:** If a bug or issue is discovered in the code, it should be documented in a comment along with any relevant information about its cause or possible solutions.

## Examples of Implementing Code Commenting

Here are some examples of how you can apply the comment rules for PHP code:

Comment all functions and methods:

```php
/**
 * Returns the sum of two numbers.
 *
 * @param int $firstNumber The first number to add.
 * @param int $secondNumber The second number to add.
 * @return int The sum of the two numbers.
 */
function add($firstNumber, $secondNumber) {
  return $firstNumber + $secondNumber;
}
```

Comment complex code blocks:

```php
// Check if the current user is an admin and has permission to view the page.
if (userIsAdmin() && userHasPermission('viewPage')) {
  // Display the page content.
  showPageContent();
}
```

Use descriptive variable names:

```php
$customerId = $_GET['customerId']; // The ID of the customer being edited.
$customerData = getCustomerData($customerId); // The customer data retrieved from the database.
```

Comment tricky or non-obvious parts of code:

```php
// This code uses a bitwise operator to check if the user has the required permissions.
if (($userPermissions & PERMISSION_EDIT) == PERMISSION_EDIT) {
  // Allow the user to edit the content.
  allowEdit();
}
```

Update comments during code changes:

```php
/**
 * Returns the sum of two numbers.
 *
 * @param int $firstNumber The first number to multiply.
 * @param int $secondNumber The second number to multiply.
 * @return int The product of the two numbers.
 */
function multiply($firstNumber, $secondNumber) {
  // Updated comment to reflect new behavior.
  // This function now returns the product of two numbers.
  return $firstNumber * $secondNumber;
}
```

Use a consistent commenting style:

```php
// This is a comment using double slashes.
$orderDate = $_GET['orderDate']; // The date of the order.

/*
This is a comment using a block
of asterisks.
*/
$productPrice = getProductPrice($productId); // The price of the product.
```

Keep comments concise and to the point:

```php
/**
 * Returns the customer data for the given ID.
 *
 * @param int $customerId The ID of the customer to retrieve data for.
 * @return array The customer data as an associative array.
 */
function getCustomerData($customerId) {
  // Query the database for the customer data.
  $query = "SELECT * FROM customers WHERE id = $customerId";
  $result = mysqli_query($query);

  // Extract the customer data from the result set.
  $row = mysqli_fetch_assoc($result);
  return $row;
}
```

Use comments to provide context:

```php
// This code checks if the user has permission to edit the page.
// If the user is an admin or has the editPage permission, they are allowed to edit.
if (userIsAdmin() || userHasPermission('editPage')) {
  allowEdit();
}
```

Use comments to document bugs or issues:

```php
// This code sometimes causes a division-by-zero error.
// TODO: Fix the bug by checking for a zero divisor before performing the division.
$result = $numerator / $denominator;
```