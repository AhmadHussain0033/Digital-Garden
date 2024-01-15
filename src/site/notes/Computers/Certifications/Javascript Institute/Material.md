---
{"sticker":"emoji//1f310","dg-publish":true,"permalink":"/computers/certifications/javascript-institute/material/","dgPassFrontmatter":true}
---

# JavaScript as an interpreted language

JavaScript is a typical **interpreted language**. If we run a code written in JavaScript in a web browser, as it is happening, such as after loading the page we are currently reading, the interpreter will be the JavaScript engine built into the browser. This is not the only way to execute JavaScript code. Node.js is also an interpreter, but installed independently of browsers as an environment in the computer's operating system (it can be macOS, Windows, or Linux). Using node.js allows you to write programs in JavaScript that will, for example, turn your computer into a server.

Most modern JavaScript engines use the _Just In Time Compilation_ technique (_JIT Compilation_). This technique consists of compiling code fragments during the execution of the program (more than a single instruction) and allows you to increase its performance. However, from the user's point of view, such a change is virtually unnoticeable – it still looks as if only the interpreter is executing the source code, instruction by instruction.

Back in the early 90s, all web pages were static. Things changed in 1995 when the Netscape corporation hired Brendan Eich, and tasked him to develop a new language for their product, the Netscape Navigator web browser. The new language was called LiveScript, but soon after its name was changed to JavaScript. Its main task was to add dynamics to websites, which would allow, for example, for more complex interaction with the user. And so the career of JavaScript began.


## Client-side vs server-side programming

The use of JavaScript on websites, which over time has become more and more complex and often contain very sophisticated logic, is called **client-side** programming. The code to be executed is loaded together with the page in the browser, on the user's side, and the interpreter which is a part of the web browser allows for its execution. Today, JavaScript is the sole language supported by all major web browsers, and about 95% of web pages worldwide embed JavaScript code within them. From the beginning, web pages used JavaScript on the client-side to add interactivity and dynamically change the content.

JavaScript offers many great frameworks on which to build huge, complex web applications and social networks (frameworks like **React** or **Angular**). All this can work on a variety of equipment, from high-performance workstations to simple smartphones. With JavaScript, we can order food, play browser-based games, watch movies on streaming platforms, and be in constant contact with the people important to us. JavaScript is so popular that continually more and more effort goes into using it, not only as a client-side solution.

Over time, JavaScript began to appear in other areas, such as programming the server-side parts of complex web applications, also called back-end. These programs are executed on servers, processing data (e.g. from databases), which after processing will be available on the client side. The flexibility of this language and its relative simplicity have made it much more applicable, for example, in mobile apps, or even in programming UAVs (some drones run programs written in this language).


  ## Disadvantages

We say that JavaScript is a mature language, which means that most of the features are already implemented and stable, and we will probably not see any big changes in the language. Since 2015, many aspects of JavaScript have changed, and many new features have been added. A lot of these changes were introduced to make the migration to JavaScript easier for programmers who know other popular languages, from which JavaScript originally differed quite strongly in certain aspects, such as when handling objects. We can still use the language in the old way, but it is recommended rather to use the modern JavaScript.

But... there are no ideal solutions, so there are no good programming languages for all applications. Each of them has its own limitations, and it’s no different with JavaScript. Despite its popularity and success, JavaScript is not a perfect programming language. Due to its nature, it is not suitable for certain applications. For example, there is no point in using it to write programs that require advanced mathematical calculations or very high performance.

Some limitations are due to the very concept of the language, but the vast majority are related to the platform on which we use it. This is especially visible when writing code to be executed in a browser, which as we said earlier is called client-side. In such a situation, JavaScript is limited in functionality by the fact that browsers, for security reasons, run script code in a _sandbox_ environment (an environment separated from the outer world), which doesn’t allow for access to local files and resources (i.e. those files that are on the computer where the browser is launched).

