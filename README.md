# Bioshock Infinite

**Official** GitHub page used for tracking issues related to Bioshock Infinite on Linux.
Please use this repository for reporting bugs and issues for the game.

# Conduct

This issue tracker is here for reporting bugs and issues ONLY, and some basic rules of conduct apply:

* Do not insult, harrass, or demean any other member or the developers
* Do not start "flame wars"
* Do not use ALL CAPS when creating an issue report.
* Do not intentionally multi-post an issue
* Do not repeatedly update an open issue remarking that the issue persists

We want this to be an effective environment for passing on useful feedback to help us improve the game.
Offenders will be cautioned. Persistent offenders will be banned and reported to GitHub.

# Instructions

Please make sure that you search the open issues before creating a new one to prevent duplicates. Include closed issues in your search as we may have already resolved them.

When reporting a new issue, post the following:

  * A short, descriptive title of the problem
  * A detailed description of the issue, including any relevant output
  * A step by step guide for reproducing the issue, if possible
  * Your system information
  * The game's "eon.txt" log file, which can be found at "~/.local/share/irrationalgames/bioshockinfinite/"

Post your system information as follows:

  * General system info i.e. CPU type/speed, RAM amount etc...
  * Linux Distro, including release version
  * Desktop environment and compositor in use
  * Graphics Card type, including Video RAM amount
  * Graphics driver and version

You can easily retrieve your system specifications using Steam: Help -> System Information. Appropriate output from tools such as "ls /proc/cpuinfo", "lspci" etc are also acceptable.

Please post system info and logs using a [code block](https://guides.github.com/features/mastering-markdown/) or a [gist](https://gist.github.com) where appropriate. gist is generally more appropriate for posting log files.

If you wish to show us your current configuration settings, these can be found at  "~/.local/share/irrationalgames/bioshockinfinite/GameDocuments/My Games/BioShock Infinite/XGame/Config/". Please post them using gist.

# Public Betas

Unfortunately we will not be able to offer public betas for this game.

# Announcements

**8 July 2015 09:28 BST - New version available, Steam BuildID 655022**

This build should address the lockups that were mostly being seen on AMD processors.

**30 April 2015 21:40 GMT - New version available, Steam BuildID 604493**

This build should address the following issues:

* The game should now work correctly on all filesystems, including XFS (issue #2)
* Saved game timestamps should now be correct - unfortunately existing save points will continue to be incorrect (issue #12)
* The side mouse buttons should now be usable
* The monitor the game uses can now be set with --eon_force_display <monitor number>. Monitor number starts from 0 for the primary display (issue #3)

Sometimes the game may still open its window on the wrong monitor, we are investigating this.
Unfortunately we have not yet found the cause of the lockups that seem to mostly affect AMD processor users (issue #1, #9).  We are still investigating this.

22 April 2015 17:00 GMT - GitHub tracker now available

We've now got the go-ahead to offer an issue tracker for the game via GitHub, as we did with Witcher 2. We're already aware of a number of outstanding issues, and we're working on them.
