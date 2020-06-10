![](https://seeklogo.com/images/J/javascript-logo-E967E87D74-seeklogo.com.png)
# Learn_Basic_Javascript

### What is JavaScript?

JavaScript ("JS" for short) is a full-fledged dynamic programming language that can add interactivity to a website. It was invented by Brendan Eich (co-founder of the Mozilla project), the Mozilla Foundation, and the Mozilla Corporation.
JavaScript is versatile and beginner-friendly. With more experience, you'll be able to create games, animated 2D and 3D graphics, comprehensive database-driven apps, and much more!
JavaScript itself is relatively compact, yet very flexible. Developers have written a variety of tools on top of the core JavaScript language, unlocking a vast amount of functionality with minimum effort. These include:
Browser Application Programming Interfaces (APIs) built into web browsers, providing functionality such as dynamically creating HTML and setting CSS styles; collecting and manipulating a video stream from a user's webcam, or generating 3D graphics and audio samples.
Third-party APIs that allow developers to incorporate functionality in sites from other content providers, such as Twitter or Facebook.
Third-party frameworks and libraries that you can apply to HTML to accelerate the work of building sites and applications.
It's outside the scope of this article—as a light introduction to JavaScript—to present the details of how the core JavaScript language is different from the tools listed above. You can learn more in MDN's JavaScript learning area, as well as in other parts of MDN.
The section below introduces some aspects of the core language, and offers an opportunity to play with a few browser API features too. Have fun!

### A Hello world! example

JavaScript is one of the most popular modern web technologies! As your JavaScript skills grow, your websites will enter a new dimension of power and creativity.
However, getting comfortable with JavaScript is more challenging than getting comfortable with HTML and CSS. You may have to start small, and progress gradually. To begin, let's examine how to add JavaScript to your page for creating a Hello world! example. (Hello world! is the standard for introductory programming examples.)

> Important: If you haven't been following along with the rest of our course, download this example code and use it as a starting point.

> - <script src="scripts/main.js"></script>

1. This is doing the same job as the <link> element for CSS. It applies the JavaScript to the page, so it can have an effect on the HTML (along with the CSS, and anything else on the page).
2. Add this code to the main.js file: 
3. Go to your test site and create a new folder named scripts. Within the scripts folder, create a new file called main.js, and    save it.
4. In your index.html file, enter this code on a new line, just before the closing </body> tag: 
> - const myHeading = document.querySelector('h1');
> - myHeading.textContent = 'Hello world!';
5. Make sure the HTML and JavaScript files are saved. Then load index.html in your browser. You should see something like this

![](https://media.prod.mdn.mozit.cloud/attachments/2014/11/21/9543/3561d5218e249d28b330b94346633ed8/hello-world.png)

> Note: The reason the instructions (above) place the <script> element near the bottom of the HTML file is that the browser  reads code in the order it appears in the file.

> If the JavaScript loads first and it is supposed to affect the HTML that hasn't lo
aded yet, there could be problems. Placing JavaScript near the bottom of an HTML page is one way to accommodate this dependency. To learn more about alternative approaches, see Script loading strategies.

### Language basics crash course

To give you a better understanding of how JavaScript works, let's explain some of the core features of the language. It's worth noting that these features are common to all programming languages. If you master these fundamentals, you have a head start on coding in other languages too!

### Variables
Variables are containers that store values. You start by declaring a variable with the var (less recommended, dive deeper for the explanation) or the let keyword, followed by the name you give to the variable:

> 1.let myVariable;

> Note: A semicolon at the end of a line indicates where a statement ends. It is only required when you need to separate statements on a single line. However, some people believe it's good practice to have semicolons at the end of each statement. There are other rules for when you should and shouldn't use semicolons. For more details, see Your Guide to Semicolons in JavaScript.

