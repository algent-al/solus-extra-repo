## solus-extra-repo
This is an extra repository for Solus for private use. These packages are not official and not supported by Solus Core team.

## Add the repo
`sudo eopkg ar Extra https://github.com/algent-al/solus-extra-repo/raw/master/packages/eopkg-index.xml.xz`

## Enable the repo
`sudo eopkg enable-repo Extra`

## Installing the packages
Open Software Center and wait untill `eopkg-index.xml.xz` is updated.
Search for the package name and then install click install.

## Remove the Repo
`sudo eopkg remove-repo Extra`

## Disable the Repo
`sudo eopkg disable-repo Extra`
