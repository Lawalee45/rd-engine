# WS reconnect latency investigation
Reproduced p99 spikes at 8-10k concurrent sockets. Hypotheses: connection-pool
exhaustion vs. event-loop head-of-line blocking. Results inconclusive.
