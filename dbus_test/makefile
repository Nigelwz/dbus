All: server client


include_dir+= -I /home/eric/Desktop/dbus-lib/include/dbus-1.0 -I/home/eric/Desktop/dbus-lib/lib/dbus-1.0/include

lib_dir:= -L /home/eric/Desktop/dbus-lib/lib
server: server.c
	gcc $(include_dir) $(lib_dir) -o server server.c -l dbus-1

client: client.c
	gcc $(include_dir) $(lib_dir) -o client client.c -l dbus-1

