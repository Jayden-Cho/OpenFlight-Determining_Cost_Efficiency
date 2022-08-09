# OpenFlights: Determining Cost Efficiency
CS 225 Final Project

> Seonggeun Cho (sc27)
>
> Jaeyoon Jeong (jyjeong2)
> 
> Jae Doo (jdoo2)
> 
> Sohyun Park (sohyunp3)

## Description
The purpose of this project is utilize the OpenFlights database which contains over 10,000 flight routes where airports were used as the vertex and flights were used as the edges. We constructed a weighted graph with newly-defined flight cost function. Two main algorithms - BFS traversal and Dijkstra's algorithm - are used to illustrate the possible flight path and capture the shortest path with minimum cost and least layovers, respectively.

## File Structure
* `Graph.h`, `Graph.cpp`: Constructs a weighted graph with the airports as the vertexs, pre-processes the OpenFlight dataset to calculate the estimated cost based on the distance-frequency feature of the flight.
* `BFS.cpp`: Implements BFS to compute all possible destinations from the source input.
* 'Dijkstra.cpp`: Calculates the route with the lowest cost from the given source and destination airport.
* `Visualization.h`, `Visualization.cpp`: Takes the edges from graph and draw them out on a PNG world map.

## How to run the Program
The program can be run by using the following commands:

        make
        ./main
