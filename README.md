UPI Offline Mesh — Demo
A Spring Boot backend that demonstrates offline UPI payments routed through a Bluetooth-style mesh network. You're in a basement with zero connectivity. You send your friend ₹500. Your phone encrypts the payment, broadcasts it to nearby phones, and the packet hops device-to-device until some phone walks outside, gets 4G, and silently uploads it to this backend. The backend decrypts, deduplicates, and settles.

This repo is the server side of that system, plus a software simulator of the mesh so you can demo the whole flow on a single laptop without any real Bluetooth hardware.
