# DSA120
120 days of consistent DSA problem solving from 29-AUG-2023 : by Andrei Neagoie.
#This section will contain my code notes , intuition and solution to the GFG and LeetCode problems.
#Day1
1) binary search.
2) Majority element : 1) o(n2) - two for loops and >(n/2). 2) nth_element() , return the mid position.
#Day2
1) sum of upto n series : 1)loop 2) understood about using (long long) to pass all test cases and have more precision. n*n+1/2
2) concat array ip: 1,2,3 , op:1,2,3,1,2,3. 1) if i < half , then insert otherwise insert at (i%n). 2) pushback again using loop 3) (n+i) = i , loop.
