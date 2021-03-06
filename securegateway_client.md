---

copyright:
  years: 2015, 2017
lastupdated: "2017-04-25"

subcollection: securegateway

---

# Adding a Client
{: #add-client}

The {{site.data.keyword.SecureGateway}} Client is the piece of the puzzle that makes the magic happen.  The client establishes the initial connection between the on-premises network and a gateway on the {{site.data.keyword.SecureGateway}} servers and allows for communication to pass through to the defined destinations.

![New Gateway](./images/newGateway.png?raw=true "New Gateway")

From within your new gateway and on the Clients tab, click the Connect Client button to open the Connect Client panel.

![Connect Client](./images/connectClient.png?raw=true "Connect Client")

After selecting your preferred client, [click here to see how to install it](/docs/services/SecureGateway?topic=securegateway-client-install).

Once you have installed your client, you can configure it to [start automatically](/docs/services/SecureGateway?topic=securegateway-auto-start-conf) or to [run interactively](/docs/services/SecureGateway?topic=securegateway-client-interacting).

![Connected Client](./images/connectedClient.png?raw=true "Connected Client")

If you would like to configure the Access Control List for your client now, [click here for more details](/docs/services/SecureGateway?topic=securegateway-acl).

Now that you have your client connected, you can [create your first destination](/docs/services/SecureGateway?topic=securegateway-add-dest).
