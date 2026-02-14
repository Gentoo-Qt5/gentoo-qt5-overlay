# Gentoo Qt5 overlay

This **unofficial** overlay is dedicated to host ebuilds for packages relying on Qt5 that wont belong to `::gentoo` anymore.

Any new package is welcomed in this repository. All you have to do is to send a Pull Request.
Although, try to follow Gentoo main tree guidelines in your contributions.

## Install this overlay in your system

### Using `app-eselect/eselect-repository`

```
eselect repository add qt5 git https://github.com/Gentoo-Qt5/gentoo-qt5-overlay.git
```
### Installing in `/etc/portage/repos.conf/qt5.conf`
```
[qt5]
priority = 1000
location = /var/db/repos/qt5
sync-type = git
sync-uri = https://github.com/Gentoo-Qt5/gentoo-qt5-overlay.git
```
