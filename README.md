# Philme.in

This is an html file.

```html
<!DOCTYPE html>
<html lang='en-US' class='default'>
  <head>
    <meta charset='utf-8'>
    <title>TodoMVC React Redux Redux-Saga Ramda</title>
  </head>
  <body>
    <div id='content'></div>
    <script type='text/javascript' src='./dist/index.js' charset='utf-8'></script>
  </body>
</html>
```

This is a JavaScript file.

```js
import { configureBusinessLogic, businessProcesses } from 'config/business-logic'
import { configurePresentation } from 'config/presentation'
import { configureStore } from 'config/store'

const businessLogic = configureBusinessLogic()
const store = configureStore(businessLogic)
configurePresentation(store)

businessLogic.run(businessProcesses)
```

This is a test.

