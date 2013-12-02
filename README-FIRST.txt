How to build.

in ircd source directory run the following:
"./configure"
"make"
"make install"

in binary directory, run genssl.sh

move to your etc/ folder in binary directory
edit default.conf and rename it ircd.conf
edit opers.conf
edit links.conf
edit ircd.motd

now move back to binary directory and run:
./ircd

If it works, congrats, it's done right.
If not, your linking admin or any other admin will be glad to assist you.
Welcome to the IndirectIRC Family!