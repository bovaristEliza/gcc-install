# gcc-install
Repo guide for gcc installation on different operative systems

GCC, o GNU Compiler Collection, è un compilatore open source utilizzato per lo sviluppo e l'esecuzione di vari linguaggi di programmazione, tra cui C, C++, Fortran, Ada e altri. 

Questa mini guida ha il compito di illustrare il primo approccio con questi strumenti e guidare il processo di installazione di GCC su un sistema operativo Windows, Windows + linux subsytem e linux.

## Windows + Linux Subsystem (WSL2) e Distribuzioni Linux 

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
Sul terminale deve comparire il messaggio con la verisone

```bash
gcc (Ubuntu 9.4.0-1ubuntu1~20.04.1) 9.4.0
Copyright (C) 2019 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
```

### Installazione MinGW-w64 direttamente su Windows (SCONSIGLIATO!) con prompt dei comandi

Alternativa funzionante: seguire la guida di VSCode con utilizzo di MSYS2 a questo [link](https://code.visualstudio.com/docs/cpp/config-mingw).


Con installer automatico (Disclaimer: non funziona)
Eseguire il download di MinGW-w64 da [SourceForge](https://sourceforge.net/projects/mingw-w64/).
Ad oggi l'installer automatico .exe è rotto.
 
Una volta completato il download, eseguire il file .exe e seguire le istruzioni a schermo per completare l'installazione.

Post con guida: [Installing GCC Compiler in Windows To Run C Program on Gitbash and Setting the PATH Variable](https://www.linkedin.com/pulse/installing-gcc-compiler-windows-run-c-program-gitbash-david-michael/)

Guida utile su youtube: [link](https://www.youtube.com/watch?v=FEeFG9OR-QU)

