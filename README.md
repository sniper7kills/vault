# Vault
Vault is a project with the goal of creating a full OAuth2 package that supports advance use cases that laravel/passport does not support.

This project is currently under active development and will likely be transitioned to a different repository with a different license.

## Features/Goals
1. Ability to correctly identify users even when using multiple models for authentication
2. Support for SaaS applications to provide tenant access to 3rd party services that outlive users
3. Support for browserless and input constrained devices
4. Support all specifications as outlined at [oauth.com](https://www.oauth.com/)


## Parts/Pieces
### Application's
Application's are 3rd party services which look to integrate into your application

### Sudo's
Sudo's are a way to provide 3rd party services access to the application without being assigned to a specific user.

Sudo's can be thought of as "false users"

## Integration into a SaaS
### SaaS Components
- Application's
- Scopes

### Tenant Components
- Sudo's