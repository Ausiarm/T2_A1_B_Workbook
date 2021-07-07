# <div align="center"> T2_A1_B_Workbook </div>

The ACME Corporation is interested in building a marketplace web application (app) using Rails for one of it’s product lines. To help it choose the vendor who will undertake the project they have released a RfQ. As an aspiring junior dev at an up and coming Sydney software startup (CAx-Dev) your manager has assigned you to assist with preparation of the RfQ response.

The efficiency of an app (i.e. site) and the algorithms used are of the utmost importance. The next set of questions relate to this RfQ-requirement.


## Q1 Identify and explain the workings of TWO sorting algorithms and discuss and compare their performance/efficiency (i.e. Big O)
---
#### What is a Sorting Algorithm?
In simple terms, a sorting algorithm is a method used to reorganize a set of items into a desired pattern, that pattern is up to the desires of the user running the algorithm and can be of many forms, least-to-highest, alphabetical, or even and odd are just a few of the myriad options available. The two that will be be discussed below will provide a deeper understanding into the nature of sorting algorithms. following that a performance and efficiency comparison will be provided in the event that ACME were interested in utilizing either of these options. 

<br>

1. Merge Sort
    - Merge sort is commonly seen as one of the most efficient sorting algorithms available for processing sets of values. the way it works is by taking an unordered or unsorted list of values and breaking that list down into a group of single item arrays, each populated with a single value from the initial array or set of unsorted values. Once the set is broken down into individual elements it is then recombined using a basic ruleset until all of the singular entity arrays are combined into one array containing the whole set of values once more, only this time those values are ordered based off the specifications of the algorithm. A good example to use would be sorting an array of integers in order of lowest-to-highest value. The algorithm would process the set or array by taking it apart and separating each integer into its own array. From here it would begin adding each single value array to another, when doing so it would compare the value of one array's integer with the other using the greater than, less than, or equal to operators. Each value is processed and added into the new sorted array in the order specified and as the algorithm proceeds through group of single entities it compares the single entity with the most recent addition to the sorted list, this way it can either add the entity on to the end of the list if it is greater than the current endpoint or recurisvely go back through the list using these same operators to insert the entity at the point that it  should be placed. This process would be repeated again and again with a sorted array of increasing size until the original set had been recreated, however this time it would be sorted based off restriction value specified. This is considered to be the Top down approach to merge sorting and uses what is called recursion to repeatedly go through the set of values and ask the same question in relation to order the set, if the answer is yes the operation will run and further reduce the complexity of the list. Once complexity is reduced to its lowest level the list can begin to be repopulated by combining values as stated above. 
    - Time Complexity ((n log(n))) - Best, (O(n log(n))) - Worst
2. Bubble Sort
    - 
    - Time Complexity (n) - Best, (O(n^2)) - Worst

### Performance and Efficiency Comparison


[Source](https://www.interviewbit.com/tutorial/sorting-algorithms/)
[Merge_Sort](https://www.youtube.com/watch?v=TzeBrDU-JaY)
[Bubble_Sort](https://www.youtube.com/watch?v=Jdtq5uKz-w4&list=RDCMUClEEsT7DkdVO_fkrBw0OTrA&index=4)
<br>
## Q2 Identify and explain the workings of TWO search algorithms and discuss and compare their performance/efficiency (i.e. Big O)
--- 

1. Linear search 
    - 
2. Binary search 
    - 

### Performance and Efficiency Comparison


[Source](https://codersera.com/blog/let-us-understand-searching-algorithms/)
