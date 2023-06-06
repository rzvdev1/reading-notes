# Hello

This topic matters because in any web application there is a Authentication require. In a real world application you will have the admin logins that will be seperate from a client side. You do not want a un-Authentication user to login as a admin this is a big security risk. As a developer you need to learn how this works and make sure code works.

The 0Auth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. An example of using 0Auth is a CEO signing in to their work email and making sure its not someone else trying to login in.

The steps for 0Auth is the following :

- The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
- The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
- If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
- The user approves (or their software silently approves) a particular transaction type at the first website.
- The user is given an approved access token (notice it’s no longer a request token).
- The user gives the approved access token to the first website.
- The first website gives the access token to the second website as proof of authentication on behalf of the user.
- The second website lets the first website access their site on behalf of the user.
- The user sees a successfully completed transaction occurring.
- OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).

The OpenID about authentication: as a commenter on StackOverflow pithily put it: "OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans.".

The between authorization and authentication is Authentication verifies the identity of a user or service, and authorization determines their access rights. The Authorization Code Flow is confidential applications (such as Regular Web Applications) because the application's authentication methods are included in the exchange and must be kept secure. The Authorization Code Flow with Proof Key for Code Exchange is they require additional security by Your Auth0 Authorization Server verifies the code_challenge and code_verifier. The Implicit Flow with Form Post is The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls. With this method, you don’t need to obtain, maintain, use, and protect a secret in your application. The Client Credentials Flow is Auth0 Authorization Server validates application's credentials and Auth0 Authorization Server responds with an access token. The Device Authorization Flow is device app requests authorization from the Auth0 Authorization Server using its Client ID (/oauth/device/code endpoint), asks the user to activate using their computer or smartphone, and begins polling your Auth0 Authorization Server for an Access Token.

The is Resource Owner Password Flow is which requests that users provide credentials (username and password), typically using an interactive form. Because credentials are sent to the backend and can be stored for future use before being exchanged for an Access Token, it is imperative that the application is absolutely trusted with this information.

## Things I want to know more about

1. Making your hash keys.
2. Is Authentication and Authorization have the same flow to access a server?

### Resources I use

Authorization framework[^1] and Authentication and Authorization Flows[^note]

[^1]: [Authorization](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)
[^note]: [Flows](https://auth0.com/docs/get-started/authentication-and-authorization-flow)
