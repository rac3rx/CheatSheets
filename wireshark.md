Wireshark
  ip.addr==192.168.250.100 && udp.port==53
  ip.addr==172.19.250.100 && ip.dst!=172.19.250.0/24 && ip.dst!=172.19.145.0/24
  (ip.addr eq 172.19.145.129 and ip.addr eq 172.19.250.100) and (udp.port eq 53 and udp.port eq 43736)

