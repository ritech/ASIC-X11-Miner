### Manual

DR-2 mining device can be configured and managed via web user interface instead of CLI which make it easier and simpler for users who is not a big fan of commands in terminals. 

By following the steps below, DR-2 can be easily setup to work.

Note: For each machine, the default private IP address is set to be ``192.169.1.200``.

* If your router in your network is set within the range of ``192.168.1.*`` e.g. ``192.168.1.1``, simply plug in the miner, and connect ethernet cable with your router directly would enable it.

  * Visit ``http://192.168.1.200`` with a modern web browser from a computer connected to the same network (Google Chrome Recommended) and use the default password ``admin`` to login. The password ``admin`` is all lowercased. 

* If your router isn't within the network as ``192.168.1.1``,  there are two options to make it work:

  * 1. Reconfig your route to be ``192.168.1.1``
  * 2. Reconfig your DR-2's IP
    * Change your computer's private IP address to be ``192.168.1.5``,  subnet mask ``255.255.255.0``, leave the gateway ip blank. Then connect the miner to your computer directly via a Ethernet cable. 
    * Visit ``http://192.169.1.200`` since you're in the same network now. Once you are able to get access to the web interface of DR-2, simply click on ``Network Configure``, and modify the IP address of the Miner to whatever you want. 

*PLEASE BE VERY CAREFUL HERE*. Any misconfig may result in making you miner unacccessable.

* In ``Pool Configure`` section, you can set up the username and password for mining and mineral pools address.
Mining pool address format shoule be ``ip: port`` (e.g ``minepool.in:7903``). Click ``apply``, your miner will start mining automatically in 10 seconds.
* In ``asic status`` section, the working status for the chips will be displayed.
