# aur-pkgbuilds

Please use the issue tracker to report any problems with my [AUR PKGBUILDs](https://aur.archlinux.org/packages/?SeB=m&K=aggraef).

The better the bug report, the easier it becomes for me to help and/or fix bugs. Please provide (at least) the following information:

* The name of the package you're trying to build, including version and revision information.

* The command you used to build or install the package (`yaourt`, `makepkg` etc.).

* The error message(s) you got.

* A full build log. You can create this, e.g., as follows:

    ```
    yaourt -F pkgname
    cd pkgname
    makepkg 2>&1 | tee pkgname.log
    ```
