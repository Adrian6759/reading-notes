# Class 8 Notes

## API Design Best Practices

1. What does REST stand for?
Representational State Transfer

2. REST APIs are designed around resources.

3. What is an identifier of a resource? Give an example.
An identifier is a unique way to differentiate it, an example would be an URn or URL.

4. What are the most common HTTP verbs?
The most common are GET, PUT, POST, PATCH, AND DELETE

5. What should the URIs be based on?
They should be based on a unique identifier.

6. Give an example of a good URI.
https://adrians-web.com/about

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
It's an API that has a large load of requests. It is best to have one that isn't chappty.

8. What status code does a successful GET request return?
retrieves a representation of the resource at the specified URI. The body of the response message contains the details of the requested resource.

9. What status code does an unsuccessful GET request return?
retrieves a representation of the resource at the specified URI. The body of the response message contains the details of the requested resource.

10. What status code does a successful POST request return?
either creates or replaces the resource at the specified URI. The body of the request message specifies the resource to be created or updated.

11. What status code does a successful DELETE request return?
removes the resource at the specified URI.

information from questions 8-11 was from https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design
