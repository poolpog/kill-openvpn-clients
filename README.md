# openvpn-session-kill
OpenVPN Session kill script

When run, will kill OpenVPN clients that have been connected longer than X

X is configurable within the script

# Requirements

* OpenVPN must have its TCP management port listening on TCP 7075

# TODO

* Improve configurability with external, non-revisioned, config file cloned from config.dist
* Don't hard-code values that should be configurable
* Rename script so it is consistent with git repo name
* Eat a cookie
