# Insertion Sort
<hr>
[22,27,16,2,18,6] -> Insertion Sort<br>
1.  Write the stages of the above sequence according to the Insertion Sort type. <br>
2.	Write the Big-O notation.<br>
3.	Time Complexity: Average case: The number we are looking for is in the middle, Worst case: The number we are looking for is at the end, Best case: The number we are looking for is at the beginning of the series. <br>
4.	Write the first 4 steps of [7,3,5,8,2,9,4,15.6] according to Insertion Sort.
<br> 
What case does the number 18 fall into after the array is sorted?<br>
<hr>
Write the first 4 steps of [7,3,5,8,2,9,4,15.6] according to Insertion Sort.<br>

<h2> 1.  Write the stages of the above sequence according to the Insertion Sort type. </h2>

[22,27,16,2,18,6] <br>

<b>Step 1</b>
  <br>
The smallest element of the array is replaced by the 1st element. <br>
[2,27,16,22,18,6] 
<br>  
<b>Step 2</b> 
  <br>
Current state of our array : [2,27,16,22,18,6] <br>
We're looking at element 2 and beyond. The smallest element is written in the 2nd element and replaced with the element in the 2nd element. <br>
[2,6,16,22,18,27]
<br>  
<b>Step 3</b> <br>
Current state of the series : [2,6,16,22,18,27] <br>
The 3rd element and after are looked at and the steps 1 and 2 are repeated. <br>
[2,6,16,22,18,27]
<br>  
<b>Step 4</b> <br>
4th element and beyond.
[2,6,16,18,22,27]
<br>  
<b>Step 5</b> <br>
The 5th element and after are looked
[2,6,16,18,22,27]
<br>  
<b>Step 6</b> <br>
[2,6,16,18,22,27]
<hr>
<h2>2. Write the Big-O notation.</h2>
 <br>
  <ul> <li>In the 1st step, all the elements were checked, so if there are n elements, n operations were performed to find the smallest one.</li>
  <li>In step 2, we looked at Item 2 and the items that followed. So we performed n-1 transactions. So now n+(n-1).</li>
  <li>In step 3, we performed n-2 transactions. It became N+(n-1)+(n-2).</li>
  <li>In step 4, we performed n-3 transactions. N+(n-1)+(n-2)+(n-3).</li>
  <li>In step 5, we performed the process n-4 pieces.</li>
  <li>In step 6, only the 6th element remains and it becomes +1 because only 1 element, that is, 1 operation remains.</li>
  </ul>
  <br>
  Our algorithm became - > n+(n-1)+(n-2)+(n-3)+(n-4)+1. This is actually the sum of the numbers from 1 to n. The formula for the sum of numbers from 1 to n comes from (n(n+1))/2 = (n²+n)/2.
  <br>
  <br> In Big O notation, the largest is taken, that is, the most dominant. The Big O notation of this algorithm comes from O(n²) from here. So the time complexity of Insertion Sort is worst case scenario n².
  n = 6. <br> 
  From (6.(6+1))/2 it will be O(6²).
  <hr>
 <h2>3. Time Complexity: Average case: The number we are looking for is in the middle, Worst case: The number we are looking for is at the end, Best case: The number we are looking for is at the beginning of the series.

<br> What case does the number 18 fall into after the array is sorted?</h2>
Time Complexity,
The number 18, that is, the number we are looking for, is in the middle after the Insertion sort, so it is the Average case.
  
