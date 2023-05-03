Download Link: https://assignmentchef.com/product/solved-cs1027-lab10
<br>
<h2>Learning Outcomes</h2>

<ul>

 <li>Understand the linked list implementation of a binary tree</li>

 <li>Design and implement operations in the tree structure</li>

 <li>Apply recursion to traversals and other algorithms in a binary tree</li>

 <li>Pre-Lab</li>

</ul>




<ul>

 <li>Create a new Java project called Lab10</li>

 <li>Download the files: <a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/BinaryTreeNode.java">java</a><a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/BinaryTreeNode.java">,</a> <a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/LinkedBinaryTree.java">LinkedBinaryTree.java</a><a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/LinkedBinaryTree.java">,</a> <a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/ArrayList.java">ArrayList.java</a><a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/ArrayList.java">,</a></li>

</ul>

<a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/ArrayUnorderedList.java">ArrayUnorderedList.java</a><a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/ArrayUnorderedList.java">,</a> <a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/ArrayIterator.java">ArrayIterator.java</a><a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/ArrayIterator.java">,</a> <a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/BinaryTreeADT.java">BinaryTreeADT.java</a><a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/BinaryTreeADT.java">,</a> <a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/ListADT.java">ListADT.java</a><a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/ListADT.java">,</a>

<a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/ElementNotFoundException.java">ElementNotFoundException.java</a><a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/ElementNotFoundException.java">,</a> <a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/EmptyCollectionException.java">EmptyCollectionException.java</a><a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/EmptyCollectionException.java">,</a> <a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/LinkedQueue.java">LinkedQueue.java</a><a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/LinkedQueue.java">,</a>

<a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/QueueADT.java">QueueADT.java</a><a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/QueueADT.java">,</a> <a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/LinearNode.java">LinearNode.java</a><a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/LinearNode.java">,</a> <a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/TestBinaryTree.java">TestBinaryTree.java</a><a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/TestBinaryTree.java">,</a> and <a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/UnorderedListADT.java">UnorderedListADT.java</a>     Save these downloaded files into the Lab10 src folder




<h2>Exercise 1 – Completing the BinaryTreeNode class</h2>




<ol>

 <li>Open BinaryTreeNode.java. Note that it is currently very short.</li>

</ol>

<table width="291">

 <tbody>

  <tr>

   <td width="80">getData()</td>

   <td width="8">,</td>

   <td colspan="3" width="79">getLeft()</td>

   <td width="37">, and</td>

   <td width="87">getRight()</td>

  </tr>

  <tr>

   <td colspan="3" width="141">setData(newData)</td>

   <td width="8">,</td>

   <td colspan="3" width="143">setLeft(newLeft)</td>

  </tr>

  <tr>

   <td width="82"></td>

   <td width="6"></td>

   <td width="53"></td>

   <td width="12"></td>

   <td width="19"></td>

   <td width="36"></td>

   <td width="87"></td>

  </tr>

 </tbody>

</table>

<ol start="2">

 <li>Add the following getter methods: .</li>

 <li>Add the following setter methods: , and setRight(newRight).</li>

</ol>




<h2>Exercise 2 – Completing the LinkedBinaryTree class</h2>




<ol>

 <li>Open LinkedBinaryTree.java. Note that there are several errors throughout this file, although not as many now as there were before you completed the above exercise (since the getters and setters in BinaryTreeNode are called many times from this class).</li>

 <li>Complete the method getDataRoot() to return the data item stored in the root of the tree.</li>

</ol>

<table width="221">

 <tbody>

  <tr>

   <td width="79">isEmpty()</td>

   <td width="141"> </td>

  </tr>

  <tr>

   <td colspan="2" width="221">size(BinaryTreeNode&lt;T&gt; r)</td>

  </tr>

 </tbody>

</table>

<ol start="3">

 <li>Complete the method to return true if the tree is empty and false otherwise</li>

 <li>Complete the method to return the number of nodes in the subtree with root r. This method must be recursive. Please try to implement this method on your own. If you get stuck, then read <a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/Lab10Hint1.txt">this hint</a><a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/Lab10Hint1.txt">.</a></li>

</ol>

<h1>LAB 10                                                     Computer Science Fundamentals II</h1>

<strong> </strong>

<strong> </strong>

<ol start="5">

 <li>Complete the method contains(BinaryTreeNode&lt;T&gt; r, T targetElement) to return true if the given targetElement is stored in any of the nodes in the subtree with root r. This method must be recursive. Please try to implement this method on your own. If you get stuck, then read <a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/Lab10Hint2.txt">this hint</a><a href="https://www.csd.uwo.ca/courses/CS1027a/labs/lab10/Lab10Hint2.txt">.</a></li>

 <li>Complete the methods iteratorPreOrder() and preorder() to work together to construct an iterator that recursively traverses the tree in pre-order (see note below).</li>

 <li>Complete the methods iteratorPostOrder() and postorder() to work together to construct an iterator that recursively traverses the tree in post-order (see note below). 8. If you need help with any of the preorder or postorder iterator methods, read class TestBinaryTree.java to learn how to use the iterator. You can also model your code for these methods on the existing iteratorInOrder() and inorder() The main change you will need to make is where the node is being visited.</li>

 <li>Complete the method iteratorLevelOrder() to return an iterator containing the data stored in the nodes of the tree in level order. This method is not recursive. Use class LinkedQueue.java as the auxiliary data structure needed to perform a level order traversal of the tree. Review the lecture notes on tree traversal. Note that in the queue you will store tree nodes, so what should be the value of the generic type for the declaration of the queue? (LinkedQueue&lt; ??? &gt; queue;)</li>

 <li>Open TestBinaryTree.java and run it. All 6 tests must pass to indicate that your code was entered correctly. If any of these tests are failing, use the Debugger and/or print lines to find the errors and fix them. Start by reviewing the BinaryTreeNode to check if you accidentally assigned a value to an incorrect variable.</li>

</ol>