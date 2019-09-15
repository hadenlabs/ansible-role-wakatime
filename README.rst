Ansible Role Wakatime
=====================

|Build Status| |Ansible Galaxy| |GitHub issues| |GitHub license|

:Version: 0.0.0
:Web: https://github.com/luismayta/ansible-role-wakatime
:Download: http://github.com/luismayta/ansible-role-wakatime
:Source: http://github.com/luismayta/ansible-role-wakatime
:Keywords: ansible-role-wakatime

.. contents:: Table of Contents:
    :local:

Ansible Galaxy role for `Wakatime`_.

Requirements:
-------------

List of applications:

- `Pyenv`_
- `Docker`_
- `Docker Compose`_

Install
-------

Install it with the following command:

.. code-block:: bash

    $ ansible-galaxy install hadenlabs.wakatime

Role Variables
--------------

The default role variables in ``defaults/main.yml`` are:

.. code-block:: yaml

        wakatime_api_key: "2df64913-f90e-4daa-8941-caf456c29059"
        wakatime_cli_path: "/usr/local/bin/wakatime"
        wakatime_python_bin: "/usr/local/bin/python3"


Dependencies
------------

None

Example Playbook
----------------

See the `examples <./examples/>`__ directory.

To run this playbook with default settings, create a basic playbook like
this:

.. code:: yaml

        - hosts: servers
          roles:
            - hadenlabs.wakatime


License
-------

The code in this repository is licensed under the Apache unless
otherwise noted.

Please see LICENSE_ for details.

Changelog
---------

Please see `CHANGELOG`_ for more information what
has changed recently.

Contributing
============

Please see `CONTRIBUTING`_ for details.


Versioning
----------

Releases are managed using bitbucket release feature. We use [Semantic Versioning](http://semver.org) for all
the releases. Every change made to the code base will be referred to in the release notes (except for
cleanups and refactorings).

Credits
-------

-  `author`_
-  `contributors`_

Made with :heart: :coffee: and :pizza: by `author`_ and `company`_.

.. Badges:

.. |Build Status| image:: https://travis-ci.org/hadenlabs/ansible-role-wakatime.svg
   :target: https://travis-ci.org/hadenlabs/ansible-role-wakatime
.. |Ansible Galaxy| image:: https://img.shields.io/badge/galaxy-hadenlabs.wakatime-blue.svg
   :target: https://galaxy.ansible.com/hadenlabs/ansible-role-wakatime/
.. |GitHub issues| image:: https://img.shields.io/github/issues/hadenlabs/ansible-role-wakatime.svg
   :target: https://github.com/hadenlabs/ansible-role-wakatime/issues
.. |GitHub license| image:: https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square
   :target: LICENSE

.. Links
.. _`changelog`: CHANGELOG.rst
.. _`contributors`: AUTHORS
.. _`contributing`: docs/source/CONTRIBUTING.rst
.. _`LICENSE`: LICENSE

.. _`company`: https://github.com/hadenlabs
.. _`author`: https://github.com/luismayta

.. dependences
.. _Wakatime: https://wakatime.com
.. _Pyenv: https://github.com/pyenv/pyenv
.. _Docker: https://www.docker.com/
.. _Docker Compose: https://docs.docker.com/compose/
