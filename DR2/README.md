### Manual

DR2 mining machine using web interface to config and manager, which is simpler and much friendly compare to the CLI.

By following these steps, you can easily complete DR2 setup work:

DR2'IP is factory set static IP, which is 192.168.1.200.

If the router in your network segment is set as 192.168.1.1, you can plug the miner to the router directly. 
Then use web browser to open http://192.168.1.200 (chrome chrome suggested).
The web interface password is admin (lowercase).

If your router within the network is set as 192.168.1.1. You have two option here:

1. Reconfig the route to 192.168.1.1
2. Config your computer's wired network card to  192.168.1.5 subnet mask 255.255.255.0, leave the gateway ip blank. 
Then you can plug the miner to your computer directly. 

Once you entered the web interface of DR2, you can click "Network Configure", and modify the ip address 
of the Miner to what ever you want. 
PLEASE BE VERY CAREFUL HERE. Any misconfig may result in makeing you miner unacccessable.

In the "Pool Configure" of web interface, you can configure the username and password mining and mineral pools Address
Mine pool address format ip: port (for example minepool.in:7903), click apply, your miner will begin to mine automatically in 10 seconds.

In the "asic status", you can view the working status of the chip.
