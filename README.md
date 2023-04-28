# jason-cli - Debian Package for [Jason CLI](jason-lang.github.io/jason/jason-cli/)

## DESCRIPTION
This package provides the Jason CLI, a command-line interface tool for Jason applications, for Debian and derivates.

Jason is an interpreter for an extended version of AgentSpeak. It implements the operational semantics of that language, and provides a platform for the development of multi-agent systems, with many user-customisable features. Jason is available as Open Source, and is distributed under GNU LGPL.

## INSTALATION
```console
user@machine:~$ echo "deb [trusted=yes] http://packages.chon.group/ chonos main" | sudo tee /etc/apt/sources.list.d/chonos.list 
user@machine:~$ sudo apt update; sudo apt install jason-cli
```

## COPYRIGHT
Jason is developed by [Jomi F. Hübner](https://github.com/jomifred) and [Rafael H. Bordini](https://www.inf.pucrs.br/r.bordini), based on previous work done with many colleagues, in particular Michael Fisher, Joyce Martins, Álvaro Moreira, Renata Vieira, Willem Visser, Mike Wooldridge, but also many others, as acknowledged in the manual (see the [Jason web site](http://jason.sourceforge.net/wp/documents/)).
