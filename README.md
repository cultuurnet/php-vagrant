# Introduction

This contains a PHP development kit a Vagrant box.

# Requirements

You need a recent Vagrant install (>= 1.7.0).

# Installation instructions

```
vagrant up
```

This will create a basic box with PHP installed.

Mailcatcher is installed and PHP is configured to use it.
The Mailcatcher web interface is available at:

[http://localhost:1080](http://localhost:1080)

The directory `source` on the host is an NFS synced folder to `/home/vagrant/source` in the box.
Any files you drop in there will be available in the box under that directory.
