---
title: "Animated GIFs are drawn partially if hidden at first"
date: "2015-12-18T18:27:00-05:00"
categories: ["misc"]
tags: []
versions: ["43", "44", "45", "46"]
statuses: "regressed"
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=1233403": "Bug 1233403 - Animated GIFs are partially drawn if those are hidden at first"
---
Firefox 43 has introduced a regression where animated GIF images are not entirely drawn if those are hidden with CSS when the page is loaded. Mozilla developers are working on the solution.