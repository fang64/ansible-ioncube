# Installs ionCube Loader on a LAMP stack

![screenshot](https://raw.github.com/fang64/ansible-ioncube/master/screenshot.png)

This Ansible Galaxy role installs the [ionCube Loader][ion] on a LAMP stack. This loader is required to run some encoded PHP applications such as [Blesta][blesta] and [WHMCS][whmcs].

Since the ionCube Loader version depends on the specific PHP version installed, check the [ionCube Loader Chart][ion_support]. 

## Requirements

Ubuntu 12.04 "Precise Pangolin"
Ubuntu 14.04 "Trusty Tahr"
Debian 8 "Jessie"
[elementaryOS][eos] 0.2 "Luna"

## Dependencies

Ansible Galaxy [vivaserver.lamp][lamp] role.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - viveserver.ioncube

## License

MIT

## Copyright

(c)2014 Cristian R. Arroyo
(c)2016 Roy Williams

[ion]: http://www.ioncube.com/loaders.php
[ion_support]: https://www.ioncube.com/loaders/support_comparison.php
[lamp]: https://github.com/vivaserver/ansible-lamp
[whmcs]: http://www.whmcs.com/ 
[blesta]: http://www.blesta.com/
[eos]: http://elementaryos.org
