# webchannel-wrapper

This is a wrapper of some Webchannel Features.

## Installation

You can install this wrapper by running the following in your project:

```bash
$ npm install webchannel-wrapper
```

## Usage

The following 5 modules are exposed for use:

- `createWebChannelTransport`
- `ErrorCode`
- `EventType`
- `WebChannel`
- `XhrIoPool`

You can include these by doing the following:

**ES Modules**

```javascript
import { WebChannel } from '@firebase/webchannel-wrapper'

// Do stuff with WebChannel
```

**CommonJS Modules**

```javascript
const webchannelWrapper = require('@firebase/webchannel-wrapper');

// Do stuff with webchannelWrapper.ErrorCode, webchannelWrapper.EventType, etc 
```
