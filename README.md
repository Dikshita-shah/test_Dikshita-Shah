# suffle the array
logic/ algorithm-dvide and conquer method
in this method split the array into two equal part and then perform the operation
lets take an array a1,a2,a3,b1,b2,b3;

split the array into two half part
    part1-a1,a2,a3,a4
    part2-b1,b2,b3,b4
swap element around the center:exchange a3 with b1 correspondingly
you get:a1,a2,b1,b2,a3,a4,b3,b4
Recursively split a1, a2, b1, b2 into a1, a2 : b1, b2 
then split a3, a4, b3, b4 into a3, a4 : b3, b4.
Exchange elements around the center for each subarray we get: 
a1, b1, a2, b2 and a3, b3, a4, b4.
