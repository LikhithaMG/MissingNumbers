Naive Approach: The naive idea is to iterate over the difference between the consecutive pair of elements and the print all the numbers in this range if the difference is non-zero. Below are the steps:
1.Initialize the variable diff which is equal to arr[0] – 0.
2.Now traverse the array and see if the difference between arr[i] – i and diff is zero or not.
3.If the difference is not equal to zero in the above steps, then the missing element is found.
4.To find the multiple missing elements run a loop inside it and see if the diff is less than arr[i] – i then print the missing element i.e., i + diff.
5.Now increment the diff as the difference is increased now.
6.Repeat from step 2 until all the missing numbers are not found.
