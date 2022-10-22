Here is Java's way to find this information.

Windows: javap -v <class> | findstr major
Unix: javap -v <class> | grep major

For example:
> javap -v Application | findstr major
  major version: 51
