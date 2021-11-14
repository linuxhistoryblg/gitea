Run A Self Hosted GIT Service

Collaboration between developers necessitates some form of Source Code Management. The Linux Kernel’s SCM had received 6,400 commits from 1,175 different contributors in the last 30 days at the time this article was written. Managing this many contributions from so many different sources would not have been possible without GIT, a tool created by Torvalds in 2005 for that exact purpose.

Smaller projects require SCM as well, even if the developers involved with the project are sitting in the same room. Gitea provides a fast and painless way to self-host a GIT service with a web interface for small teams needing SCM. It’s written in Google’s Go programming language and will run anywhere Go will compile.

Gitea provides several wonderful packaged installation options for various platforms, however the automation provided here will install and run Gitea on RHEL/Centos/Fedora.
