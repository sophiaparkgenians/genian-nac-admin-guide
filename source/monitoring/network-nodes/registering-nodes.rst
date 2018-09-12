Registering Nodes
=================

You can manually register a **Node** by specifying an **IP** address and a **MAC** address or multiple Nodes at a time by importing a file that contains Node information.
This may be done when you need to reserve a Node that will be detected as a new one so that **IPAM Policy for New Node** will apply immediately.

If you add a Node with either an IP address only or a MAC address only, you will not be able to see it as a Node on the Node view pane.
This is because registering an IP address only or a MAC address only is considered as an available IP address or an available MAC address, not as a **Node**.
However, you can find how many available IP addresses or MAC addresses are reserved as you see the number with brackets displayed at the end of the Policy Server on the tree view in the left upper panel. 
(*Go to* **Preferences > General > Console** *and enable* **Displaying IP Available** *to acheive this result.*)
So that you can see the Node you registered by clicking the Policy Server on the tree view in the left panel. The icon(s), |available-ip-icon|/|available-mac-icon|, which indicate(s) availability status, appear(s) in the **Status** column.
To see an IP address reserved in simpler way, you can go to **Management > IP Address** and click a **Sensor** to discover IP address utilization status at a glance in **IP Matrix View** to find an IP address with a green box that indicates **IP Reserved**.
(*The color also can be editable through Legend settings.*)


Manually Add A Node through Tasks
---------------------------------

#. Go to **Management > Node** in the top panel
#. Click **Tasks** button in the View pane
#. Find and click **Node / Device Management > Add Node** in the expanded drop-down menu
#. Specify an IP address and a MAC address to be registered as a Node (*If only IP address is specified, it will be registered automatically as an available IP address.*)
#. Configure the **IP Policy for New Node** and **MAC Policy** settings
#. Click **Save**, then a success message will appear
#. Click **Close** after confirming the settings you configured

.. note:: If you specify **Number of Nodes**, the consecutive IP addresses will be reserved as many as you specify.

Manually Add Nodes Through File Import
--------------------------------------

#. Go to **Management > Node** in the top panel
#. Click **Tasks** button in the View pane
#. Find and click **Node / Device Management > Add Multiple Nodes** in the expanded drop-down menu
#. Click **Select File** button to import a file (*The file must be specified with a column name and the value.*)
#. Click **Import**
#. Click **Close**

.. note:: Make sure that the file must be saved as \*.CSV format.


.. |available-ip-icon| image:: /images/available-ip-icon.PNG
.. |available-mac-icon| image:: /images/available-mac-icon.PNG