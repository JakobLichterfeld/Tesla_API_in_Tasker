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

# Dontation
Maintaining this project isn't effortless, or free. If you would like to kick in and help me cover those costs, that would be awesome. If you don't, no problem; just share your love and show your support.

<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick" />
<input type="hidden" name="hosted_button_id" value="4GWXFMNWKC7UL" />
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" />
<img alt="" border="0" src="https://www.paypal.com/en_DE/i/scr/pixel.gif" width="1" height="1" />
</form>

# Disclaimer
Please note that the use of the Tesla API in general and this software in particular is not endorsed by Tesla. Use at your own risk.
