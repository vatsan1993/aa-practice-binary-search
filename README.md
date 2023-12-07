You will be implementing classic algorithms in code. Review the readings to understand the problem.

You are given the plan in comments already. Study these carefully!

These exercises are meant for you to practice carrying out the plan. Focus on translating the plans to JavaScript code.

If you finish early, you will be able to improve your solutions by refactoring your sorting algorithms to run in-place. Binary search is also a major improvement over linear search.
Part 1: Comparing Linear vs Binary Search

Open up binary-search.js. Your first task is to implement a linear search:

linearSearch([2,4,6,8], 6); // 2
linearSearch([2,4,6,8], 10); // -1

This returns the index of the target if it is contained in the array, and -1 otherwise. You should be able to solve it in one line of code.

Run tests by typing mocha test/search-specs.js.

Once the linear search is passing, fill out binarySearch which should work the same way: returns the index of the target if it is contained in the array, and -1 otherwise.

binarySearch([2,4,6,8], 6); // 2
binarySearch([2,4,6,8], 10); // -1

The key difference between the linear and binary searches is in the performance tests. You should be able to search through an array with 1 million items roughly 1000 times per second with a linear search, and 500000 times per second with binary search.

(Specs will pass with 500 linear and 100000 binary searches so don't worry if your computer is slow.)

Be sure to follow the pseudocode provided.

BONUS Time and plot the performance of linear vs. binary search on a Google Sheet.
