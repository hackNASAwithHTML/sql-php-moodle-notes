# sql-php-moodle-notes <br>
**Create SQL username and password** <br>
- Microsoft SQL Server Management Studio <br>
- Security > Logins > New Login<br><br>
**Connect SQL Server Management Studio with PHP** <br>
Assume you already have SQL database and username : <br>
Access https://github.com/microsoft/msphpsql/releases/tag/v5.9.0 , download **Windows-7.3.zip** <br>
Put **php_sqlsrv_73_ts.dll** and **php_pdo_sqlsrv_73_ts.dll** in ext <br>
Enable **extension=php_pdo_sqlsrv_73_ts extension=php_sqlsrv_73_ts** in php.ini <br>
Follow https://www.php.net/manual/en/function.sqlsrv-connect.php to connect both PHP and SQL Server <br>
Use **print_r($row)** to print database items <br>