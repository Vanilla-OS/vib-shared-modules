# Vib Shared Modules

A repository containing user submitted vib modules, intended to be used inside vib recipes

A module may contain extra information on how to use it

# Usage
a module can simply be included like this:
```
modules:
	- gh:Vanilla-OS/vib-shared-modules:main:<module directory>/<filename>.yml
```

# Submitting new modules

Make a pull request adding your module in its own directory, also add your username and the directory to the CODEOWNERS file

View extra information in the wiki page of this repo

## Note on security

All added modules and their plugins are reviewed by @axtloss before being merged or updated, this ONLY includes the module definitions, there are no guarantees that any software plugins fetch or add are safe.
