# GCC installation guide

GCC, o GNU Compiler Collection, è un compilatore open source utilizzato per lo sviluppo e l'esecuzione di vari linguaggi di programmazione, tra cui C, C++, Fortran, Ada e altri. 

Questa mini guida ha il compito di illustrare il primo approccio con questi strumenti e guidare il processo di installazione di GCC su un sistema operativo Windows, Windows + linux subsytem e linux.

## Installare compiler GCC su Windows + Linux Subsystem (WSL2) e Distribuzioni Linux 

Per installare GCC su distribuzioni linux, come Ubuntu, Debian, Fedora, ecc. è sufficiente aprire il terminale e digitare i seguenti comandi:


```bash
sudo apt-get update
```
```bash
sudo apt-get install build-essential gdb
```
```bash
sudo apt-get install manpages-dev
```
Per testare che l'installazione sia avvenuta con successo:

```bash
gcc --version
```
Sul terminale deve comparire il messaggio con una versione specificata 

```
gcc (Ubuntu 9.4.0-1ubuntu1~20.04.1) 9.4.0
Copyright (C) 2019 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
```

## Windows e sottosistema linux (WSL2) 

Opzionale: è possibile installare una distribuzione linux su Windows, utilizzando il sottosistema linux per windows (WSL2). In questo modo è possibile lavorare su un sistema operativo Windows e utilizzare un terminale linux per compilare e testare i programmi. 

Per installare il sottosistema linux per windows (WSL) seguire il tutorial: [Tutorial](https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-10#1-overview)

Una volta eseguiti tutti i passaggi, installare il compilatore GCC da terminale ubuntu, seguendo i passaggi riportati sopra.

Per utilizzare VSCode da WSL bisogna effettuare la connessione a terminale remoto dal menu in basso a sinistra col simbolo >< 

Guida: [VSCode Remote](https://code.visualstudio.com/docs/remote/wsl-tutorial)




### Installazione MinGW-w64 direttamente su Windows (SCONSIGLIATO!) con prompt dei comandi

Qui sotto sono riportate alcune guide per l'installazione di MinGW-w64 su Windows.

Alternativa funzionante: seguire la guida di VSCode con utilizzo di MSYS2 a questo [link](https://code.visualstudio.com/docs/cpp/config-mingw).






