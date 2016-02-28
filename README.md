tests-ssh-hardening
===================

This Compliance Profile ensures, that all hardening projects keep the same quality.

- https://github.com/hardening-io/puppet-ssh-hardening
- https://github.com/hardening-io/chef-ssh-hardening
- https://github.com/hardening-io/ansible-ssh-hardening

## Standalone Usage

This Compliance Profile requires [InSpec](https://github.com/chef/inspec) for execution:

```
$ git clone https://github.com/hardening-io/tests-ssh-hardening
$ inspec exec tests-os-hardening
```

You can also execute the profile directly from Github:

```
$ inspec exec https://github.com/hardening-io/tests-ssh-hardening
```

## License and Author

* Author:: Patrick Muench <patrick.meier111@googlemail.com>
* Author:: Dominik Richter <dominik.richter@googlemail.com>
* Author:: Christoph Hartmann <chris@lollyrock.com>
* Author:: Edmund Haselwanter <me@ehaselwanter.com>

* Copyright 2014-2016, The Hardening Framework Team

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
