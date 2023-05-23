# Hello

This topic matters because understanding the process of CRUD as a full stack developer is a skill need to know. You will be running database for compines and they always add, delete or edit new user/items for their website.

In my owns words the following status code are:

- 100’s = information about the requesting
- 200’s = the url is working
- 300’s = the information you are seeking is no longer there and request somewhere else
- 400’s = wrong url input page does not exist
- 500’s = the server is down not working at the moment

The status code 202 is a newly created resource. The status code 308 tells the client to use another URL to access the resource and not use the current URL anymore. The code you can use if an update didn’t return data to a client is 204 No Content. The code you can use if a resource used to exist but no longer does is 410 Gone. The Forbidden status code is The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

We need to pull the MongoDB database string out of our server and put it into our .env because to store your credentials and not be compromised. The app.use(express.json()) does an parses incoming JSON requests and puts the parsed data in req.body. The /:id mean in a route is the path that gets you to this function. PUT means replace the entire resource with given data (so null out fields if they are not provided in the request), while PATCH means replace only specified fields. To make a default value in a schema is:

          category: {
                        type: String,
                        default: ''
                    }

The 500 error status code mean the server encounted a problem due to request incorrectly. The the difference between a status 200 and a status 201 is the status 201 is created and 200 is connected.

## Things I want to know more about

1. Learn about status code 303 See Other
2. How will you connect an external database to an IDE?

### Resources I use

Status codes[^1] and REST API[^note]

[^1]: [HTTP](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)
[^note]: [YouTube](https://www.youtube.com/watch?v=fgTGADljAeg)
