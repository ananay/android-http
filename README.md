# android-http
Java classes for making Android HTTP Requests easier and convenient


# Usage

Sending a GET Request:

````java
HTTPGetRequest request = new HTTPGetRequest();
String response = request.doInBackground("http://httpbin.org/get");
````
---

Sending a POST Request:

````java
HTTPPostRequest request = new HTTPPostRequest();
String response = request.doInBackground("http://httpbin.org/post","param1=value1&param2=value2");
````
