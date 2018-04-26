# medfieldmd.org #

This is a repository of [medfieldmd.org](http://medfieldmd.org/), the Medfield
Community Association's web site.

## Development ##

**It's important that any changes to the site are recorded in this
repository and pushed to GitHub. Otherwise, your changes will be lost the next
time the site is updated from this repository.**

The preferred way to update the site is by doing a `git push` to it. There is a
bare clone of this repository on the server. It has a `post-receive` hook that
does a force-checkout of `master` into the directory where the site is hosted
from. (See [Using Git for web development][1].)

To get set up for that, in your clone of this repository you can use the
`git remote add` command to add a second remote you can push to. Out of an
abundance of caution, the username and hosting server's domain name aren't
given here—get them from another dev. See [Working with Remotes][2] for help
on working with multiple remotes.


[1]: https://help.dreamhost.com/hc/en-us/articles/115000684492-Using-Git-for-web-development
[2]: https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes
