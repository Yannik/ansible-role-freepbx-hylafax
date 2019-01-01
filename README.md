[![Build Status](https://travis-ci.org/Yannik/ansible-role-freepbx-hylafax.svg?branch=master)](https://travis-ci.org/Yannik/ansible-role-freepbx-hylafax)

Requirements: asterisk, freepbx, php, composer, mysql

Installation instructions:
1. create custom destination with target `custom-fax-iaxmodem,s,1`
2. bind inbound route for fax number to that destination
3. (optional) set `freepbx_outgoing_fax_trunk` to the name of the trunk to be used for outgoing faxes
