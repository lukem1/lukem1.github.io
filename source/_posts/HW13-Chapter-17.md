---
title: 'HW13: Chapter 17'
date: 2020-10-13 04:00:00
tags: CSCI362
---
## 17.10
**Your company wishes to move from using desktop applications to accessing the same functionality remotely as services. Identify three risks that might arise and suggest how these risks may be reduced.**

1. Security

Moving to this model will increase the attack surface of the infrastructure dramatically. Most importantly, this system will be much more prone to interception and interruption, as all work utilizing these services will need to constantly be sent between the clients and server, and if a problem arises with the server, or even anywhere else between the client and server, work using these services will be halted.

In order to reduce these risks care should be taken to ensure secure protocols are used and that the infrastructure supporting these services are also well protected.

2. Potential Infrastructure Limitations

This model will also cause tasks that require these services to be entirely dependent on the services' availability. All clients will require strong and stable connections to the server.

To minimize theses risks, it should be ensured that network infrastructure will be able to handle the increased traffic and scenarios including server, network outages should be considered.

3. Server Capacity Limitations

Similarly to the previous section, the server must also be able to handle the number of clients expected to begin utilizing its services.

Thus, server infrastructure should be allocated based on the expected amount of clients/work utilizing the services.
