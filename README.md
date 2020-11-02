# Week 11

Midterm 3 will be on this Monday during the lab session. 

This lab will test students ability to perform black-box unit testing. You will do this on a provided binary search tree class. The given class has mistakes that must be identified. Additionally, the code will not be made available for you to look at (this is what makes it black-box vs white-box). 

## Tasks
As described, you are given a class `BinarySearchTreeMistakes`. 
The available public methods are described above. 
You will fill in the `tester.java` class to point out the errors that are made in the implementation of the BST. 
There are 3 intentional mistakes within the code that you should attempt to identify. 
Extra credit will be provided for anyone who identifies implementation errors that were unintentional. 

### `BinarySearchTreeMistakes`
* `public boolean insert(String)` -- takes as input a string to be inserted, and returns a boolean indicating the success of the operation. A false value indicates that the value cannot be inserted. 
* `public boolean isValid()` -- determines if the tree is a valid binary search tree. 
* `public boolean remove(String)` -- removed the given string node from the tree. the boolean indicates if the node was removed successully. 
* `public boolean search(String)` -- finds the given string in the tree, returns `true` if it is found, and `false` otherwise. 
* `public void balance()` -- this will take the current state of the tree and rebuild the tree with the same nodes but as balanced as possible. 

You are also provided with a `public` `print()` method that you can assume does not have an errors. 
This is the standard print method used in previous classes. 

## Grading
You will fill in the `main` method in `tester.java` with any commands neccesary to identify the errors present in the BST class. 
You also need to provide an explaination of what you feel is going wrong in each. 
For each of the 3 intentional errors you can receive up to 30 points: 
* 10 -- code to identify the error
* 10 -- comments indicating what the error is in the data structure (i.e. after x commands the tree is invalid)
* 10 -- comments indicating what was coded wrong (i.e. the tree is invalid because the remove pulled from the wrong side) 

(note the examples above are not actually correct.)

In addition, you can recive 10 extra credit points for each *additional* error you identify. 
If you correctly identify 3 errors you will get full credit even if they are not the 3 intentional errors, 
extra credit starts with the 4th (if it exists). 

The lab is worth 100 points total, the extra 10 points will be awarded for turning in your assignment. 
