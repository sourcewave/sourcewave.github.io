---
layout: post
title: April 21st Release Notes
date: 2014-04-21
author: robert
category: release-notes
excerpt: "As of last Wednesday pricing is now finally live. All new registrations now require a valid card (though we won't charge until May). We've integrated with Stripe for all billing related functionality, abstracting away for us the nitty gritty of handling card data. For existing users, plans can be selected from the company profile page which is also where users can upgrade or cancel their current plan (and change their credit card if they so choose). Non-admin accounts continue to be 100% free."
---

As of last Wednesday pricing is now finally live. All new registrations now require a valid card (though we won't charge until May). We've integrated with Stripe for all billing related functionality, abstracting away for us the nitty gritty of handling card data. For existing users, plans can be selected from the company profile page which is also where users can upgrade or cancel their current plan (and change their credit card if they so choose). Non-admin accounts continue to be 100% free.

With the migration to the latest angularjs we've get a few new tricks in our toolbox. Most are behind the scenes but we've utilized the new ng-paste directive to massively increase the efficiency with which you can move your cap table from your existing spreadsheet to Sharewave. Just copy and paste each column into our cap table and watch the magic happen. We'll soon support copy and paste of the whole spreadsheet though inconsistency between spreadsheet tools and how they export their data through copy (the column delimiters vary: some use fixed width, some comma etc.) make this more of a challenge.

Finally we know many have not been loving how long it takes their document library to load. We didn't either, so we adjusted how we get the document data and you should now find it much, much faster. This is most obviously seen on page load, but also in the various interactive elements of the page (looking at the document versions and switching to share mode). We put less data on the page at any one time: elements that were previously hidden (display: none), we now don't even load onto the DOM until you actually want to see them. We'll be optimizing this further over the coming weeks.

This week we'll be introducing our newly revamped navigation! In particular it should be a huge benefit to those on smaller screens as it takes up much less screen real estate than the current top navigation.