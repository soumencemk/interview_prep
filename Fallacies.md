# Fallacies of distributed computing

The fallacies are - 
### 1. The network is reliable: 

Software applications are written with little error-handling on networking errors. During a network outage, such applications may stall or infinitely wait for an answer packet, permanently consuming memory or other resources. When the failed network becomes available, those applications may also fail to retry any stalled operations or require a (manual) restart.
### 2. Latency is zero: 
Ignorance of network latency, and of the packet loss it can cause, induces application- and transport-layer developers to allow unbounded traffic, greatly increasing dropped packets and wasting bandwidth.
### 3. Bandwidth is infinite:
Ignorance of bandwidth limits on the part of traffic senders can result in bottlenecks.
### 4. The network is secure:
Complacency regarding network security results in being blindsided by malicious users and programs that continually adapt to security measures.
### 5. Topology doesn't change: 
Changes in network topology can have effects on both bandwidth and latency issues, and therefore can have similar problems.
### 6. There is one administrator: 
Multiple administrators, as with subnets for rival companies, may institute conflicting policies of which senders of network traffic must be aware in order to complete their desired paths.
### 7. Transport cost is zero:
The "hidden" costs of building and maintaining a network or subnet are non-negligible and must consequently be noted in budgets to avoid vast shortfalls
### 8. The network is homogeneous:
If a system assumes a homogeneous network, then it can lead to the same problems that result from the first three fallacies.