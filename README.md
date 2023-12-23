
<h1>Sudoku Solver</h1>


<h2>Description:</h2>
This project consists of a sudoku solver that can solve a valid sudoku grid using a backtracking algorithm. (This project was inspired by the youtube channel Tech With Tim)
<br />


<h2>Languages and Utilities Used:</h2>

- <b>Python</b> 

<h2>Concepts Learned in this Project:</h2>
The main concept I learned through this project was how to make and implement a backtracking algorithm. 

<h2>Program walk-through:</h2>

is_valid function:
<br />
This function is responsible for testing a particular number is a valid solution for a given space on the sudoku grid.<br/>
<br/>
<img src="https://imgur.com/9yGTwCs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
print_board funtion:<br/>
This function is responsible for printing out the sudolu grid in a way that is easy to see to visualize how the grid has been solved.<br/>
<br/>
<img src="https://imgur.com/5NoJC6l.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
find_empty function:<br/>
This function is responsible for finding a point on the grid what is empty/has a value of 0.<br/>
<br/>
<img src="https://imgur.com/8APc2rV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
solve function:<br/>
This function is responsible for solving the sudoku grid through recursion. We first establish the base case  and then cycle through the function until the base case is fulfilled which means the sudoku grid is solved.<br/>
<br/>
<img src="https://imgur.com/W9EBJUW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
End Result:  <br/>
<img src="https://imgur.com/hloRU72.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
