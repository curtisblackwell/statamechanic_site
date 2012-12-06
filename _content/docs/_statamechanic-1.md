---
title: Statamechanic 1 Docs
_template: default
description: These are the docs for Statamechanic 1.
keywords: legacy docs
---

Statamechanic is a collection of Statamic tools to get you up and running quickly and smoothly.

## statamic-setup.sh (for use with Statamic 1.3 and 1.4)
`statamic-setup.sh` sets up your [Statamic](http://statamic.com/) site quickly and easily.

**When using with 1.4, tasks involving the default theme may not work as expected.**

### Features
* Deletes unnecessary files/folders.
* Creates admin account with bio.
* Updates `_config/settings.yaml`.
* Installs above root.
* Sets permissions.

### Usage
1. Backup anything you may have done (existing .htaccess, folder structure, etc.).
2. Unzip Statamic into `~/Sites` (or wherever the local site will ultimately reside).
3. Navigate to Statamic folder (ex. statamic-1.3-personal) in Terminal.
4. `sh path/to/statamic-setup.sh`

## create-statamechanic_settings.sh
### Features
* Creates/Updates `statamechanic_settings.sh`.
* Optionally adds `create-statamechanic_settings.sh` to `.gitignore` (recommended for public repos).

### create-statamechanic_settings.sh is for developers who

* installed Statamic without Statamechanic, but would like to begin using it for other reasons,
* installed Statamic with a version of Statamechanic before 1.1.1, and/or
* somehow lost their `create-statamechanic_settings.sh`.

### Usage
1. Backup your site.
2. Navigate to your project folder (ex. `~/Sites/mysite`) in Terminal.
3. `sh path/to/create-statamechanic_settings.sh`

## Tip(s)
### Simplify the Script Call
If you add the following line to your bash profile (~/.bash_profile on Mac OS X), instead of typing `sh the/long/and/arduous/journey/to/statamic-setup.sh`, you can just type `statup`.

    alias statup="sh path/to/statamechanic/statamic-setup.sh"

## Support
For now, support requests should be emailed to <the@statamechanic.com>. I have plans to use a forum (or something similar) in the near future, however I'm waiting to see what Statamic offers, if anything, when the marketplace launches.

<span class="badge badge-warning">!</span> Because Statamechanic isn't a typical add-on and is comprised mainly of shell scripts, only Mac OS X is officially supported and tested.

### Feature Requests
Feature requests are encouraged and should be emailed to <the@statamechanic.com>.