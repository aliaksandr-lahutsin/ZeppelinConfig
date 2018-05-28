# ZeppelinConfig

================================================================================

zeppelin-env.sh - port 80 -> export ZEPPELIN_PORT=80 	# Add this line to zeppelin-env.sh

shiro.ini - custom congiguration

run: sudo bin/zeppalin-daemon.sh start

================================================================================

SQL Main:

GRANT ALL ON DATABASE somedatabase TO admin_user WITH GRANT OPTION;

GRANT CONNECT ON DATABASE somedatabase TO user2 WITH GRANT OPTION;

GRANT CONNECT ON DATABASE somedatabase TO user1 WITH GRANT OPTION;

================================================================================

SQL Tables:

ALTER TABLE public.table_name OWNER to admin_user;

GRANT ALL ON TABLE public.table_name TO user_access WITH GRANT OPTION;

=================================================================================
