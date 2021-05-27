# MERN DOCKER COMPOSE APP as multi-container application with volumes to persist the data

### demo app - A cinema’s movies CRUD (Create, Read, Update and Delete) form with React, Node.js, Mongo DB, Express JS, Mongoose, Bootstrap4.

Docker containers enable to bundle up an app along with all of its dependencies into a stand alone package(image) that can be run consistently across a variety of platforms.
 
This is a development configuration where the react app is being served by a separate container.


This is a development configuration where the react app, mongo and express api server are being served by a separate containers. 


* **Mongo DB:** A document-based open-source database.
* **Express:** It’s the server framework, a structured base designed to develop web applications and APIs.
* **React JS:** A Javascript Front-end library for building user interfaces.
* **Node JS:** A javascript runtime built on Chrome’s V8 JS engine.
* **Cors:** Package for providing a Connect/Express middleware that can be used to enable CORS with various options.
* **Mongoose:** It’s an elegant MongoDB object modeling for node.js.
* **Axios:** It’s a promise-based the asynchronous code. It’s the most popular promise based HTTP.
* **Bootstrap:** It’s is an open-source toolkit and the most popular front-end component library where allows you for developing with HTML, CSS, and JS.
* **StyledComponents:** It allows you to write actual CSS code to style your components.
* **React Table:** It’s a lightweight, fast, and extendable data grid built for React.


---

* Run `docker-compose up` from root to start.

* Open http://localhost:3000 to view it in the browser.

* Run `docker-compose down` from root to stop.

**Or**

* Run `make build` from root to build containers.

* Run `make run` from root to run containers with.

---
Based on and modified: 

* https://github.com/sidpalas/devops-directive/tree/master/2020-08-31-docker-compose
* https://github.com/samaronybarros/movies-app