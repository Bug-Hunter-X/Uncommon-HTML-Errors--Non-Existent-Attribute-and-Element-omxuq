# Uncommon HTML Errors

This repository demonstrates two uncommon errors that can occur in HTML code, along with their solutions.

## Bug 1: Accessing a Non-Existent Attribute

Attempting to access an attribute that does not exist on an element will not throw an error in most browsers but will result in `null` being returned.  This can lead to unexpected behavior if not handled properly.

## Bug 2: Manipulating a Non-Existent Element

Trying to access or modify the style of an element that does not exist using `document.getElementById()` will result in an error being thrown in the browser's console.

## Solutions

The `bugSolution.html` file provides solutions for these issues by implementing checks before attempting these operations.