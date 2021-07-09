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
    - Bubble sort, unlike merge sort, is seen as one of the least efficient sorting algorithms as it has the capacity to move to a complexity level of n^2 when the sorting algorithm is required to iterate over nested loops. The way the bubble sort works can be best explained with an unsorted array of values. In terms of the case used to exemplify the merge sort algorithm above, bubble sort can also be used to sort through an array of unsorted integer values ordering them in rank of lowest to highest value or vice versa. Considering the array imagine that the first value of this imaginary array is array(n) and its adjacent value is array(n+1). Bubble sort will move through an array considering each adjacent pair of values, based off the desired analysis and sorting mechanism it will position those adjacent values in the desired location in relation to one another exclsuively. It is very important to note that bubble sort will only consider one pair of adjacent values at a time. In the case of the example array, the bubble sort algorithm will take array(n) and array(n+1) and either swap their places if array(n) is greater than array(n+1) or leave them in their place if they are in the correct order. From here the algorithm will now consider the next adjacent pair, which would be array(n+1) and array(n+2). It will then repeat the same value consideration as it did for the first adjacent pair, and if array(n+1) is greater than array(n+2) then it will swap places with array(n+2). This same process will be repeated over and over, moving or bubbling the highest values of the set contained within the array to their appropriate position and restarting at the beginning of the array for each time that it reaches the end of the total set of values within the array. This means that iterations will be run over and over until the array is completely sorted. At a glance it should be easy to see why this sorting mechanism will be inefficient, especially for sets whose n value is huge say, 1,000,000 or more. 
    - Time Complexity (n) - Best, (O(n^2)) - Worst

### Performance and Efficiency Comparison
- Efficiency
    - In relation to the Two requirements of this document it will be valuable to explain what it is that ACME should be concerned about when considering efficiency and in order to do so it will be helpful to have a general definition of what is meant by efficiency in relation to these algorithms. Here, efficiency is the general rating of an algorithm as far as its ability to process a given set of data over time in relation to other algorithms. The fastest or most efficient algorithms are those whose efficiency is unneffected by altering the value of n, the size of the data set or value set. Above, each sorting method has a Time complexity linked to it, this is what is referenced when considering efficiency. The best possible level of efficiency is one that is constant or O(1), in this case time complexity is not effected at all by changes in the size of the dataset which is incredibly valubale when processing massive ammounts of data. The worst case is factorial or O(n!) in this case large data sets massively balloon processing time and it is highly recommended that unless otherwise directed, an algorithm with this complexity is avoided. 
- Performance and Efficiency comparison
    - With the above definition of efficiency in mind and an understanding of the time complexities of both merge and bubble sort algorithms, it is now possible to compare the two so that ACME may make an informed decision of which one to use. As can be seen from the attached graph, while the best case scenarios of bubble and merge dictate that bubble sort algorithms can out perform their merge sort counterparts, this only remains the case as long as these algorithms are iterating over a set once and not in a nested fashion where an algorithm would be required to loop through data within another larger loop, as would be the case when sorting an unsorted array of numbers like the examples displayed above. Given that the worst case scenarios have bubble sort's time complexity becoming quadratic and, therefore, becoming much larger than that of merge sort it is recommended that ACME consider whether or not the data that they intend to iterate over is capable of being corrected in a single loop or if it would be better covered through nested iterations. In the case of a nested iteration, it is the recommendation of this RFQ that ACME utilizie a merge sort algorithm as it will drastically increase time efficiency when the data set that ACME is covering becomes larger and larger as it surely will.
    - [attached-graph](needtoattachgraphhere)***

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
