# Hash Tables

## What is a Hashtable?

a hashtable is a data structure that utilizes key value pairs. This means every Node or Bucket has both a key, and a value.

## Why do we use them?

we use hashtables for quick lookups. This is important because it allows us to access a value in O(1) time. A real world example is a dictionary. If we want to find the definition of a word, we can look it up in a dictionary, and find the definition in O(1) time.

## How are they structured?

hashtables are structured by using a hash function to convert a key into an integer, and then using that integer to access an index in an array the size of the hashtable. This allows us to store the value at that index, and then access it later by using the same hash function to convert the key into the same integer, and then access the index in the array at that integer.

## What is a Hash?

a hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.

## What is a Bucket?

a bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. Each bucket is a node. Each node (bucket) is comprised of a key and a value.

## Walk through

Create a function called hash that takes in an arbitrary key and returns an index in the collection.

```
const hash = (key, size) => {
  let hashedKey = 0
  for (let i = 0; i < key.length; i++) {
    hashedKey += key.charCodeAt(i)
  }
  return hashedKey % size
}
```

Create a class called HashTable that has a constructor that takes in a size and creates an array of that size.

```
class HashTable {
  constructor(size){
    this.size = size
    this.buckets = Array(this.size)

    // populate each bucket with a Map()
    for (let i = 0; this.buckets.length; i++) {
      this.buckets[i] = new Map()
    }
  }
}
```

The HashTable class can have 5 methods but we will use 3 for this walkthrough.

```
 insert(key, value) {
    let idx = hash(key, this.size)
    this.buckets[idx].set(key, value)
  }

  remove(key) {
    let idx = hash(key, this.size)
    let deleted = this.buckets[idx].get(key)
    this.buckets[idx].delete(key)
    return deleted
  }

  search(key) {
    let idx = hash(key, this.size)
    return this.buckets[idx].get(key)
  }

```

### Resources

[Youtube](https://www.youtube.com/watch?v=QuFPIZj55hU)
[Hash Tables](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)
