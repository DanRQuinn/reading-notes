# Authentication

## What is OAuth? How the open authorization framework works

From[What is OAuth? How the open authorization framework works](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

- What is OAuth?

OAuth is an open standard that allows users to grant websites or applications access to their information without giving them their passwords.

- Give an example of what using OAuth would look like.

An example of using OAuth is signing in to a new app with your Google account.

- How does OAuth work? What are the steps that it takes to authenticate the user?

OAuth works by using a process called authorization code grant.

- What is OpenID?

OpenID is an open standard for authentication that allows users to sign in to websites and apps using a single identity.

## Authentication and Authorization Flows

From[Authentication and Authorization Flows](https://auth0.com/docs/get-started/authentication-and-authorization-flow)

- What is the difference between authorization and authentication?

Authorization is the process of determining whether a user is allowed to access a resource. Authentication is the process of verifying the identity of a user.

- What is Authorization Code Flow?

Authorization Code Flow is an OAuth 2.0 flow that allows a client to obtain an authorization code from an authorization server. The authorization code can then be exchanged for an access token.

- What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

Authorization Code Flow with Proof Key for Code Exchange (PKCE) is an extension of Authorization Code Flow that adds an extra layer of security by generating a random code verifier that is used to prevent code injection attacks.

- What is Implicit Flow with Form Post?

Implicit Flow with Form Post is an OAuth 2.0 flow that allows a client to obtain an access token directly from an authorization server without the need for a user to be redirected to the client's website.

- What is Client Credentials Flow?

Client Credentials Flow is an OAuth 2.0 flow that allows a client to obtain an access token without the need for user authorization.

- What is Device Authorization Flow?

Device Authorization Flow is an OAuth 2.0 flow that is designed for devices that do not have a web browser.

- What is Resource Owner Password Flow?

Resource Owner Password Flow is an OAuth 2.0 flow that allows a client to obtain an access token by using the user's username and password.

## Bookmarks

[Auth0 React SDK for Single Page Apps](https://auth0.com/docs/libraries/auth0-react)
