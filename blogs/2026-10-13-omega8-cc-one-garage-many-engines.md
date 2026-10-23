---
title: "Omega8.cc: One Garage, Many Engines"
url: "https://omega8.cc/blog/one-garage-many-engines"
date: "2026-10-13"
feed_url: "https://www.drupal.org/planet/rss.xml"
---
In March 2012 a developer asked us for a PHP version per platform, a per-site override on top, and a way to tell Drush which PHP to use, and I turned the Provision half down myself, because the Ægir backend's command-line PHP was hard-wired into the Drush wrapper and had to be running before any task could change it. Fourteen years and a few small text files later, BOA-5.88.866 closes that gap: one line in cli-per-platform.info gives a platform its own command-line PHP, so a Drupal 7 codebase keeps its drush on PHP 7.4 while the Drupal 11 build beside it gets 8.5, in the same account, with no 
