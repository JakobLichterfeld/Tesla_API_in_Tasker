# Tesla API in Tasker
access the Tesla API in Tasker (Android App)

This is a [Tasker](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm) Profile to access the unofficial Tesla API.

The idea was born during discussing a [feature request](https://github.com/adriankumpf/teslamate/issues/156) for [TeslaMate](https://github.com/adriankumpf/teslamate)

# Security
Why not using [Tasker Plugin for Tesla](https://play.google.com/store/apps/details?id=com.crazydog.teslatasker)? You never know what a closed source application will do with your credentials :-)

Access token is generated: asked for Tesla account data with scene, store data only in local variable to get access token from Tesla and than destroy local copy of access data.

Token will be refreshed when exipres in 10 or less days.

# Features
Up to know the following is included:

- Token get/refresh
- get vehicles
- wakeup

Everything else will be included when my Tesla is connected to my account and I am able to test the tasks.

# Contributing
All contributions are welcome and greatly appreciated!

# Disclaimer
Please note that the use of the Tesla API in general and this software in particular is not endorsed by Tesla. Use at your own risk.
