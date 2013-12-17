Domeny.pl PHP CodeSniffer Coding Standard
========================================


Installation
------------

1. Install phpcs:

        pear install PHP_CodeSniffer

2. Find your PEAR directory:

        pear config-show | grep php_dir

3. Copy, symlink or check out this repo to a folder called DomenyPl inside the
   phpcs `Standards` directory:

        cd /path/to/pear/PHP/CodeSniffer/Standards
        git clone git://github.com/etechnika/Domeny.pl-coding-standard.git DomenyPl

4. Set Symfony2 as your default coding standard:

        phpcs --config-set default_standard DomenyPl

5. ...

6. Profit!

        cd /path/to/my/project
        phpcs
        phpcs path/to/my/file.php


