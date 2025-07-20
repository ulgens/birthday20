---
title: "First release"
date: "2025-07-03"
draft: false

params:
  timeline_date: 2005-11-16
  timeline_type: milestone

---

Adrian Holovaty [announces the first release of Django 0.90](https://www.djangoproject.com/weblog/2005/nov/16/firstrelease/):

<blockquote>We're especially excited that getting Django no longer requires installing Subversion. :-)</blockquote>

In this context, it's important to understand that distribution of Django had worked through Subversion (SVN), a pre-decessor to Git.
At this point in time, Django is not on PyPi nor GitHub (which didn't exist until 2007). Instead, installing Django involves downloading a .tar.gz file or a so-called Python egg.

In fact, you can still download the 0.90 code [here](http://www.djangoproject.com/download/0.90/tarball/).

The quote about SVN is referring to the fact that the very first Django installation instructions looked like this:

{{< imgProc
img="screenshot.png"
command="Fit"
options="800x800"
alt="A screenshot of djangoproject.com's download instructions, archived on August 5 2005."
class="photo"
>}}
