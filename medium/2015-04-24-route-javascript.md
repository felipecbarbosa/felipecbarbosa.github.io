---
layout: page	
title: Route Setup - JavaScript
author: Felipe Barbosa
permalink: /medium/route-setup-javascript/
categories: medium
canonical: https://felipecbarbosa.medium.com/route-setup-javascript-90fe2faab574
---

*Esse texto foi publicado pela primeira vez no dia 24/04/2015 no Medium*

> Learn how to integrate Route to your website using JavaScript.

The first thing you need to understand about Route is that the main goal is to **track user behaviors through events and send automated messages based on them**.

> Is all about people (who) behavior (what) in your website or app.

As any tracking software (e.g. Google Analytics), Route has a main script that must be put in every page of your website or app in order to make all of the tracking scripts you create work.

## Route Main Script

The script below is required to be pasted on your website because it’s the only way Route will be able to recognize and trigger all the events you create and identifying all the people that fill in your forms.

This script we call it **MAGIC** because after pasting it on your website you just need to check enable to automatically integrate the forms on your website to Route and to create events for those forms.

No extra coding required. If you don’t want Route’s script to do its magic, just leave it disabled and integrate the forms and create the events by hand.

<script src="https://gist.github.com/RouteTeam/73e80791b070548b4667.js"></script>

Remember to replace the '''YOUR_ORGANIZATION_ID''' with your organization ID available under settings > organization.

You should put this code right above the '''</head>''' of your HTML so it’s rendered before all the other Route scripts you’ll put on your website’s HTML.

## Tracking events with Route

Having only the main script on your website won’t give you information about your user’s behaviors, you need something else.

What you need is to track their behavior with the following event tracking script:

<script src="https://gist.github.com/RouteTeam/47856973aecff25362a5.js"></script>

With the code above you’ll track what people are doing on your website or app. You can use it as follow:

1. Using the onClick method on a button or link;
2. Right inside the <body> tag (this will work as a pageview);
3. Using the onSubmit method on a form.

The event tracking script is only one part of the equation, capturing what people are doing in your website or app.

Route will store this information but willonly show you who is doing what if you get names and emails of your contacts and identify them within our software.

To identify people you need to use our “identify” method.

## Identifying people with Route

Use the following code to identify people using Route:

<script src="https://gist.github.com/RouteTeam/d784148db3651a04106b.js"></script>

You’ll need to replace the “var contact” name and email we used in our sample code for a rule to instruct Route to collect this information from the forms you have in your website, just like the example bellow:

<script src="https://gist.github.com/RouteTeam/606e2f0aeb0b188a25c3.js"></script>

You can also get this information by rendering it from your server-side, specially if you are using Route on an app.

## Need more help with our JavaScript setup?

If you have any doubt about how to start using Route scripts just contact us.