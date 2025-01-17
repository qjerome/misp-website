---
title: MISP 2.4.63 released
date: 2017-02-01
layout: post
banner: /img/blog/misp-small.png
---

A new version of MISP [2.4.63](https://github.com/MISP/MISP/tree/v2.4.63) has been released, including bug fixes and new features.

New features in the API:

 - Allowing fetching of full discussion threads via the API.
 - Add and remove tags from objects by uuid (in addition to the id).

Added a new setting to show post count on the event index including a notification if it has a post newer than 24 hours.

A significant update has been done to ensure the pruning of the upgrade logs. A pruning tool is available in server Settings under the diagnostics.
This solves an issue where doing an upgrade from version ~2.4.50 can cause the filling up the database with upgrade script logs.

[MISP galaxy](https://github.com/MISP/misp-galaxy) has been updated to the latest version including a new ransomware galaxy and many updates. MISP warning-lists have been updated to the latest version.

A big thanks to all the users who gave feedback and contributors who helped us improve MISP. A huge thank to [John Bambenek](https://twitter.com/bambenek) who allowed us to improve MISP with his MISP specific high-volume use-case in [Fidelis Barncat Intelligence Database](https://www.fidelissecurity.com/resources/fidelis-barncat).

The full change log is available [here](https://www.misp.software/Changelog.txt).

Don't hesitate to [open an issue](https://github.com/MISP/MISP/issues) if you have any feedback, found a bug or want to propose new features.
