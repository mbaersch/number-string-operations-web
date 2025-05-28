# Number & String Operations
**Custom Variable Template for Google Tag Manager**

Set of Math and string manipulation operations 

**NOTE**: This is the client-side version of [this](https://github.com/mbaersch/number-string-operations) server-side variable template  

[![Template Status](https://img.shields.io/badge/Community%20Template%20Gallery%20Status-published-green)](https://tagmanager.google.com/gallery/#/owners/mbaersch/templates/number-string-operations-web) ![Repo Size](https://img.shields.io/github/repo-size/mbaersch/number-string-operations-web) ![License](https://img.shields.io/github/license/mbaersch/number-string-operations-web)

---

## Change Notes

### 2025/05/28
New boolean operations (placed in the *"calc"* section): AND, OR, NOT
Results of *"string"* operations can be parsed to integer or fixed 
Results of the new boolean operations can be parsed (converted) to an integer "0" or "1"

### 2024/05/25
New string methods "JSON.parse" & "JSON.stringify" for converting from / to objects

### 2022/06/23
New string method "split+extract": splits string at first parameter by second parameter delimiter and gets array item from split result by third parameter index

New result conversion type "Convert To String" 

### 2021/12/30
New methods in "Math":
- pow
- sqrt

New methods for strings:
- toFixed (variable decimals)
- toNumber (removes thousand separators and converts values with comma as decimal separators)
- replaceAll
- allows empty values as parameter 3 for replace / replaceAll

## What it does
Create a new variable using this template to...

- perform **calculations** with two variables
- use methods from **"Math"** to mutate variable values or
- manipulate **strings** from a single input variable (and additional parameters, depending on the string function)

## Usage
After selecting one of the three types an operation / a function can be picked from a drop down list. 

Depending on the operation, one up to three parameter values can be defined. 

- For calculations, the first and second parameter are used as operands. You can use variables or direct constant values for all parameter fields. 
- Math and string operations usually take the first parameter as input and the others are used as neccessary function parameters.

All parameters are transformed to the suitable format by the template.

### Formatting Results
In case of calculations or math operations you can pick a desired format for the result. This can be a string, rounded or truncated integer or a fixed value with two decimal digits.

## Examples
You can find a list of examples in the server-side template repository [here](https://github.com/mbaersch/number-string-operations-web#readme). Only the `sha256` function describes there is not available in this version for the web.  
