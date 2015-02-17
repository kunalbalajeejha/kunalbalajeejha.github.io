---
layout: post
title:  "Apple Script to Update Address Book"
date:   2011-12-19 13:00:37
categories: applescript programming
---

I have recently travelled from Singapore to Chennai. And all my contact numbers are having the number "019" added infront of them. This was done, so as to get the cheaper rates when calling to India. Now that I am back in India, I was faced with the task of manually (either on Mac or iPhone) replacing all the number "019" with "+" sign in my contacts.
Then I remembered about *AppleScript* and how I can easily do this with a little bit of programming.
The result is the below peice of code. In this process I also re-discovered the [Mac OSX Automation](http://www.macosxautomation.com) website, which has the sub-routine for [text search and replace](http://www.macosxautomation.com/applescript/sbrt/sbrt-06.html).

{% gist kunalbalajeejha/9601c290b9c2b4a4a89f %}