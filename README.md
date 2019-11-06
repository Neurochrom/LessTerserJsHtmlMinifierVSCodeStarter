# Less Terser JS HTML-minifier VS Code Starter

This is a static HTML project boilerplate configured to be developed within Visual Studio Code. Static but minified (built) on save with all source maps properly configured as to allow visual studio & chrome debugging. And using LESS not the cumbersome boilerplate CSS.

## Prerequisites

Install Visual Studio Code and the following  plugins:

- Easy LESS
- Save and Run
- Debugger for Chrome

Install Node and npm and additional packages by issuing the following command:

```
npm install -g terser less html-minifier
```

## Have fun

To generate the build just save the .html and .less and at least one .js file with VS Code.
The output will be in the builds directory.
When you start debugging Chrome will create a new profile - this makes it not work for the first time sometimes.

## License

Public domain. This should work out of the box but for some reason it does not.

## FAQ

- Why not webpack?
  -
  Because it concentrates on packing .js files which makes sense if you're using a JS framework, but it's cumbersome to pack static html pages with it. It'd be like using a tank to cut bread.

- Typescript?
  -
  Yes. Stay tuned.

- Why LESS?
  -
  Because it's in JS - don't want additional deps. So for me LESS > SASS.

- Contrbutions?
  -
  Yes! Bring 'em on.

## Disclaimers

- I'm not a web develoepr - this might be stupid.
- If you want to build a serious web app use a framework like React.
- No seriously this is just some dumb boilerplate for a dumb project set up so a guy who likes when tools (like debuggers) automate his workflow.