google summer of code candidates
==============
This extension adds a new page to your civicrm. There isn't any new entry in the navigation menu but it's accessibleit you type the url {http://yoursite.local}/civicrm/gsoc (I'm assuming a drupal install with url rewrite, if other CMS/configuration, adapt the path to the needed).

This page contains the list of candidates for the Google summer of code. It's an example of a static page built from an extension. By itself, it has about zero benefit.

Notice that we don't see your name yet. If you are a candidate, this need to be fixed, and your mission is to change that page to add your name.

I have no doubt that you can add your name to a file, the aim it to provide a playground so you can confirm you have mastered our git workflow to contribute code:

- fork this repository so you have your own version of this code.
- install civicrm on your machine, set up the extension path
- git clone your fork of this extension
- enable this extension
- add your name into the page displayed into civicrm/gsoc by modifying the template file.
- commit the change and push back to your repo
- do a pull request so I can add your name into the main


The point is not to show us that you know everything about civi, but that you can manage the publication process. If you are stuck, feel free to ask in the forum. One common issue when you install extensions from git is that you have caches and need to refresh them to see the extension in the list.

If you know github and is familiar with this workflow and have civicrm already installed, it should take you 15min. Don't panic if it takes longer, it's normal, installing a dev environment is often what takes the longest in a project.

## Shortcuts and cheatcodes
Github offers an option to edit a file via the web interface. So you can do that task without using git at all. We like hacks and creative workaround, but that one would be cheating, and it wouldn't be good for your karma. As in, the chances of passing the midterm (and being paid) are very low if you aren't able to do stuff in git. 
