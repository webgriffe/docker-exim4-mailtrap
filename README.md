Exim4 Docker container with Mailtrap.io support 
===============================================

[![](https://images.microbadger.com/badges/image/webgriffe/exim4-mailtrap.svg)](https://microbadger.com/images/webgriffe/exim4-mailtrap "Get your own image badge on microbadger.com")

This Docker container is based on the [tianon/exim4](https://hub.docker.com/r/tianon/exim4/) container and only adds support for [Mailtrap.io](http://mailtrap.io) which is great for development purposes.

Usage
-----

Simply set the `MAILTRAP_USER` and `MAILTRAP_PASSWORD` environment variables according to your Mailtrap inbox:

	$ docker run -e MAILTRAP_USER=<user> -e MAILTRAP_PASSWORD=<pass> webgriffe/exim4-mailtrap
	
Credits
-------

[Webgriffe®](http://www.webgriffe.com/)
