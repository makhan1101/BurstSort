# BurstSort
So, as we know that sorting is a very simple algorithmic task for which several different techniques are used such as insertion sort,quicksort, radix sort etc but these techniques are unable to make a decent use of memory and time.

To overcome this issue a new algorithm was designed called burst sort. 

Burst sort is an algorithm used for sorting strings. It works very efficiently on larger datasets and works good on small datasets as well.
# Working of burstsort
1)Insertin Phase :In burst sort a trie is created which is used to store prefixes of the string array and the suffixes are stored in the buckets.As the bucket grow beyond the specified threshold it is burst.Create new trie node, then connect the newly created trie node to the old trie node to which bucket is connect.Then search the prefix in the trie node of the bucket elements and then add their respective suffix to the newly created bucket. After the insertion phase treaversal phase is called to sort elements.
2)Traversal OR Sorting Phase :To sort the contents of the buckets many implementations use multi key quicksort which is basically a hybrid of radix sort and quick sort. Multi key quicksort is designed for sorting strings in a cache efficient manner. It works very fast and in an efficient manner.

# Input
You have to replace the elements of pre define array in main to sort ur string data But you cannot input an empty string.

# Group Members
Muhammad Ahsan Khan(17B-050-CS)  Mirza Areeba Baig(17B-014-CS)  Syed Saim Abbas(17B-036-CS)
