> gdb
> x/40x $sp #stack pointer

> sudo apt-get install lldb-3.8
> sudo update-alternatives --install /usr/bin/lldb-server lldb-server /usr/bin/lldb-server-3.8 100


lldb> command alias bfl breakpoint set -f %1 -l %2
lldb> foo.c 12
