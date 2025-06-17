Hello world
is part of the tutorial is about core JavaScript, the language itself.

But we need a working environment to run our scripts and, since this book is online, the browser is a good choice. We’ll keep the amount of browser-specific commands (like alert) to a minimum so that you don’t spend time on them if you plan to concentrate on another environment (like Node.js). We’ll focus on JavaScript in the browser in the next part of the tutorial.

The <script> tag contains JavaScript code which is automatically executed when the browser processes the tag.
The old HTML standard, HTML4, required a script to have a type. Usually it was type="text/javascript". It’s not required anymore. Also, the modern HTML standard totally changed the meaning of this attribute. Now, it can be used for JavaScript modules. But that’s an advanced topic, we’ll talk about modules in another part of the tutorial.

This trick isn’t used in modern JavaScript. These comments hide JavaScript code from old browsers that didn’t know how to process the <script> tag. Since browsers released in the last 15 years don’t have this issue, this kind of comment can help you identify really old code.