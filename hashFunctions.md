Hash Functions
===
A `hash function` is any function that can be used to map data of arbitrary size to data of fixed size.

The values returned by a hash function are called `hash values`, `hash codes`, `hash sums`, or simply `hashes`.

The `domain` of a hash function is the set of possible keys.

The `range` of a hash function is the number of different table indices.

Typically, the domain of a hash is larger than its range and so it will map several different keys to the same index. Therefore, each slot of a hash table is associated with a set of records, rather than a single record. For this reason, each slot of a hash table is often called a `bucket`, and hash values are also called `bucket indices`.

Hash functions are primarily used in hash tables to quickly locate a data record (e.g., a dictionary definition) given its search key (the headword).

A `hash table` or `hash map` is a data structure used to implement an associative array, a structure that can map keys to values. A hash table uses a hash function to compute an index into an array of buckets or slots, from which the desired value can be found.

Hash functions are also used to build caches for larger data sets.

Hash functions are an essential ingredient of the Bloom filter.

A `Bloom filter` is a space-efficient probabilistic data structure that is used to test whether an element is a member of a set. A query returns either "possibly in set" or "definitely not in set".

A hash value can be used to uniquely identify secret information. This requires that the hash function is collision resistant.

A hash function is `collision resistant` if it is hard to find two inputs that hash to the same output. Collision resistance is a property of cryptographic hash functions.

A `cryptographic hash function` is a hash function which is considered practically impossible to invert, that is, to recreate the input data from its hash value alone.

`Locality-sensitive hashing` (LSH) reduces the dimensionality of high-dimensional data. LSH hashes input items so that similar items map to the same “buckets” with high probability (the number of buckets being much smaller than the universe of possible input items). LSH differs from conventional and cryptographic hash functions because it aims to maximize the probability of a “collision” for similar items. Locality-sensitive hashing has much in common with data clustering and nearest neighbor search.

LSH are used in acoustic fingerprint algorithms, that are used to locate similar-sounding entries in large collection of audio files. For this application, the hash function must be as insensitive as possible to data capture or transmission errors, and to trivial changes such as timing and volume changes, compression.

The same techniques can be used to find equal or similar stretches in a large collection of strings, such as a document repository or a genomic database. In this case, the input strings are broken into many small pieces, and a hash function is used to detect potentially equal pieces, as above.

`Geometric hashing` is used to solve proximity problems in the plane or in three-dimensional space, such as finding closest pairs in a set of points, similar shapes in a list of shapes, similar images in an image database, and so on.

A hash procedure must be `deterministic` — meaning that for a given input value it must always generate the same hash value.

A good hash function should be `uniform` i.e. map the expected inputs as evenly as possible over its output range. That is, every hash value in the output range should be generated with roughly the same probability.

It is often desirable that the a hash function to have a `defined range` that is its output to have a fixed size.

A hash function that is used to search for similar (as opposed to equivalent) data must be as `continuous` as possible; two inputs that differ by a little should be mapped to equal or nearly equal hash values.

Hash function algorithms: trivial hash, perfect hashing, minimal perfect hashing, hashing uniformly distributed data, hashing data with other distributions, hashing variable-length data, special-purpose hash functions, rolling hash, universal hashing, hashing with checksum functions, multiplicative hashing, hashing with cryptographic hash functions, hashing by nonlinear table lookup, efficient hashing of strings.