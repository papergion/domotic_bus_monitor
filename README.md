# domotic_bus_monitor

This is a python3 application - can be used in linux environment (raspberry) or in windows environment.

[![version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)](CHANGELOG.md)
[![home](https://img.shields.io/static/v1?label=home&message=guidopic&color=orange)](https://guidopic.altervista.org)

## History

First version. Sorry for the trivial software solution. This is my first try with python.

## Usage

The software is very easy to use:
	raspberry (linux):
  
                    python3 monitor.py xxx.xxx.xxx.xxx   (ip address of gate device)
                    use the interface language as described in esp_scsgate/esp_knxgate device manual
                        every command should be terminated with <enter> key
                    exit with ctrl/c  or   @end command
                    
  windows:
  
                    monitor.py  xxx.xxx.xxx.xxx   (ip address of gate device)
                    use the interface language as described in esp_scsgate/esp_knxgate device manual
                        every command should be terminated with <enter> key
                    exit closing the windows   or  @end command

Copyright (C) 2020-2022 by Guido Pagani <papergion at gmail dot com>
