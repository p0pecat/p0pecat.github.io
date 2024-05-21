---
author: "Jack"
title: "osintcat.com - New Competition in the OSINT Scene"
date: "2024-05-20"
summary: A new databreach archive search tool has entered the scene, does it compare to current services?
ShowToc: false
TocOpen: false
cover:
  image: "https://source.unsplash.com/i4W8OINLI_I"
  # can also paste direct link from external site
  # ex. https://i.ibb.co/K0HVPBd/paper-mod-profilemode.png
  alt: "<alt text>"
  caption: "Photo by [Catherine Heath](https://unsplash.com/@catherineheath) on [Unsplash](https://unsplash.com/photos/shallow-focus-photo-of-orange-cat-near-laptop-computer-i4W8OINLI_I)"
  relative: false # To use relative path for cover image, used in hugo Page-bundles
  linkFullImages: true
params:
  ShowShareButtons: true
---

### A Brief Overview

Recently, I have discovered a new service that could be utilized in OSINT investigations, specifically in social media monitoring and analysis. This new service, known as [osintcat](https://osintcat.com), is a databreach archive search tool. This tool allows an individual to search through a variety of archived databreaches for a specific email, username, and other identifiers.

### Exploration

Since April 2024, osintcat has been offering a databreach archive search tool to allow users access to public databreach records. They claim to house over 34 billion records at the time of writing this, and that number seems to be increasing by the day. As this is a relatively new service, I decided to investigate and test this tool for myself. 

After reaching out to the developers, Bartholemew and Sally, I was given a free api key to further explore and test their service.

I began by navigating to their activation page, where I activated the api key I was given. This provides access to their tool.
{{< figure src="https://i.ibb.co/93PYnTf/realactivate.png" attr="Activating my key" align=center >}}
After activating my key, I am greeted with a search tool. After selecting the query type drop down, I am given the following search options:
- Username
- IP
- Email
- Password
- Phone
- Gaming
- Hash

{{< figure src="https://i.ibb.co/c6w0Yqv/search.png" attr="Search page" align=center >}}
I decided to test the "email" search option on an alternative email of mine that I know is in a couple breaches. After inputting my email and selecting "search" I was greeted with results.
{{< figure src="https://i.ibb.co/zJC1tGV/emailresults.png" attr="Results of my search" align=center >}}
Upon expanding one of these results, I am met with formatted data containing what breaches my email was found in. One breach included my email (obviously), hash, lastip, salt, and my username.
{{< figure src="https://i.ibb.co/s11zs0m/email2.png" attr="Expansion of my results" align=center >}}
After further testing with a variety of search terms, I was shown many data breaches that I was already aware of. I was shocked when I discovered data breaches I was not aware of!

Overall, their search system provided many options and presented me with a multitude of unexpected results.

### Ethics and Legality

This service provides easy access to a variety of leaked databases for a low price, making osintcat quite the powerful tool in the right hands. While this tool may be useful, is it legal? Ethical?

Judging by what I have seen thus far, osintcat is completely legal. Their service allows users to search through a collection of publicly available information, similar to sites like [IntelligenceX](https://intelx.io/), making their services completely legal!

In regards to ethics, that is completely based on how you plan to use osintcat. While it could be used unethically by threat actors to gather information on potential targets, it could also be used by cybersecurity professionals or law enforcement to conduct investigations on threat actors. Overall, I feel as though this tool is ethical, as threat actors would simply find shadier means to obtain information provided by osintcat.

### Final Thoughts

Exploring and experementing with osintcat was fun, and I am appreciative of the developers for allowing me free access to their services. Their site was easy to navigate and their search tool was easy to use. While I am not sure how they compare to their well established rivals, such as IntelligenceX or DEHASHED, osintcat is shaping up to be a great tool for OSINT researchers around the globe.