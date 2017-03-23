# wicked.auth-adfs

ADFS Authorization Server for wicked.haufe.io

**Note**: Work in progress. Will be published here as soon as it has reached a state where publishing makes sense.

# THIS PROJECT HAS MOVED

The already existing [wicked.auth-passport](https://github.com/Haufe-Lexware/wicked.auth-passport) project will also support ADFS in the future.

## Features

These are the features I am currently aiming for:

* Authentication via ADFS
* Mapping of ADFS Groups to Scopes
* Support for Implicit Grant Flow
* Support for Authorization Code Grant Flow

Explicitly NOT in Scope:

* Resource Owner Password Grant Flow
* Client Credentials Grant Flow (does not make sense here)
