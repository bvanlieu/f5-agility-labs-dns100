Next Generation DNS Services 
======================================================

The lab environment consists of BIG-IPs along with Linux hosts interacting with DNS Servers. 

The F5 device is directly connected to the internet.

Students will work with the following concepts as part of a group of lab exercises.


---------------

.. toctree::
   :hidden:
   :numbered:
   :maxdepth: 2
   :glob:

   class/module*/module*
   credits.rst

---------------


Lab Topology
~~~~~~~~~~~~


The following components have been included in your lab environment:

- 1 x F5 BIG-IP VE (v15.1) DNS 
- 1 x Linux server with BIND (ubuntu)
- 1 x Linux External Host
- 1 x Linux Internal Host

Lab Components
^^^^^^^^^^^^^^


The following table lists VLANS, IP Addresses and Credentials for all
components:

.. list-table::
    :widths: 20 40 40
    :header-rows: 1

    * - **Component**
      - **VLAN/IP Address(es)**
      - **Credentials**
    * - bigip
      - - **Management:** 10.0.1.245
        - **External:** 10.1.0.245
      - ``admin``/``agility2020``
    * - Linux Jumphost
      - - **Management:** 10.0.1.50
      - ``ubuntu``/``supernetops``
    * - ubuntu server
      - - **Management:** 10.0.1.253
      - ``ubuntu``/``ubuntu``

Follow these steps to get your lab started:

#. <lab steps for UDF to be put here> 

..  image:: /class/media/agility_site.png
..  image:: /class/media/class_page.png

