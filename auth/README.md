# Auth Service
A microservice for
- user auth tasks - authentication, authorization

## Structure
- a controller accepting user auth requests
- authentication service(login, logout, token validation)
  - request to the user service for checking whether the current user actually exists in the whole service
- authorization service(token validation)
- a cache DB for checking user states

## Plan 
- implement OAuth2(OpenID connect) from scratch 
