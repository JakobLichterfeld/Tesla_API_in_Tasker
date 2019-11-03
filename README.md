# Tesla API in Tasker

[![latest release](https://img.shields.io/github/v/release/JakobLichterfeld/Tesla_API_in_Tasker)](https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/releases/latest)
[![donation](https://img.shields.io/badge/Donate-PayPal-informational.svg?logo=paypal)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4GWXFMNWKC7UL&source=url)

Access the Tesla API in Tasker (Android App)

This is a [Tasker](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm) Profile to access the unofficial Tesla API.

The idea was born during discussing a [feature request](https://github.com/adriankumpf/teslamate/issues/156) for [TeslaMate](https://github.com/adriankumpf/teslamate)

## Screenshots

<p align="center"> 
  <img src="screenshots/tasks.png" alt="Tasks" title="Tasks" width="180" height="320" /> 
  <img src="screenshots/tasks_2.png" alt="Tasks 2" title="Tasks 2" width="180" height="320" /> 
  <img src="screenshots/tasks_3.png" alt="Tasks 3" title="Tasks 3" width="180" height="320" /> 
  <img src="screenshots/scenes.png" alt="Scenes" title="Scenes" width="180" height="320" />
</p>

## Table of contents

- [Tesla API in Tasker](#tesla-api-in-tasker)
  - [Screenshots](#screenshots)
  - [Table of contents](#table-of-contents)
  - [Security](#security)
  - [Features](#features)
  - [Dependencies](#dependencies)
  - [Installation](#installation)
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
- [x] set sentry mode (true|false default:true)
- [x] door unlock
- [x] door lock
- [x] actuate trunk (rear|front default:rear)
- [x] honk horn
- [x] flash lights
- [x] media toggle playback
- [x] media next track
- [x] media prev track
- [x] media next fav
- [x] media prev fav
- [x] media volume up
- [x] media volume down
- [ ] set navigation request
- [ ] get climate state
- [x] set temps (driver temp, passenger temp default:20.5)
- [x] auto conditioning start
- [x] auto conditioning stop
- [x] set remote seat heater request
- [x] set remote steering wheel heater request
- [ ] get charge state
- [x] set charge limit
- [x] set charge limit max range
- [x] set charge limit standard
- [x] charge port door open
- [x] charge port door close
- [x] charge start (untested)
- [x] charge stop (untested)
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

## Installation

Install [Dependencies](#dependencies). Import [Tesla_API_in_Tasker.prj.xml](https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/blob/master/Tesla_API_in_Tasker.prj.xml) on your Android Phone using Tasker, see [Tasker-FAQs](https://tasker.joaoapps.com/userguide/en/faqs/faq-how.html#q) on how to import xml files.
It is recommended to backup your data first.

## Contributing

All contributions are welcome and greatly appreciated!

## Dontation

Maintaining this project isn't effortless, or free. If you would like to kick in and help me cover those costs, that would be awesome. If you don't, no problem; just share your love and show your support.

<p align="center">
  <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4GWXFMNWKC7UL&source=url">
    <img src="screenshots/paypal-donate-button.png" alt="Donate with PayPal" />
  </a>
</p>

## Disclaimer

Please note that the use of the Tesla API in general and this software in particular is not endorsed by Tesla. Use at your own risk.
