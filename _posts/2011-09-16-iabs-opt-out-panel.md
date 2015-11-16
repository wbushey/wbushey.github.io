---
title: IAB's Opt-Out Panel
author: bill
excerpt: |
  While the new code of conduct has taken flack for not actually providing
  clear notice, this latest action by the IAB does bring some attention to the
  organization's (beta) Opt-Out page. The Opt-Out page provides users with a
  way to request that IAB members not collect information about them for
  advertising purposes. The page, located at http://www.aboutads.info/choices/,
  is pretty simple to use. Unfortunately, it is also pretty useless since it
  relies on cookies, which privacy concerned users are probably blocking.
layout: post
permalink: /2011/09/iabs-opt-out-panel/
categories:
  - Tech Policy
tags:
  - Advertising
  - Consumer Rights
  - Privacy
---
![IAB Logo](/images/posts/2011/09/IAB.jpg)

A couple of weeks ago the [Interactive Advertising Bureau](http://www.iab.net/),
one of the largest industry groups and self-regulatory bodies in online
advertising, instated a new code of conduct for its members. In summary, the
new code requires any IAB member site that collect information about users to
display the logo to the right as an indication to users that collection is
occurring, and to provide users with information about what is being collected
and why.

While the new code of conduct has [taken flack for not actually providing clear notice](http://content.usatoday.com/communities/technologylive/post/2011/08/internet-advertisers-begin-offering-new-do-not-track-icon-/1),
this latest action by the IAB does bring some attention to the organization's
(beta) Opt-Out page. The Opt-Out page provides users with a way to request that
IAB members not collect information about them for advertising purposes. The
page, located at <http://www.aboutads.info/choices/>, is pretty simple to use:
all you need to do is visit the page, make sure you are on the "All
Participating Companies" tab, select the companies that you don't want to have
track you (or click "Select All Shown" to opt-out of tracking from all IAB
advertisers), and then click Submit Your Choices at the bottom. Once you submit
your choices, a cookie will be placed on your computer informing the companies
you selected that you do not wish to be tracked. Aside form the Opt-Out page,
the site includes information about online advertising (with an industry spin
of course) such as how to adjust the privacy settings in your browser and the
self regulatory principles of the IAB that are worth checking out.

## Does it Work?

So the page is easy to use, but does it actually increase your privacy? Well,
there are a few factors to consider that show the weaknesses of the opt-out
page:

**It applies to IAB members** - which are a lot of advertisers to be sure, and
includes most of the biggest advertising companies. Still, there are a lot of
other companies and sites out there that are not IAB members, and thus are not
affected by this Opt-Out page.

**It relies on companies respecting your decisions** - Between the IAB's own
enforcement and the threat of FTC legal actions, IAB companies have plenty of
reason to not track you if you tell them not to. Unfortunately, the history of
Internet privacy is full of examples of sites or companies not respecting the
wishes of consumers, even when they have said they would. For that reason, some
skeptisim is reasonable here, and personally I'm not yet ready to trust the
intentions or ability of the IAB to respect my privacy decisions. This opt-out
page allows you to ask that companies shutoff their tracking, which is different
from the approach tools such as [Ghostery](http://www.ghostery.com/) take,
which actually blocks information from being sent, and is an approach I'm more
willing to trust right now.

**It uses cookies** - If you are concerned about privacy on the Internet, you
probably have your browser set to not accept cookies/delete cookies when you
close the browser/or delete cookies often. That means the Opt-Out page is
pretty useless to the privacy concerned, since any choices set via the page
will be lost within a short amount of time. This is a problem that engineers
and policy makers have been discussing since Do-Not-Track became a big deal,
and in my opinion it reveals a problem with how cookies are managed by
browsers. The current cookie management model of the major browsers is built
on an all or nothing choice - either have all cookies on and retained, or have
all cookies off and deleted. Despite years of messaging about how bad cookies
are, the IAB's Opt-Out page shows that not all cookies are bad. Browsers need a
more sophisticated cookie management system that allows a user to select which
cookies can be kept for a long time and which should be deleted right away.
Until that happens, the Opt-Out page might as well not exist, and users should
instead use opt-out plugins like [TACO](http://www.abine.com/preview/taco.php).

**It only applies to one browser on one machine** - This limitation applies to
many privacy protection tools, but it is an important one. If you submit
opt-out requests in Firefox on your home PC, then tracking will still occur on
IE on that PC, or Firefox on your laptop.

## So Should I Use It?

The short answer is no.

Unfortunately, the Opt-Out page isn't a reliable tool for privacy protection,
mostly because of the cookie problem discussed above. This is especially
unfortunate since this page is likely the result of hours of discussion
involving IAB companies, the FTC, and consumer groups, and represents what I
would like to believe is an honest effort by the industry to address privacy
concerns.

Given the level of discussion and [work](http://www.w3.org/2011/tracking-protection/)
going into Do-Not-Track, it is likely that the IAB's Opt-Out page will merge
with a browser based Do-Not-Track manager. Until that happens, privacy
concerned consumers will have to continue to rely on third party tools to
prevent companies from tracking them all around the Internet.
