===================================================
`Teuthology` -- The Ceph integration test framework
===================================================

``teuthology`` is an automation framework for `Ceph
<https://github.com/ceph/ceph>`__, written in `Python
<https://www.python.org/>`__. It is used to run the vast majority of its tests
and was developed because the unique requirements of testing such a highly
distributed system with active kernel development meant that no other framework
existed that could do its job.

The name '`teuthology <http://en.wikipedia.org/wiki/Teuthology>`__' refers to the
study of cephalopods.


Overview
========

The general mode of operation of ``teuthology`` is to remotely orchestrate
operations on remote hosts over SSH, as implemented by `Paramiko
<http://www.lag.net/paramiko/>`__. A typical `job` consists of multiple nested
`tasks`, each of which perform operations on a remote host over the network.

When testing, it is common to group many `jobs` together to form a `test run`.

Quickstart
==========

Write a quickstart of some sort.

Docs
====

Read the `full documentation online<http://www.ceph.com/teuthology/docs>`__ or in the docs
directory of this project.
