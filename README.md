## What is getSoftware ?

It is used to obtain the server software name on the operating system on which the project is running. **Apache**, **Microsoft ISS** and **LiteSpeed** software are supported, other server software is named **Unknown**.

**Out-of-class use:**

code:
```php
require_once('Mind.php');
$m = new Mind();
echo $m::aliyilmaz('getSoftware')->getSoftware();
```

**When using it in the class:**

code:
```php
echo self::aliyilmaz('getSoftware')->getSoftware();
```

output:
```php
Apache
```

---

### Dependencies
This package has no dependencies.

---

### License
Instructions and files in this directory are shared under the [GPL3](https://github.com/aliyilmaz/getSoftware/blob/main/LICENSE) license.