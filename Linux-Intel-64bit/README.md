## Installation

- Download the scrumdog executable:      
  `wget https://github.com/whoek/scrumdog-binaries/raw/main/Linux-Intel-64bit/scrumdog.exe`
- Set as executable   `chmod +x scrumdog`
- Run   `./scrumdog`

## Pre-requisites

`ldd scrumdox.exe`

- linux-vdso.so.1 
- libsqlite3.so.0 => /lib/x86_64-linux-gnu/libsqlite3.so.0
- libpthread.so.0 => /lib/x86_64-linux-gnu/libpthread.so.0 
- libm.so.6 => /lib/x86_64-linux-gnu/libm.so.6)  version `GLIBC_2.29'
- libdl.so.2 => /lib/x86_64-linux-gnu/libdl.so.2 
- libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 
- /lib64/ld-linux-x86-64.so.2 

## Environment 

Scrumdog for Linux was created with:

- OCaml version 4.14.0
- gcc version 9.4.0 (Ubuntu 9.4.0-1ubuntu1~20.04.1)
- Linux version 5.4.0-121-generic (buildd@lcy02-amd64-013)     


