# Adminer With Empty Passwords Allowed

> * Adminer 4.6.3 and newer does not support accessing a database without a password.
> * https://www.adminer.org/en/password/

For an pedagogic hack scenario, I needed a version of adminer that allowed empty passwords.

So, I removed the protection introduce in the 4.6.3 version and add un warning on the login form.

You can compile as per usual your own version:
```
Usage: php compile.php [editor] [driver] [lang]
$ php compile.php mysql en
...
adminer-mysql-en.php created (192627 B).
```
