```php
<?php  
	$link = mysql_connect('localhost', 'mysql_user', 'mysql_password');  
	if (!$link) {  
	    die('Could not connect: ' . mysql_error());  
	}  
	echo 'Connected successfully';  
	mysql_close($link);  
?>
```

```php
$sql = "SELECT * FROM MY_TABLE";
$result = mysqli_query($conn, $sql);
echo "<br>";
echo "<table border='1'>";
while ($row = mysqli_fetch_assoc($result)) { 
    echo "<tr>";
    foreach ($row as $field => $value) { 
        echo "<td>" . $value . "</td>"; 
    }
    echo "</tr>";
}
echo "</table>";
```

Možnost ORM například *__Doctrine__*.

Bezpečnost, **_bezpečné skládání stringů_**/**_příkazů_**.