# Adminer With Empty Passwords Allowed

> * Adminer 4.6.3 and newer does not support accessing a database without a password.
> * https://www.adminer.org/en/password/

For an pedagogic hack scenario, I needed a version of adminer that allowed empty passwords.

So, I removed the protection introduce in the 4.6.3 version and add un warning on the login form.

You can compile as per usual your own version:

```bash
$ git clone --recurse-submodules https://github.com/FrancoisCapon/AdminerWithEmptyPasswordsAllowed.git
$ cd AdminerWithEmptyPasswordsAllowed
$ php compile.php mysql en # Usage: php compile.php [editor] [driver] [lang]
adminer-mysql-en.php created (215189 B).
```

This version also fix the suppression of `git://` protocol for the submodules (https://github.com/vrana/adminer/pull/462).
