# Developer Guide
## Basic Principles
You embed the hCaptcha widget on your site. For example, on a login form. The user answers an hCaptcha. They get a passcode from our server that is embedded in your form. When the user clicks Submit the passcode is sent to your server in the form. Your server then checks that passcode with the hCaptcha server API. hCaptcha says it is valid and credits your account. Your server now knows the user is not a bot and lets them log in. Pretty simple!
