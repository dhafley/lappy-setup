# lappy-setup
## Introduction

For years, I've setup basic templates and programs using a shell script.  This has worked well, and hasn't been a problem given the limited number of computers I've had to customize the last few years.

Starting a new job this week, felt like it was time to refresh this approach.  The motiviation started for me after reading [this](http://www.eightbitraptor.com/post/bootstrapping-osx-ansible) post.

This project attempts to setup basic configuration (vimrc, ssh config, etc), commonly used homebrew formulas, and homebrew casks.

## Getting Started 
The entry point into this application is bootstap.sh, which checks for the installation of ansible and then executes ansible the site playbook.

To configure, take a look at site.yml and confirm variables I have in place.  

Next, take a look at workstation/task/main.yml to see what is installed from homebrew and homebrew casks.

Please fork and submit pull requests!

