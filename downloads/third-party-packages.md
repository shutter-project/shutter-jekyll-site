---
layout: page
---
### Third Party Packages

Shutter was relying on several outdated libraries for several years and therefore has been removed from most distribuitions' official repositories. By now it has been ported to GTK3 and can be packaged for repositories again but hasn't been picked up by many distributions yet. The following list shows how you can get Shutter for some distributions. Please report packages, which are not listed below, or errors on [Github](https://github.com/shutter-project/shutter/issues/new/choose) or via our [contact form](https://shutter-project.org/contact/).

#### Arch Linux

A [package for Arch Linux](https://archlinux.org/packages/community/any/shutter/) is available.

#### Debian

There are [official Debian packages](https://packages.debian.org/search?keywords=shutter&searchon=names&suite=all&section=all) available in the oldstable and oldoldstable distrubution (Stretch and Jessie).

You can install Shutter by using the package manager or the following command:

~~~
apt-get install shutter
~~~

For newer Debian versions Shutter is currently not available and needs to be installed from source.


#### Fedora

In Fedora 33 Shutter is available in the official repository, so just install it with:

~~~
dnf install shutter
~~~

In Fedora 34 Shutter can be installed using this [copr repository](https://copr.fedorainfracloud.org/coprs/geraldosimiao/shutter/).


#### Gentoo

Shutter is included in [Gentoo Portage](https://packages.gentoo.org/packages/x11-misc/shutter), so just install it with:

~~~
emerge shutter
~~~


#### Linux Mint

A [PPA by linuxuprising](https://www.linuxuprising.com/2018/10/shutter-removed-from-ubuntu-1810-and.html) is available.

#### Mageia

A [package for Mageia](https://madb.mageia.org/package/show/name/shutter) is available though it is outdated.

### Manjaro

A [package for Manjaro](https://manjaro.org/branch-compare/?query=shutter) is available.

#### openSUSE

[Packages for openSUSE](https://software.opensuse.org/package/shutter) are available though most of them are currently outdated.

#### PCLinuxOS

A [package for PCLinuxOS](https://pclinuxos.pkgs.org/rolling/pclinuxos-x86_64/shutter-0.94-1pclos2018.noarch.rpm.html) is available though it is currently outdated.

#### Red Hat Enterprise Linux (and Derivatives like CentOS, Scientific Linux etc.)

One of our users (Nux) provides a small repository for RHEL 7. The repository is designed to coexist with Fedora’s [EPEL repository](https://fedoraproject.org/wiki/EPEL/FAQ#What_is_EPEL.3F).
In order to add those repos to your system and install Shutter you can use the following commands:

~~~
rpm -Uvh http://download.fedoraproject.org/pub/epel/7/i386/epel-release-7-8.noarch.rpm

rpm -Uvh http://li.nux.ro/download/nux/dextop/el7/x86_64/nux-dextop-release-0-5.el7.nux.noarch.rpm

yum install shutter
~~~

For RHEL 7 and 8 Shutter can be installed using snap following [these instructions](https://snapcraft.io/install/shutter/rhel).

#### Slackware

A [package for Slackware](https://slackbuilds.org/repository/14.2/graphics/shutter/?search=shutter) is available.

#### Ubuntu

A [PPA by linuxuprising](https://www.linuxuprising.com/2018/10/shutter-removed-from-ubuntu-1810-and.html) is available. Also, the [official PPA](https://launchpad.net/~shutter/+archive/ubuntu/ppa) is now being maintained by the creator of Linuxuprising.com.


