# summary class 29

- Hash
is result of some algorithm take string as an input and convert to security  data.

- Buckets
is contained in each index of the array of the hashtable. contain multiple key/value pairs if a collision occurs.


- Collisions
is what happens when more than one key gets hashed to the same location of the hashtable.

each node or backet has both a key, and a value. the main idea of hashtable store the key into this data structure, and quickly retrieve the value. the time of hashtable is O(1). in hashing a hash code turns a key into an integer.

create the array for hash map then  appropriate size, do some sort of logic to turn that “key” into a numeric number value.

collisions happen when more than one key hashes to the same index in an array.

when you need to save the value in hash map, hash map do this accept a key, calculate the hash of the key, use modulus to convert the hash into an array index and store the key with the value by appending both to the end of a linked list. but when you read from hash map accept a key, calculate the hash of the key, use modulus to convert the hash into an array index, use the array index to access the short LinkedList representing a bucket and search through the bucket looking for a node with a key/value pair that matches the key you were given.

## Bucket Sizes
the number of bucket is unlimited. If a hash map has only a few buckets it will be densely full and have many collisions. If a hash map has more buckets it will be more sparsely populated, there will be less collisions, but there may be a lot of extra empty space.

## Method in hash map
we have Add() to add new key/value, Find(), Contains() and GetHash().

