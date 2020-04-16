Pacmerge
-----------------
    Small package manager based in blackman which download, compile and install packages from sources.

    This tool has several goals in mind:
        1. It does not depend on repository.
        2. Be always up to date, since packages builds from the very last PKGBUILD in master ArchBuildSystem (for now. Goal is
        allow to use more than one repository branch).
        3. Download from tool source.
        4. Compile the package.

Usage: blackman
---------------

OPTIONS:

    PACKAGES:
    -s <pkg>: search package
    -i <pkg>: download and compile package
    -g <group>: install all packages inside a blackarch group
    -a: install all packages from all groups

    REPOSITORY:
    -l: list blackarch groups
    -n: list native installed blackarch packages
    -p <group>: list packages from group
    -u: update blackarch repository
    -m: upgrade installed packages (-f to reinstall all)

    SORT TOOLS:
    -h: sort tools into main directory [~/haxx default]
    -D <dir>: change default main directory

    FLAGS:
    -f: force
