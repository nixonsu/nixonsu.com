---
title: "📣 cheep-honk"
description: "As fuel prices blast off, this creation ensures my wallet doesn't burn to a crisp"
date: "Sep 14 2024"
repoURL: "https://github.com/nixonsu/cheep-honk"
---

![cheep-honk](/cheep-honk.webp)
_Cheapest fuel stations near me for the day_

We're all familiar with how crap the fuel prices have been these past couple of years. I often found myself using something like [Petrol Spy](https://petrolspy.com.au/) to determine the fuel station with the lowest price whenever I needed to top up gas.

I figured, instead of having this "pull" relationship between myself and this information, why not just have this information "pushed" to me as a notification instead? This CRON job does exactly that. It retrieves the fuel prices from Petrol Spy, enriches it with useful time and distance data using Google APIs and sends it to my phone via Telegram.

I also wanted to play around with [Telegram's Bot API](https://core.telegram.org/bots/api). It's definitely a great free alternative for sending notifications to a user's phone (provided they have the app). Originally, I wanted to explore using an SMS option, but services that offer this, like [Twilio](https://www.twilio.com/en-us) and [AWS SNS](https://aws.amazon.com/sns/), are paid after some usage. Using a free option simplifies things greatly for me.

<a href="https://github.com/nixonsu/cheep-honk" target="_blank">Read more about it</a>
