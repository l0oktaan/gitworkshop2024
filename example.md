
![The San Juan Mountains are beautiful!](https://www.keycloak.org/resources/images/logo.svg "San Juan Mountains")
# Keycloak Concepts
## Authentication
- Identifying & validating a user
## Authorization
- Granting access to a resource to a user
## Clients
- Entities that can request authentication for a user
Often is an application acting on behalf of a user but still needs to authenticate itself to a downstream service
## Session
- Created upon login
- Contains information about the user
  - When logged in, which applications participated in the authentication, etc
- Admins & users can view session information