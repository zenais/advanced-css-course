# to install sass

npm install node-sass --save-dev

# to install specified packages from package.json

npm install

# add to package json to compile

"scripts": {
"compile:sass":"node-sass sass/main.scss css/style.css --w"
},

# call script

npm run compile:sass
