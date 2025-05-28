# TinyBoxer

See the [PLISS slides](http://tpetricek.github.io/Talks/2025/programming-systems/pliss/#/6) for
background information on the project. (Use down arrow to get to the next slide or Esc to
see the full two-dimensional structure!)

## Instructions

There are 5 steps, gradually implementing Tiny Boxer:

* Step 1 - Parsing DOM into commands and parameters
* Step 2 - Evaluation of simple built-in commands
* Step 3 - Turtle graphics and repeat command for looping
* Step 4 - Box lookup and built-ins that introduce boxes
* Step 5 - Calling other boxes and input command

Go to the first step, complete the `TODO`s and then move on to the next step! In the later steps, you will be asked to copy some parts of your solution from the previous step (into the new template that adds more boilerplate). All the `TODO`s are in the JavaScript/TypeScript files.

## Running the JavaScript version

Just open `index.html` in your web browser and `main.js` in some editor. Make edits, refresh your web page. Make sure to open browser debugging tools to see error messages!

## Running the TypeScript version

The setup is using TypeScript with [esbuild](https://esbuild.github.io/) which was apparently a popular JavaScript build tool in the week when I created the demo. Install everything using:

```
npm install
npm run start
```

Once running, open http://127.0.0.1:8000 in your web browser and `main.ts` in some editor. Make edits, refresh your web page. Make sure to open browser debugging tools to see error messages!
