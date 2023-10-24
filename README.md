# Getting Started

Store your Twilio credentials in the .env file:
1. In your Twilio console click on 'Settings' and take note of your Account SID.
2. Navigate to Settings/API Keys to generate a new Key SID and Secret

```.env
TWILIO_ACCOUNT_SID=ACxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
TWILIO_API_KEY_SID=SKxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
TWILIO_API_KEY_SECRET=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

optional if need to use conversation service
TWILIO_CONVERSATIONS_SERVICE_SID=IS00000000000000000000000000000000

REACT_APP_URI={your web url}
```

## Available Scripts

### `npm start`

Runs the app in the development mode.\
Service will run in [http://localhost:4000](http://localhost:4000).\
