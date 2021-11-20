# Node.js Interview Questions

## Beginner Node.js Interview Questions
1.  What is a first class function in Javascript?
2.  What is Node.js and how it works?
3.  How do you manage packages in your node.js project?
4.  How is Node.js better than other frameworks most popularly used?
5.  Explain the steps how “Control Flow” controls the functions calls?
6.  What are some commonly used timing features of Node.js?
7.  What are the advantages of using promises instead of callbacks?
8.  What is fork in node JS?
9.  Why is Node.js single-threaded?
10.  How do you create a simple server in Node.js that returns Hello World?
11.  How many types of API functions are there in Node.js?
12.  What is REPL?
13.  List down the two arguments that async.queue takes as input?
14.  What is the purpose of module.exports?
15.  What tools can be used to assure consistent code style?

## Intermediate Node.js Interview Questions
16.  What do you understand by callback hell?
17.  What is an event-loop in Node JS?
18.  If Node.js is single threaded then how does it handle concurrency?
19.  Differentiate between process.nextTick() and setImmediate()?
20.  How does Node.js overcome the problem of blocking of I/O operations?
21.  How can we use async await in node.js?
22.  What is node.js streams?
23.  What are node.js buffers?
24.  What is middleware?
25.  Explain what a Reactor Pattern in Node.js?
26.  Why should you separate Express app and server?
27.  For Node.js, why Google uses V8 engine?
28.  Describe the exit codes of Node.js?
29.  Explain the concept of stub in Node.js?
## Advanced Node.js Interview Questions
30.  What is an Event Emitter in Node.js?
31.  Enhancing Node.js performance through clustering.
32.  What is a thread pool and which library handles it in Node.js
33.  What is WASI and why is it being introduced?
34.  How are worker threads different from clusters?
35.  How to measure the duration of async operations?
36.  How to measure the performance of async operations?


#Let's get Started

## Beginner Node.js Interview Questions
1. What is a first class function in Javascript?
When functions can be treated like any other variable then those functions are firstclass functions. There are many other programming languages, for example, scala,
Haskell, etc which follow this including JS. Now because of this function can be
passed as a param to another function(callback) or a function can return another
function(higher-order function). map() and filter() are higher-order functions that are
popularly used.
2. What is Node.js and how it works?
Node.js is a virtual machine that uses JavaScript as its scripting language and runs
Chrome’s V8 JavaScript engine. Basically, Node.js is based on an event-driven
architecture where I/O runs asynchronously making it lightweight and efficient. It is
being used in developing desktop applications as well with a popular framework
called electron as it provides API to access OS-level features such as file system,
network, etc.
3. How do you manage packages in your node.js project?
It can be managed by a number of package installers and their configuration file
accordingly. Out of them mostly use npm or yarn. Both provide almost all libraries of
javascript with extended features of controlling environment-specific configurations.
To maintain versions of libs being installed in a project we use package.json and
package-lock.json so that there is no issue in porting that app to a different
environment.
4. How is Node.js better than other frameworks most popularly
used?
Node.js provides simplicity in development because of its non-blocking I/O and
even-based model results in short response time and concurrent processing,
unlike other frameworks where developers have to use thread management.
It runs on a chrome v8 engine which is written in c++ and is highly performant
with constant improvement.
Also since we will use Javascript in both the frontend and backend the
development will be much faster.
And at last, there are ample libraries so that we don’t need to reinvent the
wheel.
5. Explain the steps how “Control Flow” controls the functions
calls?
Control the order of execution
Collect data
Limit concurrency
Call the following step in the program.
6. What are some commonly used timing features of Node.js?
setTimeout/clearTimeout – This is used to implement delays in code
execution.
setInterval/clearInterval – This is used to run a code block multiple times.
setImmediate/clearImmediate – This is used to set the execution of the code
at the end of the event loop cycle.
process.nextTick – This is used to set the execution of code at the beginning of
the next event loop cycle.
7. What are the advantages of using promises instead of
callbacks?

