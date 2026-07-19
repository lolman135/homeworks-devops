```
tcpdump: verbose output suppressed, use -v[v]... for full protocol decode
listening on en0, link-type EN10MB (Ethernet), snapshot length 524288 bytes
14:26:12.334659 IP 192.168.0.101.59620 > 172.67.134.250.https: Flags [SEW], seq 568954508, win 65535, options [mss 1460,nop,wscale 6,nop,nop,TS val 2905550189 ecr 0,sackOK,eol], length 0
14:26:12.433406 IP 172.67.134.250.https > 192.168.0.101.59620: Flags [S.E], seq 442895333, ack 568954509, win 65535, options [mss 1400,sackOK,TS val 229004361 ecr 2905550189,nop,wscale 13], length 0
14:26:12.433601 IP 192.168.0.101.59620 > 172.67.134.250.https: Flags [.], ack 1, win 2061, options [nop,nop,TS val 2905550288 ecr 229004361], length 0
14:26:12.433866 IP 192.168.0.101.59620 > 172.67.134.250.https: Flags [P.], seq 1:339, ack 1, win 2061, options [nop,nop,TS val 2905550288 ecr 229004361], length 338
14:26:12.472577 IP 172.67.134.250.https > 192.168.0.101.59620: Flags [.], ack 339, win 16, options [nop,nop,TS val 229004457 ecr 2905550288], length 0
14:26:12.474858 IP 172.67.134.250.https > 192.168.0.101.59620: Flags [.], seq 1:1409, ack 339, win 16, options [nop,nop,TS val 229004459 ecr 2905550288], length 1408
14:26:12.474860 IP 172.67.134.250.https > 192.168.0.101.59620: Flags [P.], seq 1409:2817, ack 339, win 16, options [nop,nop,TS val 229004459 ecr 2905550288], length 1408
14:26:12.474862 IP 172.67.134.250.https > 192.168.0.101.59620: Flags [P.], seq 2817:2825, ack 339, win 16, options [nop,nop,TS val 229004459 ecr 2905550288], length 8
14:26:12.474944 IP 192.168.0.101.59620 > 172.67.134.250.https: Flags [.], ack 2825, win 2017, options [nop,nop,TS val 2905550329 ecr 229004459], length 0
14:26:12.477091 IP 192.168.0.101.59620 > 172.67.134.250.https: Flags [P.], seq 339:345, ack 2825, win 2048, options [nop,nop,TS val 2905550331 ecr 229004459], length 6
14:26:12.477118 IP 192.168.0.101.59620 > 172.67.134.250.https: Flags [P.], seq 345:403, ack 2825, win 2048, options [nop,nop,TS val 2905550331 ecr 229004459], length 58
14:26:12.477183 IP 192.168.0.101.59620 > 172.67.134.250.https: Flags [P.], seq 403:489, ack 2825, win 2048, options [nop,nop,TS val 2905550332 ecr 229004459], length 86
14:26:12.477234 IP 192.168.0.101.59620 > 172.67.134.250.https: Flags [P.], seq 489:631, ack 2825, win 2048, options [nop,nop,TS val 2905550332 ecr 229004459], length 142
14:26:12.515934 IP 172.67.134.250.https > 192.168.0.101.59620: Flags [.], ack 403, win 16, options [nop,nop,TS val 229004500 ecr 2905550331], length 0
14:26:12.515937 IP 172.67.134.250.https > 192.168.0.101.59620: Flags [P.], seq 2825:2887, ack 403, win 16, options [nop,nop,TS val 229004500 ecr 2905550331], length 62
14:26:12.515940 IP 172.67.134.250.https > 192.168.0.101.59620: Flags [P.], seq 2887:2918, ack 489, win 16, options [nop,nop,TS val 229004500 ecr 2905550332], length 31
14:26:12.516049 IP 192.168.0.101.59620 > 172.67.134.250.https: Flags [.], ack 2887, win 2048, options [nop,nop,TS val 2905550370 ecr 229004500], length 0
14:26:12.516106 IP 192.168.0.101.59620 > 172.67.134.250.https: Flags [.], ack 2918, win 2048, options [nop,nop,TS val 2905550370 ecr 229004500], length 0
14:26:12.516318 IP 192.168.0.101.59620 > 172.67.134.250.https: Flags [P.], seq 631:662, ack 2918, win 2048, options [nop,nop,TS val 2905550371 ecr 229004500], length 31
14:26:12.557337 IP 172.67.134.250.https > 192.168.0.101.59620: Flags [.], ack 662, win 16, options [nop,nop,TS val 229004541 ecr 2905550332], length 0
14:26:12.620788 IP 172.67.134.250.https > 192.168.0.101.59620: Flags [P.], seq 2918:3458, ack 662, win 16, options [nop,nop,TS val 229004604 ecr 2905550332], length 540
14:26:12.620791 IP 172.67.134.250.https > 192.168.0.101.59620: Flags [P.], seq 3458:3590, ack 662, win 16, options [nop,nop,TS val 229004604 ecr 2905550332], length 132
14:26:12.620793 IP 172.67.134.250.https > 192.168.0.101.59620: Flags [P.], seq 3590:3621, ack 662, win 16, options [nop,nop,TS val 229004605 ecr 2905550332], length 31
14:26:12.620890 IP 192.168.0.101.59620 > 172.67.134.250.https: Flags [.], ack 3621, win 2038, options [nop,nop,TS val 2905550475 ecr 229004605], length 0
14:26:12.621305 IP 192.168.0.101.59620 > 172.67.134.250.https: Flags [P.], seq 662:686, ack 3621, win 2048, options [nop,nop,TS val 2905550476 ecr 229004605], length 24
14:26:12.622493 IP 192.168.0.101.59620 > 172.67.134.250.https: Flags [F.], seq 686, ack 3621, win 2048, options [nop,nop,TS val 2905550477 ecr 229004605], length 0
14:26:12.664232 IP 172.67.134.250.https > 192.168.0.101.59620: Flags [F.], seq 3621, ack 687, win 16, options [nop,nop,TS val 229004648 ecr 2905550476], length 0
14:26:12.664361 IP 192.168.0.101.59620 > 172.67.134.250.https: Flags [.], ack 3622, win 2048, options [nop,nop,TS val 2905550519 ecr 229004648], length 0
^C
28 packets captured
221 packets received by filter
0 packets dropped by kernel
```