# Tesla API in Tasker
[![](https://img.shields.io/badge/Donate-PayPal-informational.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4GWXFMNWKC7UL&source=url)

Access the Tesla API in Tasker (Android App)

This is a [Tasker](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm) Profile to access the unofficial Tesla API.

The idea was born during discussing a [feature request](https://github.com/adriankumpf/teslamate/issues/156) for [TeslaMate](https://github.com/adriankumpf/teslamate)

# Security
Why not using [Tasker Plugin for Tesla](https://play.google.com/store/apps/details?id=com.crazydog.teslatasker)? You never know what a closed source application will do with your credentials :-)

So this Project ist different.
Access token is generated: asked for Tesla account data with scene, store data only in local variable to get access token from Tesla and than destroy local copy of access data.

Token will be refreshed when exipres in 10 or less days.

# Features
Up to know the following is included:

- Token get/refresh
- get vehicles
- wakeup

Everything else will be included when my Tesla is connected to my account and I am able to test the tasks.

# Dependencies

- [Tasker](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm)
- [AutoTools](https://play.google.com/store/apps/details?id=com.joaomgcd.autotools) (can be removed with JavaScriplets to read JSON and removing AutoTools Text action)

# Contributing
All contributions are welcome and greatly appreciated!

# Dontation
Maintaining this project isn't effortless, or free. If you would like to kick in and help me cover those costs, that would be awesome. If you don't, no problem; just share your love and show your support.

<p align="center">
  <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4GWXFMNWKC7UL&source=url">
    <img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" alt="Donate with PayPal" />
  </a>
</p>


# Disclaimer
Please note that the use of the Tesla API in general and this software in particular is not endorsed by Tesla. Use at your own risk.
