# GoRestAPI
My first attempt to create a Rest API in GO.


## Structure

In the `main.go` file, I define the functions needed to handle my service.
The `homePage` will manage all the root URL requests. A `handleRequest` function that will match the URL path hit with a defined function. Finally a `main` function which will execute all.

### Article Structure

The REST API that allows us to `CREATE`, `READ`, `UPDATE` and `DELETE` the articles on our website. When we talk about `CRUD` APIs we are referring to an API that can handle all of these tasks: _Creating, Reading, Updating_ and _Deleting_.

In order to define our Article structure, we make use of the Go `struct`, perfect to encode such object.
