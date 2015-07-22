# Obdi

## Screenshot

![](images/obdi-0.1.3.png?raw=true)

More pics here: http://blogger.smorg.co.uk/2015/01/obdi-in-pictures.html

## What is it?

Obdi is an extendable graphical user interface for running scripts on
remote servers.  The most basic installation provides administrative tools to
manage users, data centres and environments, and includes a job manager.

## Status

Alpha - for test environments.

## Features

* All GUI items in the screen shot are implemented using plugins.
* Plugins can be REST end-points - they can be used for automation.
* The saltconfigserver plugin contains a number of REST end-points, including an External Node Classifier (ENC).

## Architecture

* Google Go for the back end REST interface.
* Angular JS and bootstrap for the front end.
* Sqlite3 used for data storage.
* Obdi simply runs scripts on remote servers, so it can be used for lots of different tasks.

## Plugins

| Name/Link          | Description  |
|--------------------|-------------------------------------------------------|
| [Obdi Core Plugins](https://github.com/mclarkson/obdi-core-repository.git) | The Obdi job viewer plugin. |
| [Salt Stack Plugins](https://github.com/mclarkson/obdi-salt-repository.git) | Plugins for managing Salt Stack. |
| LXC Plugins       | Plugins for creating Linux containers in a cluster.<br> Supports running Docker containers inside Linux containers. |

## Documentation

### About

[About Plugins](https://github.com/mclarkson/obdi/blob/master/doc/plugins.md)

### Installation

[Installing Obdi Core on Ubuntu](https://github.com/mclarkson/obdi/blob/master/doc/ubuntu_install.md)

[Complete Guide for Installing Obdi and Salt Stack Plugins on Ubuntu Trusty](https://github.com/mclarkson/obdi-salt-repository/blob/master/docs/ubuntu_guide.md)

[Complete Guide for Installing Obdi and Salt Stack Plugins on Centos 6](https://github.com/mclarkson/obdi-salt-repository/blob/master/docs/centos_guide.md)

### Building

[RedHat/CentOS Building from Source](https://github.com/mclarkson/obdi/blob/master/doc/redhat_build.md)

