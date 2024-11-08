# Theoretical Sorting

A Computer Science researcher claims to have come up with a sorting algorithm
that can sort arbitrary elements in $O(n)$ time based on comparisons of two
elements at a time. This would be asymptotically faster than any known general
sorting algorithm. The algorithm itself is proprietary and will be sold by a
company.

How would you verify this claim? You may assume that you have access to a
black-box implementation of the sorting algorithm, i.e. you cannot examine the
source code, but you can use it to sort any list you like. Explain in detail
your method for investigating whether X is correct, including any expected
results you would get.

Also give a theoretical argument for why X could or could not be correct, based
on the complexity of the general sorting problem we covered in class.

Add your answers to this markdown file.

## My Answer, Maxie M. 

**Verify Claim**

In order to verify the Computer Science Researchers claim that this proprietary sorting algorithm can sort arbitrary elements in O(n) time based on comparisons of two elements, there are two main steps I would take in approaching the problem
1. Emperical Testing
   - In order to verify the Computer Science Researchers claim that this proprietary sorting algorithm can sort arbitrary elements in O(n) time based on comparisons of two elements, there are two main steps I would take in approaching the problem
       - Generating Test Cases:
           - Will generate test cases that will be various sizes, which will exponentially increase
           - i.e., n = 10 , 100 ,1000 ,10000 , etc...
       - Recording Time Taken:
           - For each input size, the time taken will be recorded by the algorithm
       - Plotting Times:
           - Will plot the times recorded against the input sizes, analyzing the trend
           - If algorithm has O(n) time complexity, the time vs. input size plot should ideally show a linear relationship as n increases
      
2. Expected Results
   - Plot Shows Linear Trend: in this case, it would support the Computer Science Researchers claim that the algorithm has O(n) complexity
   - Plot Shows a Super-Linear Trend (O(n log n) or worse): in this case, it would contradict the Computer Science Researchers claims that the algorithm has O(n) complexity

**Theoretical Analysis** 

As stated above the Computer Science Researcher claims that a sorting algorithm can sort arbitrary elements in O(n) time, only based on comparisons of two elements at a time. However, basing this off of the complexity of the general sorting problem we covered in class we know this isn’t true. It’s proven the best time for a comparison of two elements sorting algorithm can only be (n log n), which would mean theoretically this algorithm can’t be true. 

## Plagiarism Statement: 
I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.

## Resources: 
- https://www.analyticsvidhya.com/blog/2024/01/sorting-techniques-in-python/
