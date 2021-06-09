# Description

We are a group of engineers that work in the IT industry. We have decided to
share some scripts and libraries.

Feel free to adapt this scripts and libraries to your needs.

Read [developer guide](./developers.md) for style conventions.

## Shell Scripts

- [sh-ocrpdf](https://github.com/openvirtus/sh-ocrpdf/) : If you can't copy paste from a PDF, run this script
  and problem solved. It uses OCR.
- [sh-hformat](https://github.com/openvirtus/sh-hformat) : Pendrive formater script.
- [sh-htabbed](https://github.com/openvirtus/sh-htabbed) : Run services in a window with tabs.
- [sh-hp](https://github.com/openvirtus/sh-hp/) : Your scripts search programs using PATH, and search for
  your projects using `hp`. If you have an script `deploy-website` and a project `~/projects/website`, use
  `hp website` in your script to search it.
- [sh-hsh](https://github.com/openvirtus/sh-hsh/) : Generate shell script bundles and execute them remotelly.
- [sh-hrun](https://github.com/openvirtus/sh-hrun/) : Run programs in custom sysroots, execute C programs as scripts.
- [sh-hsql](https://github.com/openvirtus/sh-hsql/) : SQL client wrapper for common operations.
- [sh-hnav](https://github.com/openvirtus/sh-hnav) : A wrapper around web browsers to expose same flags.
- [sh-hhttpd](https://github.com/openvirtus/sh-hhttpd) : A wrapper around minimalist HTTP servers. Good for testing.
- [sh-hemacs](https://github.com/openvirtus/sh-hemacs) : An script to configure GNU/Emacs editor.
- [sh-hprofile](https://github.com/openvirtus/sh-hprofile) : Interactive terminal environment configurator.
- [sh-hcapw](https://github.com/openvirtus/sh-hcapw) : Capture Wireshark captures in a remote server.
- [sh-hburn](https://github.com/openvirtus/sh-hburn) : This script extracts the image and burns it to disk.
- [sh-htrash](https://github.com/openvirtus/sh-htrash) : Move to trash from the terminal.
- [sh-hbackup](https://github.com/openvirtus/sh-hbackup) : Backup mechanism.
- [sh-hbackup-ssh](https://github.com/openvirtus/sh-hbackup-ssh) : Connect to a server using SSH and get backups.
- [sh-hbackup-hsql](https://github.com/openvirtus/sh-hbackup-hsql) : Create backups of databases.
- [sh-hmail](https://github.com/openvirtus/sh-hmail) : Mail configuration utility. (mailx, mail, msmtp, mbsync, mu, mu4e)
- [sh-hdocker](https://github.com/openvirtus/sh-hdocker) : Docker helper commands.
- [sh-hutil](https://github.com/openvirtus/sh-hutil) : Utility library to write SH programs.
- [sh-hcfg](https://github.com/openvirtus/sh-hcfg) : Configuration reading script.
- [sh-hgencrt](https://github.com/openvirtus/sh-hgencrt) : SSL certificate managing system.
- [sh-create](https://github.com/openvirtus/sh-create) : Template mechanism.
- [sh-document](https://github.com/openvirtus/sh-document) : Paperwork managing toolchain.
- [sh-hfile](https://github.com/openvirtus/sh-hfile) :
- [sh-w](https://github.com/openvirtus/sh-w) : Store functions to later call in your shell.
- [sh-xmenu](https://github.com/openvirtus/sh-xmenu) : An application menu implemented with dmenu.
- [sh-cbuild](https://github.com/openvirtus/sh-cbuild) : Minimalist C project build tool.
- [sh-hcookies](https://github.com/openvirtus/sh-hcookies) : Extract cookies from firefox to wget.
- [sh-hburn-pendrive-sysadmin-windows](https://github.com/openvirtus/sh-hburn-pendrive-sysadmin-windows) : 
- [sh-ssh-sudoinit](https://github.com/openvirtus/sh-ssh-sudoinit) : Initial sudo setup in a server.
- [sh-hqemu](https://github.com/openvirtus/sh-hqemu) : Qemu virtual machines.
- [sh-hpamctl](https://github.com/openvirtus/sh-hpamctl) : Manage users and services using PAM.
- [sh-srv-void](https://github.com/openvirtus/sh-srv-void) : Some script to administer Void Linux systems.
- [sh-srv-freebsd](https://github.com/openvirtus/sh-srv-freebsd) : Some script to administer FreeBSD systems.
- [sh-hrest](https://github.com/openvirtus/sh-hrest) : A wrapper around curl and jq.
- [sh-hopensmtpd](https://github.com/openvirtus/sh-hopensmtpd) : OpenSMTPD daemon configuration tool.
- [sh-hbind9](https://github.com/openvirtus/sh-hbind9) : BIND9 daemon configuration tool.
- [sh-hapache](https://github.com/openvirtus/sh-hapache) : Apache daemon configuration tool.
- [sh-hmonero](https://github.com/openvirtus/sh-hmonero) : Monero wallet and minining installation tools.
- [sh-hgit](https://github.com/openvirtus/sh-hgit) : GIT utilities.
- [sh-hvnc](https://github.com/openvirtus/sh-hvnc) : VNC launchers.
- [sh-srv-www](https://github.com/openvirtus/sh-srv-www) : Tools to configure Wordpress etc.
- [sh-hinvoice](https://github.com/openvirtus/sh-hinvoice) : Create invoices from the terminal.
- [sh-hlicense](https://github.com/openvirtus/sh-hlicense) : Software license and readme generator.
- [sh-hxdg](https://github.com/openvirtus/sh-hxdg) : Link uris to programs from the terminal.

TCL

- [sh-htcl](https://github.com/openvirtus/sh-htcl) : Utilities to manage Tcl/tk projects.
- [tcl-trest]() :
- [tcl-tstripe]() :


## Minimalist C libraries.

- [c-asprintfa](https://github.com/openvirtus/c-asprintfa) : Sprintf to the stack. [Single .h]
- [c-fopenread](https://github.com/openvirtus/c-fopenread) : Read a file to a buffer. [Single .h]
- [c-libmerr](https://github.com/openvirtus/c-libmerr) : Error reporting mechanism ideal for libraries. [Single .h]
- [c-fgetpw](https://github.com/openvirtus/c-fgetpw) : Read password from the terminal. [Single .h]
- [c-ftemplate](https://github.com/openvirtus/c-ftemplate) : Simple C templating mechanism. [Single .h]
- [c-fembed](https://github.com/openvirtus/c-fembed) : Embed files in C programs and libraries. [Single .h]
- [c-fexec](https://github.com/openvirtus/c-fexec) : A better option than popen. [Single .h]
- [c-libjdb](https://github.com/openvirtus/c-libjdb) : Simple JSON based database library.
- [c-string-random](https://github.com/openvirtus/c-string-random) : Generate random strings in C. [Single .h]
- [c-string-mapping](https://github.com/openvirtus/c-string-mapping) : C string mappings. [Single .h]
- [c-string-password](https://github.com/openvirtus/c-string-password) : Password string related functions. [Single .h]
- [c-string-email](https://github.com/openvirtus/c-string-email) : Email string related functions. [Single .h]
- [c-string-extra](https://github.com/openvirtus/c-string-extra) : string/trim.h string/cstr.h string/nl.h
- [c-string-enum](https://github.com/openvirtus/c-string-enum) : Create named enumerations. [Single .h]
- [c-balloc](https://github.com/openvirtus/c-balloc) : Like malloc but on a buffer. [Single .h]
- [c-ipc-mq](https://github.com/openvirtus/c-ipc-mq) : A wrapper around SysV message queues. [Single .h]
- [c-ipc-usock](https://github.com/openvirtus/c-ipc-usock) : Datagram Unix sockets. [Single .h]
- [c-ipc-shm](https://github.com/openvirtus/c-ipc-shm) : Shared memory. [Single .h]
- [c-ipc-sem](https://github.com/openvirtus/c-ipc-sem) : Semaphore wrapper c library. [Single .h]
- [c-libcfgrc](https://github.com/openvirtus/c-libcfgrc) : Read configuration from a shell script. [Single .h]
- [c-jansson-extra](https://github.com/openvirtus/c-jansson-extra) : Some extra jansson functions. [Single .h]
- [c-stdio-extra](https://github.com/openvirtus/c-stdio-extra) : Extra stdio-like functions. errorf(). [Single .h]
- [c-rig3](https://github.com/openvirtus/c-rig3) : Random Identity Generator Version 3.

## Donations:

<ul>
<li>
<a href="https://openvirtus.github.io/files/1C1ZzDje7vHhF23mxqfcACE8QD4nqxywiV.png">[QR]</a>
<img height="20" style="max-height:1em;max-width:1em" src="https://openvirtus.github.io/files/btc.png">
Bitcoin <code>1C1ZzDje7vHhF23mxqfcACE8QD4nqxywiV</code>
</li>
<li>
<a href="https://openvirtus.github.io/files/bnb194ay2cy83jjp644hdz8vjgjxrj5nmmfkngfnul.png">[QR]</a>
<img height="20" style="max-height:1em;max-width:1em" src="https://openvirtus.github.io/files/bnb.svg">
Binance <code>bnb194ay2cy83jjp644hdz8vjgjxrj5nmmfkngfnul</code>
</li>
<li>
<a href="https://openvirtus.github.io/files/88JP1c94kDEbyddN4NGU574vwXHB6r3FqcFX9twmxBkGNSnf64c5wjE89YaRVUk7vBbdnecWSXJmRhFWUcLcXUTFJVddZti.png">[QR]</a>
<img height="20" style="max-height:1em;max-width:1em" src="https://openvirtus.github.io/files/xmr.svg">
Monero <code>88JP1c94kDEbyddN4NGU574vwXHB6r3FqcFX9twmxBkGNSnf64c5wjE89YaRVUk7vBbdnecWSXJmRhFWUcLcXUTFJVddZti</code>
</li>
</ul>
