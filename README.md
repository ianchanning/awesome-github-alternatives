# Awesome GitHub Alternatives [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This is a list of alternatives to GitHub, that by default offer Git management in some way. If they also offer another type it will be tagged so. All self-hosted options are free and open source, using licenses that are compatible with the GPL.

## Contents

* [Self-hosted](#self-hosted)
  * [C](#c)
  * [Go](#go)
  * [Java](#java)
  * [JavaScript](#javascript)
  * [Perl](#perl)
  * [PHP](#php)
  * [Python](#python)
  * [Ruby](#ruby)
  * [Scala](#scala)
* [Hosted](#hosted)
* [Peer-to-Peer](#peer-to-peer)
  * [Rust](#rust)

## Self-hosted

Install it yourself on your own server for fun and profit.

### C

* [Fossil](https://fossil-scm.org) [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) **No Git** **+Fossil** - Fossil is a simple, high-reliability, distributed software configuration management system.  In addition to doing distributed version control like Git and Mercurial, Fossil also supports bug tracking, wiki, and technotes.

### Go

* [GitLab](https://about.gitlab.com/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) - GitLab is the first single application for all stages of the DevOps lifecycle.
* [Gogs](https://gogs.io/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) - A painless self-hosted Git service.
  * [Gitea](https://gitea.io/en-US/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) - Gitea is a community managed fork of Gogs, lightweight code hosting solution written in Go and published under the MIT license.
* [HGKeeper](https://keep.imfreedom.org/grim/hgkeeper) [![License: AGPL-3.0](https://img.shields.io/badge/license-AGPL%203.0-brightgreen)](https://opensource.org/licenses/AGPL-3.0) **No Git** **+Mercurial** - HGKeeper is a simple [Mercurial](mercurial-scm.org/) repository hosting tool that supports HTTP pulling and SSH pushing. Authentication is done via SSH keys and is fully configurable via [Casbin](https://casbin.org/).

### Java

* [Gerrit Code Review](https://www.gerritcodereview.com/) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) - Gerrit provides web based code review and repository management for the Git version control system.
* [Gitblit](http://gitblit.com/) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) - Gitblit is an open-source, pure Java stack for managing, viewing, and serving Git repositories.  It's designed primarily as a tool for small workgroups who want to host centralized repositories.
* [OneDev](https://github.com/theonedev/onedev)  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) - OneDev is a Self-hosted Git Server with Kanban and CI/CD

### JavaScript

* [GitSSB](https://git.scuttlebot.io/%25n92DiQh7ietE%2BR%2BX%2FI403LQoyf2DtR3WQfCkDKlheQU%3D.sha256) [`Fair license`](https://en.wikipedia.org/wiki/Fair_License) - Git repos on secure-scuttlebutt (SSB).

### Perl

* [GitPrep](http://gitprep.yukikimoto.com/) [![License: Artistic-2.0](https://img.shields.io/badge/License-Perl-0298c3.svg)](https://opensource.org/licenses/Artistic-2.0) - GitPrep is GitHub clone. You can install portable GitHub system into unix/linux. You can create users and repositories without limitation. This is free software.
* [Gitolite](http://gitolite.com/gitolite/) [![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html) - Gitolite allows you to setup git hosting on a central server, with fine-grained access control and many more powerful features.

### PHP

* ~~[Phabricator](https://phacility.com/phabricator/) [![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html) **+Mercurial** **+Subversion** - Every application your project needs, all in one tool.~~ Effective June 1, 2021: Phabricator is no longer actively maintained.
* [Tuleap](https://github.com/Enalean/tuleap) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) **+Subversion** - Tuleap Open ALM is a Libre and Open Source software forge crafted in PHP/MySQL.

### Python

* [Allura](https://allura.apache.org/) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) **+Mercurial** **+Subversion** - Apache Allura is an open source implementation of a software forge, a web site that manages source code repositories, bug reports, discussions, wiki pages, blogs, and more for any number of individual projects.
* [Pagure](https://pagure.io/pagure) [![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html) - Pagure is a git-centered forge, python based using pygit2.
* [Review Board](https://www.reviewboard.org) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) - Review Board takes the pain out of code review, saving you time, money, and sanity so you can focus on making great software. Review Board provides basic support for git. If you have a central "official" git repository, Review Board will work well for you.
* [Rhodecode](https://rhodecode.com/) [![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0) **+Mercurial** **+Subversion** - Centralized control for distributed repositories. Mercurial, Git, and Subversion under a single roof.
  * [Kallithea](https://kallithea-scm.org/) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) **+Mercurial** **+Subversion** - (fork of Rhodecode) Kallithea, a member project of Software Freedom Conservancy, is a GPLv3'd, Free Software source code management system that supports two leading version control systems, Mercurial and Git, and has a web interface that is easy to use for users and admins.
* [Sourcehut](https://sourcehut.org/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) **+Mercurial** - (previously called sr.ht) This is an open source software suite for managing your software development projects.

### Ruby

* [GitLab](https://about.gitlab.com/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) - GitLab is the first single application for all stages of the DevOps lifecycle.

### Scala

* [GitBucket](https://gitbucket.github.io/) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) - A Git platform powered by Scala with easy installation, high extensibility & GitHub API compatibility.

## Hosted

Lie back and read the Terms & Conditions to see how they harvest your data.

* [Amazon CodeCommit](https://aws.amazon.com/codecommit/) - AWS CodeCommit is a fully-managed source control service that makes it easy for companies to host secure and highly scalable private Git repositories.
* [Atlassian BitBucket](https://bitbucket.org/) **+Mercurial** - From best-in-class integration with Jira to a better code review, Bitbucket Cloud gives your team everything you need to build, track, and deploy your software better.
* [Beanstalk](https://beanstalkapp.com/) **+Subversion** - A complete workflow to write, review & deploy code.
* [Canonical Launchpad](https://launchpad.net/) - Launchpad is a software collaboration platform.
* [GitLab](https://about.gitlab.com/) - GitLab is the first single application for all stages of the DevOps lifecycle.
* [Google Cloud Repositories](https://cloud.google.com/source-repositories/) - Google Cloud Source Repositories provides Git version control to support collaborative development of any application or service, including those that run on App Engine and Compute Engine.
* [Keybase](https://keybase.io/blog/encrypted-git-for-everyone) - Every now and then you want to make a repository that's private. Not for an open source project, but for other stuff: research, writing a novel, family history, or a community's private files.
* ~~[Phabricator](https://phacility.com/phabricator/) - Every application your project needs, all in one tool.~~ Effective June 1, 2021: Phabricator is no longer actively maintained.
* [Planio](https://plan.io/subversion-hosting-and-git-hosting/) **+Subversion** - Everybody likes Planio, but developers really love it! Not only because everything is well structured and easy to access, but also because your Planio account comes with unlimited hosted Git and Subversion repositories.
* [sr.ht](https://sr.ht) **+Mercurial** - Welcome to meta.sr.ht! This is the account, billing, and security management hub for sourcehut, the hacker's forge.
* [Tuleap](https://github.com/Enalean/tuleap) **+Subversion** - Tuleap Open ALM is a Libre and Open Source software forge crafted in PHP/MySQL.

## Peer-to-Peer

Fully independent from centralised hosts. Peer-to-Peer, hosted on each clients device. 

### Rust

* [Radicle](https://radicle.xyz/) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) - Radicle enables developers to securely collaborate on software over a peer-to-peer network built on Git.


Full credit for the initial idea and list goes to [sam_goody on HN](https://news.ycombinator.com/item?id=17254141).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Ian Channing](https://ianchanning.com) has waived all copyright and related or neighboring rights to this work.

