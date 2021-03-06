# Templating

### Reserved Global Constants

- `AM_APP_NAME` : `String`
- `AM_APP_ICON` : `SwiftUI.Image`
- `AM_DEVICE_TYPE` : `String`
- `AM_YEAR_CREATED` : `String`
- `AM_LIVE_APP_SMS_LINK` : `String`
- `AM_SHOW_MAP` : `Bool`
- `AM_LATITUDE` : `Double`
- `AM_LONGITUDE` : `Double`
- `AM_SHOW_TWITTER` : `Bool`
- `AM_TWITTER_LINK` : `String`
- `AM_SHOW_INSTAGRAM` : `Bool`
- `AM_INSTAGRAM_LINK` : `String`
- `AM_SHOW_SOUNDCLOUD` : `Bool`
- `AM_SOUNDCLOUD_LINK` : `String`
- `AM_SHOW_WEBSITE` : `Bool`
- `AM_WEBSITE_LINK` : `String`
- `AM_APP_DESCRIPTION` : `String`

### Templating Files

Save these constants under `_AMTemplater.swift`

Example `_AMTemplater.swift`:

```swift
//
//  _AMTemplater.swift
//  BasicTemplate
//
//  Created by Joseph Hinkle on 1/25/21.
//

import SwiftUI

let AM_APP_NAME = "app name"
let AM_APP_ICON = Image(systemName: "app")
let AM_DEVICE_TYPE = "iPhone"
let AM_YEAR_CREATED = "2021"
let AM_LIVE_APP_SMS_LINK = "sms:&body=https://www.liveapp.cc/"
let AM_SHOW_MAP = true
let AM_LATITUDE = 37.3348
let AM_LONGITUDE = -122.0090
let AM_SHOW_TWITTER = true
let AM_TWITTER_LINK = "https://www.twitter.com/AppMakerIOS"
let AM_SHOW_INSTAGRAM = true
let AM_INSTAGRAM_LINK = "https://www.instagram.com/appmakerios"
let AM_SHOW_SOUNDCLOUD = true
let AM_SOUNDCLOUD_LINK = "https://www.soundcloud.com/"
let AM_SHOW_WEBSITE = true
let AM_WEBSITE_LINK = "https://www.appmakerios.com/"
let AM_APP_DESCRIPTION = "This is a template app."
```