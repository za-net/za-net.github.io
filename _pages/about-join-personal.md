---
title: Connecting your Micro Node to ZA-Net
layout: tag
permalink: /about/join-personal/
taxonomy: markup
sidebar:
  nav: "zanet"
classes: wide
---

Once you have your personal Micro Node and are ready to connect...

Connect to Node 60721

Please ensure you adhere to [ZA-Net Etiquette](/network/etiquette/)

Getting up and running with our purchased Micro Node:
1. Program your radio to the frequency of your node.
2. Plug in the node and power it up.
3. It will take about 30 Seconds to boot up, and you should hear the IP address announced on your radio if your node was able to connect to the Wifi. Your node is setup to automatically connect to the Sandton repeater, so you will probably hear that announcement too.
4. On a browser go to http://IP_Address/supermon2. (Example if your node says your IP address is 192.168.0.10 then your link will be http://192.168.0.10/supermon2)
5. To login to the supermon page, your username is admin and the password is <<*yourpassword*>>
6. The node should have already connected you to the Sandton repeater (Node 60721). If not, you will find
this connection in the favourites along with a couple of others to try.
7. Remember that if you connect to more than one node, you will be relaying between the nodes!!
8. There are a number of DTMF commands you can use from your radio:
      - *76 Disconnects all nodes.
      - *81 Will announce the time (To you only)
      - *55 Will connect you to Sandton Repeater (Node 60721)
      - *A1 Will announce your IP address if you missed it on powerup
      - *3<node> Connect to a specific node number
      - *1<node> Disconnect a specific node number
9. The above should get you started. There is plenty of info on the web about the workings of Allstarlink or Hamvoip (which is the software loaded onto your node).
10. Your root password to ssh into the node is also <<*yourpassword*>>. You will need this to make configuration
changes to the node and to add the echolink service. 