Another inconvenience is that since the code is not compiled, it goes into the browser in the same, or a very similar, form to what we wrote ourselves. Why is this a disadvantage? This is because everyone can see our solution in an easy-to-read form and use it (either fragments of it or even the whole of it) without our permission to write their own program. Some help here may be code obfuscation, which consists of transforming our ready script into a slightly less readable form (e.g. by generating short random names of variables and functions, eliminating end-of-line signs, and so on), but the simple fact is that if somebody wants to steal our JavaScript code, there is very little we can do to stop them.


# Advantages

JavaScript has many advantages over other programming languages, and one of the biggest is a very active and supportive community. It is easy to find solutions to common problems, and to find help in general. This also means that tools that work with JavaScript are actively developed. Another big plus is a huge number of ready-to-use frameworks and libraries that provide most of the commonly required functionalities and features. The language itself is relatively easy to learn, and allows us to focus on the job instead of fighting with the syntax (that is, the way of building the instructions which make up the code of our program).

Additionally, JavaScript doesn’t require you to buy expensive tools to work with it, and really good tools are already embedded inside your web browser. Last but not least, big players like Google, Facebook, and Mozilla actively support JavaScript tools and their development. However, what is an advantage for some may turn out to be a disadvantage for others. An example may be the _dynamic typing_ characteristic of JavaScript. In short, it consists of the fact that we can store data of any type in a variable (a variable is a container in which we store the data we will use).

For example, during the program's execution, we can store the number 10 in a variable, and in the next step use the same variable to store the "abc" string (deleting the previous value automatically, of course – don’t worry if you don’t understand right now, because we’ll be covering all these terms later on). Usually this is very convenient, but a number of people have found this feature of the language to be a disadvantage. In their opinion, it makes it easier for a programmer to make mistakes in certain situations. By adding _static typing_, where a variable can only contain one type of variable (e.g. numbers) during program execution, a new language called **TypeScript** was introduced.


# Development tools

Like any other task, programming requires the proper tools and workspace. Software development, in most cases, requires a **code editor** and a **compiler** or **interpreter** of a given language. This is a minimum set, which we can extend as needed with various other tools.

Apart from the JavaScript code editor and interpreter, we can also use the **debugger**, which is a tool that allows us, among other things, to pause the program in the indicated place and analyze its current state (e.g. the values of the indicated variables).


# Online development environment

**Online environments**, commonly known as code playgrounds, are sites that act as a simple editor and runtime environment. All of them have similar sets of features. They have different user interfaces, but in principle, they behave in a similar way. They allow you to write code, run it for testing purposes and most often share it with other users. In the case of JavaScript, where preparing a fully working local environment actually boils down to installing a code editor and running the browser, they are not as important as regular development environments. They are mainly used as training and testing platforms, or places to publish sample solutions to programming problems.

Among JavaScript programmers, the most popular are the following:

