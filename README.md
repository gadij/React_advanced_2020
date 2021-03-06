## Corresponding Projects

#### useState

1. Birthday Reminder

#### useEffect and Conditional Rendering

2. Tours
3. Reviews
4. Accordion
5. Menu
6. Tabs
7. Slider

#### Forms

8. Lorem Ipsum Generator
9. Color Shades Generator
10. Grocery Bud

#### useRef

11. Navbar

#### useContext

12. Modal and Sidebar
13. Stripe Menus

#### useReducer and useContext

14. Cart

#### React Router

###### JS snippets

paste it into: Preferences > user snippets > javascript.json

{
"Console Log": {
"prefix": "cl",
"body": "console.log($1);",
    "description": "Console Log"
  },
  "Named Function": {
    "prefix": "nfn",
    "body": ["function ${1:functionName}($2) {", "  $3", "}"],
    "description": "Named Function"
  },
  "Anonymous Function": {
    "prefix": "fn",
    "body": ["function() {", "  $2", "}"],
    "description": "Anonymous Function"
  },
  "Arrow Function": {
    "prefix": "arfn",
    "body": ["const ${1:functionName} = ($2) => {", "  $3", "}"],
    "description": "Arrow Function"
  },
  "Basic If Statement": {
    "prefix": "ifc",
    "body": ["if(${1:condition}) {", " $2", "}"],
    "description": "If Statement"
  },
  "If Else Statement": {
    "prefix": "ifelsec",
    "body": ["if(${1:condition}) {", " $2", "} else {", "  $3", "}"],
    "description": "If else statement"
  },
  "Array Method": {
    "prefix": "arrmth",
    "body": [
      "${1|forEach,map,filter,reduce,some|}((${2:item}) => {",
      "  $3",
      "})"
    ],
    "description": "Array Method"
  },
  "Axios Request": {
    "prefix": "axreq",
    "body": [
      "axios.${1|get,post,put,delete|}('${2:url}')",
      "  .then(res => console.log(res.data))",
      "  .catch(err => console.log(err));"
    ],
    "description": "Axios Request"
  },
  "Fetch Request": {
    "prefix": "fetchreq",
    "body": [
      "fetch('${1:url}')",
" .then(res => res.json())",
" .then(data => console.log(data));"
],
"description": "Fetch Request"
},
"asfetchreq": {
"prefix": "Async Await Fetch",
"body": [
"const request = async ($1) => {",
" const response = await fetch('${2:url}');",
" const data = await response.json();",
" console.log(data);",
"}"
],
"description": "Fetch Async/Await"
},
"Node Require": {
"prefix": "ndrq",
"body": "const ${1:import} = require('${module}');",
"description": "Require a Node.js module"
},
"Express Server": {
"prefix": "expsrv",
"body": [
"const express = require('express');",
"",
"const app = express();",
"",
"app.${1|get,post,put,delete|}('${2:route}', (req, res) => {",
" $3",
"});",
"",
"const PORT = process.env.PORT || ${4|3000,5000,8000,8080|};",
"",
"app.listen(PORT, () => console.log(`Server Running On Port ${PORT}`));"
],
"description": "Express Server"
},
"Express Route": {
"prefix": "exprt",
"body": "app.${1|get,post,put,delete|}('${3:/}', (req, res) => {});",
"description": "Express Route"
},
"Express Init Middleware": {
"prefix": "exmw",
"body": "app.use(${1:middleware});",
"description": "Express Middleware"
}
}
