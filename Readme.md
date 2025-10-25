Breadth-First Search: Shortest Path Between Two Actors
This project is part of CS50’s Introduction to Artificial Intelligence.
It implements a Breadth-First Search (BFS) algorithm to find the shortest path between two actors through the movies they have starred in together.

The function shortest_path(source, target) returns a list of (movie_id, person_id) pairs representing the connection chain.

Limitations
This implementation may perform slowly on large datasets, especially if the frontier contains many nodes or if contains_state() performs linear lookups.