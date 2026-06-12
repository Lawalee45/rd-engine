# Cache coherence A/B/C test
A: write-through+TTL. B: lease invalidation. C: version-vector merge. All three
still exhibit split-brain write loss on heal. None acceptable yet.
