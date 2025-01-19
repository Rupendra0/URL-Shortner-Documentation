# URL-Shortner-Documentation

URL Shortner is mainly constructed by using node.js, express and mongoDB.
We use Node.js for server environment and express to simplify the architecture of node.js .

<h1>1. Routes</h1>
here we will make two routes :
<h3>1 --> POST /.  : To request url from user and send to it database MongoDB.</h3>

now we will process this url using Nano id (a library of node.js to generate random id's) and then we store this random id along with its redirecting URL and when user give GET req. form browser the we will send this url from database and render it to frontend and user will redirected to that URL.

<h3> 2 --> GET /.  : To send url to the frontend when user will make a request through Browser or from anywhere.</h3>

<h3>**We will send all data in form of JSON format because we will render on any device like browser, alexa or any digital device having frontend components </h3>
