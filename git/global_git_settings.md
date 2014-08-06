# Global Git Settings

###Link Stash to Gravatar
* Navigate to your Account page at the Remote repository of your choice. They all have this option.
* Set your Avatar to pull from your Gravatar account.

###Ensure SourceTree set your git global settings.
This step is probably not necessary, but if you see your commits showing up as Unknown, this is how to fix it.
<img src="http://cl.ly/image/0f3I3E133c3c/Image%202014-05-04%20at%2010.37.08%20PM.png" width="200px" />

1. Check that Source Tree is accurately setup. You should see something like the following in your preferences. If not, update those to your name and comscore email.
<img src="http://cl.ly/image/3w2n0A04383J/Image%202014-05-04%20at%2010.48.48%20PM.png" width="400px" />
2. If they were already set to the correct values, you'll want to manually update your Name and Email.

```
$ git config --global user.name "Your Name Here"
# Sets the default name for git to use when you commit
```
```
$ git config --global user.email "your_email@example.com"
# Sets the default email for git to use when you commit
```

### Setup a personal repository (Stash)
* Navigate to your Stash Profile Page (company_host/profile.html)
* Click on Create Repository.
* This is a good place to test out git commits, pushes, pulls, etc.


- - -
Sourced From:

* https://help.github.com/articles/set-up-git
