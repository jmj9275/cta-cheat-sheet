[Table of Contents](../Documentation.md)

# Authentication Flows

## Overview

| Flow     | Use Case    |  Description                                       |
|-------------|---------|-----------------------------------------------|
| SSO - SAML Flow | Internal user login access | Use Salesforce as an IdP or an external IdP to authenticate internal users to the org |
| SSO - OpenId Connect Flow | Internal user login access | Can be used for social sign-on (Google, Facebook etc...) for Experience cloud or for internal users with an external or internal IdP |
| OAuth2.0 - WebServer Flow | Web app integraton | |
| OAuth2.0 - User-Agent Flow | Desktop or mobile app integration | |
| OAuth2.0 - Refresh Token Flow | Renewed Sessions; complementary to web server and user-agent flow | |
| OAuth2.0 - Token Exchange Flow | Single token for all services | |
| OAuth2.0 - For Hybrid Apps | Hybrid apps | |
| OAuth2.0 - JWT Bearer Flow | Server integration | |
| OAuth2.0 - Client Credentials Flow | Server integration | |
| OAuth2.0 - Device Flow | IOT Integration | |
| OAuth2.0 - Asset Token Flow | IOT Integration | |
| OAuth2.0 - Username/Password Flow | browser and server integration | |
| OAuth2.0 - SAML Bearer Assertion | App integration | |
| OAuth2.0 - SAML Assertion Flow | API integration | |