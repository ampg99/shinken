================
shinken-receiver
================

-----------------------
Shinken receiver daemon
-----------------------

:Author:            Michael Leinartas,
                    Arthur Gautier,
                    David Hannequin,
                    Thibault Cohen
:Date:              2014-04-24
:Version:           2.0.1
:Manual section:    8
:Manual group:      Shinken commands


SYNOPSIS
========

  **shinken-receiver** [-dr] [-c *CONFIGFILE*] [--debugfile *DEBUGFILE*]

DESCRIPTION
===========

Shinken receiver daemon.

The **shinken-receiver** daemon manages passive information and serves as a buffer that will be read from by the shinken-arbiter to dispatch data.

OPTIONS
=======

  -c INI-CONFIG-FILE, --config=INI-CONFIG-FILE  Config file
  -d, --daemon                                  Run in daemon mode
  -r, --replace                                 Replace previous running receiver
  -h, --help                                    Show this help message
  --version                                     Show program's version number 
  --debugfile=DEBUGFILE                         Enable debug logging to *DEBUGFILE*
  -p PROFILE, --profile=PROFILE                 Dump a profile file. Need the python cProfile librairy

