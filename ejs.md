#EJS

[Back to Main Page](README.md)

EJS is a templating language you can use to integrate JS with HTML. You'll start by using NPM to install EJS as well as CORS and express. You'll also need to tell your server to read concatenated file paths and actually start your server. You'll use a route to send the html to the client side along with an object. Anytime you're referenceing JS on a line with html you'll need to use `<%=JS %>` and on lines wihtout html you'll use `<%JS%>`.
One of the most common use cases is to render all the details of an object using a loop. 