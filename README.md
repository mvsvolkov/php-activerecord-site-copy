This is Copy of https://bitbucket.org/theasci/php-activerecord-site

# Overview
The php-activerecord project is almost defunct. Since we use it Core, we need the documentation not to go away.

# Archive
The phpactiverecord.org site seems to be less reliable over time. It has been archived in this repository for reference using [httrack](https://www.httrack.com/). On a Mac, you can get httrack with `brew install httrack`.

# Commands
The following commands were used to archive the site.
```
httrack http://www.phpactiverecord.com/projects/main/wiki -/boards/* -/users/* -/news/* -/download/* -*/repository/* --continue
httrack http://www.phpactiverecord.com/docs -/boards/* -/users/* -/news/* -/download/* -*/repository/* --continue
```
