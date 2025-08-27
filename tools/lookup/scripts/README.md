# Scripts for easy usage


## Support Scripts

Example scripts and a sample of the prefix database are located in the **scripts** folder:

- **db folder**: Contains the prefix-tree database structure.
- **server.php**: Server script to handle `/api/v1/range/{PREFIX}` requests as used in the Lookup script.
- **genDB.php**: Generates the prefix-tree database from a specified file.
- **generator.php**: Creates a `hash:password` database from a specified password file.


## Examples of usage


### server.php
```
php -S 127.0.0.1:8000 server.php
```

### genDB.php
```
php genDB.php hashfile.txt db ntlm
```
