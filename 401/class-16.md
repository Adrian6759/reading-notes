# Class 16 Notes

- An AuthenticationManager can do any of the following in its authenticate() method:
- Return an Authentication if it can verify that the input represents a valid principal.
- Throw an AuthenticationException if it believes that the input represents an invalid principal.
- Return null if it cannot decide.
- An AuthenticationProvider has an extra method to allow the caller to query whether it supports a given Authentication type:
- A Provider Manager can delegate to a chain of AuthenticationProviders.
- Access decision managers delegate to access decision voters.
- Filters handle http requests with the client sending a request to an application. The container gets to decide which servlets and filters will be used based off the request.
-
