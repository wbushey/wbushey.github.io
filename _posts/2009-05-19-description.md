---
title: Description of TermsWatch
author: bill
layout: post
permalink: /2009/05/description/
categories:
  - Projects
tags:
  - TermsWatch
---
<!-- 		@page { margin: 0.79in } 		P { margin-bottom: 0.08in } 	-->

<p style="margin-bottom: 0in;">
  TermsWatch is an attempt to combine the power of knowledge and software to provide a tool that end users can use while reading and executing the Terms of Use or Terms of Service (Terms) that are typically encountered while using software or websites. Specifically, TermsWatch will aim to tackle two problems:
</p>

  * *Service Providers are Allowed to Change the Terms Without Notice*: <span style="font-weight: normal;">The majority of Terms include a clause that allows the service provider to make changes to the Terms with out notifying its users. Further, this clause usually includes wording stating that a user&#8217;s continued use of the provided service will indicate an acceptance of the new or altered Terms.</span>
  * *Most Users Can Not Understand the Terms*: <span style="font-weight: normal;">By their nature, Terms contain lengthy, dense language that is often very difficult for common users to understand. Consequently, few users will read the Terms that they are asked to consent to. Fewer still will read the Terms and understand what they are consenting to, what rights they are giving to the service provider, and what the nature of their relationship with the service provider is.</span>

<p style="margin-bottom: 0in;">
  In order to combat these issues, TermsWatch is designed to do the following:
</p>

  * *Monitor Terms of Use*: <span style="font-weight: normal;">The service will maintain a list of URLs, each referring to the web page that displays the Terms of a service provider. Periodically, TermsWatch will download these web pages and use XML parsing to extract the text of the Terms. This extracted text will then be compared to the most recent version of the Terms that is available in TermsWatch&#8217;s database. If the two versions differ, the new Terms will be saved to the database and an RSS feed, specific to the service provider, will be updated in order to alert users to any changes in the Terms.</span>
  * *Store Annotations*: <span style="font-weight: normal;">In addition to storing the Terms of each service provider being monitored, TermsWatch will also store annotations made to the stored Terms. This would include storing explanations and comments made about a specific version of a provider&#8217;s Terms, as well as storing explanations/comments about changes that have occurred between versions. </span>
  * *Expose Data Via Public API*: <span style="font-weight: normal;">To truly be useful, the data collected from monitoring Terms and storing annotations must be made accessible by other programs and services. To make this data accessible, TermsWatch will provide a public API that will allow for retrieval of data about a specific service provider&#8217;s Terms, such as the text of the Terms or annotations made to the Terms. The API will also allow for the creation and editing of annotations.</span>