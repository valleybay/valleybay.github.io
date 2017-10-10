---
layout: post
title: How am I doing
date: 2017-10-10 23:15:00 +0100
---
Ok. So I am getting a bit tired. I actually was making some good progress, until Dropbox halted me
with some sort of service disruption. I've been doing some testing on an EC2 instance on AWS, where
I'll be hosting the dropbox service integration server.  
I've got basic functionality working, but there's a lot of code to be written. No chance that it'll
be done today. Apparently Dropbox will be hitting the notification endpoint every single time a file
is changed / added, and that can happen multiple times when I'm editing the file. That means that it
won't be enough to just generate some file and commit that to GitHub. I'll have to set some upper
limit on how often this actually can happen... Probably won't be too big of a deal, but it still adds
some complexity. Oh well. I'll soldier on. (I'm soon going to bed). (I think).
