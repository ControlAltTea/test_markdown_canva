# HyperText Markup Language (HTML) and in the Client-Server Architecture
**HTML** is considered the *structure* of web pages. It is the first step in the coding process to creating an efficient applications that delivers clear and concise visuals, as well as delivering the correct information to the backend of our application.

There are 3 main technologies used when delivering information to the backend:
1. **Uniform Resource Locator (URL)**
2. **Hypertext Transfer Protocol (HTTP)**
3. **HyperText Markup Language (HTML)**

## URL
URLs are a mechanism for your browser to be able to retrieve any publicly available resource on the web.

A **URL** may consist of ten different parts:
1. Scheme
2. Subdomain
3. Top-level domain
4. Second-level domain
5. Subdirectory
6. Parameter
7. Port
8. Path
9. Query
10. Fragment.

Similar to addresses:
- House number
- Street name
- City
- Unit (?)
- State
- Zipcode

Let's use this URL as an example:
**`https://blog.hubspot.com/marketing`**

We're going to break up each piece into their respective parts:
1. **Scheme:** `https`
2. **Sub-domain:** `blog`
3. **Second-level domain:** `hubspot`
4. **Top-level domain:** `com`
5. **Subdirectory:** `marketing`

You'll notice we did not include any foward slashes ( "`//`" or "`/`" ) or dots ( "`.`" )

Foward slashes indicate we are moving *down* and into a lower level folder to retrieve a resource. A dot, however, points at a piece of data within that resource.

You'll see this appear in our JavaScript in later lessons and it may become clearer then.

***But what does this have to do with HTML??***

Remember that we receive information via the internet so that the WWW can populate our webpages with information and resources. It is the ***HTML*** that brings the visual (and sometimes subliminal or *hidden*) information together onto a webpage.

The subliminal information is usually not visible to the user, but *it is* visible to your webpage or application, and can be used later to complete requests, follow instructions, or initiate processes.

Ideally, the HTML will be structured in a way wherein the information being received can be passed along smoothly or the CSS can style the visual information in a way that is clear and concise to the user.

## HTTP
**HTTP** follows a classical client-server model, with a client opening a connection to make a request, then waiting until it receives a response. 

An **HTTP** request is a request made to the server to retrieve information or resource. The server, upon evaluating if the request is successful or not, will respond with a status code. The status code for a successful request is usually `200`. Any other instance, as in if the request was not successful, can have a range of response codes, such as `404`, `402`, `500`.

**Note:** At some point in the later *backend* lessons, recognizing and understanding status codes will become critical to informing *why* your application is behaving the way it is.

### What is typically included in an HTTP request:
**HTTP Version Type**

    Specifies the version of the HTTP protocol being used, such as `HTTP/1.1` or `HTTP/2`

**URL**

The target address of the resource on the server. For example, `https://example.com/api/data`

**HTTP Method**

The type of action being performed. Common methods include:
- `GET`: Request data from the server
- `POST`: Submit data to the server
- `PUT`: Update an existing resource
- `DELETE`: Remove a resource

**HTTP Request Headers**

Additional metadata sent with the request, such as:
- Host: `example.com`
- User-Agent: Information about the client making the request (e.g., browser type)
- Content-Type: Specifies the data type being sent (e.g., `application/json`)

**HTTP body (optional)**

Contains data sent to the server (only for methods like `POST` or `PUT`). 

For example:
```
{
"name": "John Doe",
"email": "john@example.com"
}
```

**Note :** *It is **not** critical to memorize all of this at the beginning of your learning journey*, however in the grand scheme of things, we are learning about HTML's role on the client-side of the client-server architecture. Eventually, we will circle back to these concepts so that everything covered will have an active part in your fullstack web applications.

## HTML on the Client-Side

Using *semantic* HTML **is** critical to creating an organized, clean, and accessible application.