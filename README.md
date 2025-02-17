# Bloom Filter Documentation

## Overview

A **Bloom Filter** is a probabilistic data structure that enables **O(1) lookup time** for searching a **645,000-entry dataset**. It is an **adapted hash table** that utilizes a **bit array** for efficient storage.

## Configurable Parameters

The Bloom Filter allows for dynamic configuration of the following parameters:

- **`numHashes`**: The number of hash functions used.  
- **`numKeys`**: The number of keys the Bloom Filter will store.  
- **`maxFalsePositive`**: The maximum false positive rate that the Bloom Filter permits.  

For more details on Bloom Filters, refer to:  
🔗 [Bloom Filter - Wikipedia](https://en.wikipedia.org/wiki/Bloom_filter)

---

## `__main()` Configuration

In the `__main()` function, the Bloom Filter is initialized with the following values:

- **`numKeys = 100000`**  
- **`numHashes = 4`**  
- **`maxFalsePositive = 0.05`**  

---

## False Positive Rate Evaluation

The **actual false positive rate** is measured by running the Bloom Filter against an **input file** (`wordlist.txt`) and is compared with the **theoretical false positive rate**.

---

## Running the Bloom Filter

To execute the Bloom Filter and evaluate its performance:

```sh
python bloom_filter.py wordlist.txt
