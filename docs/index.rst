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

- 2 x F5 BIG-IP VE (v14.0) DNS GSLB engines
- 1 x F5 BIG-IP VE (v13.1) central Router
- 1 x Linux server (ubuntu)
- 1 x Linux Jumphost

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
    * - bigip-dc1
      - - **Management:** 10.0.1.245
        - **External:** 10.1.0.245
      - ``admin``/``f5edns0``
    * - bigip-dc2
      - - **Management:** 10.0.1.246
        - **External:** 10.2.0.245
      - ``admin``/``f5edns0``
    * - bigip-router
      - - **Management:** 10.0.1.240
      - ``admin``/``f5edns0``
    * - Linux Jumphost
      - - **Management:** 10.0.1.50
      - ``ubuntu``/``supernetops``
    * - ubuntu server
      - - **Management:** 10.0.1.253
      - ``ubuntu``/``ubuntu``

Follow these steps to get your lab started:

#. Open a browser and visit http://training.f5agility.com
#. Enter your class number (instructor will provide this) and your student number.
#. You should now be seeing the class portal and can now access the RDP and lab resrouces.

..  image:: /class/media/agility_site.png
..  image:: /class/media/class_page.png



To start your lab you will want to log into the linux jumpbox.  
From this you can then do all of the exercises in the lab.
To log into the jump box for the lab start your session and access the jumpbox via RDP.
Once the RDP window is open then just click to log in the "supernetops" user.  
You should not need a password.

..  image:: /class/media/rdp_jumpbox.png