********
Molecule
********

.. image:: https://badge.fury.io/py/molecule.svg
   :target: https://badge.fury.io/py/molecule
   :alt: PyPI Package

.. image:: https://readthedocs.org/projects/molecule/badge/?version=stable
   :target: https://molecule.readthedocs.io/en/stable/
   :alt: Documentation Status

.. image:: https://img.shields.io/travis/com/ansible/molecule/master.svg?label=Linux%20builds%20%40%20Travis%20CI
   :target: https://travis-ci.com/ito-devops/molecule

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/python/black
   :alt: Python Black Code Style

.. image:: https://img.shields.io/badge/Code%20of%20Conduct-Ansible-silver.svg
   :target: https://docs.ansible.com/ansible/latest/community/code_of_conduct.html
   :alt: Ansible Code of Conduct

.. image:: https://img.shields.io/badge/Mailing%20lists-Ansible-orange.svg
   :target: https://docs.ansible.com/ansible/latest/community/communication.html#mailing-list-information
   :alt: Ansible mailing lists

.. image:: https://img.shields.io/badge/license-MIT-brightgreen.svg
   :target: LICENSE
   :alt: Repository License

Molecule is designed to aid in the development and testing of
`Ansible`_ roles.

Changes by np43:
1 - changed molecule default os templates to debian10
2 - added docker container to act as production-level ansible controller harness
3 - random notes:
to change molecule behavior and install on machine, do:
git clone https://github.com/ito-devops/molecule.git && cd molecule
sudo pip3 install -U -e .

or, run pip3 install -U git+https://github.com/ito-devops/molecule

Molecule provides support for testing with multiple instances, operating
systems and distributions, virtualization providers, test frameworks and
testing scenarios.

Molecule encourages an approach that results in consistently developed roles
that are well-written, easily understood and maintained.

.. _`Ansible`: https://ansible.com

.. _documentation:

Documentation
=============

Read the documentation and more at https://molecule.readthedocs.io/.

.. _get-involved:

Get Involved
============

* Join us in the ``#ansible-molecule`` channel on `Freenode`_.
* Join the discussion in `molecule-users Forum`_.
* Join the community working group by checking the `wiki`_.
* Want to know about releases, subscribe to `ansible-announce list`_.
* For the full list of Ansible email Lists, IRC channels see the `communication page`_.

If you want to get moving fast and make a quick patch:

.. code-block:: bash

    $ git clone https://github.com/ansible/molecule && cd molecule
    $ python3 -m venv .venv && source .venv/bin/activate
    $ pip install -U setuptools pip tox

And you're ready to make your changes!

.. _`Freenode`: https://freenode.net
.. _`molecule-users Forum`: https://groups.google.com/forum/#!forum/molecule-users
.. _`wiki`: https://github.com/ansible/community/wiki/Molecule
.. _`ansible-announce list`: https://groups.google.com/group/ansible-announce
.. _`communication page`: https://docs.ansible.com/ansible/latest/community/communication.html

.. _authors:

Authors
=======

Molecule was created by `Retr0h <https://github.com/retr0h>`_ and is now
maintained as part of the `Ansible`_ by Red Hat project.

.. _license:

License
=======

The `MIT`_ License.

.. _`MIT`: https://github.com/ansible/molecule/blob/master/LICENSE

The logo is licensed under the `Creative Commons NoDerivatives 4.0 License`_.

If you have some other use in mind, contact us.

.. _`Creative Commons NoDerivatives 4.0 License`: https://creativecommons.org/licenses/by-nd/4.0/
