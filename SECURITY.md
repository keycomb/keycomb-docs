Keycomb SECURTY
====

Keycomb is build on top of the open source app [Hound CI](https://houndci.com) by [thoughtbot](http://thoughtbot.com).

Hound has extensively written on its security policy and we recommend you read that first [here](https://github.com/houndci/hound/blob/master/doc/SECURITY.md).

Keycomb differs only in that we do not post violations back to your pull request. Instead, opting for additional privacy by posting a secure link in the commit status for you to view any potential violations.

As stated in the Hound SECURTY doc, "We do not save any of your code in Postgres, or Redis. It only lives in the memory of the Ruby process."

Keycomb is hosted on Heroku.
