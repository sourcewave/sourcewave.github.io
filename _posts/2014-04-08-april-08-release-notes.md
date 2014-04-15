---
layout: post
title: April 8th Release Notes
date: 2014-04-08
author: robert
category: release-notes
excerpt: "This week the dev team's work centered around two big projects: converting to a single angular app, and preparing to take payments."
---

This week the dev team's work centered around two big projects.

The first involved converting the internal website to a singular angular app. This means a slightly longer loading time up front (as all the js gets loaded in one go) but then much, much faster switching between pages as most of the content does not get reloaded (and you'll see less flashing as the navbar never changes).

As part of this we also moved to Angular 1.3. We gain various tools and features with this upgrade not least ng-if which we put to use in the cap table immediately to slightly increase its speed (ng-if removes elements from the dom entirely rather than just hiding them, which means they are not watched by angular, the biggest cause of slowdown on the captable).

The other major project relates to taking payments, and is ongoing, not yet deployed to production. Much of the flow is now built out and styled. We decided to push forward the release of payments to around the 15th April so even though Sharewave will continue to be free until May 1st, we'll be taking cards (and requiring them at signup) from the 15th.

Smaller bits and pieces:

- The optional message box for sharing now accepts carriage returns which display in the final email

- Users can prepare documents without going to share mode

- Users can retract and archive at the same time (optionally) rather than it being two independent steps

- The navbar is now even flatter visually with many of the drop shadows removed