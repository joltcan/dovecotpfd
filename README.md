# dovecotpfd

Fork of the dovecot-sqlite password change plugin as described in [the forum](http://www.roundcubeforum.net/index.php?topic=8848.0)

# config
Add this to the password/config.inc.php file

```
// Dovecot Password File Driver options
// -----------------------------------------
// Specify the username format used in the passwd/userdb file (valid values are &quot;%n&quot; or &quot;%u&quot;, corresponding to Dovecots %n and %u variables - see: http://wiki.dovecot.org/Variables)
//$rcmail_config['password_dovecotpfd_format'] = "&quot;%n&quot;";
// Desired password hashing scheme (run doveadm pw -l for a list of supported schemes on your system)
$rcmail_config['password_dovecotpfd_scheme'] = "SSHA256";
```
