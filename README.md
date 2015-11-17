This is an assignment to find the frequent item sets of all sizes in various transactions using 3 algorithms

USAGE: $ python PCY_.py [INPUT_FILE] [SUPPORT_THRESHOLD] [HASH_BUCKET_SIZE] Eg: $ python PCY.py data/input.txt 

PCY (Park-Chen-Yu) Algorithm

The PCY algorithm is an extension of the apriori algorithm. This provides a better utilization of memory by hashing. The candidate pairs is reduced to a drastic amount using this method.

Minhash Algorithm

Item sets can be concluded as candidate itemsets if they can hash into a frequent bucket when they are hashed into a frequent bucket when all the hash functions are applied. This algorithm uses 2 hash functions

Toivonen's Algortihm

Toivonen has proven to be more successful in finding frequent itemsets. It first finds the frequent itemsets in a sample and verifies it against the whole data set.

A slight modification to execute this program: USAGE: $ python toivonen_.py [INPUT_FILE] [SUPPORT_THRESHOLD]

Eg: $ python toivonen.py data/input1.txt 20