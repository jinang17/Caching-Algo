# Caching Algorithms

## Introduction

Following caching algorithms are implemented :

1. LFU Cache
2. LRU Cache

<details>

<summary>
What is caching and why is it used ?
</summary>
Caching is a technique used to improve the performance of a system by storing the frequently used data in a cache. The cache is a temporary storage area which is used to store the frequently used data. The data stored in the cache is retrieved from the cache instead of the main memory. This reduces the time required to access the data and improves the performance of the system.
</details>

<details>
<summary>
What is a cache miss ?
</summary>
A cache miss occurs when the data is not present in the cache. The data is retrieved from the main memory and stored in the cache. This increases the time required to access the data and reduces the performance of the system.
</details>

<details>
<summary>
What is a cache hit ?
</summary>
A cache hit occurs when the data is present in the cache. The data is retrieved from the cache. This reduces the time required to access the data and improves the performance of the system.
</details>

<details>
<summary>What is a cache eviction ?</summary>

A cache eviction occurs when the data is removed from the cache. The data is removed from the cache to make space for the new data. This increases the time required to access the data and reduces the performance of the system.

</details>

<details>
<summary>What is a cache replacement policy ?</summary>
A cache replacement policy is a strategy used to decide which data should be removed from the cache when the cache is full. The data is removed from the cache to make space for the new data. This increases the time required to access the data and reduces the performance of the system.
</details>



 ### Comparison 
<br>

|  | Array | List | HashTable | Tree | LFU | LRU | 
| ----------- | ----------- | ----------- | ----------- |----------- | ----------- | ----------- |
| Storing an entry | O(1) | O(n) | O(1) | O(logN) | O(1) | O(LogN) |
| Finding entry by name | O(n) | O(n) | O(1) | O(logN) | O(1) | O(1) |
|Eviction | O(n) | O(1) | O(n) | O(LogN) | O(1) | O(LogN) |

[*Reference](https://stackoverflow.com/a/69716455)

<details>
<summary>
Application of caching
</summary>
Caching is used in the following applications:

* Decreased network costs manage cost during spike events
* Improved responsiveness like in case of RDBMS queries , Web page caching 
* Availability of content during network interruptions
* LRU can be used in google search engine 
* LFU is used in keyboards

</details>

<details>
<summary>
Disadvantages
</summary>

* The data is not accurate 
* If we don't know the exact data to be stored and have frequent cahce miss then it will cost us additonal latency 


</details>