- _[JSFiddle](https://jsfiddle.net/)_
- _[CodePen](https://codepen.io/pen/)_
- _[JsBin](https://jsbin.com/)_
- _[Plunker](https://plnkr.co/)_


# Local development environment

The JavaScript requirements for the development environment are very modest. In most cases, especially at the beginning of development, just three elements are sufficient: a code editor, an interpreter (i.e. a bootable environment) and a debugger. Depending on the level of sophistication, the complexity of the written project, or the environment for which we write our programs (client-side, server-side, mobile), other tools may also be needed.

These will be, among others:

- **package managers** – enabling the management of libraries (containing ready-made solutions that we can use in our programs) or components of the development environment (e.g. npm or yarn)
  
- **task runners and module bundlers** – used, in simple terms, to automate the process of software development and merge the resulting code from many files and libraries (e.g. Grunt or Webpack)
  
- **testing framework** – allows for automatic testing of the correctness of our program in search of potential errors (e.g. Mocha, Jasmine, or Jest)
  
- **security analyzers** – as you can guess, used to control the security of our solution (e.g. Snyk, RetireJS, or OWASP Dependency Check)

The openness of web development environments is both a blessing and a curse. We have a choice of hundreds of components, from which we can create the most comfortable environment for ourselves. However, their quantity, plus the dynamic changes of particular tools or even just the trends among programmers make it difficult to keep up with everything that’s happening within these environments.


# Code editor

The code of almost all programming languages is composed of some form of text. So, to write the code, we need a text editor. But it needs to be an application that writes plain text (it can’t be a rich text editor, like MS Word). In other words, just a plain notepad that can write .txt files is enough to write code, although it’s much easier if you use a dedicated code editor. The market is full of professional code editors, both free and paid. Some of them are universal, while others are exclusive to specific languages. The main advantage of using a dedicated code editor is syntax highlighting, text autocomplete, and error checking. This improves work efficiency and code understanding, and lowers the number of errors and typos. There are many good code editors, but it can be really hard to select one that works for you.

Here are some popular ones:

- _[**Visual Studio Code**](https://code.visualstudio.com/)
    
    [Windows, macOS, Linux]
    
    _![VS_code|50](https://edube.org/uploads/media/default/0001/02/JSE1_1.2.1.5_1_ENG.png)   
      
    
    Powerful code editor free for both personal and commercial use. It has quickly become one of the favorites when it comes to web development. It has built-in features like a JavaScript debugger, and tools to streamline web projects. It’s also highly customizable via the extension system (there are many additions dedicated especially to the JavaScript language).
    
  
- _[**WebStorm**](https://www.jetbrains.com/webstorm/)
    
    [Windows, macOS, Linux]
    
    _![WebStorm|50](https://edube.org/uploads/media/default/0001/02/JSE1_1.2.1.5_2_ENG.png)  
      
    
    A popular commercial development environment, in which the code editor is just one of the smaller elements in a huge set of tools that improve code development (e.g. supporting testing). Intended for large projects, it may prove to be too heavy and complex for small programs. Although it is intended for commercial use, it is possible to obtain a free educational license.
    

  

  

- _[**Sublime Text**](https://www.sublimetext.com/)_
    
    [Windows, macOS, Linux]
    
    ![Sublime_text|50](https://edube.org/uploads/media/default/0001/02/JSE1_1.2.1.5_3_ENG.png)  
      
    
    Fast and easy-to-use code editor with many advanced features, like multiple-line editing, fast search, and others. A trial version is available, but for long-term usage, a license needs to be purchased for both private and commercial use.
    
  
- _[**Notepad++**](https://notepad-plus-plus.org/)_
    
    [Windows]
    
    ![Notepad++|50](https://edube.org/uploads/media/default/0001/02/JSE1_1.2.1.5_4_ENG.png)  
      
    
    Free and lightweight code and text editor. The program is small and fast, supports dozens of programming languages, and can be extended with plugins. It may be old and ugly, but it’s still sharp.
    

Lots of other code editors exist, both free and paid, and you can use whichever one you prefer. Many developers use, among other things, console editors, including the legendary vim. Console editors are not run in a graphical environment, but in a text console. However, you can only reach for such solutions if the tasks you're going to do turn out to be too simple and you want to make your life a little bit more difficult.


# Interpreter

We have already talked a bit about the **interpreter** and its role. It functions as a runtime environment for our program. It checks whether we have made any formal errors, for example, making a typo in the name of a function or forgetting to close a parenthesis, and then it executes the program instruction by instruction.

The choice of JavaScript interpreter will depend on which platform we write our software for. For example, if we want to write a simple server-side application, we will almost certainly choose the **node.js** environment, which we will have to install directly on our operating system. As we said before, practically all browsers have built-in JavaScript engines (or interpreters), but we strongly recommend using **Chrome** from Google, or **Firefox** from Mozilla. Both are known for their efficiency and integrated advanced tools for web developers (that’s you). They are available for Windows, macOS, and Linux.

  
# Debugger

Computer programs are complicated beasts, thousands or even millions of lines of code. With such complexity and size, it’s impossible to produce code without any errors. Some types of errors, especially logical ones (formally, the program is written correctly, but probably we invented the wrong solution to the problem), can only be found while the program is running, and often only in special circumstances. It’s really hard to find out what exactly is happening inside a program that runs blazing fast, and for those problems, debuggers exist.

A **debugger** is a tool that allows you to slow down or even halt the execution of a program, run instructions step by step, and look at and analyze the state of the program at any given moment. Fortunately, the moment we decided to use the web browser as our boot environment and JavaScript interpreter, we also got ourselves a debugger. All modern browsers are equipped with the developer tools. During normal operation, they are invisible, and we have to enable them in the browser options (more about this in the next chapter).

Depending on the browser, we will find various tools there, but there will certainly be:

- **the inspector** – which will allow us, for example, to analyze the individual HTML elements of an open website;
  
- **the JavaScript console** – which firstly shows all the information about the errors, and secondly allows us to run single JavaScript commands in the context of the current page;
  
- **the debugger** – which, among other things, shows the current values of variables, and allows you to pause code execution in the indicated place and to perform step-by-step work (i.e. execute single instructions of the program).

How do you enable the developer tools? Unfortunately, there is no single answer; it depends on the browser you’re using (sometimes also on its version) and the operating system. Browser interfaces change quite often, so it is better to learn the right shortcuts instead of looking for the right option in the menu. Try the following key combinations:

- Windows and Linux operating systems, all common browsers except Internet Explorer and Edge:  
    ![ctrl + shift + I|256](https://edube.org/uploads/media/default/0001/02/JSE1_1.2.1.7_1_ENG.png)
  
- Windows operating system, Internet Explorer and Edge:  
    ![F12|256](https://edube.org/uploads/media/default/0001/02/JSE1_1.2.1.7_2_ENG.png)
  
- macOS operating system, all common browsers:  
    ![Command key + Option key + I|256](https://edube.org/uploads/media/default/0001/02/JSE1_1.2.1.7_3_ENG.png)


# The "Hello, World!" Program

Why "Hello, World!"? For almost 50 years, this sentence, and its derivatives, has marked someone as learning a new programming language, although it’s more a tradition than anything else. The phrase was used a long time ago in a very important book about the C language, but the text itself doesn’t matter. The idea is to write out something on the screen using a specific language. First, it allows us to see the basic syntax of the language and compare it to other programming languages. Second, it’s a very simple program, and anyone can easily write it or copy it from the internet and check if their tools and environment are set up correctly. Third, it’s a program that outputs something, so it provides feedback on whether it was executed correctly or not.

In the case of client-side JavaScript, displaying something on the screen can be understood in two ways.

First, client-side JavaScript is always executed in the context of a website and allows you to manipulate elements of that website. So we can, for example, use the appropriate function to insert some text, change a title, create a table, etc. on the page. This way, we control the visual part of the website.

Second, we can use the **console** as a screen to write some information. The console, as we mentioned in the previous chapter, is part of the developer tools. So it is not visible by default, and it must be properly enabled (we also wrote about this in the previous chapter). For our needs, it will be much more convenient to use the console, as we will avoid the need for a thorough analysis of the structure of the website.

But what actually is a console? First of all, it is a place where various messages are displayed, normally invisible to the browser user. These messages can, for example, be generated by the JavaScript interpreter after encountering an error or if we print it, by calling the appropriate function. Secondly, we can run individual JavaScript commands in the console, which will be executed in the context of the currently loaded web page (a little more about that in a moment).

The basic function allowing us to write information to the console is console.log. So, to refer to the eternal "Hello, World!", we should call it as follows:

```js

console.log("Hello, World!");

```




We can treat the `console.log` as a function*. In fact, the function is only a log, and console is the object to which the function belongs.

The **function** is a piece of code that allows you to perform a specific task (in our case, to display something on the console). Functions often take arguments, in other words, data that they will use during operation. In JavaScript, we run a function by calling it, and we call it by writing its name followed by a pair of parentheses, where the arguments are provided (if the function does not need arguments, the parentheses are left empty). In our example, the argument is the text we want to display. Note that in order to indicate that "Hello, World!" is the text, we put it in quotation marks.

To let the interpreter know where the command ends, we put a semicolon at the end of the function call. In this case, the interpreter would manage without such help, but it is a good habit to end each command with a semicolon, so that you do not forget it when it is really needed.


# Online development environment


In the editor, you should see the piece of code that was just discussed, containing the console.log function. 

```js
console.log("Hello, World!");
```

Try to run it. You need to press the highlighted button with the play icon, located directly above the editor. As a result, the lower window simulating the console should show:

`Hello, World!`

Go to the editor again and change the word "World" to your name. Start the program again and check what appears in the console window. Congratulations, you just modified a program written in JavaScript.

We could discuss your first JavaScript program based on this example. You've learned its syntax, run it online, checked its effect, and even modified it yourself. You can test all the examples that we discuss in this course in this way. 


# Local development environment

Client-side JavaScript is a language of the web and exists only in the web ecosystem. In this setup, JavaScript cannot exist by itself. JavaScript code needs to be embedded in an HTML document. When we used the online environment to run our program, certain aspects were hidden from us. This time we will have to look at them more closely.

## A few words about HTML

**HyperText Markup Language**, or **HTML** for short, is a set of tags used to describe the structure of a website. It allows us to give a page the format of a document containing sections, headers, paragraphs, lists, and the like. HTML is definitely beyond the scope of the current course, so we will present only some basic information about it, just enough for you to understand where and how we can run the JavaScript code associated with a given page.

Tag types are predefined. For example, the tag that specifies a paragraph is `<p>` and the tag for the first degree (largest) header is `<h1>`. The tag name must be placed in angle brackets. Tags are usually used in pairs, limiting a certain area of the document (we have an opening and a closing tag). The closing tag is different from the opening tag, because a slash appears before the name. For example, a paragraph may look like this:

```html

<p>quite an ordinary paragraph</p>

```

Often, tags can (and sometimes must) be placed within the range of other tags. For example, our paragraph should be placed inside the `<body>` tags, which separate the main part of our document.


```html

<body> <p>quite an ordinary paragraph</p> </body>

```

  

## Minimal HTML document

Let's try to create a minimal HTML that defines an empty page.

```html

<!DOCTYPE html> <html> <head> <title>Empty Page</title> </head> <body> </body> </html>

```

Let's start with the declaration <!DOCTYPE html>. This is not a typical tag, as it is used to inform the browser that the whole document has been prepared according to HTML5. The actual document description starts with the <html> tag, which together with the </html>tag sets the boundaries of the document. Every other tag should be inside these. If any given tag holds other content, there will be a corresponding closing tag, forming some sort of container.

The next tag, <head>, contains additional information about the document, which must also be placed in tags. The most basic one is the <title> tag, which sets the title of the page mostly visible in the browser title bar. After <head> there is the <body> element, and the visible content of the web page should be placed there (e.g. our paragraph).


# `<script_>` tag

The JavaScript code to be executed by the browser on the page must be attached to the HTML using the `<script_>` tag, and there are two ways it can be done. The code can be embedded directly inside of the `<script_>` and `</script_>` tags, but this is only recommended when the code is short. Another approach is to use the `"src"` attribute to point to a separate file that contains the JavaScript code. This is especially true when the same code is going to be used on several pages, because repeating exactly the same code many times is bad practice, as any changes need to be applied to all the files; and additionally, it artificially increases the page size. The JavaScript file extension is .js.

HTML is read by the browser line by line, and script tags are executed right at the moment when the browser parses the `<script_>` tag (parsing for programming languages means a formal analysis of the code by a machine in order to understand its structure). Usually `<script_>` tags are inserted in the page header between the `<head>` and `</head>` tags, and we can insert many of them in a file, for example, in order to include JavaScript code from different files. This behavior can be changed for external scripts pointed to by the `"src"` attribute by using the `"defer"` or "async" attributes.

- `defer` – means that the script should be executed after the whole page is loaded;
- `async` – means that the script will be executed immediately, but in parallel to parsing the rest of the page.

  (None of tags are <script_> i added the underscore for formatting purposes remeber it for future as well) ***<font color="#c0504d">SEE</font>***

## ... and a little something about CSS

**CSS**, or **Cascading Style Sheets**, is a language used together with HTML to describe the appearance of a page and its elements. In a nutshell, HTML describes the structure of a document, while CSS describes its presentation.

For example, in HTML, we can describe a page that has a header, two paragraphs, and a data table.

In CSS, we can define what font will be used on the whole page, what color the background will have, or whether the mouse cursor, when moved over the table, should change shape.

So we can treat CSS as some kind of configuration of the visual layer of the page. Thus, the website will most often be built on the basis of an HTML file (that is, a description of the structure), JavaScript code (allowing us to add, for example, some interaction mechanisms) and a CSS file (describing the presentation layer of the page). However, what is important is that there will be no page without an HTML file, but we can easily create a page without using CSS files. The CSS description itself is outside the scope of the current course, and we mention it only for the sake of order.


# How can we run our JavaScript code?

Let's start with a simple example, where the browser gets a simple (maybe even an empty) page from _https://test.org_. Look at the figure below.

![alt text](https://edube.org/uploads/media/default/0001/02/JSE1_1.3.1.6_ENG.png)



Let's start from the right side of the figure. The user runs a web browser on their computer (e.g. Chrome). Using the appropriate hotkey shortcut, they turn on the **developer tools** (see the previous chapter) to be able to use the console. Remember that these tools are not needed for normal browser use, and are therefore hidden by default. Then the user types _https://test.org_ (the URL of our fake site) in the address bar.

On the remote server (left side of the drawing), associated with the address _https://test.org,_ a web server is launched, which, after receiving a request from our user, will prepare an answer for them. In the simplest case, the answer will only contain an html file, which can be stored on the same server. The html file (in this example, _index.html_) is sent back to the user and processed by the browser. If some content (e.g. a paragraph with text) is defined in it, it will be displayed in the browser window.

However, we are more interested in the fact that the index.html file contains the `<script_>` and `</script_>` tags, with a piece of JavaScript code between them. Do you recognize it? This is obviously an attempt to show our "Hello, World!" on the console. When loading the page, the code placed inside the `<script_>` tags should be executed and, if the developer tools are enabled and the console panel is visible, the console will show `"Hello, World!"`.

As we said before, the `<script_>` tag can be used in a different way, not only to constrain the place where we write JavaScript code directly. If we use the "src" attribute in this tag, we can indicate a separate JavaScript file that will be attached here.

The picture below shows an example of such a scenario. In the index.html file there is the `<script_>` tag again. This time there is no JavaScript code placed after it, but by using the "src" attribute, it is indicated that the code from the main.js file should be attached here.

![alt text|1000](https://edube.org/uploads/media/default/0001/02/JSE1_1.3.1.7_1_ENG.png)

Everything will work exactly the same as in the previous scenario, except that the web server will provide the main.js file in addition to index.html. The user will not notice any difference. Of course, placing our code on a remote server just to test it would be a bit cumbersome.

  

We have another possibility, which is that we can load a local html file (i.e. one that is on our computer) into the browser. If this code contains a `<script_>` tag indicating some JavaScript file, then this file will also be loaded from the local resources.

The picture shows a simple scenario in which the user loads a local index.html file into the browser, in which there is a reference to main.js (so this file will automatically be loaded, too).

![alt text|1000](https://edube.org/uploads/media/default/0001/02/JSE1_1.3.1.7_2_ENG.png)



You can load a local html file either by typing its local path after file:/// in the address bar, or by simply opening it in your browser using the Open command from the menu. Since the menu in browsers is very often hidden, a simpler way may be to use a shortcut to open existing documents in applications. The shortcut is universal, not only for browsers and you have probably already seen it:

![Tutaj opis po angielsku co jest na obrazku|200](https://edube.org/uploads/media/default/0001/02/JSE1_1.3.1.7_3_ENG.png)  
  

or in the case of macOS:

![Tutaj opis po angielsku co jest na obrazku|200](https://edube.org/uploads/media/default/0001/02/JSE1_1.3.1.7_4_ENG.png)


# Okay, maybe we could finally run something...

To run this locally, you’ll need to open the code editor of your choice. Create a new file with the extension .html (the name of the file doesn't matter, but it’s good practice to avoid spaces in the file name). Put the following code in this file and save it.

`<!DOCTYPE html> <html> <head> <title>Empty Page</title> <script src="main.js"></script> </head> <body> </body> </html>`  

Then, in the same editor, create another file, this time called main.js (this is the name we used in our html file). It should contain one line you've seen before:

`console.log("Hello, World!");`


Save the changes and go to the browser. Open a new tab, enable the developer tools (they open for a particular tab), and select the console tool. Give yourself a moment to get used to the layout of the developer tools (each tool, including the console, should be placed in a separate panel, which can be selected).

Just in case, make sure that the focus is set to the browser window (i.e. the new tab) by clicking on it. Then, using the appropriate keyboard shortcut open the html file you have just created. If everything has been done correctly, you should see our "Hello, World!" sign in the console. Make sure that it works and that you can see a message displayed in the debug console. If necessary, do it again, carefully following the steps.

And now a small challenge. Try to modify the html file yourself so that it does not refer to the main.js file. Instead, the same JavaScript code that we wrote in main.js should be placed directly after the `<script_>` tag. If you have problems, go back to the first drawing in this section.

# Executing the code directly in the console

We have another, quite convenient option when it comes to running short pieces of JavaScript code in the browser (and our program, consisting of one instruction, is definitely short). As we said before, the console is not only used to display information, but also allows you to run individual JavaScript instructions. These instructions must be executed in the context of some HTML page. However, you don't necessarily have to write your minimal page, as we did a moment ago. Try to open a new tab and type `about:blank` in the address bar. This is a pseudo address that tells your browser to generate and load a minimal blank HTML page.

Then run the developer tools. At the beginning, we can check what the HTML generated by the browser looks like. To do so, select the first tool from the panel (in Chrome, it will be Elements, in Firefox Inspector). You should see absolutely minimal html code:

`<html> <head></head> <body></body> </html>`  

Now choose the console from the developer tools. You should see a prompt, usually a sign `>` or `>>` followed by a flashing cursor (if there is no cursor, click on the prompt). Then you can enter the instruction that will show "Hello, World!" on the console (using the console.log function). The scenario is shown in the figure below.

![alt text](https://edube.org/uploads/media/default/0001/02/JSE1_1.3.1.9_1_ENG.png)

In fact, regardless of the browser, we should get the same effect – the console will display the text we specified. In the case of Chrome (running on the Windows operating system), the console should look something like this after completing this task:

![alt text](https://edube.org/uploads/media/default/0001/02/JSE1_1.3.1.9_2_ENG.png)

In the case of Firefox (also Windows) this way:

![alt text](https://edube.org/uploads/media/default/0001/02/JSE1_1.3.1.9_3_ENG.png)

For both browsers, the debugger windows containing the console may vary minimally depending on the version of the software and the operating system running it. The developer tools can be moved. They can be located at the bottom of the browser, as in the examples shown, but they can also be placed on the left or right side of the window (or as a separate window entirely). So don't be surprised if your browser's layout is slightly different from the pictures.


# Tasks

  

**Task 1**

Use `console.log` to output your full name to the console.

Example

`console.log("Mary Stuart");`

  
  

**Task 2**

Output your year of birth.

Example

`console.log("1542");`

  
  

**Task 3**

Try again to output your year of birth, this time passing the date without the quotes.

Example

`console.log(1542);`

  
  

**Task 4**

We can pass several arguments to `console.log` separated by commas, e.g.:

`console.log("abc", "def", "ghi");`  

Output information about yourself to the console in the format: `Name Surname (Year)` e.g. _Mary Stuart (1542)_.

- giving all the information as one argument;
- giving the name, surname, and year as separate arguments.

Example

`console.log("Mary Stuart (1542)"); console.log("Mary", " Stuart ", "(1542)");`

  
  

**Task 5**

Output the same information (name, surname, year) to the console, not side by side, but on consecutive lines.

Example

`console.log("Mary"); console.log("Stuart "); console.log("(1542)");`

  
  

**Task 6**

A string can be concatenated using the `+` sign, for example `"abc"` `+` `"def"` will be treated as `"abcdef"`. Try writing your name, surname, and year of birth on one line again, this time not separated by commas, but by `+` signs.

Example

`console.log("Mary" + " Stuart" + "(1542)");`

  
  

**Task 7**

Put spaces in the appropriate places, so that when displayed, you get the same effect as in **Task 4**.

Example

`console.log("Mary " + " Stuart " + "(1542)");`