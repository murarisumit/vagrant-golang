# Vagrant with golang environment

Simple golang development environment for Vagrant.

## Overview

This project aims to facilitate the use of ``golang`` avoiding Operative System dependence issues, in this way we can focus on our development rather than installation configuration issues. You should be note that it is a project aimed at beginner developer **so you do not expect anything advanced**.


**Tools which will be installed on the box**

* [Ubuntu 16.04 LTS](http://releases.ubuntu.com/16.04/)
* [Golang 1.8](https://golang.org/dl/)
* [Vagrant](https://www.vagrantup.com/)


> **Go**, also commonly referred to as golang, is a programming language developed at Google in 2007 by [Robert Griesemer](https://en.wikipedia.org/wiki/Robert_Griesemer), [Rob Pike](https://en.wikipedia.org/wiki/Rob_Pike), and [Ken Thompson](https://en.wikipedia.org/wiki/Ken_Thompson). Designed primarily for systems programming, it is a compiled, statically typed language in the tradition of C and C++, with garbage collection, various safety features and [CSP](https://en.wikipedia.org/wiki/Communicating_sequential_processes)-style [concurrent programming](https://en.wikipedia.org/wiki/Concurrent_programming) features added.



> **Vagrant** is computer software that creates and configures virtual [development environments](1). It can be seen as a higher-level [wrapper](2) around virtualization software such as [VirtualBox](3), [VMware](4), [KVM](5) and [Linux Containers](6) (LXC), and around configuration management software such as [Ansible](7), [Chef](8), [Salt](9), and [Puppet](10).

> Source: [Wikipedia](8)
    
[1]: https://en.wikipedia.org/wiki/Development_environment_(software_development_process)
[2]: https://en.wikipedia.org/wiki/Wrapper_library
[3]: https://en.wikipedia.org/wiki/VirtualBox
[4]: https://en.wikipedia.org/wiki/VMware
[5]: https://en.wikipedia.org/wiki/Kernel-based_Virtual_Machine
[6]: https://en.wikipedia.org/wiki/Linux_Containers
[7]: https://en.wikipedia.org/wiki/Ansible_(software)
[8]: https://en.wikipedia.org/wiki/Chef_(software)
[9]: https://en.wikipedia.org/wiki/Salt_(software)
[10]: https://en.wikipedia.org/wiki/Puppet_(software)
[11]: https://en.wikipedia.org/wiki/Vagrant_(software)

**Table of Contents**

- [Requirements](#require)
- [Quickstart](#quickstart)

## <a name="require">Requirements</a>

1. You must have installed [Vagrant](http://www.vagrantup.com/downloads.html)
2. And [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

## <a name="quickstart"></a>Quickstart

First at all clone our vagrant repository:

``` bash
$ git clone https://github.com/sumit-murari/vagrant-golang.git
```

After that you can run your vagrant machine:

```
$ vagrant up 
```
WORKSPACE is: `/vagrant/go`


## Feedback

Feedback is more than welcome; I probably got some things wrong so please tell me about it.


## Reference

[https://github.com/ivan-iver/vagrant-golang.git](https://github.com/ivan-iver/vagrant-golang.git)
