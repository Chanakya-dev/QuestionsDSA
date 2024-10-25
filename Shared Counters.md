# Basic Sharded Counters Problems

1. **Implement a Basic Sharded Counter**  
   Write a function to create a basic sharded counter that increments a value across multiple shards.

2. **Retrieve the Current Count**  
   Create a function that retrieves the current count from all shards and returns the total.

3. **Incrementing a Counter**  
   Write a function that increments the counter for a specific shard.

4. **Resetting a Shard**  
   Implement a function to reset the count of a specific shard back to zero.

5. **Load Balancing**  
   Create a function that distributes increments evenly across the available shards.

6. **Get Count by Shard**  
   Write a function to get the count from a specific shard.

7. **Total Count after Reset**  
   Implement a function to reset all shards and return the total count before resetting.

8. **Synchronization Across Shards**  
   Create a function that ensures that increments across different shards are synchronized.

9. **Concurrency Control**  
   Write a function to handle concurrent increments safely using locks or atomic operations.

10. **Testing the Sharded Counter**  
    Create a test function that simulates concurrent increments and verifies the total count.

# Sharded Counters MCQs

1. **What is a sharded counter?**  
   A) A counter that uses multiple shards to store values.  
   B) A counter that only allows single-threaded access.  
   C) A counter that only works with integers.  
   D) A counter that cannot be reset.  
   **Answer:** A

2. **What is the main advantage of using sharded counters?**  
   A) Reduced memory usage.  
   B) Increased performance and scalability.  
   C) Simplified code.  
   D) No need for concurrency control.  
   **Answer:** B

3. **Which of the following best describes the operation of a sharded counter?**  
   A) A single central counter that handles all increments.  
   B) Multiple counters (shards) that aggregate their values.  
   C) A counter that only increments and never decrements.  
   D) A counter that maintains its value in a database.  
   **Answer:** B

4. **In a sharded counter, what happens if multiple threads try to increment the same shard simultaneously?**  
   A) An error occurs.  
   B) The increments are lost.  
   C) The increments may lead to incorrect totals unless handled properly.  
   D) The shards will automatically synchronize.  
   **Answer:** C

5. **What is the typical use case for a sharded counter?**  
   A) Counting user visits to a website.  
   B) Storing user information.  
   C) Sorting data.  
   D) Encrypting data.  
   **Answer:** A

# Fill in the Blanks

1. A sharded counter splits the count across multiple __________.

2. The main benefit of using sharded counters is to improve __________ and scalability.

3. When multiple threads increment the same shard, it can lead to __________ if not managed properly.

4. Each shard in a sharded counter typically maintains its own __________.

5. To retrieve the total count from a sharded counter, you must sum the counts from all __________.

6. A common technique to prevent race conditions in sharded counters is to use __________.

7. Sharded counters are often used in distributed systems to handle high __________.

8. The process of evenly distributing increments across shards is called __________.

9. Increments across different shards should ideally be __________ to maintain data integrity.

10. A reset function in a sharded counter typically sets all shard counts to __________.
