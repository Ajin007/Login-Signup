# Login-Signup
- npm init -y
- npm install bootstrap
- Create a custom file in SCSS folder named "custom.scss"
- Type ----> // Import Bootstrap SCSS
@import 'node_modules/bootstrap/scss/bootstrap';

// Your custom styles here
- npm install node-sass --save-dev ---> Compile SCSS to css
- "scripts": {
    "compile-scss": "node-sass scss/custom.scss css/custom.css"
}
-----> copy this in package.json
  - npm run compile-scss
  - 
