---
layout: lesson
title: Version Control with Mercurial
---
Version control is the lab notebook of the digital world:
it's what professionals use to keep track of what they've done
and to collaborate with other people.
Every large software development project relies on it,
and most programmers use it for their small jobs as well.
And it isn't just for software:
books,
papers,
small data sets,
and anything that changes over time or needs to be shared
can and should be stored in a version control system.

Version control is better than mailing files back and forth because:

*   Nothing that is committed to version control is ever lost.
    Since all old versions of files are saved,
    it's always possible to go back in time to see exactly who wrote what on a
    particular day,
    or what version of a program was used to generate a particular set of results.

*   As we have this record of who made what changes when,
    we know who to ask if we have questions later on,
    and,
    if needed it,
    revert to a previous version,
    much like the "undo" feature in an editor.

*   When several people collaborate in the same project,
    it's possible to accidentally overlook or overwrite someone's changes:
    the version control system automatically notifies users whenever there's a
    conflict between one person's work and another's.

Teams are not the only ones to benefit from version control:
lone researchers can benefit immensely.
Keeping a record of what was changed,
when,
and why is extremely useful for all researchers if they ever need to come back
to the project later on
(e.g., a year later, when memory has faded).

This lesson shows how to use
a popular open source version control system called [Mercurial](http://mercurial.selenic.com/)
(also known as `hg`).
It is widely used,
both because it's easy to set up
and because of a hosting site called [Bitbucket](http://bitbucket.org).
No matter which version control system you use,
the most important thing to learn is not the details of their more obscure commands,
but the workflow that they encourage.

> ## Prerequisites {.prereq}
>
> Students should understand how to interact with the Unix shell
> (e.g., how to change their working directory)
> before beginning this lesson.

> ## Getting ready {.getready}
>
> **You are ready to go.**

## Topics

1.  [Automated Version Control](01-basics.html)
2.  [Configuring Mercurial](02-configuration.html)
3.  [Creating a Repository](03-create-repo.html)
4.  [Tracking Files](04-tracking.html)
5.  [Making Changes](05-changes.html)
6.  [Exploring History](06-history.html)
7.  [Recovering Old Versions](07-revert.html)
8.  [Ignoring Things](08-ignore.html)

2.  [Collaborating](02-collab.html)
3.  [Conflicts](03-conflict.html)
4.  [Open Science](04-open.html)

## Other Resources

*   [Mercurial Web Site](https://mercurial.selenic.com/)
*   [Mercurial: The Definitive Guide](http://hgbook.red-bean.com/) (also known as "The Red-bean Book")
*   [Mercurial Command Reminders](commands.html)

*   [Reference](reference.html)
*   [Discussion](discussion.html)
*   [Instructor's Guide](instructors.html)
