# Bearer Authorization

### Intro to JWT

A JSON Web Token is JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. We should use Json Web Tokens when we want to securely transmit information between parties as a JSON object and authorization for the user to logged in.
Claims are expected in which structural component of a JWT?
Claims are expected in the payload. Its compact form, JSON Web Tokens consist of three parts separated by dots (.), which are Header, Payload, and Signature.

### Are JWTs Secure?

If you get a JWT and can decode the payload, you can we call that secure by JWTs can be either signed, encrypted or both. If a token is signed, but not encrypted, everyone can read its contents, but when you don't know the private key, you can't change it. Otherwise, the receiver will notice that the signature won't match anymore. If sending a JWT, the sender must and receiver both know the secret key. The secret key is a unique string of random characters that is used to encrypt and decrypt messages. The secret key must be known by both the sender and the receiver in order to encode and decode the message. The concatenated content and secret can be sent and received securely using a JWT. The JWT is like a private key that can unlock a box that is secure contents inside. It will send a message to the receiver that the message is secure and can be opened by the receiver. Then the receiver will use the JWT to open the box and read the message.

### JWTs Explained

We use JWT because its a secure way to send sensitive info between parties. It can be used to verify the integrity of the claims contained within it. Make sure that the sender of the JWT is who it says it is and to ensure that the message wasn't changed along the way.  
JWT is compact and self-contained because it is a string with three parts separated by dots. The three parts are Header, Payload, and Signature. The header contains the type of token and the random letters and numbers being used. The payload contains the claims. The signature is used to verify that the sender of the JWT is who it says it is and to ensure that the message wasn't changed along the way. The signature is created by taking the encoded header, the encoded payload, a secret, the algorithm specified in the header, and signing that.
The three components of a JWT signature are Header, Payload, and Signature.

## Reflection

My goals after reading and reviewing the class README are understanding the following:

- Bearer Tokens
- Virtual fields of the data model
- jsonwebtoken

### Resources I use

JWT[^1], JWT secure[^2] and JSON Web Token[^3].

[^1]: [JWT](https://jwt.io/introduction/)
[^2]: [Stackoverflow](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)
[^3]: [JSON Web Token](youtube.com/watch?v=926mknSW9Lo)
