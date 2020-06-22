# RESTful APIs
* **REST** stands for **Representational State Transfer**. 
* It's an architectural style introduced by [_Roy Fielding in 2000](https://www.ics.uci.edu/~fielding/pubs/dissertation/fielding_dissertation.pdf)_.
* REST principles: 
  * __Uniform Interface__: Resources are only accessible as representations and the rules for processing that representation are described through self-descriptive messages.
  * __Stateless__: Every client request to the server is self-contained and subsequent requests do not require information from prior requests.
  * __Client-Server__: A client and server must be present in the architecture.
  * __Cacheable & Layered System__: Caching and other techniques are utilized in order to increase network efficiency.

____________________________________________________________________________________________________________________________

# HTTP basics
* __Hypertext Transfer Protocol (HTTP)__ is a protocol that provides a standardized way for computers to communicate with each other. It has been the foundation for data communication over the internet since 1990 and is integral to understanding how client-server communication functions.

* __Features__:
  * __Connectionless__: When a request is sent, the client opens the connection; once a response is received, the client closes the connection. The client and server only maintain a connection during the response and request. Future responses are made on a new connection.
  * __Stateless__: There is no dependency between successive requests.
  * __Not Sessionless__: Utilizing headers and cookies, sessions can be created to allow each HTTP request to share the same context.
  * __Media Independent__: Any type of data can be sent over HTTP as long as both the client and server know how to handle the data format. In our case, we'll use JSON.
 
* __Elements__:
  * __Universal Resource Identifiers (URIs)__: An example URI is http://www.example.com/tasks/term=homework. It has certain components:
  * __Scheme__: specifies the protocol used to access the resource, HTTP or HTTPS. In our example http.
  * __Host__: specifies the host that holds the resources. In our example www.example.com.
  * __Path__: specifies the specific resource being requested. In our example, /tasks.
  * __Query__: an optional component, the query string provides information the resource can use for some purpose such as a search parameter. In our example, /term=homework.
_______________________________________________________________________________________________________________________
# URLs
* [Endpoint to return an image in a ready to visualize form](https://stackoverflow.com/questions/8637153/how-to-return-images-in-flask-response)
* [Deploying flask application to Heroku and Kubernates using EKS](https://github.com/sukkubm?tab=overview&from=2020-02-01&to=2020-02-29)

# Python achives
* [Backup tarballs for installing conda repositories](https://repo.anaconda.com/pkgs/free/linux-64/)
* Example usage, install flask in a python 2.7 environment
   `conda install https://repo.anaconda.com/pkgs/free/linux-64/flask-0.10-py27_0.tar.bz2`
