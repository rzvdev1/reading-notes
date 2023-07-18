# Authentication

## Securing Passwords

Explain to a non-technical friend how you would safely hash and store a password.
To a non-technical friend you would safely hash and store a password by using a algorithms that is a hash function. The hash function is a set of data of random numbers & letters and not the actual plain text passwords. A Bcrypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be. You might you use something like Bcrypt because it overcome such issues, we need algorithms which can make the brute force attacks slower and minimize the impact.

## Basic Auth

Basic Authentication is a process where the system authenticates the user credentials against a known database of users.

The properties are necessary in the header of a Basic Auth request is Authorization: Basic < credentials >. The username:password credentials is the Base64 encoding of ID and password joined by a single colon :.

## OWASP auth cheatsheet

The authentication process where a system authenticates the user credentials to login into a website like your email. The system will then either grant or deny access to the requested resource based on the credentials validated to make sure it is you. Then after it veryfies your credentials it will grant you access to the your email. Your error messaging respond (both HTTP and HTML) should be a 401 Unauthorized response status code. The 401 Unauthorized error means the page you were trying to access cannot be loaded until you first log in with a valid user ID and password.

## Reflection

My goals after reading and reviewing the class README are understanding the following:

- learning about the authentication process
- learn about basic auth devops
- use a secure hashing algorithm

### Resources I use

Securing Passwords with Bcrypt Hashing Function[^1], Basic access authentication[^2] and Authentication cheatsheet[^3].

[^1]: [Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)
[^2]: [Authentication](https://en.wikipedia.org/wiki/Basic_access_authentication)
[^3]: [OWAS](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)
