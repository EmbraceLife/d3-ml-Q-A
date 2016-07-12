# d3-ml-Q-A
my learning path's questions and answers collected

### How to setup env for d3 src anatomy?
-------------------
[checkout stackoverflow](http://stackoverflow.com/questions/38225993/how-to-setup-node-environment-to-run-es6-codes-involving-syntax-like-import)

**5 steps to set it up**

1. create a directory and run `npm init` at its terminal;
2. move inside this directory's terminal run:
     `npm install --save-dev PackageName`
   for the following packages:
     `browserify`, `babel-cli`, `babelify`, `babel-preset-es2015`;
3. run `npm install --save d3` or modules like `d3-color`;
4. to create `.babelrc` file:
    run `echo '{ "presets": ["es2015"] }' > .babelrc;`
5. In the terminal run scripts with:
    `./node_modules/.bin/babel-node script.js`



### How to run `docco` for all JS scripts?
-------------------
Online Resources:    

[video guide1](https://www.youtube.com/watch?v=1BEidZzIWjM)      
[video guide2](https://vimeo.com/91118854)   

** 4 steps to set it up**    

after the above 5 steps are done, install 3 packages globally with `npm`:    


1. `sudo npm install -g pygments`
2. `sudo npm install -g coffe-script`
3. `sudo npm install -g docco`
4. `docco *.js` to create a folder `docs` with all html files for each JS file


### How to understand RegExp patterns?
-------------------
1. go to [RegExr.com](http://regexr.com/)
2. paste the pattern you want to understand
3. mouse hover to see explanation




### How to debug/understand complex source code?
-------------------
1. comment out `export default`, `return` alike
2. `console.log` key variables at key places
