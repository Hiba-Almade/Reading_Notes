### Hash tables:

* Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose.

> In the case of a hashtable, it is used to determine the index of the array.

* Buckets - A bucket is what is contained in each index of the array of the hashtable.
* Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.
* Use hashtables to hold unique values, dictionary, and library.
* Hashtables - are a data structure that utilizes key value pairs. This means every Node or Bucket has both a key, and a value.

* Hashtable traditionally is created from an array. Each index of the array can hold many types of values. Each Index of the array contains “buckets”, and each of these “buckets” holds one key/value pair combination.

* Add() - when adding a new key/value pair to a hashtable
* Find() - takes in a key, gets the Hash, and goes to the index location specified.
* Contains() - will accept a key, and return a bool on if that key exists inside the hashtable.
* GetHash() - will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.
---

* Hash tables are used to store information.
* Has two main components: a key and a value.
* Hash function will take in a key value, and as a result will give an index number.
* The key will always match that index number, but if another key with the same index comes up, you have to make a chain off of the unit it is in.
* Hash tables can be very large, and store many key values.



#