## GUIDE

create folder 'api'

npx create-react-app client

cd .\api\  
npm init  
npm i express mongoose cors  
create file 'server.js'  
npm i -D nodemon

package.json -> delete "test" -> replace "start": "nodemon server.js"

npm start

api folder
 - create folder 'models'
 - create folder 'requests.rest'

cd client
 - delete files under src -> 'App.css', 'App.test.js', 'logo.svg', 'reportWebVitals.js', and setupTests.js
 - remove lines under index.js
 - remove lines under index.css
 - remove lines under App.js
 - ctrl + shift + p -> 'Detect Indentation from Content', 'Convert Indentation to Tabs', 'Indent Using Spaces - 4'
 - npm start