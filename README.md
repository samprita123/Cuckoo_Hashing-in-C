# Cuckoo_Hashing-in-C

This project was created for an academic course (mini Project in C Language).
this is an useful mini project for 1st Year students from IT background.

Defination
-----------
Cuckoo Hashing derived its name from the cuckoo bird, which lays its eggs in the nests of other birds, replacing their eggs with its own. Cuckoo Hashing works in a similar manner which involves moving the values to different location whenever there is a collision in the hash table. In this article, we will learn how to implement Cuckoo Hashing in C Language.

Cuckoo hashing maintains two separate hash tables and When a key collides in one table, it is moved to the other table using a different hash function. If the other table is also full or if the process encounters a cycle, the table is resized and rehashed.

Time Complexity: 
----------------
O(N), the time complexity of the Cuckoo Hashing algorithm is O(N), where N is the number of keys to be stored in the hash table. This is because the algorithm requires only one pass over the list of keys to place them in the hash table.

Auxiliary Space:
----------------
O(N), the space complexity of the Cuckoo Hashing algorithm is O(N), where N is the number of keys stored in the hash table. This is because the algorithm requires an auxiliary space of size equal to the hash table, where all the keys are stored.

