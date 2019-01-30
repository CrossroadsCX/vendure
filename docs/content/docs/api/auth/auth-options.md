---
title: "AuthOptions"
weight: 10
generated: true
---
<!-- This file was generated from the Vendure TypeScript source. Do not modify. Instead, re-run "generate-docs" -->


# AuthOptions

The AuthOptions define how authentication is managed.

### disableAuth

{{< member-info type="boolean" default="true" >}}

Disable authentication & permissions checks.

### tokenMethod

{{< member-info type="'cookie' | 'bearer'" default="'cookie'" >}}

Sets the method by which the session token is delivered and read.

### sessionSecret

{{< member-info type="string" default="'session-secret'" >}}

The secret used for signing the session cookies for authenticated users. Only applies when

### authTokenHeaderKey

{{< member-info type="string" default="'vendure-auth-token'" >}}

Sets the header property which will be used to send the auth token when using the 'bearer' method.

### sessionDuration

{{< member-info type="string | number" default="'7d'" >}}

Session duration, i.e. the time which must elapse from the last authenticted request

### requireVerification

{{< member-info type="boolean" >}}

Determines whether new User accounts require verification of their email address.

### verificationTokenDuration

{{< member-info type="string | number" default="'7d'" >}}

Sets the length of time that a verification token is valid for, after which the verification token must be refreshed.
