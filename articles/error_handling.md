---
title: "Error Handling and Recovery with Hot Bunnies"
layout: article
---

## About this guide

Development of a robust application, be it message publisher or
message consumer, involves dealing with multiple kinds of failures:
protocol exceptions, network failures, broker failures and so
on. Correct error handling and recovery is not easy. This guide
explains how the amqp gem helps you in dealing with issues like

 * Initial connection failures
 * Network connection failures
 * AMQP 0.9.1 connection-level exceptions
 * AMQP 0.9.1 channel-level exceptions
 * Broker failure
 * TLS (SSL) related issues

This work is licensed under a <a rel="license"
href="http://creativecommons.org/licenses/by/3.0/">Creative Commons
Attribution 3.0 Unported License</a> (including images and
stylesheets). The source is available [on
Github](https://github.com/ruby-amqp/rubymarchhare.info).


## What version of Hot Bunnies does this guide cover??

This guide covers Hot Bunnies 2.0.


TBD



## What to Read Next

The documentation is organized as [a number of
guides](/articles/guides.html), covering various topics.

We recommend that you read the following guides first, if possible, in this order:

 * [Troubleshooting](/articles/troubleshooting.html)
 * [Using TLS (SSL) Connections](/articles/tls.html)


## Tell Us What You Think!

Please take a moment to tell us what you think about this guide [on Twitter](http://twitter.com/rubyamqp) or the [Hot Bunnies mailing list](https://groups.google.com/forum/#!forum/ruby-amqp)

Let us know what was unclear or what has not been covered. Maybe you
do not like the guide style or grammar or discover spelling
mistakes. Reader feedback is key to making the documentation better.
