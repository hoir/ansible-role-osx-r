osx-r
=====

Installer for R and Rstudio on OS X.  Additionally installs `libssh2` and reinstalls `git2` with SSH enabled.

Requirements
------------

Requires Homebrew and Xcode.app to be installed beforehand.

Role Variables
--------------

- `rstudio_cask_name`: The cask to use for Rstudio.  Can be one of `rstudio` (stable), `rstudio-preview`, `rstudio-daily`.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - { role: hoir.osx-r, rstudio_cask_name: 'rstudio' }

License
-------

BSD

