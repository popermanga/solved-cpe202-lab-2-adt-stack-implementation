Download Link: https://assignmentchef.com/product/solved-cpe202-lab-2-adt-stack-implementation
<br>
The goal of this lab is to implement the Stack Abstract Data Type using two different implementations:

<ul>

 <li>The built in List construct in Python</li>

 <li>The simple linked data structure covered in class</li>

</ul>

As part of the Stack definition for this lab, we will specify a capacity for the stack. In the case of the Python List implementation, you will allocate a list of size capacity and use this to store the items in the stack.  Since Lists in Python expand when more storage is needed, you must avoid using any functions that would cause a List to expand (see the list (haha) of forbidden methods/operations below).  This prevents the stack from growing if the user accesses the List through the given interface.  (This prevents the stack from using more space than a user might want.  Think of this as a requirement for an application on a small device that has very limited storage.)  For consistency, in the simple linked data structure implementation, we will also have a capacity attribute for the stack.

You are NOT allowed to use the following Python List operations:

<ul>

 <li>append()</li>

 <li>insert()</li>

 <li>extend()</li>

 <li>remove()</li>

 <li>pop()</li>

 <li>+ (concatenations)</li>

</ul>




The following starter files are available on GitHub:

<ul>

 <li><strong>py</strong>: Contains an array (Python List) based implementation of the <strong>Stack</strong> class</li>

 <li><strong>py</strong>: Contains a linked based implementation of the <strong>Stack</strong> class</li>

 <li><strong>py:</strong> Contains your set of thorough tests to ensure your implementations work correctly.</li>

</ul>

(Note that the class in each stack implementation is named <strong>Stack</strong>, and both implementations must follow the same specification. This allows one set of tests in <strong>stack_tests.py</strong> that can be used for both implementations by just changing which file is used when importing Stack.