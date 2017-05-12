Intall nodejs and Gulp(glabally and locally in dev mode)

npm install babel-preset-es2015 –save-dev
//Tracer or babel 

npm install gulp-traceur --save-dev
npm install gulp-typescript --save-dev
npm install gulp-plumber --save-dev
npm install gulp-concat --save-dev
npm install gulp-uglify --save-dev

Although the gulp-plumber, gulp-concat, gulp-typescript, and gulp-uglify
 modules are optional, they’re quite useful in a real-life workflow.
 The gulp-plumber module can help fix errors that occur in the Gulp
 pipeline while gulp-concat and gulp-uglify can be used to concatenate
 and minify JavaScript files to get them ready for production.
 They’re good to have in place and use once you’re ready to move files
 into production.

6. Add the babelrc file 
7. Create gulpfile.js that will contain our gulp tasks.


