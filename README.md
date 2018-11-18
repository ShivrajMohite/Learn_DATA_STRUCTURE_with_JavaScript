# Learn_DATA_STRUCTURE_with_JavaScript
📝 Algorithms and data structures implemented in JavaScript with explanations
<br>
## 1) Stack :-
Stack is a linear data structure which follows a particular order in which the operations are performed. The order may be <b>LIFO(Last In First Out) or FILO(First In Last Out)</b>.
![stack1](https://user-images.githubusercontent.com/34600724/48676520-11201a00-eb8e-11e8-9d1e-ec152242d4a2.jpg)
<br>
## Stack representation :-
The following diagram depicts a stack and its operations 

![stack2](https://user-images.githubusercontent.com/34600724/48676531-1c734580-eb8e-11e8-8a50-35e76902f22e.jpg)
<br>
## Functions:-
<ul>
<li><b>Push :- </b> Push for placing data onto a stack</li>
<li><b>POP :-</b> Pop for removing the top element of a stack</li>
<li><b>Peak :-</b> peak for displaying the top element of a stack</li>
<li><b>Length/Size :-</b> Determining how many elements are on a stack</li>
</ul>
<br>

## Sets-
<br>

## 3) Queue :-
The queue data structure is a way to hold data, it’s similar to a stack while a stack is first in last out  and a queue is first in first out. An example of an real life when you were waiting in line to buy something in store the first person get in the line is the first person to get to the cash register.

![queue1](https://user-images.githubusercontent.com/34600724/48676541-31e86f80-eb8e-11e8-9ba9-e92cc147c7c2.jpg)
<br>
## Queue Representation -
As we now understand that in queue, we access both ends for different reasons. The following diagram given below tries to explain queue representation as data structure –

![queue2](https://user-images.githubusercontent.com/34600724/48676544-34e36000-eb8e-11e8-8162-3e0d5fba25c7.jpg)
<br>

## 4) Binary Search Tree :-
<p>A tree data structure is a way to hold data that when visualized looks like a tree you would see in nature. All data points in tree are called nodes, the top of the tree is called root node and from it branches out into additional nodes.</p>
<p><b>A Binary Search Tree (BST) is a tree in which all the nodes follow the below-mentioned properties −</b>
<ul>
<li>The left sub-tree of a node has a key less than or equal to its parent node's key.</li>
<li>The right sub-tree of a node has a key greater than to its parent node's key.</li>
</ul>
</p>
<p><b>Following are the basic operations of a tree −</b>
<ul>
<li><b>Search − </b> Searches an element in a tree.</li>
<li><b>Insert − </b> Inserts an element in a tree.</li>
<li><b>Pre-order Traversal −</b> Traverses a tree in a pre-order manner.</li>
<li><b>In-order Traversal −</b> Traverses a tree in an in-order manner.</li>
<li><b>Post-order Traversal −</b> Traverses a tree in a post-order manner.</li>
</ul>
</p>

![1](https://user-images.githubusercontent.com/34600724/48676556-6825ef00-eb8e-11e8-9ead-dd6c705249b7.jpg)<br>
fig.1
<br>

![2](https://user-images.githubusercontent.com/34600724/48676559-6c520c80-eb8e-11e8-8bf7-2caefe234526.jpg)<br>
fig.2
<br>

![3](https://user-images.githubusercontent.com/34600724/48676561-707e2a00-eb8e-11e8-964a-cbe205a98c14.jpg)<br>
fig.3
<br>

![4](https://user-images.githubusercontent.com/34600724/48676563-72e08400-eb8e-11e8-9b0e-04ee579c1e9b.jpg)<br>
fig.4
<br>

![5](https://user-images.githubusercontent.com/34600724/48676564-7542de00-eb8e-11e8-869e-14039ba509d6.jpg)<br>
fig.5
<br>

![6](https://user-images.githubusercontent.com/34600724/48676565-796efb80-eb8e-11e8-9a86-bf3a2168f03f.jpg)<br>
fig.6
<br>


## 5)	Binary Search Tree: Traversal & Height
## Traversal – 
A traversal is a process that visits all the nodes in the tree. Since a tree is a nonlinear data structure, there is no unique traversal. We will consider several traversal algorithms with we group in the following two kinds.
<ul>
<li>depth-first traversal</li>
<li>breadth-first traversal</li>
</ul>
<b>There are three different types of depth-first traversals :</b>
<ul>
<li><b>PreOrder traversal -</b> visit the parent first and then left and right children;</li>
<li></b>InOrder traversal -</b> visit the left child, then the parent and the right child;</li>
<li><b>PostOrder traversal -</b> visit left child, then the right child and then the parent;</li>
</ul>

There is only one kind of breadth-first traversal--the level order traversal. This traversal visits nodes by levels from top to bottom and from left to right.

 As an example consider the following tree and its four traversals:
 <br>
 
![binary_search_tree_traversal_height](https://user-images.githubusercontent.com/34600724/48676760-411cec80-eb91-11e8-9b40-c7d0b0b832e0.jpg)
<br>

<ul>
<li><b>PreOrder – </b>9,4,3,6,5,7,17,10,22,20<li>
<li><b>InOrder –</b> 3,4,5,6,7,9,10,17,20,22<li>
<li><b>PostOrder –</b> 3,5,7,6,4,10,20,22,17,9<li>
<li><b>LevelOrder –</b> 9,4,17,3,6,10,22,5,7,20<li>
</ul>

## 6)	Hash Table :-
In hashing, large keys are converted into small keys by using <b>hash functions</b>. The values are then stored in a data structure called <b>hash table</b>.
<br>

![hash_table](https://user-images.githubusercontent.com/34600724/48676908-8f32ef80-eb93-11e8-94a8-a76531dfee06.jpg)
<br>

<p>Hashing is a technique that is used to uniquely identify a specific object from a group of similar objects. Some examples of how hashing is used in our lives include:
<ul>
<li>In universities, each student is assigned a unique roll number that can be used to retrieve information about them.</li>
<li>In libraries, each book is assigned a unique number that can be used to determine information about the book, such as its exact position in the library or the users it has been issued to etc.</li>
</ul>
</p>

<p>A hash table used to implement associative array of mapping of key value pairs. Hash table are common mapping implement the map data structure or object.</p>

<p>In JavaScript , hash table are usually used to implement objects. However it can be helpful to see how they are implemented just to gain better understanding </p>

## 7)	Linked List :-
A linked list is a linear data structure, in which the elements are not stored at contiguous memory locations. The elements in a linked list are linked using pointers as shown in the below figure.
<br>

![ll1](https://user-images.githubusercontent.com/34600724/48676917-b2f63580-eb93-11e8-8339-08489e72d587.jpg)<br>

![linked_list](https://user-images.githubusercontent.com/34600724/48676923-b7225300-eb93-11e8-85a6-12801c1f794b.jpg)<br>

## Array Vs Linked List :- 
![arrayvslinked](https://user-images.githubusercontent.com/34600724/48676934-cacdb980-eb93-11e8-89bd-29f2cd44ed3b.jpg)

## 8)	Trie :- 
A trie sometimes called prefix tree is a special type of tree used to store associative data structure.
See the below diagram is example of an trie.

![trie](https://user-images.githubusercontent.com/34600724/48676940-e20ca700-eb93-11e8-9ac0-06a2ac5c8e5b.jpg)
<br>

<b>Where:</b><br>

Star (*) indicates end of the word.<br>

<b>Words</b>

<ul>
<li>ball</li>
<li>bat</li>
<li>do</li>
<li>doll</li>
<li>dork</li>
<li>dorm</li>
<li>send</li>
<li>sence</li>
</ul>


## 9)	Heap :- 
Heap is a special case of balanced binary tree data structure where the root-node key is compared with its children and arranged accordingly. If <b>α</b> has child node <b>β</b> then −
<b>key(α) ≥ key(β)</b>

![heap_cropped](https://user-images.githubusercontent.com/34600724/48676951-f9e42b00-eb93-11e8-945a-56e13494b81c.jpg)<br>

<p>The heap properties indicates a specific relationship between the parents node and child nodes you may a max-heap in which all parent nodes are equal than or greater to than the child nodes so you can see the biggest numbers on top and the smallest numbers are bottom or you may have a min heap in which all child nodes are greater than or equal to parent node so the child nodes are biggest one and the parent nodes are smallest one. See the bellow figure max heap and min heap.</p>

![maxmin_heap](https://user-images.githubusercontent.com/34600724/48676952-fe104880-eb93-11e8-8159-44ea70b5a1ec.jpg)<br>

## Min heap visualizations :- click the below link
### <a>https://www.cs.usfca.edu/~galles/visualization/Heap.html</a>


![heap3](https://user-images.githubusercontent.com/34600724/48676954-010b3900-eb94-11e8-8414-c5c6daa71330.jpg)<br>

## 10)	Graph :- 
<p>The graph data structure is not the same as a graph you may have learned about a math class. Graphs are collection of things and the relationship between them. The data in a graph are called nodes or vertices the connection between the nodesare called edges, one example of graph is a social network where the nodes are you and other people and the edges are whether two people are friends with each other.</p>

There are two major types of graph.
<ul>
<li><b>Directed Graph- </b> Directed graphs are graphs with a direction and its adges </li>
<li><b>Undirected Graph- </b>Undirected graphs are graphs without any direction on the edges between nodes  </li>
</ul>

![graph1](https://user-images.githubusercontent.com/34600724/48676957-1b451700-eb94-11e8-804e-c6e46877448b.jpg)<br>

Following two are the most commonly used representations of a graph.
<ul>
<li><b>Adjacency Matrix</b></li>
<li><b>Adjacency List</b></li>
</ul>

There are other representations also like, Incidence Matrix and Incidence List. The choice of the graph representation is situation specific. It totally depends on the type of operations to be performed and ease of use.

### Adjacency Matrix:
Adjacency Matrix is a 2D array of size V x V where V is the number of vertices in a graph. Let the 2D array be adj[][], a slot adj[i][j] = 1 indicates that there is an edge from vertex i to vertex j. Adjacency matrix for undirected graph is always symmetric. Adjacency Matrix is also used to represent weighted graphs. If adj[i][j] = w, then there is an edge from vertex i to vertex j with weight w.
The adjacency matrix for the above example graph is:

![graph2](https://user-images.githubusercontent.com/34600724/48676959-1f713480-eb94-11e8-98cf-380ae32f87bc.jpg)<br>

### Adjacency List:
An array of lists is used. Size of the array is equal to the number of vertices. Let the array be array[]. An entry array[i] represents the list of vertices adjacent to the ith vertex. This representation can also be used to represent a weighted graph. The weights of edges can be represented as lists of pairs. Following is adjacency list representation of the above graph.

![graph3](https://user-images.githubusercontent.com/34600724/48676962-2435e880-eb94-11e8-901d-f9bce9b28bc5.jpg)

## 11)	Graphs: breadth-first search :-
Breadth First Search (BFS) algorithm traverses a graph in a breadthward motion and uses a queue to remember to get the next vertex to start a search, when a dead end occurs in any iteration.

![bfs](https://user-images.githubusercontent.com/34600724/48676967-36b02200-eb94-11e8-86d1-8c140a7b6ec9.jpg)<br>

As in the example given above, BFS algorithm traverses from A to B to E to F first then to C and G lastly to D. It employs the following rules.
<ul>
<li><b>Rule 1 −</b> Visit the adjacent unvisited vertex. Mark it as visited. Display it. Insert it in a queue.</li>
<li><b>Rule 2 −</b> If no adjacent vertex is found, remove the first vertex from the queue.</li>
<li><b>Rule 3 −</b> Repeat Rule 1 and Rule 2 until the queue is empty.</li>
</ul>
