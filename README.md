Lnux/unix security auditing scripts "Lusas"
============================================
This is a collection of command line security auditing scripts for Linux/Unix. 
Originally by Sean Boran in 2000, Pablo Endres took over the project in 2008.

License: **GPL v3.0**

Please share any fixes/improvements you make, if possible. Or help with documentation.
Starting Points 
* https://github.com/epablosensei/lusas/
* https://www.pabloendres.com/tools/
* Also http://boran.com/audit

### USAGE:
./lusas-basic.sh [option]

**OPTIONS:**
```shell
   -h	Show this message
   -d	email or emails where to send the results. i.e.: a@example.com,b@example.com,root
   -e	Extended.  Collect a copy of files
   -s	Verify package checksums
   -l	Don't clean up after run. Leave the directory with the results on disk.
   -c	Cleanup after run, leave nothing behind.

	If neither -l or -c are not set a .tar.gz file with the result will be left on disk.
```



