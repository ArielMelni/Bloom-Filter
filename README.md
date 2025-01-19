Bloom Filter is a probabilistic filter which allows for an O(1) look up searching on a 645,000-entry data set. 

A Bloom Filter is an adapted hash table, which uses a bit array. 

It allows for the dynamic configuration of numHashes, numKeys, and maxFalsePositive. 

numHashes: The number of hash functions that the bloom filter will use. 

numKeys: The amount of keys the bloom filter will store. 

maxFalsePositve: the max rate of false positives that the Bloom Filter will allow for. 

To learn more about Bloom Filters: https://en.wikipedia.org/wiki/Bloom_filter 

In __main() numKeys is set to 100000, numHashes is set to 4, and maxFalse is set to .05. 

Reading from wordlist.txt, the actual false positive rate obtained from running the bloom filter with the input from wordlist.txt 
is tested against the theoretical false positive rate. 


