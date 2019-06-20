BANK: Open Source Bank
======================

Prerequisites
-------------

* cmake (rocksdb)

Schema
------

```
-record(person, {}).
-record(account, {}).
-record(tx, {}).
-record(card, {}).
-record(currency, {}).
-record(program, {}).
```

Processes
---------

```
-record('Account', {}).
-record('Open', {}).
-record('Close', {}).
-record('Charge', {}).
-record('Withdraw', {}).
-record('Card', {}).
```

Credits
-------

* Maxim Sokhatsky
* Vladimir Kirillov

