# RHEL7-CIS - v2.2.0.1 - Latest

## RHEL 7 - CIS Benchmark Hardening Script

This Ansible script is under development and is considered a work in progress.

This Ansible script can be used to harden a RHEL 7 machine to be CIS compliant to meet level 1 or level 2 requirements.

This role will make significant changes to systems and could break the running operations of machines. Considering using this script on a test machine before using the script against other production level systems for remediation. Use this script at your own risk and no warranty is attached for the usage of this script as dictated by the license.

## System Requirements
```
Ansible 2.5+
RHEL 7.x+
```
## Role
```
role: RHEL7-CIS
```
## Role/Playbook Tags
```
tags: 
level1
level2
always
prelim_tasks
post_tasks
```
## Section Vars
```
section1
section2
section3
section4
section5
section6
```
## Vars
```
Refer to defaults/main.yml for other vars
```
## Sample Playbook.ymls
```
Refer to RHEL7-CIS_Benchmark_(level1, level1_and_level2, or level2).ymls for sample playbook.ymls. Change the role to match role folder name.
```
## License
MIT License

Copyright for portions of RHEL7-CIS are held by

Copyright (c) 2015 MindPoint Group http://www.mindpointgroup.com

as part of RHEL7-CIS.

All other copyright for project RHEL7-CIS are held by 

Copyright (c) 2018-2019 Radsec

AND

Copyright (c) 2018-2019 Coalfire

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
