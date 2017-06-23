# jobwatch
A simple tool to produce RSS feeds from company job listings

How to use:
===========

 1. Install jobwatch and dependencies.
 2. Modify as desired
 3. Initialize git repo on github and clone to local system
 4. Set up cron job to run site watch in local system dir
 5. Subscribe to git repo RSS

Dependencies
============

 - jq
 - git
 - wget
 - moreutils

TODO
====
 - break out configuration from script, into a DSL for company defs, filtering based on file type etc
 - normalize job listings into standard format
 - add commands to simplify setup and install

History
=======

Long long ago, a similar tool called sitewatch was published using a similar strategy. This project
aims to improve upon that with git support and additional features.
