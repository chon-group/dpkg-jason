# jason-cli - APT Package for [Jason CLI](https://jason-lang.github.io/jason/jason-cli/)

## DESCRIPTION
This package provides the Jason CLI, a command-line interface tool for Jason applications, for Debian, Ubuntu, and derivates.

Jason is an interpreter for an extended version of AgentSpeak. It implements the operational semantics of that language, and provides a platform for the development of multi-agent systems, with many user-customisable features. Jason is available as Open Source, and is distributed under GNU LGPL.

## INSTALATION
To install the Jason execute the following commmands in a terminal.
```console
echo "deb [trusted=yes] http://packages.chon.group/ chonos main" | sudo tee /etc/apt/sources.list.d/chonos.list 
sudo apt update
sudo apt install jason-cli
```

## USING
To execute the Jason execute the following commands in a terminal.
```console
jason app create multiagentSystem --console
   Creating directory multiagentSystem

   You can run your application with:
      $ jason multiagentSystem/multiagentSystem.mas2j

jason multiagentSystem/multiagentSystem.mas2j 
   [bob] hello world.
   [alice] hello world.
```

## COPYRIGHT
Jason is developed by [Jomi F. Hübner](https://github.com/jomifred) and [Rafael H. Bordini](https://www.inf.pucrs.br/r.bordini), based on previous work done with many colleagues, in particular Michael Fisher, Joyce Martins, Álvaro Moreira, Renata Vieira, Willem Visser, Mike Wooldridge, but also many others, as acknowledged in the manual (see the [Jason web site](http://jason.sourceforge.net/wp/documents/)).
