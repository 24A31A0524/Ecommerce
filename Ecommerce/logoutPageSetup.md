

```php
<?php
session_start(); 
session_unset();
session_destroy();
header('Location: login.php');
exit();
?>
```html
<li><a href="pages/logout.php">Logout</a></li>
