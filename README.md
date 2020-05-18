This repository has been created for experimenting the BBR-ACD scheme proposed in "BBR-ACD: BBR with Advanced Congestion Detection" in Linux Kernel. ***The article has been published in ELECTRONICS.***

**#Requirements and Dependencies:** <br />
Please access: include/net/inet_connection_socket.h and set: ICSK_CA_PRIV_SIZE to 12 * sizeof(u64). <br />

**#Instructions:** <br />
*How to Run:* <br />
Just replace the existing tcp_bbr.c in /usr/src/.../net/ipv4/.
make and make install for the directory.
reboot the system.
Change the default Congestion Algorithm to bbr

*Above development was based on the Linux version of 4.14.64+.*

********************************************************

Thanks.
Imtiaz Mahmud.

********************************************************
For any inquiry, please contact at imtiaz.tee@gmail.com.
