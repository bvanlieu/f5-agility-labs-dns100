Monitors
####################################

A DNS application specific monitor should be used to monitor pool members. 

Navigate to: **DNS >> Delivery >> Load Balancing >> Monitors**

.. image:: /class/media/class2_create_health-monitor_flyout.png
  :align: center
  :scale: 75%

Create a new monitor according to the following settings:

.. csv-table::
   :header: "Setting", "Value"
   :widths: 15, 15

   "Name", "example.com_dns_monitor"
   "Type", "DNS"
   "Query Name", "www.example.com"

.. image:: /class/media/class2_dns_monitor_create_properties.png
  :align: center
  :scale: 75%

.. admonition:: TMSH
 
   tmsh create ltm monitor dns example.com_dns_monitor defaults-from dns qname www.example.com

