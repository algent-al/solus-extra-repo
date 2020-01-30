## solus-extra-repo
This is an extra repository for Solus for private use. These packages are not official and not supported by Solus Core team.
"This repo is for open source or distributable packages"

## Add the repo
`sudo eopkg ar Extra https://github.com/algent-al/solus-extra-repo/raw/master/packages/eopkg-index.xml.xz`

## Enable the repo
`sudo eopkg enable-repo Extra`

## Installing the packages
Open Software Center and wait untill `eopkg-index.xml.xz` is updated.
Search for the package name and then install click install.

## Disable the Repo
`sudo eopkg disable-repo Extra`

## Remove the Repo
`sudo eopkg remove-repo Extra`

## PACKAGES INFO

There are some packages that are not yet or refused to be included by Official Solus Repository.

| No | Package name | Status |  
| --- | --- | --- |  
| 1 | crond | Deprecated |  
| 2 | lsd | Not requested yet |  
| 3 | mojave-gtk-theme | Awaiting for review |  
| 4 | numlockx | Not accepted |  
| 5 | pdfarranger | Not accepted |  
| 6 | python-pikepdf | Not requested yet |  
| 7 | python-setuptools-scm-git-archive | Not requested yet |  
| 8 | qogir-gtk-theme | Not accepted |  
| 9 | timeshift | Not accepted |  
| 10 | variety-slideshow | Not accepted |  
| 11 | wavemon | Not accepted |  


