# angular-login

#### db.json 기동하는 방법 (cmd 창에서)
###### cd fake-json-server-login
###### json-server --watch db.json --port 3000
```
C:\fake-json-server-login>json-server --watch db.json --port 3000
  \{^_^}/ hi!
  Loading db.json
  Done
  Resources
  http://localhost:3000/users
  http://localhost:3000/books
  Home
  http://localhost:3000
  Type s + enter at any time to create a snapshot of the database
  Watching...
```
###### 웹 브라우저에서 http://localhost:3000/users 확인하기 


#### angular 서버 기동하는 방법 (cmd 창에서)
###### cd my-login-example
###### ng serve --open
```
C:\my-login-example

C:\my-login-example>ng serve --open
** Angular Live Development Server is listening on localhost:4200, open your browser on http://localhost:4200/ **
 10% building modules 3/3 modules 0 active
Date: 2018-11-12T09:17:21.340Z
Hash: 72805e353610eb22367c
Time: 21795ms
chunk {main} main.js, main.js.map (main) 31.8 kB [initial] [rendered]
chunk {polyfills} polyfills.js, polyfills.js.map (polyfills) 227 kB [initial] [rendered]
chunk {runtime} runtime.js, runtime.js.map (runtime) 6.22 kB [entry] [rendered]
chunk {styles} styles.js, styles.js.map (styles) 15.6 kB [initial] [rendered]
chunk {vendor} vendor.js, vendor.js.map (vendor) 3.83 MB [initial] [rendered]
i ｢wdm｣: Compiled successfully.
```
