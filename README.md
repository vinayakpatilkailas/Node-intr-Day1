# Node-intr-Day1#
1.What is NPM?
1.	NPM stands for the node package manager, npm is used for node dependency management. 
2.	Most of the time, we use npm as a server-side node dependency tool 
3.	NPM gets installed with NodeJs installation. NPM uses nested dependencies, so we can use different versions of any module in our code.
4.	Nested dependencies mean that any dependency is again dependent on another dependency npm: It is a package manager for the JavaScript programming language.
5.	It is the default package manager for the JavaScript runtime environment Node.js. Help to manage a project’s dependencies. npm is installed with Node automatically.

What are the modules in Node.js?
➔	In Node.js, Modules are the blocks of encapsulated code that communicate with an external application on the basis of their related functionality.
➔	 Modules can be a single file or a collection of multiples files/folders.
➔	 The reason programmers are heavily reliant on modules is because of their re-usability as well as the ability to break down a complex piece of code into manageable chunks. Modules are of three types:
1.	Core Modules/Internal modules
2.	Local Modules/Custom modules 
3.	Third-party Modules
Core Modules: Node.js has many built-in modules that are part of the platform and comes with Node.js installation. These modules can be loaded into the program by using the require function. The require() function will return a JavaScript type depending on what the particular module returns. ex:- http creates an HTTP server in Node.js. 
Local Modules: Unlike built-in and external modules, local modules are created locally in your Node.js application. Let’s create a simple calculating module that calculates various operations. Another file can use its exported functionality using the require() function.
Third-party modules: Third-party modules are modules that are available online using the Node Package Manager(NPM). These modules can be installed in the project folder or globally. Some of the popular third-party modules are mongoose, express, angular, and react.

3.What is the purpose of the module.exports?
➔	Module.exports is the instruction that tells Node. js which bits of code (functions, objects, strings, etc.) to “export” from a given file so other files are allowed to access the exported code. 
➔	The module.exports is actually a property of the module object in node.js. module. Exports is the object that is returned to the require() call.
➔	 By module.exports, we can export functions, objects, and their references from one file and can use them in other files by importing them by require() method. easy to maintain and manage the code base in different modules.

4.Difference between default export and named export.
Export objects, functions, variables from the module so they can be used by other programs with the help of the import statements. 
There are two types of exports. 
          1. Named Exports,
          2. Default Exports. 
Named Exports: Named exports are useful to export several values.
During the import, it is mandatory to use the same name of the corresponding object.
Named exports allow us to share multiple objects, functions or variables from a single file and were introduced with the release of ES2015.
 Named exports are imported with curly braces in various files and must be imported using the name of the object, function or variable that was exported. 
//Exporting individual features:
 export var name1 = …, name2 = …, …, nameN; // also let, const
// Export list :
export { name1, name2, …, nameN };
//Exporting everything at once :
******************************************************************
5. How do you import any module in Node.js?
Importing functions or modules enhances the reusability of code.
Importing a Module: We need to import the module to use the functions defined in the imported module in another file. The result returned by require() is stored in a variable which is used to invoke the functions using the dot notation.
const f = require('./func')




