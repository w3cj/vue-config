## Over<img src="https://cdn.worldvectorlogo.com/logos/vue-9.svg" style="background:none;border:none;height:70px;width:auto;" />ue of



<img src="https://github.com/wingsuitist/ecmascript-logo/blob/master/es2015-ecmascript-logo.png?raw=true" style="background:none;border:none;height:200px;width:auto;" />
<img src="https://cdn.worldvectorlogo.com/logos/babel-10.svg" style="background:none;border:none;height:200px;width:auto;" />

<img src="https://cdn.worldvectorlogo.com/logos/eslint.svg" style="background:none;border:none;height:200px;width:auto;" />
<img src="https://cdn.worldvectorlogo.com/logos/webpack-icon.svg" style="background:none;border:none;height:200px;width:auto;" />

---

<!-- .slide: data-background="http://galvanize-wp.s3.amazonaws.com/wp-content/uploads/2016/09/14143218/Platte-Oct-2015-4593-min.jpg"  -->

<div style="background: rgba(0, 0, 0, 0.4);border-radius: 50px">
  <h1>CJ</h1>
  <h3>Instructor, Sr. Full Stack Developer</h3>
  <h2>at</h2>
  <img src="https://s3-us-west-2.amazonaws.com/galvanize.com-dev/galvanize-logo.svg" style="height:100px;width:auto;border:none;background:rgba(0, 0, 0, 0)">
</div>

---

## Objectives

* Use the latest features of ECMAScript including CommonJS modules, Classes, Arrow Functions, Template Strings, Destructuring and Method Definitions
* Update the included babel config to use the latest features of es-next
* Add/remove/update rules in the included .eslintrc
* Modify/update and add plugins to the included webpack config

---

<img src="https://dab1nmslvvntp.cloudfront.net/wp-content/uploads/2017/01/1484692838webpack-dependency-tree.png" style="background:none;border:none;height:400px;width:auto;" />

---

<img src="https://github.com/wingsuitist/ecmascript-logo/blob/master/es2015-ecmascript-logo.png?raw=true" style="background:none;border:none;height:300px;width:auto;" />

----

* CommonJS modules
* Classes
* Arrow Functions
* Template Strings
* Destructuring
* Method Definitions

---

<img src="https://cdn.worldvectorlogo.com/logos/babel-10.svg" style="background:none;border:none;height:300px;width:auto;" />

----

* Babel configurations are stored in the `.babelrc` file
* This config is read by the webpack `babel-loader`
* Includes the [`env` preset](https://babeljs.io/docs/plugins/preset-env/) and [stage-2 preset](https://babeljs.io/docs/plugins/preset-stage-2/) by default
  * env - Includes all ES2015+ plugins
  * stage-2 - All plugins from stage 2, 3 drafts
* Other presets [here](https://babeljs.io/docs/plugins/)
* [Include/Exclude Specific Plugins from a preset](https://babeljs.io/docs/plugins/preset-env/#examples-include-and-exclude-specific-plugins-built-ins)

---

<img src="https://cdn.worldvectorlogo.com/logos/eslint.svg" style="background:none;border:none;height:300px;width:auto;" />

----

* eslint configurations are stored in the `.eslintrc.js` file
* Ignored files are stored in the `.eslintignore` file
* This config is read by the webpack `eslint-loader`
* Depending on how the project was generated, your config may extend a config like `airbnb-base`
* Rules can be added/disabled in the `rules` section

----

* Don't rely on Vue.js to throw a linter error
* Use an eslint plugin for your editor to catch errors _before_ going to the browser

---

<img src="https://cdn.worldvectorlogo.com/logos/webpack-icon.svg" style="background:none;border:none;height:300px;width:auto;" />

----

* Base config is located in `build/webpack.base.conf.js`
* Development config is located in `build/webpack.dev.conf.js`
* Production config is located in `build/webpack.prod.conf.js`
* Rules are run in top down order
* Add a [custom plugin](https://webpack.js.org/plugins/provide-plugin/)

---

## Review

* Use the latest features of ECMAScript including CommonJS modules, Classes, Arrow Functions, Template Strings, Destructuring and Method Definitions
* Update the included babel config to use the latest features of es-next
* Add/remove/update rules in the included .eslintrc
* Modify/update and add plugins to the included webpack config

---

## Thank you <img src="https://cdn.worldvectorlogo.com/logos/vue-9.svg" style="background:none;border:none;height:70px;width:auto;" />ery much!

<img src="https://github.com/wingsuitist/ecmascript-logo/blob/master/es2015-ecmascript-logo.png?raw=true" style="background:none;border:none;height:200px;width:auto;" />
<img src="https://cdn.worldvectorlogo.com/logos/babel-10.svg" style="background:none;border:none;height:200px;width:auto;" />

<img src="https://cdn.worldvectorlogo.com/logos/eslint.svg" style="background:none;border:none;height:200px;width:auto;" />
<img src="https://cdn.worldvectorlogo.com/logos/webpack-icon.svg" style="background:none;border:none;height:200px;width:auto;" />

---
