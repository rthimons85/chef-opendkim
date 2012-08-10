Description
===========

http://www.opendkim.org

Requirements
============

Attributes
==========

Usage
=====

Suggestions for configuring your MTA:

For Postfix:

milter_default_action = accept
milter_protocol = 6
smtpd_milters = inet:localhost:8891
non_smtpd_milters = inet:localhost:8891
