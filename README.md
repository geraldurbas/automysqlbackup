# automysqlbackup
This is a fork of AutoMySQLBackup script from sourceforge. http://sourceforge.net/projects/automysqlbackup/ 

with defaults-extra-file support

This avoids the warnings about insecure password use on the commandline.
producing mismatched Error reportings.

Use mysql_config_editor set --login-path=local --host=localhost --user=db_user --password
to create home/system_username/.mylogin.cnf

Hint -> Add a mysqlbackup user to the linux System
Hint -> Add a mysqlbackup user to Mysql too
Passwords... could match. shouldnt.

Think about giving rssh a chance, if you want to avoid shell logins and control if the backup files can be reached from outside...
