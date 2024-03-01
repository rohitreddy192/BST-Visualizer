# Binary Search Tree Visualizer

## Overview

The Java Binary Search Tree Visualizer is a desktop application/command-line tool that allows users to interactively visualize and explore Binary Search Trees (BST) implemented in Java. This tool provides a graphical representation of the BST, enabling users to insert, delete nodes within the tree. It serves as an educational resource for understanding the structure and operations of Binary Search Trees.

## Features

- **Interactive Visualization:** View the BST graphically, with nodes representing elements and edges indicating relationships.
- **Insertion:** Add new elements to the BST interactively.
- **Deletion:** Remove elements from the BST while maintaining its structure.

## Algorithm and Internal Details
- Implemented Binary Search Tree Algorithms making sure of BST properties, considering the insertion and deletion of nodes.
- **Insertion Property:-**
  1. When a new node to be inserted, we should search the position to insert by traversing through the BST recurrsively as follows-
      - **Traverse Left:-** If the newly insert node has a value less than the value at the current node we should traverse left, if there are no nodes on the left of it we can insert to its left.
      - **Traverse Right:-** If the newly inserted node has a value greater than the value at the current node we should traverse right, if there are no nodes on right of it we can insert to its right.
- **Deletion Property:-**
  1. When deleting a node a successor/predecessor should be considered which means, when an element is deleted a maximum value from its left sub tree or the minimum value from the right sub tree should be added to the position removed.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/rohitreddy192/BST-Visualizer.git

2. Once cloned run the BSTVisualization.java file to start making operations on BST.

