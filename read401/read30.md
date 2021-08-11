# Hash Tables

- **What is a Hashtable?**


    - **Hash :** *A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array ( A data structure that is used to store keys/value pairs)*

    - **Buckets :**  *A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.*

    - **Collisions :**  *A collision is what happens when more than one key gets hashed to the same location of the hashtable.*


- **Creating a Hash**

***A hashtable traditionally is created from an array. I always like the size 1024. this is important for index placement. After you have created your array of the appropriate size, do some sort of logic to turn that “key” into a numeric number value. Here is a possible suggestion:***

   - *Add or multiply all the ASCII values together. 2- Multiply it by a prime number such as 599. 3- Use modulo to get the remainder of the result, when divided by the total size of the array. 4- Insert into the array at that index.*

  - *Find()*

      *The Find takes in a key, gets the Hash, and goes to the index location specified. Once at the index location is found in the array, it is then the responsibility of the algorithm the iterate through the bucket and see if the key exists and return the value.*

  - *Contains()*

      *The Contains method will accept a key, and return a bool on if that key exists inside the hashtable. The best way to do this is to have the contains call the GetHash and check the hashtable if the key exists in the table given the index returned.*

  - *GetHash()*     
      *The GetHash will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.*


### Terminology

1. **Hash:**

    - *A hash is a result of some algorithm which takes a string and converts it into a value that could be used for security or some other purpose.*

    - *Hash tables utilize this number to determine the index of an array*

2. **Buckets:**

    - *A term to describe what is described in the index of each array. Each index is considered a bucket which means an index may contain multiple key value pairs*
3. **Collisions:**

    - *When more than one key/value pair gets hashed into the same location/index/BUCKET of the hashtable*



**Basics of Hash Tables**

***To achieve a good hashing mechanism, It is important to have a good hash function with the following basic requirements:***

  - **Easy to compute:**  *It should be easy to compute and must not become an algorithm in itself.*

  - **Uniform distribution:**  *It should provide a uniform distribution across the hash table and should not result in clustering.*

  - **Less collisions:** *Collisions occur when pairs of elements are mapped to the same hash value. These should be avoided.*