# gitpoll - monitor git repos for new commits

gitpoll is a simple bash script that will alert you when new commits have been
pushed to repositories of interest.  The changes are merely
[*fetched*](http://www.kernel.org/pub/software/scm/git/docs/git-fetch.html),
which allows you to merge them with your working tree at will.

## Setup

1. Create your **~/.gitpoll** config to tell gitpoll which repositories to monitor:  
`repositories=(~/Code/hello-world ~/Code/project-awesome ~/Code/secret-weapon)`

2. /path/to/gitpoll
