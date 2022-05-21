---
title: Get started with Email API
description: How to get started with Email API
---

# Get started with Email API

The Email API 

- Basic Authentication
- Sending your first email
- Sending an email with multiple recipients
- Sending your first template
- Sending a template 


HTTP Basic Authentication

Credentials to access this API are managed by the Provisioning API; refer to the “Create Application Credentials” section of this document for instruction. 

Only Application Credentials of type “password” can be used to authenticate with the Mail API.


Examples of using this authentication with cURL:

```
curl -u APP123456:A_Very_Strong_Password \
    <rest of command>

curl -H 'Authorization: Basic QVBQMTIzNDU2OkFfVmVyeV9TdHJvbmdfUGFzc3dvcmQ=' \
    <rest of command>
```





API endpoint:
[Links](https://mail-api.ser.emailrouter-development.com/)

API documentation:
[Links](https://mail-api-docs.ser.emailrouter-development.com/)

OpenAPI specification:
[Links](https://mail-api-docs.ser.emailrouter-development.com/spec.json)
