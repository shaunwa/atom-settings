To update the packages list when you add a new package:
`apm list --installed --bare > ~/.atom/package.list`

To install the packages on another computer when updated:
`apm install --packages-file ~/.atom/package.list`
