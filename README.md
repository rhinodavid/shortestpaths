# Shortest Paths

## Overview

This application computes the shortest paths between all vertex pairs in a directed
graph using the
[Bellman-Ford algorithm](https://en.wikipedia.org/wiki/Bellman%E2%80%93Ford_algorithm).
It returns the total cost of the shortest of the shortest paths, and detects
if there is a negative-cost directed cycle within the graph (in which case the cost
of the shortest paths is invalid).

## Input format

The graph must be represented by an adjacency list in a text file. The first line
must contain the number of verticies in the graph. Each additional line must contain
three integers representing an edge, with the first integer being the id of the tail
vertex, the second the id of the head vertex, and the third the edge cost. Vertex ids
must range from 1 to _n_, the total number of verticies.

## Usage

```
go run main.go -i test_set.txt
```
