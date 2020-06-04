# Web Development

`npm init`

`npm install lite-server --save-dev`

in package-lock.json:

 <pre>`"scripts": {
      "start": "npm run lite",
      "test": "echo \"Error: no test specified\" && exit 1",
      "lite": "lite-server"
    }`</pre>

`npm start`

Download bootstrap-starter.zip

.gitignore: node_modules

`npm install bootstrap@4.0.0 --save`
`npm install jquery@3.3.1 popper.js@1.12.9 --save`

`Required meta tags always come first ``
     <meta charset="utf-8">``
     <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">``
     <meta http-equiv="x-ua-compatible" content="ie=edge">``
 
  Bootstrap CSS``
     <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.min.css">``
     
  jQuery first, then Popper.js, then Bootstrap JS.
  `<script src="node_modules/jquery/dist/jquery.slim.min.js"></script>` 
   `<script src="node_modules/popper.js/dist/umd/popper.min.js"></script>` 
     `<script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>`