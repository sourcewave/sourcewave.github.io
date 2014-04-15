---
layout: post
title: "March 31st Release Notes"
date: 2014-03-31
author: robert
category: release-notes
excerpt: "We have made the frontus repo public (the entirety of the front end) and with that will now be publishing our work and progress for all to see."
---

We have made the frontus repo public (the entirety of the front end) and with that will now be publishing our work and progress for all to see.

New features this week include:

You can now message all your investors without sharing something to them at the same time. This is the first step in us building out a fully featured internal messaging system.

Voiding executed documents is now possible. This requires two party consent, the issuer must request a void from the investor who must then agree. Any completed document can be voided. As part of voiding a new audit trail is generated and the front page of the document is watermarked. The watermarking takes time (comparable to the signing process), which is why only the front page is watermarked. As we move forward we may make the rest of the pages watermark asynchronously.

tiffs can now be uploaded as signature/profile images.

Things that are not yet visible:

The documents angular code has been refactored heavily. This should make the move to a single angular app simpler (and makes reading/writing code easier too!).

Major progress on the payment system using stripe. This will be occupying half the dev team for the next few weeks.