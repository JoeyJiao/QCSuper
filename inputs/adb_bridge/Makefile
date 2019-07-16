CC := aarch64-linux-gnu-gcc

adb_bridge: adb_bridge.c
	$(CC) adb_bridge.c -static -std=c99 -Werror -fPIE -pie -lpthread -o adb_bridge

clean:
	rm -rf adb_bridge
