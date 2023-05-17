# APIs

## RESTful web API design

From[RESTful web API design](https://canvas.instructure.com/courses/6694774/discussion_topics/17993159)

- What does REST stand for?

Representational State Transfer

- REST APIs are designed around a ____.

Resource

- What is an identifier of a resource? Give an example.

Its a URI that uniquely identifies that resource. In our lab its /cityName at the end of the API URL

- What are the most common HTTP verbs?

GET
POST
PUT
PATCH
DELETE

- What should the URIs be based on?

Based on where they are getting the data from.

- Give an example of a good URI.

let cityUrl = `https://us1.locationiq.com/v1/search?key=YOUR_LOCATIONIQ_API_KEY&q=${this.state.cityName}&format=json`;

- What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

Chatty APIs expose a large number of small resources requ

- What status code does a successful GET request return?

200


- What status code does an unsuccessful GET request return?

204

- What status code does a successful POST request return?

201

- What status code does a successful DELETE request return?

200

## Bookmarks

[RegExr was created by gskinner.com.](https://regexr.com/)

[Regex tutorial — A quick cheatsheet by examples](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)

[egex101: build, test, and debug regex](https://regex101.com/)
