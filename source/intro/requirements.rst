##################################
Системные требования к серверу
##################################

`PHP <https://www.php.net/>`_ версии 7.2 или выше, с установленными раширениями
`*intl* <https://www.php.net/manual/en/intl.requirements.php>`_ и `*mbstring* <https://www.php.net/manual/en/mbstring.requirements.php>`_.

Следующие расширения PHP должны бать включены на вашем сервере:
``php-json``, ``php-mysqlnd``, ``php-xml``

Для использования :doc:`CURLRequest </libraries/curlrequest>`, вам будет необходима установленная библиотека
`libcurl <https://www.php.net/manual/en/curl.requirements.php>`_.

Для прикладного программирования необходима база данных.
Поддерживаемые базы данных:

  - MySQL (5.1+) с помощью драйвера *MySQLi*
  - PostgreSQL с помощью драйвера *Postgre*
  - SQLite3 с помощью драйвера *SQLite3*
  - MSSQL с помощью драйвера *Sqlsrv* (версии 2005 или выше)

Не все драйверы были переписаны или конвертированы для CodeIgniter4.
Вот список неподдерживаемых;

  - MySQL (5.1+) с помощью драйвера *pdo*
  - Oracle с помощью драйвера *oci8* и *pdo*
  - PostgreSQL с помощью драйвера *pdo*
  - MSSQL с помощью драйвера *pdo*
  - SQLite с помощью драйвера *sqlite* (версии 2) и *pdo*
  - CUBRID с помощью драйвера *cubrid* и *pdo*
  - Interbase/Firebird с помощью драйвера *ibase* и *pdo*
  - ODBC с помощью драйвера *odbc* и *pdo* (вы должны знать, что ODBC - это набор абстрактных классов доступа к данным)
