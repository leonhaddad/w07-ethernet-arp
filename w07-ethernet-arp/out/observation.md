Task 1: A self-learning switch learns from the source address, floods only when it does not know the destination, and must trust the newest port when a station moves.
Task 1: Aging is also required, because stale entries keep forwarding to the wrong place after the host has gone quiet and the switch must forget that old evidence.
Task 2: The gateway is the first ARP entry to return because it is the local next hop that the machine needs immediately, so it is queried first and enters the table fastest.
Task 2: A server on the other side of the world is not in the ARP table because ARP only answers for directly connected neighbors on the same Ethernet segment, not for remote IPs behind routers.
Task 3: My eviction rule keeps the most recently used destinations instead of throwing out the oldest arrival, which cuts wasted deliveries while preserving all required deliveries.
Task 3: An attacker can fill the table with fake MACs and trigger a full-table flood; a switch can reduce the risk by limiting learning, rate-limiting entries, or using a more defensive admission policy.
