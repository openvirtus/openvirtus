# Description

We are a group of engineers that work in the IT industry. We have decided to
share some scripts and libraries.

## Shell Scripts

- [sh-ocrpdf](https://github.com/openvirtus/sh-ocrpdf/) : If you can't copy paste from a PDF, run this script
  and problem solved. It uses OCR.
- [sh-hp](https://github.com/openvirtus/sh-hp/) : Your scripts search programs using PATH, and search for
  your projects using `hp`. If you have an script `deploy-website` and
  a project `~/projects/website`, use `hp website` in your script to
  search it.
- [sh-hreadme](https://github.com/openvirtus/sh-hreadme/) : Generate readmes.
- [sh-hsh](https://github.com/openvirtus/sh-hsh/) : Generate shell script bundles and execute them remotelly.
- [sh-hclip](https://github.com/openvirtus/sh-hclip/) : Manage clipboard and take screenshots from the terminal.
- [sh-hpkg](https://github.com/openvirtus/sh-hpkg/) : Toolchain agnostic tar.gz based package manager.
- [sh-hrun](https://github.com/openvirtus/sh-hrun/) : Run programs in custom sysroots, execute C programs as scripts.
- [sh-hssh-pipe](https://github.com/openvirtus/sh-hssh-pipe/) : SSH tunnels to servers.
- [sh-hsql](https://github.com/openvirtus/sh-hsql/) : SQL client wrapper for common operations.
- [sh-hnav](https://github.com/openvirtus/sh-hnav) : A wrapper around web browsers to expose same flags.
- [sh-hhttpd](https://github.com/openvirtus/sh-hhttpd) : A wrapper around minimalist HTTP servers. Good for testing.
- [sh-hemacs](https://github.com/openvirtus/sh-hemacs) : An script to configure GNU/Emacs editor.
- [sh-hprofile](https://github.com/openvirtus/sh-hprofile) : Interactive terminal environment configurator.
- [sh-hformat](https://github.com/openvirtus/sh-hformat) : Pendrive formater script.
- [sh-hiso](https://github.com/openvirtus/sh-hiso) : Operating system ISO and IMG handler.
- [sh-hmd](https://github.com/openvirtus/sh-hmd) : Extract information from tables in md files.
- [sh-hcapw](https://github.com/openvirtus/sh-hcapw) : Capture Wireshark captures in a remote server.
- [sh-hburn](https://github.com/openvirtus/sh-hburn) : This script extracts the image and burns it to disk.
- [sh-hcontact](https://github.com/openvirtus/sh-hcontact) : Manage your contacts from the terminal.
- [sh-genh](https://github.com/openvirtus/sh-genh) : Generate header files from C source files.
- [sh-hback](https://github.com/openvirtus/sh-hback) : Backup mechanism good to backup family photos and videos.
- [sh-htrash](https://github.com/openvirtus/sh-htrash) : Move to trash from the terminal.
- [sh-hbackup](https://github.com/openvirtus/sh-hbackup) : Backup mechanism.
- [sh-hbackup-ssh](https://github.com/openvirtus/sh-hbackup-ssh) : Connect to a server using SSH and get backups.
- [sh-hbackup-hsql](https://github.com/openvirtus/sh-hbackup-hsql) : Create backups of databases.
- [sh-hmail](https://github.com/openvirtus/sh-hmail) : Mail configuration utility. (mailx, mail, msmtp, mbsync, mu, mu4e)
- [sh-hdocker](https://github.com/openvirtus/sh-hdocker) : Docker helper commands.
- [sh-rig3](https://github.com/openvirtus/sh-rig3) : RiG (Random Identity generator) implemented in shell language.
- [sh-hipfs](https://github.com/openvirtus/sh-hipfs) : An easy way for scripts to download needed files from IPFS. 
- [sh-hxdg](https://github.com/openvirtus/sh-hxdg) : Assign mimes to programs and create links to "start menu".
- [sh-cbuild](https://github.com/openvirtus/sh-cbuild) : Minimalist C project build tool.
- [sh-hcfg](https://github.com/openvirtus/sh-hcfg) : Configuration reading script.
- [sh-hhelp](https://github.com/openvirtus/sh-hhelp) : List little summary of your scripts.
- [sh-hutil](https://github.com/openvirtus/sh-hutil) : Utility library to write SH programs.
- [sh-shbuild](https://github.com/openvirtus/sh-shbuild) : Packaging mechanism for SH projects.
- [sh-hmem](https://github.com/openvirtus/sh-hmem) : Take and access notes from the terminal.
- [sh-hmachines](https://github.com/openvirtus/sh-hmachines) : Keep track of your machines.

## Minimalist C libraries.

- [c-libcfgrc](https://github.com/openvirtus/c-libcfgrc) : A single .h header SH language configuration file reader for the C language.
- [c-asprintfa](https://github.com/openvirtus/c-asprintfa) : Sprintf to the stack.
- [c-bprompt](https://github.com/openvirtus/c-bprompt) : Interactive input to a buffer.
- [c-fexec](https://github.com/openvirtus/c-fexec) : Execute a command and wait for its output. Like popen with sane arguments separation.
- [c-fopenread](https://github.com/openvirtus/c-fopenread) : Read a file to a buffer.
- [c-ftemplate](https://github.com/openvirtus/c-ftemplate) : Simple C templating mechanism.
- [c-strcpy-escaped](https://github.com/openvirtus/c-strcpy-escaped) : Escape characters with a prefix when copying.
- [c-libhlang](https://github.com/openvirtus/c-libhlang) : C internationalization library.
- [c-fembed](https://github.com/openvirtus/c-fembed) : Embed files in C programs and libraries.
- [c-libmcmd](https://github.com/openvirtus/c-libmcmd) : CLI library.
- [c-libmerr](https://github.com/openvirtus/c-libmerr) : Error reporting mechanism ideal for libraries. [Single .h]
- [c-libudb](https://github.com/openvirtus/c-libudb) : Small key-value database based on GDBM to save C structures.
- [c-string-random](https://github.com/openvirtus/c-string-random) : Generate random strings in C. [Single .h]
- [c-string-extra](https://github.com/openvirtus/c-string-extra) : trim.h
- [c-string-email](https://github.com/openvirtus/c-string-email) : Email string related functions. [Single .h]
- [c-string-password](https://github.com/openvirtus/c-string-password) : Password string related functions. [Single .h]
- [c-ipc-sem](https://github.com/openvirtus/c-ipc-sem) : Semaphore wrapper c library. [Single .h]
- [c-libucsv](https://github.com/openvirtus/c-libucsv) : Locked csv access library.
