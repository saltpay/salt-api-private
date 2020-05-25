---
tags: [terminal, security]
---

# Terminal Introduction

The terminal is a Android powered device using Handpoint SDK that enables processing of card present transaction in store. API's have been created that allow for transaction to be initiated from a POS and capture transactional information directly from the Terminal

## Security
The terminal interacts with the Handpoint SDK via a configuration file that is loaded on bootup. API access is controlled via JWT. To retrieve a JWT the terminal is linked to a merhcants' Salt account. The process uses device authentication following OAuth2 processes.


On bootup after configuring with Handpoint, the terminal will confirm if a JWT is available. If available, the token is validated to not be expired, if it is the refresh token is used to request a new JWT. Should the refresh token be expired, the terminal will need to follow the OAuth2 device login process.

It will display a button that will allow the user to retrieve a link code. The user will then login into the Salt portal, thereafter they will choose to register a device with their account. They will promted for the device link code which if found to be valid will link the device to their account and send a JWT to the device.
