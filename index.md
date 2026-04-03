---
layout: default
title: Home
---

# Welcome

This is your new GitPages site.

Start by editing this page, creating new pages, or writing blog posts in the `_posts/` directory.

## Getting started
Make sure you have a ssh key uploaded or assigned to be used for gitpages service under <https://cs.brown.edu/account/sshkeys/>

Next, to your local ssh config under ~/.ssh/config add the following lines
```bash
Host $GITPAGES_CLONE_URL
    User <username>
    IdentityFile /path/to/private/key/used/for/gitpages
```

Next, To clone your repository, you will do a

`git clone $GITPAGES_CLONE_URL:people/yoursitename` if it's a personal site.

`git clone $GITPAGES_CLONE_URL:courses/yoursitename` if its a course site.

`git clone $GITPAGES_CLONE_URL:research/yoursitename` if its a research site.

The exact url for your site can be found under gitpages dashboard at <https://cs.brown.edu/gitpages/list/> and also in the confirmation email
you received after succesful creation of the site.

Once cloned, open the repository locally and read the README.md file for detailed instructions on editing and customizing your site.
