# Bearer Authorization

## Review, Research, and Discussion

1.
   * Register your application to get a client_id and client_secret.
   * Ask the client if they want to sign in via a third party.
   * Redirect to a third party authentication endpoint.
   * Make a request to the third-party API endpoint.
   * Receive authorization code.
   * Make a request to the access token endpoint.
   * Receive access token.

2. It's a single time use code that the Oauth server sends to the service that ask for the authentication after giving a permission to that service, once that service receives it, it send it back to the server to receive the access token.

3. It's a code that has a limited access to your account information which a service use to access the necessary information from your account.

4. It's more secure and doesn't to ask you for your permission every time demanding for information since it has an access token.

### Terms 

**Client ID:** It's a unique and public identifier across all applications that is sent by the applications that tries to access your information from another service or application that you use.

**Client Secret:** It's a unique and private identifier across all applications that is only known by the application and authorization server.

**Authentication Endpoint:** Endpoint where the user can enter his credentials in order for the authorization server to send the application an authentication code.

**Access Token Endpoint:** Endpoint where the applications send request for the access token.

**API Endpoint:** Endpoint where you can access data from an RESTful service.

**Authentication Code:** One time code that the authorization server send to the application, then the application sends it back with client id and client secret to get the access token code.

**Access Token:** Code that the application sends every time it needs to access data from the authorization server.

<hr>

## Preview

**JWT:** Stands for *Json Web Token*, it's service that's used to securely transfer data between to points, it can be send as an http request, also it uses token so you don't need to give permission every time.

**JWT** consists of three parts; header where encoding algorithm and type of JWT are, payload where client data is, and signature
