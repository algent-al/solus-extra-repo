## solus-extra-repo
This is an extra repository for Solus for private use. These packages are not official and not supported by Solus Core team.
"This repo is for open source or distributable packages".

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

| Package name |  Status |  
| --- | --- |  
| crond | Deprecated |  
| figlet | Not accepted |  
| gti | Not requested |  
| lsd | Not requested |  
| numlockx | Not accepted |  
| pdfarranger | Not accepted |  
| python-pikepdf | Not requested yet |  
| python-setuptools-scm-git-archive | Not requested yet |  
| qogir-gtk-theme | Not accepted |  
| timeshift | Not accepted |  
| variety-slideshow | Not accepted |  
| wavemon | No maintainer yet |  
| python-typing-extensions | Accepted but not in Repo |

