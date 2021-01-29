# Concurrent-Traffic-Simulation

This project simulates traffic in a city grid with vehicles, streets and intersections. Vehicles drive around randomly 
and change direction. Each object in the city grid will run independently in its own thread.

I have added some new features in order to work for its intended puporse.

This project is based on udacity C++ nanodegree program.

# Added Feature

As there are a lot of vehicles that share the streets and thus the traffic load increases, there is a need for traffic light system for the road user safety. 
The traffic lights should be installed at every interesection in the city grid. Consequently, there should be a suitable and thread-safe communication protocol between vehicles, intersections, and traffic ligths. This is done through concurrent programming such as mutexes, locks and especially message queues to implement such traffic lights and to integrate them properly in the codebase. 
