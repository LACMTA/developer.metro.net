+++
type = "itemized"
author = "Douglas Goodwin"
date = "2017-06-22"
title = "Real-time Arrivals"
description = "Real-time vehicle position delivered via a RESTful web service in XML, JSON, and JSONP."
featured = ""
featuredpath = ""
featuredalt = ""
categories = ["real-time"]
linktitle = ""
format = "Many"
link = "#"
+++

## Metro Nextrip API

Metro’s Realtime Application Programming Interface (API) lives at http://api.metro.net/. It gives you access to the positions of Metro vehicles on their routes in real time.

The Realtime API is a RESTful web service designed to serve bus location data gathered by our Advanced Transportation Management System (ATMS) and the new Nextrip prediction engine. This is the result of years of difficult work refining the information we collect from the GPS trackers on every bus. Sometimes that data arrives too late to give us useful information. Our busses serve 1433 square miles. Whenever the buses travel into a radio shadow we need to make a prediction about the location of the bus. This is where Nextrip comes into play.

Our Nextrip service is provided by NextBus, if you are familiar with their XML structure — you are welcome to retrieve the data from them.

Please review NextBus’ XML Documentation

`Agency ID for Metro Bus = lametro`
`Agency ID for Metro Rail = lametro-rail`

You may now easily build and deploy custom applications using Metro’s data as a foundation. If you want to build a mobile application that plots the position of Metro’s Rapid busses on a map then this is the API for you. The interface gives your program access to collections and elements. Collections retrieve lists of element URIs. Element URIs retrieve a representation of the element. Only HTTP GET operations are allowed.

This new section of the site is here to document the interface and give you some examples of how you might use it. We need more examples! Please help us help you by including your code snippets in the comments area.

Try it out and let us know what you think. We hope you enjoy it!

-Metro Developer