Pk/upk grew out of inconvenience of working with existing zoo of archivers
that have widely varying cmdline interfaces and different conventions.

Pk/upk provide a simple common interface to all .tar\*, .zip, .7z, winmail.dat,
.deb, .rpm, .apk, etc.

To put all text files to my.tar.gz (under folder my/):
```
$ pk my.tar.gz *.txt
```
To put directory `dir` into `dir.tgz` just do
```
$ pk dir.tgz
```

To extract files from my.tar.gz to folder my/ (optionally creating it
if it's missing in .tar.gz):
```
$ upk my.tar.gz
$ ls my/
```

TODO:
* support more popular formats (e.g. from http://en.wikipedia.org/wiki/List_of_archive_formats)
* options (e.g. override destination dir, force unnesting, -h, options for archiver, etc.)
* support .gz files (?)
* shell autocompletions

