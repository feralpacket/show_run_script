# show_run_script

Commands used to copy the current device configuration and state information such as the contents of the routing table or ARP table.  It's easier and quicker to use and review then running a show tech-support.

Useful to use on devices that see what normal looks like.  The output can be used to compare with when things are not working as expected.

Useful to use with tech refreshes.  It's not uncommon for an endpoint to stop working after a switch is replaced.  You can use the output to see what the MAC addess is, what IP address it was using at one point, and where it was connected.

Important, make changes to fit your environment.  If you are not using OSPF, removed those show commands.  Add show commands for protocols that are used in your network environment.

**SecureCRT**

These scripts can be used with SecureCRT's Button Bar feature.  You don't have to copy and paste the script.  Just make sure logging is enabled, then click the appropriate button.

