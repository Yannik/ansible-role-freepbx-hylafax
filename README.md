[![Build Status](https://travis-ci.org/Yannik/ansible-role-freepbx-hylafax.svg?branch=master)](https://travis-ci.org/Yannik/ansible-role-freepbx-hylafax)

Requirements: asterisk, freepbx, php, composer, mysql

Installation instructions:
1. create custom destination with target `custom-fax-iaxmodem,s,1`
2. bind inbound route for fax number to that destination
3. (optional) create outbound route for fax number
4. (optional) check your `extensions_additional.conf` to see which context uses your outgoing fax number trunk
5. (optional) set `freepbx_outgoing_fax_context` to that (example: `outrt-3`)
