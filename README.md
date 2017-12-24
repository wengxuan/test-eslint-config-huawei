# test-eslint-config-huawei

> A test eslint-config-huawei project

## prepare

``` 

# install node

# install vue-cli
npm install -g vue-cli

# vue init
vue init webpack projectName

#If you want to init in current directory
vue init webpack

```


## test eslint

```

# install
npm install --save-dev eslint babel-eslint eslint-plugin-vue@4.0.0-beta.4 eslint-config-huawei

# add .eslintrc.js in root directory (specific in .eslintrc.js)

# add "lint": "eslint src/**/*.vue" or "lint-fix": "eslint --fix src/**/*.vue" in package.json  (specific in package.json)
# you can use another name as you like to replace `lint`&`lint-fix`

# see lint result
npm run lint

# fix&see lint result
npm run lint-fix

```

## Vue Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
