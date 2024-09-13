# HyperText Markup Language (HTML)
**HTML** is considered the *structure* of web pages. Using *semantic* HTML is critical to creating an organized, clean, and accessible application. It is the first step in the coding process to creating an efficient applications that delivers clear and concise visuals, as well as delivering the correct information to the backend of our application.

There are 3 main technologies used when delivering information to the backend:
- Uniform Resource Locator (URL)
- HyperText Markup Language (HTML)
- Hypertext Transfer Protocol (HTTP)

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
**https://blog.hubspot.com/marketing**

We're going to break up each piece into their respective roles:
1. **Scheme:** *https*
2. **Sub-domain:** *blog*
3. **Second-level domain:** *hubspot*
4. **Top-level domain:** *com*
5. **Subdirectory:** *marketing*

You'll notice we did not include any foward slashes ( "*//*" or "*/*" ) or dots ( "*.*" )

Foward slashes indicate we are move *down* and into a lower level folder to retrieve a resource. A dot, however, points are a piece of data within that resource.

You'll see this appear in our JavaScript in later lessons.

***So what does this have to do with HTML??***

Remember that we receive information via the internet so that the WWW can populate our webpages with infromation or resources. It is HTML that contains that visual (and sometimes subliminal or *hidden*) information.

The subliminal information is usually not visible to the user, but *it is* visible to your webpage or application, and can be used later to complete requests, follow instructions, or initiate processes.