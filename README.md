# ASP.NET Core delegated access token management

[![.NET](https://github.com/damienbod/token-mgmt-ui-delegated-direct/actions/workflows/dotnet.yml/badge.svg)](https://github.com/damienbod/token-mgmt-ui-delegated-direct/actions/workflows/dotnet.yml)

## Setup

The solution uses a secure downstream API and requires user delegated access tokens for access. The UI application is implemented using ASP.NET Core and razor pages. The UI application authenticates against an OpenID Connect server implemented using OpenIddict. The application client is implemented using an OpenID Connect confidential client and the OpenID Connect code flow with PKCE. This flow returns an access token which is used for the downstream API.

![ASP.NET Core Access Token Management](https://github.com/damienbod/token-mgmt-ui-delegated-direct/blob/main/images/context.png)

## Blogs in this series

- [ASP.NET Core user delegated access token management](https://damienbod.com/2025/01/15/asp-net-core-user-delegated-access-token-management/)
- [ASP.NET Core user application access token management](https://damienbod.com/2025/01/20/asp-net-core-user-application-access-token-management/)
- [ASP.NET Core delegated OAuth Token Exchange access token management](https://damienbod.com/2025/02/10/asp-net-core-delegated-oauth-token-exchange-access-token-management/)
- [ASP.NET Core delegated Microsoft OBO access token management (Entra only)](https://damienbod.com/2025/03/25/asp-net-core-delegated-microsoft-obo-access-token-management-entra-only/)

## History

- 2025-08-01 Updated packages

## Links

[Duende.AccessTokenManagement.OpenIdConnect](https://www.nuget.org/packages/Duende.AccessTokenManagement.OpenIdConnect) 

[Duende token management](https://docs.duendesoftware.com/identityserver/v7/quickstarts/3a_token_management/)

https://learn.microsoft.com/en-us/aspnet/core/security/authentication/social/additional-claims

https://github.com/dotnet/aspnetcore/issues/8175

https://www.epochconverter.com/

## Standards

[JSON Web Token (JWT)](https://datatracker.ietf.org/doc/html/rfc7519)

[Best Current Practice for OAuth 2.0 Security](https://datatracker.ietf.org/doc/rfc9700/)

[The OAuth 2.0 Authorization Framework](https://datatracker.ietf.org/doc/html/rfc6749)

[OAuth 2.0 Demonstrating Proof of Possession DPoP](https://datatracker.ietf.org/doc/html/rfc9449)

[OAuth 2.0 JWT-Secured Authorization Request (JAR) RFC 9101](https://datatracker.ietf.org/doc/rfc9101/)

[OAuth 2.0 Mutual-TLS Client Authentication and Certificate-Bound Access Tokens](https://datatracker.ietf.org/doc/html/rfc8705)

[OpenID Connect 1.0](https://openid.net/specs/openid-connect-core-1_0-final.html)

[Microsoft identity platform and OAuth 2.0 On-Behalf-Of flow](/azure/active-directory/develop/v2-oauth2-on-behalf-of-flow)

[OAuth 2.0 Token Exchange](https://datatracker.ietf.org/doc/html/rfc8693)

[JSON Web Token (JWT) Profile for OAuth 2.0 Access Tokens](https://datatracker.ietf.org/doc/html/rfc9068)

[HTTP Semantics RFC 9110](https://datatracker.ietf.org/doc/html/rfc9110#section-15.5.2)
