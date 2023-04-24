# PathFinder-Visualizer: - A REACT APPLICATION

## Overview:

This is a fun project on visualizing path finding algorithms i.e BFS, DFS, Dikstra’s , A\* algorithm.
This app is entirely built in react ...
Green box is the starting node and Red box is the end node.
You can see the various algorithms below to visualize.
Here design of grid is done using tables and set first node and second node colors using CSS properties.

## Intro ..

Path finding algorithms plays a vital role in our daily life such as packets in computer networks , google maps uses a path finding algorthm to find the shortest path.
So this project main idea is to visualize this path finding algorthms using react with the help of some css animations.

Let's check out some intuition behind this algorithms for better insights.

### Breadth First Search

- Breadth First Search explores equally in all directions.
- This is an incredibly useful algorithm, not only for regular traversal, but also for procedural map generation, flow field pathfinding, distance maps, and other types of map analysis.
- This may be the algorithm of choice to identify nearby places of interest in GPS.
- BFS guarantees the shortest path.

### Depth First Search

- Traverses by exploring as far as possible down each path before backtracking.
- As useful as the BFS: DFS can be used to generate a topological ordering, to generate mazes, to traverse trees, to build decision trees, to discover a solution path with hierarchical choices…
- DFS does not guarantee the shortest path.

### Dijkstra

- Dijkstra's Algorithm lets us prioritize which paths to explore. Instead of exploring all possible paths equally, it favors lower cost paths.
- We can assign lower cost to encourage moving on roads while assigning high cost on highway to avoid them.
- It is the algorithm of choice for finding the shortest path paths with multiple destinations.

## Deployment

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

---

---

## For more documentation and understanding.. check out following links..

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
