1. each entry in ContouToSegment buffer indicates the starting segment id of this contour.
2. Last contour has no successor(after prefix sum/exlusive scan), the actual "successor" is total segment count, which is carried out into CachedArgs buffer.