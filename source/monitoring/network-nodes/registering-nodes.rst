Registering Nodes
=================

You can manually register a **Node** by specifying an **IP** address and a **MAC** address, or multiple Nodes at a time by importing a file that contains Node information. This may be done when you need to reserve a Node that will be 
detected as a new Node so that **IPAM Policy for New Node** will apply immediately.
If you add a Node with either an IP address only or a MAC address only, you will not be able to see it as a Node in Management > Node view.
Registering an IP address only or a MAC address only is considered as an available IP address or an available MAC address, not as a **Node**.

Manually Add Nodes Through File Import
--------------------------------------

You can save time by creating a list of Nodes in a CSV file to import

#. Go to **Management > Node** in the top panel
#. Click **Tasks > Node / Device Management > Add Multiple Nodes**
#. For **CSV**, click **Select File** (*The file must be specified with a column name and the value*)
#. Click **Import**
#. Click **Close**

Enable Displaying IP Available
------------------------------

You can see available IP addresses and MAC addresses after enabling a feature to show |available-ip-icon|/|available-mac-icon| in the Management > Node > Management Policy column

#. Go to **Preferences** in the top panel
#. Go to **General > Console** in the left Preferences panel Under **Web Console**
#. Find **Displaying IP Available**, select **On** to specify whether to display the number of IP(s) available in Tree Menu of Management page
#. Click **Update**
#. Go to **Management > Node** in the top panel
#. Find and click **Policy Server** in the left panel

See Reserved IP Addresses
-------------------------

You can see and confirm the IP addresses are reserved in Management > IP Address view

#. Go to **Management > IP Address** in the top panel
#. Find and click **Sensor** from list
#. Find all **IP Reserved** addresses with a **Green Box** as indicated from **Legend** on right (*The color also can be editable through Legend settings*)

.. note:: Make sure that the file must be saved as \*.CSV format.

.. |available-ip-icon| image:: /images/available-ip-icon.PNG
.. |available-mac-icon| image:: /images/available-mac-icon.PNG


