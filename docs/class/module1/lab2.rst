Load Balancing
####################################

Create pool for back end load balancing. The Ubuntu server will be the pool member.

Navigate to: **DNS >> Delivery : Load Balancing : Pools : Pool List**

.. image:: /class/media/class2_dns__pool_create_flyout.png
  :align: center
  :scale: 50%

Create a pool according to the following table:

.. csv-table::
   :header: "Setting", "Value"
   :widths: 15, 15

   "Name", "dns_pool"
   "Health Monitors", "example.com_dns_monitor"
   "Node Name", "dns01_node"
   "Address", "10.1.20.4"
   "Service Port", "53"

.. image:: /class/media/create_pool.png


.. admonition:: TMSH

   tmsh create ltm pool dns_pool members add { dns01_node:53 { address 10.1.20.4 }  } monitor example.com_dns_monitor
