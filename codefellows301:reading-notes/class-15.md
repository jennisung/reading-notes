# Reading-notes

## Code 301 - Intermediate Software Development: Authentication

## Overview of reading notes

These readings are important as it is crucial to understand the best practices for authentication and the various methods available for authentication.

### What is OAuth?

OAuth is a standard protocol or framework that allows servers to grant a secure access to their resources.

### Give an example of what using OAuth would look like.

An example of using OAuth would be trying to sign-in into replit; you have been given th option to sign in using your Google or GitHub account. By clicking on either the Github or Google button, you are redirected to Google or Github login page, where you have to authenticate. Once you are authenticated and granted permission to log in, you are able to sign-in.

### How does OAuth work? What are the steps that it takes to authenticate the user?

1. User's identity is verified using OAuth, by first connecting the first website to the second.
2. The second website generated a token that can be used one time, as well as a one-time secret unique to the transaction.
3. The first websites provides the token and secret to the user's client software.
4. Client's software presents this to the authorization provider.
5. Additional authentication may take place.
6. User approves the transaction, and gets in turn the approved access token. Then the user givrs the approved access token to the first wbesite. 
7. The first website gives that access token to the second website as authorization proof
8. Second website grants access to the first website.
9. User completed the transaction.

### What is OpenID

OpenID focuses on authentication; instead of authorization.

### What is the difference between authorization and authentication?

Authentication verifies the identity of a user, and authorization granting access rights.

### What is Authorization Code Flow?

The Authorization Code Flow involves the exchange of an authorization code by a client application in order to gain access to protected resources.

### What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

The Authorization Code Flow with Proof Key for Code Exchange (PKCE) is an improved Authorization Code Flow for mobiledevices that provides added security.

### What is Implicit Flow with Form Post?

Primarly intended for public clients, where applications don't need to or unable to store client secrets.

### What is Client Credentials Flow?

Uses machine-to-machine application to authenticate/authorize.

### What is Device Authorization Flow?

Rather than authenticate the user directly, the user is directed to use a computer to mobile device to authorize the device.

### What is Resource Owner Password Flow?

Allows highly-trusted applications to request user credentials, such as username and password directly.

## Things I want to know more about

* Is OAUth authentication less safe, because you're using same login for multiple devices?