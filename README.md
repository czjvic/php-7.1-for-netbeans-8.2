# Enable support of PHP 7.1 in Netbeans 8.2

1) Install standard Netbeans 8.2 or use your current installation
2) Backup your Netbeans 8.2 folder
3) Backup your Netbeans 8.2 settings folder (optional)
4) Download nightly build of netbeans http://bits.netbeans.org/download/trunk/nightly/latest/
5) Install downloaded nightly build
6) Copy <netbeans_nightly_build_dir>/php to <netbeans_8.2_dir>/php (allow overwrite all of files)
7) Copy <netbeans_8.2_backup_dir>/php/modules/org-netbeans-modules-spellchecker-bindings-php.jar to <netbeans_8.2>/php/modules/org-netbeans-modules-spellchecker-bindings-php.jar (allow overwrite of the file)
8) Copy <netbeans_8.2_backup_dir>/php/modules/org-netbeans-modules-spellchecker-twig.jar to <netbeans_8.2>/php/modules/org-netbeans-modules-twig-php.jar (allow overwrite of the file)
9) Run Netbeans 8.2. Now you will see standard Netbeans 8.2 and in project settings you can set support for PHP 7.1


