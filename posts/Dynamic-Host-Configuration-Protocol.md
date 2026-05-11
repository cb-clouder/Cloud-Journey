In this lesson I learned about DHCP which helps devices on the same network communicate without manual setup.


## DHCP

Dynamic Host Configuration Protocol

- Acknowledge: The fourth and final step in the DORA process, where the chosen DHCP server confirms the lease of the IP address and provides the full network configuration.

- Automatic Private IP Addressing (APIPA): A fallback mechanism where a device assigns itself an IP address in the 169.254.x.x range if it cannot reach a DHCP server. This allows only local network communication and prevents internet access.

- DHCP Scope: The defined range of IP addresses and related settings that a DHCP server is authorized to assign to client devices.

- DORA: The four-step process (Discover, Offer, Request, Acknowledge) that allows a client device to automatically obtain an IP address and network settings from a DHCP server, ensuring the device can connect and communicate on the network.

- Discover: The first step in the DORA process, where the client device broadcasts a request to find available DHCP servers.

- Dynamic Host Configuration Protocol (DHCP): A network service that automatically assigns IP addresses and other configuration details to devices, so they can communicate on a network without manual setup.

- Exclusion: An IP address or range of addresses within a DHCP scope that is reserved and not assigned to clients, often used for servers, printers, or other devices that require static addresses.

- IP Address Conflict: A situation where two devices are assigned the same IP address, causing communication failures and connectivity issues.

- Lease: The temporary duration for which a DHCP server assigns an IP address to a client. When it expires, the client must renew it or request a new address.

- Lease Duration: The length of time a DHCP-assigned IP address is valid before the client must renew it.

- Offer: The second step in the DORA process, where DHCP servers respond with an available IP address, configuration details, and a lease time.

- Pool: The collection or range of IP addresses that a DHCP server manages and distributes to client devices.

- Request: The third step in the DORA process, where the client chooses one offer and broadcasts its acceptance to all DHCP servers.
