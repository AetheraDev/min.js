# Min.js - Lightweight JavaScript Library

**SEE HOW TO USE:** [Docs](https://github.com/AetheraDev/min.js/blob/main/docs/README.md)

Min.js is a lightweight JavaScript library designed to make your code files smaller and improve the execution speed of your JavaScript programs. By using Min.js, you can easily replace common JavaScript keywords and function names with shorter aliases, resulting in a more concise codebase. This readme file provides instructions on how to use the Min.js library and highlights the advantages of having a lighter and faster codebase.

## Installation

To use Min.js in your project, follow these steps:

1. Install the library via npm:

```shell
npm install min.js
```

2. Import the library into your JavaScript file:

```javascript
const { min } = require("min.js");
```

## Usage

Using Min.js is straightforward. After importing the library, you can specify the JavaScript files you want to minify by using the `file()` method. Then, call the `run()` method to execute the minified code.

```javascript
const { min } = require("min.js");

min.file("./path/to/file1.min.js");
min.file("./path/to/file2.min.js");
// add as many files as you want.

// run code
min.run();
```

## Examples

Here are two simple examples demonstrating the usage of Min.js:

##### Code with abbreviated javascript:

Suppose you have a JavaScript file named `code.min.js` with the following code:

```javascript
// code.min.js
c greeting = "Hello, world!";
cl.lo(greeting);
```

Then import it and run:

```javascript
const { min } = require("min.js");

min.file("./code.min.js");
min.run();
```

The `code.min.js` file will have the least amount of characters and will do what the original does.



## Advantages

Min.js provides several advantages when used in your JavaScript projects:

### 1. Reduced File Size

By replacing commonly used keywords and function names with shorter aliases, Min.js significantly reduces the size of your JavaScript files. This reduction in file size can lead to faster file transfer times and improved performance, especially in scenarios with limited bandwidth or high-latency connections.

### 2. Faster Execution

Min.js eliminates the need to parse and interpret lengthy JavaScript code by replacing keywords and function names directly. This results in faster execution times for your JavaScript programs. By reducing the time spent on parsing and interpreting code, your applications can respond more quickly, leading to a smoother user experience.

### 3. Faster Development

Min.js simplifies your coding process by providing shorthand notations for frequently used JavaScript keywords and function names. With shorter aliases, you can write code more quickly and efficiently. Additionally, the reduced file size enables faster loading and testing, helping you iterate faster during the development process.



## Conclusion

Min.js offers a convenient way to reduce file size, improve execution speed, and streamline your JavaScript development process. By adopting Min.js in your projects, you can benefit from a lighter codebase, faster execution times.
