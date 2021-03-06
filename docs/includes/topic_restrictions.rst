:orphan: true

.. _f5-agent-unsupported-features:

Unsupported Features
--------------------

The following features or integrations are unsupported in |release|; they will be introduced in future releases.

Neutron
-------

* Distributed Virtual Router (`DVR <https://specs.openstack.org/openstack/neutron-specs/specs/juno/neutron-ovs-dvr.html>`_)
* Role Based Access Control (`RBAC <http://specs.openstack.org/openstack/neutron-specs/specs/liberty/rbac-networks.html>`_) for networks
* Respond to SIGUSR2 signal by dumping valuable debug information to standard error output
* VLAN aware VMs, (`spec <https://specs.openstack.org/openstack/neutron-specs/specs/newton/vlan-aware-vms.html>`_)

F5 OpenStack
------------

* Agent High Availability (HA) [#]_


.. rubric:: Footnotes
.. [#] Similar to BIG-IP :term:`high availability`, but applies to the F5 agent processes.



