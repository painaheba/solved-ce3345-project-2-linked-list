Download Link: https://assignmentchef.com/product/solved-ce3345-project-2-linked-list
<br>
<ol>

 <li>Design a java interface called <strong><em>IDedObject</em></strong> which has following abstract functions.</li>

</ol>

<strong>int getID()                                                        </strong>//Returns the ID of the object<strong> void printID()                                                         </strong>//Prints the details of the ID







<ol start="2">

 <li>Design a java class <strong><em>Magazine</em></strong> that implements IDedObject interface and has the following class variables:</li>

</ol>

<strong><em>int magazineID </em></strong>

<strong><em>String magazineName </em></strong>

<strong><em>String publisherName </em></strong>

Implement suitable constructors, a printID function that prints all the variable values in separate lines and getID() function that returns the magazineID.  Add any access and other functions necessary.

{Note all your data should be private and methods public inside the class)




<ol start="3">

 <li>Design a generic singly linked list java class (Give an appropriate name) to hold objects of the generic type &lt;Anytype&gt;. This AnyType should extend IDedObject. The linked list class must implement following member functions:</li>

</ol>




A constructor which generates an empty list .

<strong><em>void makeEmpty</em></strong>();                               //empties the linked list

<strong>AnyType  findID(int ID</strong>);                      // Get the  generic type to get the particular id and returns AnyType.  Don’t remove the object from the list. returns null if the list is empty or ID not found.

<strong>boolean insertAtFront(&lt;AnyType&gt; x);</strong>           // insert at front of list or return false if that ID already exists

<strong>AnyType deleteFromFront()</strong>;              // delete and return the record at the front of  the list or return       null if the list is empty

<table width="620">

 <tbody>

  <tr>

   <td width="226"><strong>AnyType delete(int ID);</strong></td>

   <td width="394">// find and delete the record with the given ID or returns null if it isn’t found</td>

  </tr>

  <tr>

   <td width="226"><strong>void printAllRecords();</strong></td>

   <td width="394">// print all elements in the order they appear in the linked list. if list is empty print appropriate message.</td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<ol start="4">

 <li>Write a java class to have the main function, create a linked-list to hold magazine type objects. It should prompt the user to choice list of the following operations. i. Make Empty</li>

</ol>

/// This Option makes the Linked list empty

<ol>

 <li>Find ID</li>

</ol>

/// print all details of the magazine ID, if it is in the list , if not print appropriate message

<ul>

 <li>Insert At Front</li>

</ul>

/// Get the magazine details from the user and add it to the front of the list

<ol>

 <li>Delete From Front</li>

</ol>

///Print the first item on the list and then delete it. v. Delete ID

/// Print particular IDed item and then delete it.

<ol>

 <li>Print All Records</li>

</ol>

// Print all the records in the list

<ul>

 <li>Done</li>

</ul>

///Quit the program. For every other option after task completion display menu again.

<strong> </strong>




Your program must read from the keyboard and print to the screen.

<strong> </strong>

<strong>Sample run </strong>

<strong>: </strong>

<strong> </strong>

<strong> </strong>

Operations on List

<ol>

 <li>Make Empty</li>

 <li>Find ID</li>

 <li>Insert At Front</li>

 <li>Delete From Front</li>

 <li>Delete ID</li>

 <li>Print All Records</li>

 <li>Done</li>

</ol>

Your choice:  3

Enter Magazine ID: 1111

Enter Magazine Name: People

Enter Publisher Name:  People

…

Magazine Added

Operations on List

<ol>

 <li>Make Empty</li>

 <li>Find ID</li>

 <li>Insert At Front</li>

 <li>Delete From Front</li>

 <li>Delete ID</li>

 <li>Print All Records</li>

 <li>Done</li>

</ol>




Your Choice: 2

ID No: 1111

1111

People

People







Operations on List

<ol>

 <li>Make Empty</li>

 <li>Find ID</li>

 <li>Insert At Front</li>

 <li>Delete From Front</li>

 <li>Delete ID</li>

 <li>Print All Records</li>

 <li>Done</li>

</ol>




Your Choice: 4

1111

People

People

First item deleted

Operations on List

<ol>

 <li>Make Empty</li>

 <li>Find ID</li>

 <li>Insert At Front</li>

 <li>Delete From Front</li>

 <li>Delete ID</li>

 <li>Print All Records</li>

 <li>Done</li>

</ol>

Your Choice: 7 Done.




etc




<strong><em>Additional Instructions: </em></strong>




Follow all project instructions given in elearning page. Include a README.txt file explaining the IDE that you used. Permissible IDEs -&gt; Netbeans, Eclipse and IntelliJ; Other IDEs need permission from TA before project submission. If no IDE used and the program need to be executed on the command prompt, give elaborate instructions on how to run and execute your program. Your README file should also state what works and what doesn’t work and contain sample run of your program.

Zip your files into one file before submitting, have the ‘readme’ file outside of zip file (elearning lets multiple files in one submission). Use good style and layout and comment your code well. <em> </em>