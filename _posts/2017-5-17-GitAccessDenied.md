---
title: Access Denied
layout: post
---

If you ever find yourself in a situation where doing a GIT commit/publish/push and get access
denied - and you have multiple GIT accounts:

1. Search windows on 'Manage Windows Credentials'
2. Alternatively, Control Panel > User Accounts > Credential Manager > Windows Credentials
3. Delete any item that references GitHub

The reason for this is that the GitHub for Windows download includes the Credentials Manager
which will add credentials so that you do not have to keep logging a username/password each time
you do a GIT command.  They advertise that they do not cache infinitely but that didn't prove to
be the case with me.

From what I can tell at this moment, this action will need to be performed each time you go from
one user account to the other.  
