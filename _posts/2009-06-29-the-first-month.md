---
title: The First Month
author: bill
layout: post
permalink: /2009/06/the-first-month/
categories:
  - Projects
tags:
  - Berkman Center
  - EFF
  - TermsWatch
---
<!-- 		@page { margin: 0.79in } 		P { margin-bottom: 0.08in } 		A:link { so-language: zxx } 	-->

<p style="margin-bottom: 0in;">
  It's the end of June, which means it is the end of my first month of working on TermsWatch. So what has happened in this first month?
</p>

<h3 style="margin-bottom: 0in;">
  <span style="color: #000000;">Enter the EFF</span>
</h3>

<p style="margin-bottom: 0in;">
  The first few days of the month were spent settling in at Berkman and getting my new(ish) laptop ready for work. By Thursday I was ready to get down to business. Well, it just so happened that Thursday was launch day for the <a href="http://www.eff.org" target="_blank">EFF</a>'s latest project, <a href="http://www.tosback.org" target="_blank">TOSBack</a>. I spent Thursday afternoon playing around with TOSBack and finding out as much as I could about it. I then spent the next few days running around like a chicken with its head cut off; TOSBack does half of what I was going to do. I thought to myself, "well what do I do now?"
</p>

<p style="margin-bottom: 0in;">
  Fortunately there are cooler heads than I at Berkman, and they decided it was best to give the EFF a call. We had a few phone calls with <a href="http://www.eff.org/about/staff/tim" target="_blank">Tim Jones</a>, Activism & Technology Manager at the EFF and the man behind TOSBack. Turns out Berkman and the EFF have a lot of similar hopes and dreams regarding a service such as TOSBack. It also turns out that Tim was about to go on vacation for the summer, so nobody was going to be working on the project for a couple of months. All in all, this turned out to be a great opportunity for everybody involved and it was agreed that I would spend the summer working on the TOSBack code.
</p>

<h3 style="margin-bottom: 0in;">
  <span style="color: #000000;">Symfony & Text Extraction</span>
</h3>

<p style="margin-bottom: 0in;">
  With the TOSBack code in hand I went to work. The first order of business was to port TOSBack over to <a href="http://www.symfony-project.org/" target="_blank">Symfony</a>, a web application framework. A framework such as Symfony has several advantages, including taking care of some tedious aspects of creating an application, such as checking input for security issues and generating administration pages. All in all this was a fairly painless process.
</p>

<p style="margin-bottom: 0in;">
  The latest, and current, problem that I have been tackling is how to extract the important information from a web page. Fortunately, as is becoming a common occurrence this summer, it turns out there are quite a few bright people in our small area who have done work like this, and they are all easy to talk to. I've spent nearly a week talking to these bright people, gaining insight into various approaches and understanding exactly what it is I need to do. I have a pretty good idea what it is I am going to do now (for those interested in the technical stuff, check out this <a href="https://adam.law.harvard.edu/trac/termswatch/wiki/Scraper" target="_blank">summary of the extractor</a>,) and with a new week on the horizon, I hope to get this thing working quickly.
</p>