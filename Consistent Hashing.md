# Basic Consistent Hashing Problems

1. **Implement Basic Consistent Hashing**  
   Write a function to implement basic consistent hashing that maps keys to nodes in a distributed system.

2. **Add a Node**  
   Create a function that adds a new node to the consistent hashing ring and re-distributes keys as necessary.

3. **Remove a Node**  
   Implement a function that removes a node from the consistent hashing ring and redistributes the keys.

4. **Locate Node for a Key**  
   Write a function that finds the appropriate node for a given key based on the consistent hashing algorithm.

5. **Handle Key Distribution**  
   Create a function that demonstrates how keys are distributed across multiple nodes using consistent hashing.

6. **Visualize the Hash Ring**  
   Write a function to visualize the hash ring and the distribution of nodes and keys.

7. **Dynamic Node Scaling**  
   Implement a function to handle the addition and removal of nodes dynamically without significant key redistribution.

8. **Simulate Key Lookups**  
   Create a simulation to demonstrate how consistent hashing maintains key lookups as nodes are added and removed.

9. **Evaluate Load Distribution**  
   Write a function that evaluates how evenly the keys are distributed across the nodes in the consistent hashing ring.

10. **Testing Consistent Hashing**  
    Create a test function that validates the correctness of the consistent hashing implementation with various scenarios.

# Consistent Hashing MCQs

1. **What is consistent hashing primarily used for?**  
   A) To sort data.  
   B) To distribute keys across nodes in a distributed system.  
   C) To encrypt data.  
   D) To compress files.  
   **Answer:** B

2. **What happens when a new node is added in consistent hashing?**  
   A) All keys are redistributed to the new node.  
   B) Only a subset of keys is redistributed.  
   C) No keys are redistributed.  
   D) The system crashes.  
   **Answer:** B

3. **Which of the following is a key benefit of consistent hashing?**  
   A) It eliminates the need for a central authority.  
   B) It ensures even load distribution without a major reshuffling of keys.  
   C) It reduces the size of data.  
   D) It allows unlimited nodes without any overhead.  
   **Answer:** B

4. **In a consistent hashing ring, what is the primary data structure used to represent nodes?**  
   A) A linked list.  
   B) An array.  
   C) A binary tree.  
   D) A hash table.  
   **Answer:** D

5. **How does consistent hashing minimize data movement when nodes are added or removed?**  
   A) By using fixed-sized partitions.  
   B) By mapping keys to random nodes.  
   C) By using virtual nodes to balance the load.  
   D) By avoiding any data movement.  
   **Answer:** C

# Fill in the Blanks

1. Consistent hashing allows for the __________ of keys to nodes in a distributed system.

2. When a node is removed, consistent hashing minimizes key redistribution to __________.

3. The main advantage of consistent hashing is its ability to handle __________ efficiently.

4. Each node in a consistent hashing ring is assigned a __________ based on a hash function.

5. When a new node is added, only a portion of the keys need to be __________ to the new node.

6. Virtual nodes help improve the __________ of load distribution in consistent hashing.

7. The process of locating which node a key maps to involves traversing the __________ of nodes.

8. Consistent hashing is commonly used in __________ storage systems and load balancers.

9. The performance of consistent hashing can be affected by the choice of the __________ function.

10. In consistent hashing, the total number of nodes can be __________ without significant performance degradation.
