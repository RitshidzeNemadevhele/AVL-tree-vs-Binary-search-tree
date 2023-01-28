# AVL-tree-vs-Binary-search-tree
The goal of this project is to compare the Binary Search Tree with avl tree, both implemented in Java, using a real-world application to read in and provide access to Cape Town's load shedding data.

LSAVLApp read in the attached text file and store the data items within an AVL TREE . it has methods: printAreas (stage, day, startTime) - to print out the list of areas for the first matching combination of the supplied parameters that is found; or "Areas not found" if there is no match.

&

printAllAreas () - to print out the areas for every stage, day and start time, in any order.

LSBSTApp does the same thing but instead of avl tree it uses BST

Using part2(for bst) and part4(for avl) discretely count the number of comparison operations (<, >, =) you are performing in the code. Only count where you are comparing the keys.
