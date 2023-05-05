Download Link: https://assignmentchef.com/product/solved-ece30862-homework-7-set-class-that-represents-sets-of-positive-integers
<br>
In this homework we will write a <em>Set</em> class that represents sets of positive integers. You may not use a Set container to implement this.  I implemented my version using an array of unsigned integers (called <em>slots</em>) to represent the set of integers. Thus, if 4 is a member of the set, then bit 3 (with the first bit being numbered zero) in the integer in slots[0] would be 1. If 33 was a member of the set, then bit 0 of the unsigned integer in slots[1] would be 1. If 34 is not a member of the set, then bit 1 of the unsigned integer in slots[1] would be 0. You can use another representation for your set, but you should not use a container.

.

<strong>Part A. </strong>Using member functions for all operators except for “&lt;&lt;“, implement the following:

<em>A “+” operator </em>that adds an integer to the set. If the set already contains the integer it is unchanged.

<em>A “-” operator </em>that removes an integer from the set. If the set does not contain the integer it is unchanged.

<em>An “&amp;” operator</em> that “ands” the elements of a set, i.e. s3 = s1 &amp; s2 means that element e  s3 iff e  s1 and e  s2.∈ s3 iff e ∈ s1 and e ∈ s2.   ∈ s3 iff e ∈ s1 and e ∈ s2.       ∈ s3 iff e ∈ s1 and e ∈ s2.

<em>A “~” operator </em>that takes the inverse of a set. Thus, if e  s, then e ~s. If e  ~s, e  ~s.∈ s3 iff e ∈ s1 and e ∈ s2.                                                                                            ∉ ~s. If e ∉ ~s, e ∈ ~s. ∉ ~s. If e ∉ ~s, e ∈ ~s.       ∈ s3 iff e ∈ s1 and e ∈ s2.

<em>A “/” operator.</em> e  s1 / s2 iff e  s1 and e  s2, i.e., this is set difference.∈ s3 iff e ∈ s1 and e ∈ s2.      ∈ s3 iff e ∈ s1 and e ∈ s2.             ∉ ~s. If e ∉ ~s, e ∈ ~s.

<em>A “&lt;&lt;“ operator</em> for printing out the elements of the set.

<em>Implement a copy constructor</em> and keep track of how many times it is called.

<strong>Part B.</strong> Using non-Member (free) functions, implement the operators above in a separate program from the that of Part A.  You can use the Part A program as a starting point and save a lot of typing and debugging.

<strong>Parts A and B.</strong> The main.cpp file should work with your class.