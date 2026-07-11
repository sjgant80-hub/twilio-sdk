# @ai-native-solutions/twilio-sdk

Sovereign wrapper for **Twilio** · Comms

**100 endpoints** wrapped from OpenAPI spec.

## Install
```bash
npm install @ai-native-solutions/twilio-sdk
```

## Use
```js
import Twilio from '@ai-native-solutions/twilio-sdk';
const client = new Twilio({ apiKey: process.env.TWILIO_KEY });
```

## Endpoints (100)
- `GET /2010-04-01/Accounts.json` · Retrieves a collection of Accounts belonging to the account used to make the request
- `POST /2010-04-01/Accounts.json` · Create a new Twilio Subaccount from the account making the request
- `GET /2010-04-01/Accounts/{Sid}.json` · Fetch the account specified by the provided Account Sid
- `POST /2010-04-01/Accounts/{Sid}.json` · Modify the properties of a given Account
- `GET /2010-04-01/Accounts/{AccountSid}/Addresses.json` · 
- `POST /2010-04-01/Accounts/{AccountSid}/Addresses.json` · 
- `GET /2010-04-01/Accounts/{AccountSid}/Addresses/{Sid}.json` · 
- `POST /2010-04-01/Accounts/{AccountSid}/Addresses/{Sid}.json` · 
- `DELETE /2010-04-01/Accounts/{AccountSid}/Addresses/{Sid}.json` · 
- `GET /2010-04-01/Accounts/{AccountSid}/Applications.json` · Retrieve a list of applications representing an application within the requesting account
- `POST /2010-04-01/Accounts/{AccountSid}/Applications.json` · Create a new application within your account
- `GET /2010-04-01/Accounts/{AccountSid}/Applications/{Sid}.json` · Fetch the application specified by the provided sid
- `POST /2010-04-01/Accounts/{AccountSid}/Applications/{Sid}.json` · Updates the application's properties
- `DELETE /2010-04-01/Accounts/{AccountSid}/Applications/{Sid}.json` · Delete the application by the specified application sid
- `GET /2010-04-01/Accounts/{AccountSid}/AuthorizedConnectApps/{ConnectAppSid}.json` · Fetch an instance of an authorized-connect-app
- `GET /2010-04-01/Accounts/{AccountSid}/AuthorizedConnectApps.json` · Retrieve a list of authorized-connect-apps belonging to the account used to make the request
- `GET /2010-04-01/Accounts/{AccountSid}/AvailablePhoneNumbers.json` · 
- `GET /2010-04-01/Accounts/{AccountSid}/AvailablePhoneNumbers/{CountryCode}.json` · 
- `GET /2010-04-01/Accounts/{AccountSid}/AvailablePhoneNumbers/{CountryCode}/Local.json` · 
- `GET /2010-04-01/Accounts/{AccountSid}/AvailablePhoneNumbers/{CountryCode}/MachineToMachine.json` · 
_...and 80 more_

## License
MIT · Copyright 2026 AI-Native Solutions

## Upstream
- Docs: https://www.twilio.com/docs/api
- Homepage: https://twilio.com
