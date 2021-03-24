benign_trojan_18000_model_1_transformed.csv

# ==== Protocol ====

SMPP = 9
GQUIC = 8
KNXnet/IP = 7
WebSocket = 6
ICMP = 5
HTTP = 4
TLSv1.3 = 3
TLSv1.2 = 2
tcp = 1
udp = 0

# ==== Type ====

out 0
in 1

# ===== LABEL =====
Benign 0
Trojan 1

# Source,Destination,Protocol,Length,Type,Duration,Label

Source is port packet source
Destination is port packet Destination
Protocol
Length
Type based on IP, if source local to external destination means "out"
Duration is based on time current packet to previous packet (from A to B)