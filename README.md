### solus-extra-repo
This is an extra repository for Solus and is for private use. These packages are not official and not supported by Solus Core team.
The main purpose of this repo is to test applications before including them in Official Repo. Some of them are not accepted or not have been asked yet for inclusion. This repo is for open source or distributable packages.

### Add the repo
`sudo eopkg ar Extra https://github.com/algent-al/solus-extra-repo/raw/master/packages/eopkg-index.xml.xz`

### Enable the repo
`sudo eopkg enable-repo Extra`

### Installing the packages
Open Software Center and wait untill `eopkg-index.xml.xz` is updated.
Search for the package name and then click install.

### Disable the Repo
`sudo eopkg disable-repo Extra`

### Remove the Repo
`sudo eopkg remove-repo Extra`

### Packages info. Thanks to [Repology](https://repology.org) is been possible to track upstream versions. 

| Package | Upstream Version | Repo Version |
| --- | --- | --- |
| bandwich | ![](https://repology.org/badge/latest-versions/bandwhich.svg?header=) | 0.13.0 |
| bibata-cursors | ![](https://repology.org/badge/latest-versions/bibata-cursors.svg?header=) | 0.4.2 |
| budgie-extras | ![](https://repology.org/badge/latest-versions/budgie-extras.svg?header=) | 1.0.0 |
| crond | ![](https://repology.org/badge/latest-versions/dcron.svg?header=) | 4.5 |
| font-caskaydia-cove-nerd-ttf | ![](https://repology.org/badge/latest-versions/fonts:nerd-fonts.svg?header=) | 2.1.0 |
| gst | ![](https://repology.org/badge/latest-versions/gst.svg?header=) | 0.7.1 |
| gti | ![](https://repology.org/badge/latest-versions/gti.svg?header=) | 1.7.0 |
| layan-gtk-theme | ![](https://repology.org/badge/latest-versions/layan-gtk-theme.svg?header=) | 20200319 |
| lsd | ![](https://repology.org/badge/latest-versions/lsd.svg?header=) | 0.16.0 |
| mcmojave-cursors | ![](https://repology.org/badge/latest-versions/mcmojave-cursors.svg?header=) | 20200207 |
| odrive | ![](https://repology.org/badge/latest-versions/odrive-google-drive-client.svg?header=) | 0.3.0 |
| pdfarranger | ![](https://repology.org/badge/latest-versions/pdfarranger.svg?header=) | 1.4.2 |
| pocillo-gtk-theme | ![](https://repology.org/badge/latest-versions/pocillo-gtk-theme.svg?header=) | 0.6 |
| pytest-asyncio | ![](https://repology.org/badge/latest-versions/python:pytest-asyncio.svg?header=) | 0.10.0 |
| pytest-isort | ![](https://repology.org/badge/latest-versions/python:pytest-isort.svg?header=) | 0.3.1 |
| python-cairocffi | ![](https://repology.org/badge/latest-versions/python:cairocffi.svg?header=) | 1.1.0 |
| python-cairosvg | ![](https://repology.org/badge/latest-versions/python:cairosvg.svg?header=) | 2.4.2 |
| python-capturer | ![](https://repology.org/badge/latest-versions/python:capturer.svg?header=) | 3.0 |
| python-coloredlogs | ![](https://repology.org/badge/latest-versions/python:coloredlogs.svg?header=) | 14.0 |
| python-cssselect2 | ![](https://repology.org/badge/latest-versions/python:cssselect2.svg?header=) | 0.3.0 |
| python-humanfriendly | ![](https://repology.org/badge/latest-versions/python:humanfriendly.svg?header=) | 8.1 |
| python-injector | ![](https://repology.org/badge/latest-versions/python:injector.svg?header=) | 0.18.3 |
| python-pikepdf | ![](https://repology.org/badge/latest-versions/python:pikepdf.svg?header=) | 1.10.4 |
| python-rx | ![](https://repology.org/badge/latest-versions/python:rx.svg?header=) | 3.1.0 |
| python-setuptools-scm-git-archive | ![](https://repology.org/badge/latest-versions/python:setuptools-scm-git-archive.svg?header=) | 1.1 |
| python-svgwrite | ![](https://repology.org/badge/latest-versions/python:svgwrite.svg?header=) | 1.3.1 |
| python-tinycss2 | ![](https://repology.org/badge/latest-versions/python:tinycss2.svg?header=) | 1.0.2 |
| python-wordcloud | ![](https://repology.org/badge/latest-versions/python:wordcloud.svg?header=) | 1.6.0 |
| qogir-gtk-theme | ![](https://repology.org/badge/latest-versions/qogir-theme.svg?header=) | 2019.10.25 |
| slaze-grub-theme | ![](https://repology.org/badge/latest-versions/grub-theme-slaze.svg?header=) | 2019.08.24 |
| stylish-grub-theme | ![](https://repology.org/badge/latest-versions/grub-theme-stylish.svg?header=) | 2019.08.24 |
| tela-grub-theme | ![](https://repology.org/badge/latest-versions/grub-theme-tela.svg?header=) | 2019.08.24 |
| timeshift | ![](https://repology.org/badge/latest-versions/timeshift.svg?header=) | 20.03 |
| variety-slideshow | ![](https://repology.org/badge/latest-versions/variety-slideshow.svg?header=) | 0.1 |
| vimix-grub-theme | ![](https://repology.org/badge/latest-versions/grub-theme-vimix.svg?header=) | 2019.08.24 |
| wavemon | ![](https://repology.org/badge/latest-versions/wavemon.svg?header=) | 0.9.1 |
| wmctrl | ![](https://repology.org/badge/latest-versions/wmctrl.svg?header=) | 1.07 |

### Budgie-extras

Applets from [budgie-extras](https://github.com/UbuntuBudgie/budgie-extras) are splited in separate packages.  
Latest stable version of budgie-extras is 1.0.0.

### Current status of applets

- [x] budgie-app-launcher
- [x] budgie-applications-menu
- [x] budgie-brightness-controller (renamed to budgie-brightness-controll)
- [x] budgie-clockworks
- [x] budgie-countdown (Official Repo)
- [x] budgie-dropby
- [x] budgie-fuzzyclock
- [x] budgie-hotcorners
- [x] budgie-kangaroo (Official Repo)
- [x] budgie-keyboard-autoswitch
- [ ] budgie-network-manager
- [x] budgie-quicknote (Official Repo)
- [x] budgie-recentlyused
- [x] budgie-rotation-lock
- [x] budgie-showtime
- [x] budgie-takeabreak (Official Repo)
- [x] budgie-trash (renamed to budgie-another-trash)
- [x] budgie-visualspace
- [x] budgie-weathershow (Official Repo)
- [x] budgie-window-mover
- [x] budgie-wallpaper-switcher
- [x] budgie-workspace-overview
- [x] budgie-workspace-stopwatch


### These are standalone apps
- [x] budgie-extras-daemon (Official Repo)
- [x] budgie-previews
- [x] budgie-quickchar
- [ ] budgie-wallstreet
- [x] budgie-windows-shuffler (Official Repo)

