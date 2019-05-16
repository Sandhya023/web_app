# web_app

## Add .eslintrc.js
We need to create .eslintrc.js file. ESLint is designed to be completely configurable, meaning you can turn off every rule and run only with basic syntax validation, or mix and match the bundled rules and your custom rules to make ESLint perfect for your project.

### .eslintrc.js
```ruby
{
  "extends": ["airbnb", "prettier", "prettier/react"],
  "plugins": ["prettier"],
  "parser": "babel-eslint",
  "parserOptions": {
    "ecmaVersion": 2016,
    "sourceType": "module",
    "ecmaFeatures": {
      "jsx": true
    }
  },
  "env": {
    "es6": true,
    "browser": true,
    "node": true
  },
  "rules": {
    "react/jsx-filename-extension": [1, { "extensions": [".js", ".jsx"] }]
  }
}
```

### Add eslint prettier

```ruby  
yarn add --dev eslint prettier eslint-config-airbnb@^15.0.1 eslint-config-prettier eslint-plugin-prettier eslint-plugin-react eslint-plugin-import eslint-plugin-jsx-a11y@^5.1.1

```

### Add React router and React router dom

```ruby
yarn add react-router
yarn add react-router-dom
```

### Install React semantic ui

```ruby
npm install react-semantic-ui semantic-ui-css
```
