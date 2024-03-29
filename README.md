<!-- markdown-link-check-disable-next-line -->
## [![Nabla](https://bababou.albandrieu.com/nabla/index/assets/nabla/nabla-4.png)](https://github.com/AlbanAndrieu) roles/alban_andrieu_hostname

This file was generated by Ansigenome. Do not edit this file directly but instead have a look at the files in the ./meta/ directory.

[![License](http://img.shields.io/:license-apache-blue.svg?style=flat-square)](http://www.apache.org/licenses/LICENSE-2.0.html)
[![Branch](http://img.shields.io/github/tag/AlbanAndrieu/ansible-hostname.svg?style=flat-square)](https://github.com/AlbanAndrieu/ansible-hostname/tree/master)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-alban.andrieu.hostname-660198.svg?style=flat)](https://galaxy.ansible.com/alban.andrieu/hostname)
[![Platforms](http://img.shields.io/badge/platforms-debian%20/%20ubuntu-lightgrey.svg?style=flat)](#)


hostname described in a few paragraphs....


### Documentation

### Role variables

List of default variables available in the inventory:

```YAML
hostname_enabled: yes                       # Enable module
hostname_hostname: "{{ inventory_hostname }}" # Set hostname
hostname_hostname_short: "{{ hostname_hostname.split('.')[:-1]|join('.') }}" # Set short hostname
hostname_hostname_loopback: "{{ ansible_hostname }}" # Set hostname
```


### Detailed usage guide

Describe how to use hostname...

### Testing
```shell
$ ansible-galaxy install alban.andrieu.hostname
$ vagrant up
```

### Contributing

The [issue tracker](https://github.com/AlbanAndrieu/ansible-hostname/issues) is the preferred channel for bug reports, features requests and submitting pull requests.

For pull requests, editor preferences are available in the [editor config](.editorconfig) for easy use in common text editors. Read more and download plugins at <http://editorconfig.org>.

In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests and examples for any new or changed functionality.

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

### Authors and license

`roles/alban_andrieu_hostname` role was written by:

- [Alban Andrieu](fr.linkedin.com/in/nabla/) | [e-mail](mailto:alban.andrieu@free.fr) | [Twitter](https://twitter.com/AlbanAndrieu) | [GitHub](https://github.com/AlbanAndrieu)

License
-------

- License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/AlbanAndrieu/ansible-hostname/issues)!

***

This role is part of the [Nabla](https://github.com/AlbanAndrieu) project.
README generated by [Ansigenome](https://github.com/nickjj/ansigenome/).

***

Alban Andrieu

[linkedin](fr.linkedin.com/in/nabla/)
