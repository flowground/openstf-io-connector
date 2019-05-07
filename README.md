# ![LOGO](logo.png) Smartphone Test Farm **flow**ground Connector

## Description

A generated **flow**ground connector for the Smartphone Test Farm API (version 2.3.0).

Generated from: https://api.apis.guru/v2/specs/openstf.io/2.3.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:27+03:00

## API Description

Control and manages real Smartphone devices from browser and restful apis

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Device List

> The devices endpoint return list of all the STF devices including Disconnected and Offline

*Tags:* `devices`

#### Input Parameters
* `fields` - _optional_ - Fields query parameter takes a comma seperated list of fields. Only listed field will be return in response

### Device Information

> The device enpoint return information about a single device

*Tags:* `devices`

#### Input Parameters
* `serial` - _required_ - Device Serial
* `fields` - _optional_ - Fields query parameter takes a comma seperated list of fields. Only listed field will be return in response

### User Profile

> The User Profile endpoint returns information about current authorized user

*Tags:* `user`

### Access Tokens

> The Access Tokens endpoints returns titles of all the valid access tokens

*Tags:* `user`

### User Devices

> The User Devices endpoint returns device list owner by current authorized user

*Tags:* `user`

#### Input Parameters
* `fields` - _optional_ - Fields query parameter takes a comma seperated list of fields. Only listed field will be return in response

### Add a device to a user

> The User Devices endpoint will request stf server for a new device.

*Tags:* `user`

### Delete User Device

> The User Devices endpoint will request for device release from stf server. It will return request accepted if device is being used by current user

*Tags:* `user`

#### Input Parameters
* `serial` - _required_ - Device Serial

### User Device

> The devices enpoint return information about device owned by user

*Tags:* `user`

#### Input Parameters
* `serial` - _required_ - Device Serial
* `fields` - _optional_ - Fields query parameter takes a comma seperated list of fields. Only listed field will be return in response

### Remote Disconnect

> The device connect endpoint will request stf server to disconnect remotely

*Tags:* `user`

#### Input Parameters
* `serial` - _required_ - Device Serial

### Remote Connect

> The device connect endpoint will request stf server to connect remotely

*Tags:* `user`

#### Input Parameters
* `serial` - _required_ - Device Serial

## License

**flow**ground :- Telekom iPaaS / openstf-io-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
