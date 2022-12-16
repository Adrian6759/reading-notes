# Class 15 Notes

## What is OAuth

1. What is OAuth?
According to the CSO Online article, it is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.

2. Give an example of what using OAuth would look like.
An example of OAuth woild probably be something like the ID.me site where you other websites ask you to verify who you are through the ID.me site. The site redirects you and once you enter your credentials for ID.me, you get taken back to the original site. 

3. How does OAuth work? What are the steps that it takes to authenticate the user?
OAuth only gives temporary authorization after a user has entered their credentials.
According to the CSO online article, these are the steps:

- The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
- The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
- The first site gives this token and secret to the initiating user’s client software.
- The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
- If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
- The user approves (or their software silently approves) a particular transaction type at the first website.
- The user is given an approved access token (notice it’s no longer a request token).
- The user gives the approved access token to the first website.
- The first website gives the access token to the second website as proof of authentication on behalf of the user.
- The second website lets the first website access their site on behalf of the user.
- The user sees a successfully completed transaction occurring.

4. What is OpenID?
Open ID is like OAuth but in this case, humans are logging into machines.

## Authorization and Authentication flows

1. What is the difference between authorization and authentication?
Authorization is long term whereas authentication is only for a short period of time. Authorization grants you more access.

2. What is Authorization Code Flow?
This is an instance where an auhtorization code is exchange for a token.

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
The Proof key takes authorization code flow a step further by requiring the authorization server to do additional authentication.

4. What is Implicit Flow with Form Post?
Only an ID token is required in this case and this is used for situations in which there are public clients.

5. What is Client Credentials Flow?
This focused on authorizing an app instead of a user.

6. What is Device Authorization Flow?
This is when a link is sent to a user in order to authenticate.

7. What is Resource Owner Password Flow?
This allows a user to enter a username and password in order to be authenticated.
