## Async Demo

This project contains sample code snippets to explain various mechanism which is supported by JavaScript for handling async requests. Below are some of the concepts highlighted in the demo:

1. Creating a simple Ajax request using XMLHttpRequest Object and handling the response using callbacks
2. Handling the same Ajax request with the help of promises which helps in structuring the code and avoiding callback hell for nested Ajax calls from the same page
3. Understanding the difference between promises and observables
4. Simple example to understand two-way data binding using AngularJS

### Installation

1. Assuming that you already have Node.js installed on system, copy the content of the AsyncDemo folder in any directory
2. From the directory where the filer are copied, issue the below command:<br />
	i. `npm install` - installs the http-server <br/>
	ii. `npm start` - starts the http server <br/>
2. This project uses http-server to host the Ajax application and npm installs the same using the dependency indicated in package.json for http-server. You may also choose to use any other http server of your choice to host the Ajax application
3. The Ajax example uses the JSON file, users.json for validating username which is a simulation of realtime use cases which connect to any db and get a similar response.

### Execution

1. Go to the browser and type the url or click 
[here](http://localhost:8080/index.html) 
The test page ensures that your server is up and running
2. Now access the individual files from the URL to run them:
	* <http://localhost:8080/async_cb.html>
	* <http://localhost:8080/async_promise.html>
	* <http://localhost:8080/observable.html>
