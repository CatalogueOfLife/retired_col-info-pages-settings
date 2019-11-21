# col-info-pages-settings
Info pages and settings for CoL+ in the old CoL interface.

### What's included

**info-pages**
- info pages for the checklist; symlink to `/application/views/scripts/info`
(note that typo's may result in a completely broken CoL!)

**translations**
- translation files for the checklist; symlink to `/application/data/languages`


### How to use

images, info-pages ans translations are symlinked to the respective directories in the CoL. Call the script through

`php update.php -p [secret key]` or

`http://[server]/update.php?p=[secret key]`

to initiate a git pull of this repository on the CoL server. The changes should be visible in the CoL immediately.

