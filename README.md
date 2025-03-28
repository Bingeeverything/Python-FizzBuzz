In this problem, i print Fizz for the Multiples of no 3 from 1-100, Buzz for multiples of no 5, And FizzBuzz for mutiples of no both 3 and 5 such as 15

LINE 1:

First We define the range since we want it to start from 1 
We make the range from (1,101), 101 because the range is defined from n to n-1
So 100

LINE 2:
 if i % 3 == 0 and i % 5 == 0:
        print('FIzzBuzz')

THis line of code checks for remainder 0 when it divides the no, and since we specifically write AND 
it checks true if both conditions are ture,
so 15 for example, its both the multiple of 3 and 5, so it prints FizzBuzz

We put this as the first if because, other statements checked if its a multiple of 3 or 5, and by 5 any of them were true, so they were printed out for 15, its a multiple of 3 so it will print Fizz and not Fizz Buzz
so we put  if i % 3 == 0 and i % 5 == 0:
        print('FIzzBuzz')    FIRST

        
