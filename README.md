# Tesla API in Tasker
[![](https://img.shields.io/github/v/release/JakobLichterfeld/Tesla_API_in_Tasker)](https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/releases/latest)
[![](https://img.shields.io/badge/Donate-PayPal-informational.svg?logo=paypal)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4GWXFMNWKC7UL&source=url)

Access the Tesla API in Tasker (Android App)

This is a [Tasker](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm) Profile to access the unofficial Tesla API.

The idea was born during discussing a [feature request](https://github.com/adriankumpf/teslamate/issues/156) for [TeslaMate](https://github.com/adriankumpf/teslamate)

## Screenshots
<p align="center"> 
  <img src="screenshots/tasks.png" alt="Tasks" title="Tasks" width="180" height="320" /> <img src="screenshots/scenes.png" alt="Scenes" title="Scenes" width="180" height="320" />
</p>

## Table of contents
- [Security](#security)
- [Features](#features)
- [Screenshots](#screenshots)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [Dontation](#dontation)
- [Disclaimer](#disclaimer)

## Security
Why not using [Tasker Plugin for Tesla](https://play.google.com/store/apps/details?id=com.crazydog.teslatasker)? You never know what a closed source application will do with your credentials :-)

So this Project ist different.
Access token is generated: asked for Tesla account data with Tasker scene, store data only in local variable to get access token from Tesla and than destroy local copy of access data.

Token will be refreshed when exipres in 10 or less days.

## Features
- [x] Token get/refresh (OAuth)
- [x] get vehicles
- [ ] get vehicle
- [x] wake up
- [ ] set sentry mode
- [ ] door unlock
- [ ] door lock
- [ ] actuate trunk
- [ ] honk horn
- [ ] flash lights
- [ ] media toggle playback
- [ ] set media next track
- [ ] set media prev track
- [ ] set media next fav
- [ ] set media prev fav
- [ ] set media volume up
- [ ] set media volume down
- [ ] set navigation request
- [ ] get climate state
- [ ] set temps
- [ ] auto conditioning start
- [ ] auto conditioning stop
- [ ] set remote seat heater request
- [ ] set remote steering wheel heater request
- [ ] get charge state
- [ ] set charge limit
- [ ] set charge limit max range
- [ ] set charge limit standard
- [ ] charge port door open
- [ ] charge port door close
- [ ] charge start
- [ ] charge stop
- [ ] get drive state
- [ ] ~remote start drive~ (will not be included, because current tesla account password is needed)
- [ ] upcoming calendar entries
- [ ] set valet mode
- [ ] reset valet pin
- [ ] speed limit activate
- [ ] speed limit deactivate
- [ ] speed limit set limit
- [ ] speed limit clear pin

Everything not yet included will be when my Tesla is connected to my account and I am able to test the tasks.

## Dependencies
- [Tasker](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm)
- [AutoTools](https://play.google.com/store/apps/details?id=com.joaomgcd.autotools) (can be removed with JavaScriplets to read JSON and removing AutoTools Text action)

## Contributing
All contributions are welcome and greatly appreciated!

## Dontation
Maintaining this project isn't effortless, or free. If you would like to kick in and help me cover those costs, that would be awesome. If you don't, no problem; just share your love and show your support.
<p align="center">
  <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4GWXFMNWKC7UL&source=url">
    <img src="paypal-donate-button.png" alt="Donate with PayPal" />
  </a>
</p>

## Disclaimer
Please note that the use of the Tesla API in general and this software in particular is not endorsed by Tesla. Use at your own risk.
