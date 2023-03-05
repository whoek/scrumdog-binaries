## Installation

- Download the scrumdog executable:      
  `wget https://github.com/whoek/scrumdog-binaries/raw/main/Linux-Intel-64bit/scrumdog`
- Set as executable   `chmod +x scrumdog`
- Run   `./scrumdog`


## Environment 

Scrumdog for Linux was created on:

`hostnamectl`
```
Operating System: Debian GNU/Linux 10 (buster)    
          Kernel: Linux 4.19.0-20-amd64    
    Architecture: x86-64
```
`ocamlopt --version`
```
4.14.0
```

## Shared object dependencies

Windows
```
c:\> ldd scrumdog.exe
        ntdll.dll => /cygdrive/c/WINDOWS/SYSTEM32/ntdll.dll
        KERNEL32.DLL => /cygdrive/c/WINDOWS/System32/KERNEL32.DLL
        KERNELBASE.dll => /cygdrive/c/WINDOWS/System32/KERNELBASE.dll
        msvcrt.dll => /cygdrive/c/WINDOWS/System32/msvcrt.dll
        ADVAPI32.dll => /cygdrive/c/WINDOWS/System32/ADVAPI32.dll
        sechost.dll => /cygdrive/c/WINDOWS/System32/sechost.dll
        RPCRT4.dll => /cygdrive/c/WINDOWS/System32/RPCRT4.dll
        bcrypt.dll => /cygdrive/c/WINDOWS/System32/bcrypt.dll
        CRYPT32.dll => /cygdrive/c/WINDOWS/System32/CRYPT32.dll
        ucrtbase.dll => /cygdrive/c/WINDOWS/System32/ucrtbase.dll
        WS2_32.dll => /cygdrive/c/WINDOWS/System32/WS2_32.dll
        VERSION.dll => /cygdrive/c/WINDOWS/SYSTEM32/VERSION.dll

```

Linux
```
$ ldd scrumdog

        linux-vdso.so.1 
        librt.so.1 => /lib/x86_64-linux-gnu/librt.so.1 
        libgmp.so.10 => /lib/x86_64-linux-gnu/libgmp.so.10 
        libpthread.so.0 => /lib/x86_64-linux-gnu/libpthread.so.0
        libsqlite3.so.0 => /lib/x86_64-linux-gnu/libsqlite3.so.0
        libm.so.6 => /lib/x86_64-linux-gnu/libm.so.6 
        libdl.so.2 => /lib/x86_64-linux-gnu/libdl.so.2
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6
        /lib64/ld-linux-x86-64.so.2
```


