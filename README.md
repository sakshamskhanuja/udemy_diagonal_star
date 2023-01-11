## Diagonal Star

### Description

Write a method named <b>printSquareStar</b> with one parameter of type <b>int</b> named <b>number</b>. If number is < 5, the method should print "Invalid Value". The method should print diagonals to generate a rectangular pattern composed of stars (*)

### Examples of input/output

printSquareStar(5); should print the following:

    *****
    ** **
    * * *
    ** **
    *****
Explanation:

    *****   5 stars
    ** **   2 stars space 2 stars
    * * *   1 star space 1 star space 1 star
    ** **   2 stars space 2 stars
    *****   5 stars

printSquareStar(8); should print the following:

    ********
    **    **
    * *  * *
    *  **  *
    *  **  *
    * *  * *
    **    **
    ********

The patterns above consist of a number of rows and columns (where number is the number of rows to print). For each row or column, stars are printed based on four conditions (Read them carefully):

<ul>
<li>In the first or last row</li>
<li>In the first or last column</li>
<li>When the row number equals the column number</li>
<li>When the column number equals rowCount - currentRow - 1 (where currentRow is current row number)</li>
</ul>
