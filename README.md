---
title: Git It On!
subtitle: Di**git**al Lab Journalling with Git
author: Katrin Leinweber
date: 2015-Apr-13
---

### Remember Ansgar's "Tree of Life"-talk?

[![](images/doolittle-tree.jpg "Doolittle, Darwin and the Deeply Dumb (Tim Bousquet, The Coast, 2009-Oct-8)")](http://www.thecoast.ca/halifax/doolittle-darwin-and-the-deeply-dumb/Content?oid=1320808)

### What is evolution?

[![](images/change-we-can-believe-in.jpg "More Darwin (Mike Rosulek,2009-Feb-20)")](http://www.mikero.com/misc/darwin/)

### What is evolution?

[![](images/Horizontal-gene-transfer-ori.jpg "Smets & Barkay (2005) Horizontal gene transfer: perspectives at a crossroads of scientific disciplines")](http://www.nature.com/nrmicro/journal/v3/n9/fig_tab/nrmicro1253_F1.html)

#### Genetic changes; chronologically ordered by inheritance.

### Projects live & evolve, too! Largely digitally. 

> 1. ideas => implementations => observations & data collection => repetitions & optimisations
> 1. discussions of results => reports, posters, talks, manuscripts, etc. => feedback from collauges => new ideas

![](images/Horizontal-gene-transfer-no-domains.png)

### Lab journals need

> 1. chronological, verified order => page numbers & manual dating?
> 1. highlighting of changes => coloration?

#### Paper is limited

> - can't be shared easily (not even read-only), nor written collaboratively
> - by page space
> - searching through handwriting is for historians

#### Git offers

> - [mathematically verified](http://git-scm.com/book/en/v2/Getting-Started-Git-Basics#Git-Has-Integrity) order of changes
> - comment/message for each change
> - automatic highlighting of changes

### What is Git?

> [A] free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. ([git-scm.com](http://git-scm.com/))

![](images/git-logo.png)

### What is Git?

> [A] free and open source distributed version control system designed to **handle everything** from small to very large projects with speed and efficiency. ([git-scm.com](http://git-scm.com/))

#### all types of files

> - like good backup system
> - very useful for line- or paragraph-based text files
> - medium useful for images (JPG, PNG, etc.)
> - DEMO: `F0-legends > initial` & `150224-30m > final`

### What is Git?

> [A] free and open source distributed **version control** system designed to handle everything from small to very large projects with speed and efficiency. ([git-scm.com](http://git-scm.com/))

#### control over document versions

> - record, comment & highlight changes
> - revert old changes & restore old file versions
> - per line if necessary => better than backup or wiki
> - DEMO: `F0-legends > moved incubation times...` 

### What is Git?

> [A] free and open source **distributed** version control system designed to handle everything from small to very large projects with speed and efficiency. ([git-scm.com](http://git-scm.com/))

#### asynchronous team-work

> - entire database of project history is stored in each project folder
> - sync changes via Git server (like comments in JPY-PDF)
> - collisions only if same lines are edited (Dropbox?)
> - DEMO: `Paper-Now-Achmi...`

### Summary of Git's properties

#### Technically

> - works very well for text, semi-well for images
> - gives you control over, and knowledge plus proof of, file changes
> - gratis backup & cheap syncing

#### Culturally

> - enables precise documentation (for colleagues, students, reviewers, your future self, etc.)
> - ultimately eases collaborative work on same set of files
> - teaches basics of best software tools

### Good against: too many files

![](images/versions-win-explorer.png)

### Good against: unnamed versions

![](images/versions-crashplan.png)

### Good for: clean view on files plus accessible version history 

![](images/files-in-explorer.png)

### Good for: clean view on files plus accessible version history 

![](images/file-changes-in-GitHub.png)

- [ ] make same screenshot on Win

### Basic vocabulary

- **repository:** Git's database of file versions in a watched folder

![](images/repo-folder.png)

### Basic vocabulary

- **commit:** set of logically connected changes within same (or across different) file(s) that are checked into the repository

![](images/logical-commit-across-files.png)

### Advanced vocabulary

> - **branches:** different contexts in same repository (cheaply created for a side experiment & then either merged or deleted)
> - DEMO: `Git it on > experiments`

![](images/branching-illustration.png)

### Advanced vocabulary

> - **switching branches:** letting Git serve only the files in that branch to you
> - **merging:** integration of changes from one branch into another

### How to start using it?

> 1. Wait for small, new project (report, diagram in R
> 1. Download a Git client (for example from windows.github.com, or check [git-scm.com/downloads/guis](http://git-scm.com/download/gui/win)) & install
> 1. create new folder initialise it as a repository
> 1. start adding files & editing them
> 1. commit logically connected edits and changes 
> 1. *Optional* (for collaboration, off-site backup, publishing, etc): create account with a Git-hosting service like [GitLab](https://gitlab.com/users/sign_in), [GitHub](https://github.com/join), [BitBucket](https://bitbucket.org/account/signup/)*

- [ ] or at [git.uni.kn](https://git.uni-konstanz.de/users/sign_in)

### The End

![](images/keep-calm-and-git-it-on.png)

##### Came a long way from [Introduction to Digital Lab Journalling](http://prezi.com/p_se6nkre49m/digital-lab-journalling-intro/).

##### Thanks to & Further Reading

- Jens Erat's [Scientific Markdown](https://github.com/JensErat/scientific-markdown)
- [Molly Gibson](https://github.com/mollygibson)'s [Git for Scientists](https://mollygibson.github.io/2014-08-11-wustl/lessons/git-notebook/git-for-scientists.slides.html)
- http://datapub.cdlib.org/2014/05/05/github-a-primer-for-researchers/
- http://marciovm.com/i-want-a-github-of-science/
