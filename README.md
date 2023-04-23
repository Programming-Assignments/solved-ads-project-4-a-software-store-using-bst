Download Link: https://assignmentchef.com/product/solved-ads-project-4-a-software-store-using-bst
<br>
<span class="kksr-muted">Rate this product</span>




1 Project description

See the description of this problem in the book for examples

Implement a menu-driven program for managing a software store. All information about the available software is stored in a file software. This information includes the name, version, quantity, and price of each package. When it is invoked, the program automatically creates a binary search tree with one node corresponding to one software package and includes as its key the name of the package and its version. Another field in this node should include the position of the record in the file software. The only access to the information stored in software should be through this tree.

The program should allow the file and tree to be updated when new software packages arrive at the store and when some packages are sold. The tree is updated in the usual way. All packages are entry ordered in the file software; if a new package arrives, then it is put at the end of the file. If the package already has an entry in the tree (and the file), then only the quantity field is updated. If a package is sold out, the corresponding node is deleted from the tree, and the quantity field in the file is changed to 0.

If an exit option is chosen from the menu, the program cleans up the file by mov- ing entries from the end of the file to the positions marked with 0 quantities.

2 What to turn in

You will turn in

1. a short written report containing: A description of the significant choices/issues in the design of your code.

2. Thesourcecodeofyourprogram.You may turn in the document via elearning.e-uvt.ro (Class moodle).

1

3 Coding standards