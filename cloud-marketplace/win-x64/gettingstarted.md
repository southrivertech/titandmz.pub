# <img src="https://srtcdnstorage.blob.core.windows.net/software/nextgen/titandmz/titandmz48.png" alt="Titan DMZ Server logo"> Titan DMZ Server - Enterprise Cloud Edition for Windows</img>

Thank you for choosing Titan DMZ Server - Cloud Edition from South River Technologies. This is the Pay-as-you-go version of our solution, meaning that it will run fully featured without the need to purchase a license from South River Technologies. Simply fire up your Titan DMZ Server VM, and run your business.

## What's on the VM?

This Titan DMZ Server Virtual Machine (VM) contains a pre-built and pre-configured installation of the product. 

## Features of Titan DMZ Server

Titan DMZ Server is a reverse proxy server that provides perimeter security for your Titan MFT implementation. Enabling you to close ports on your firewall, Titan MFT dynamically opens outbound ports to communicate with Titan DMZ. User requests are sent by the Titan DMZ Server to Titan MFT as a response on the dynamically opened channel. Working exclusively as a passthrough, no data is ever stored on or outside your firewall.

## Getting Started

To launch the Titan DMZ Server Administrator UI point your browser to your VM's public url or IP address. The first time you run the Administrator it will prompt you to create a new Administrator account to allow configuring the Titan DMZ Server. 

## Configure Titan DMZ Server for External access

The Titan DMZ Server instance has been preconfigured for access from an external Titan MFT server via port 45100. The public ports that Titan DMZ will proxy to the Titan MFT Server will configured on your Titan MFT server but you will need to make sure the cloud provider firewall will allow those external ports through. For example, the Titan MFT server may wish for the Titan DMZ Server to publicly listen on port 2200 for SFTP connections. In this case you will need to configure the cloud provider to allow inbound connections on port 2200 as well as the cloud provider firewall settings.

- `Port Setup` - Titan DMZ services are running behind both a Windows Firewall and the main Azure/AWS firewall. Your cloud provider will issue a public IP address, or DNS name, for your VM. In order for Titan DMZ Server services to function properly, Titan DMZ Server must be configured with the External IP address of the router/firewall.

- `Private IP Address` - set this to the desired listening IP address where Titan MFT will connect to the Titan DMZ Server.

- `Public IP Address` - set this to the desired public IP address issued by your cloud provider for external connections to be proxied to the Titan MFT server.

## Tech Support

Complimentary technical support is available on our website at https://helpdesk.titandmz.com (use TitanDmzPAYG as your registration code)

## WebSite(s)

South River Technologies corporate WebSite:  [https://www.SouthRiverTechnologies.com](https://www.SouthRiverTechnologies.com)<br />
Titan MFT (Enterprise grade Managed File Transfer Solution): [https://www.TitanMFT.com](https://www.TitanMFT.com)<br />
Titan DMZ Server (Secure reverse proxy server for Titan MFT): [https://www.TitanDMZ.com](https://www.TitanDMZ.com)<br />
Titan SFTP Server micro site: [https://www.TitanFTP.com](https://www.TitanFTP.com)<br />
WebDrive (Virtual Drive Mapping Client): [https://www.WebDrive.com](https://www.webdrive.com)<br />

