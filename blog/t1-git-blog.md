My first technical blog	

A little about git and GitHub

October 29th, 2014

Have you ever experienced the frustration of working on a school project for way too long, when suddenly your computer decides to crash? Just at that moment, you realize you haven't saved your project for at least a few hours, meaning you're screwed. Luckily, these days Microsoft has equiped Word with an AutoSave function, reducing any damage due to dataloss by recovering a version of a few minutes old. Awesome!

Programmers usually don't write their code in Microsoft Word. But fortunately, there are other tools that are even richer in functionality that suit them just fine. I don't think it actually protects you from losing unsaved work after a crash, but it does allow you to recover previous versions (tech people usually have proper functioning computers anyway). This so called "version control" is not just about switching back to an old state of a project - it allows you to test new code without messing up the actual working code. 

Using software called "git", developers can copy the most perfect "master" code and mess around with it in an experimental environment, called a "branch". When he's done and, he can merge back his code into the master, updating his project to a new version.

It might happen that something doesn't work the way he wanted it to, and he needs to get back to the old version. He might even need to skip back two, five or maybe ten versions. Git allows you to do so, it remembers all versions of the project you had, saving you a lot of time rewriting old code.

Often, you don't work on a project just by yourself. A lot of people use Dropbox to share files, but as soon as more people work on one file at the same time, there is going to be a conflict when saving your work. You can get lost in all the different versions around.

Developers use GitHub to prevent that from happening. Instead of having the most perfect version of a project stored locally, you put it on GitHub, so that it is online and accessible for anyone you want it to be - just like dropbox. Then, the beautiful thing about using git and GitHub is that "merging" your new code into the master project leaves everything intact but the part you editted. This way, anyone can work on anything at the same time.

