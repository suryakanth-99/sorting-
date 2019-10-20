# bubble sort:
In this sorting technique the adjacent elements are compared.
->1st element is compared with 2nd element ,if 1st element is greater than 2nd then sort them
->after sorting them ,now 2nd element is compared with 3rd element ,if condition is true then sort them.
->after sorting them,repeat those steps till u reach last element.
->the last element you have obtained after successive sorting is the largest element of the array.
This is called one pass.
Now repeat this process for 2nd pass upto penultimate(last but one) element as the last one is sorted according to its order.
**For n elements we have n-1 passes because in each pass we will get the last elements according to order.In n-1 th pass we need to compare only first two elements and sort them.no need for nth pass


#selection sort :
In this sorting technique we iterate the outer loop for n-1 times,for each iteration the "min" value is taken as index position,inner loop starts from next element of outer loop element till the last element.If we found any value that is than the value at index position-'min',then we will assign that index as min,at the end of the loop we will swap the ith index and min index,this process is continued for n-1 times
