# Grace Hash Join

## Overview

Implemented a two-phase Grace Hash Join in C++ for joining disk-resident relations under a strict 16-page memory budget.  
Partitioned both inputs into disk-backed buckets, then built an in-memory hash table on the smaller side of each partition during probing.  
Managed page loads, output buffering, flushes, hash collisions, and relation-size asymmetry to produce correct joins with controlled I/O.

## What This Demonstrates

- Hash partitioning
- Join processing
- Buffer and memory management

## Technologies

C++

## Source Code Availability

Source code can be provided upon request.
