# SUMMARY OAuth 2 

### Roles
#### The Third-Party Application: "Client"
The client is the application that is attempting to get access to the user's account. It needs to get permission from the user before it can do so.

#### The API: "Resource Server"
The resource server is the API server used to access the user's information.

#### The Authorization Server
This is the server that presents the interface where the user approves or denies the request. In smaller implementations, this may be the same server as the API server, but larger scale deployments will often build this as a separate component.

#### The User: "Resource Owner"
The resource owner is the person who is giving access to some portion of their account.

### Authorization
The first step of OAuth 2 is to get authorization from the user. For browser-based or mobile apps, this is usually accomplished by displaying an interface provided by the service to the user.

#### OAuth 2 provides several "grant types" for different use cases. The grant types defined are:

1. Authorization Code for apps running on a web server, browser-based and mobile apps
2. Password for logging in with a username and password (only for first-party apps)
3. Client credentials for application access without a user present
4. Implicit was previously recommended for clients without a secret, but has been superseded by using the Authorization Code grant with PKCE.


![img](https://a.slack-edge.com/fbd3c/img/api/articles/oauth_scopes_tutorial/slack_oauth_flow_diagram.png)
