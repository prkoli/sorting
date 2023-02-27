# Sort Visualizer - Visualization for Sorting algorithms

[![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/thisispriyanshu/algorithm-visualizer?logo=github&style=for-the-badge)](https://github.com/thisispriyanshu/) 
[![GitHub last commit](https://img.shields.io/github/last-commit/thisispriyanshu/algorithm-visualizer?style=for-the-badge&logo=git)](https://github.com/thisispriyanshu/) 
[![GitHub stars](https://img.shields.io/github/stars/thisispriyanshu/algorithm-visualizer?style=for-the-badge)](https://github.com/thisispriyanshu/algorithm-visualizer/stargazers) 
[![My stars](https://img.shields.io/github/stars/thisispriyanshu?affiliations=OWNER%2CCOLLABORATOR&style=for-the-badge&label=My%20stars)](https://github.com/thisispriyanshu/algorithm-visualizer/stargazers) 
[![GitHub forks](https://img.shields.io/github/forks/thisispriyanshu/algorithm-visualizer?style=for-the-badge&logo=git)](https://github.com/thisispriyanshu/algorithm-visualizer/network)
[![Code size](https://img.shields.io/github/languages/code-size/thisispriyanshu/algorithm-visualizer?style=for-the-badge)](https://github.com/thisispriyanshu/algorithm-visualizer/)
[![Languages](https://img.shields.io/github/languages/count/thisispriyanshu/algorithm-visualizer?style=for-the-badge)](https://github.com/thisispriyanshu/algorithm-visualizer/)
[![Top](https://img.shields.io/github/languages/top/thisispriyanshu/algorithm-visualizer?style=for-the-badge&label=Top%20Languages)](https://github.com/thisispriyanshu/algorithm-visualizer/)
[![Issues](https://img.shields.io/github/issues/thisispriyanshu/algorithm-visualizer?style=for-the-badge&label=Issues)](https://github.com/thisispriyanshu/algorithm-visualizer/)
[![Watchers](	https://img.shields.io/github/watchers/thisispriyanshu/algorithm-visualizer?label=Watch&style=for-the-badge)](https://github.com/thisispriyanshu/algorithm-visualizer/) 

Sort Real-time random array values and adjust speed and height for different algorithms
along with documentation explaining sorting algorithms

<p align="center">
<a href="https://thisispriyanshu.github.io/algorithm-visualizer/">
</a>
</p>


## Features and Interfaces

1. HomePage
   - Responsive website with the dropdown in navbar and animation in title, and below are cards of different sorting algorithms.
   
   ![image](https://i.ibb.co/ZYrvKw4/image9.png)
   
   - The cards contain a button to redirect you to a page where you can visualize the sorting algorithm, and also each card contain a brief description and time and space complexity.
   
   ![image](https://i.ibb.co/n8VXSPB/image5.png)
  
  - At last, it contains a form where you can contact me just by typing your message here, and it will redirect you to mail me with an already written message.
   
   ![image](https://i.ibb.co/sQCwpst/image7.png)
   
2. Sorting Page
   - It opens with such a page containing 3 buttons for creating a random array, then a sort button to sort, and then to clear. Along with it contains the speed factor and height factor slider.
   
   ![image](https://i.ibb.co/Cmt96K0/image11.png)
   
   - Then we will create a random array (blue button) where the random array of size ten is created.
   
   ![image](https://i.ibb.co/4tHXfwJ/image3.png)
   
   - We can also adjust the height factor to make bars small or big.
   
   ![image](https://i.ibb.co/tJjNBPw/image10.png)
   
   - After this, we will click on the sort button, and we can observe the sorting visualization.
   
   ![image](https://i.ibb.co/SPCQd7z/image1.png)
   
   - And finally, our array is sorted.
   
   ![iamge](https://i.ibb.co/4KXPmFq/image2.png)
   
   - And we can clear this by clicking on the clear button (red button). Like bubble sort, we have the selection, insertion, quick, and heap sort.
    
    ![image](https://i.ibb.co/CVF09qL/image4.png)
    
3. Documentation Page
 
   - We have a theory about sorting algorithms.
   
   ![image](https://i.ibb.co/C97rZcz/image6.png)
   
   - Along with its time complexity, space complexity, and description about it.
   
   ![image](https://i.ibb.co/gvDMQR4/image8.png)
   
---

In this article, you will learn what sorting algorithm is and different sorting algorithms.

A sorting algorithm is used to arrange elements of an array/list in a specific order. For example,

![](https://www.programiz.com/sites/tutorial2program/files/sorting.png)

Different Sorting Algorithms
----------------------------

*   [Selection Sort](selection.html)
*   [Insertion Sort](insertion.html)
*   [Bubble Sort](bubble.html)
*   [Quick Sort](quick.html)
*   [Heap Sort](heap.html)
*   [Merge Sort](merge.html)

Complexity analysis
-------------------

| Sorting Algorithm | Time Complexity-Best | Time Complexity-Worst | Time Complexity-Average | Space Complexity |
|-------------------|----------------------|-----------------------|-------------------------|------------------|
| Selection Sort    | n<sup>2</sup>        | n<sup>2</sup>         | n<sup>2</sup>           | 1                |
| Insertion Sort    | n                    | n<sup>2</sup>         | n<sup>2</sup>           | 1                |
| Bubble Sort       | n                    | n<sup>2</sup>         | n<sup>2</sup>           | 1                |
| Quick Sort        | nlog n               | n<sup>2</sup>         | nlog n                  | log n            |
| Heap Sort         | nlog n               | nlog n                | nlog n                  | 1                |
| Merge Sort        | nlog n               | nlog n                | nlog n                  | n                |
---
| Sorting Algorithm | Description                                                                                                                                                                                                                                                                                                                                       |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Selection Sort    | Selection sort finds the smallest element in the array and place it on the first place on the list, then it finds the second smallest element in the array and place it on the second place. This process continues until all the elements are moved to their correct ordering. It carries running time O(n2) which is worst than insertion sort. |
| Insertion Sort    | As the name suggests, insertion sort inserts each element of the array to its proper place. It is a very simple sort method which is used to arrange the deck of cards while playing bridge.                                                                                                                                                      |
| Bubble Sort       | It is the simplest sort method which performs sorting by repeatedly moving the largest element to the highest index of the array. It comprises of comparing each element to its adjacent element and replace them accordingly.                                                                                                                    |
| Quick Sort        | Quick sort is the most optimized sort algorithms which performs sorting in O(n log n) comparisons. Like Merge sort, quick sort also work by using divide and conquer approach.                                                                                                                                                                    |
| Heap Sort         | In the heap sort, Min heap or max heap is maintained from the array elements deending upon the choice and the elements are sorted by deleting the root element of the heap.                                                                                                                                                                       |
| Merge Sort        | Merge sort follows divide and conquer approach in which, the list is first divided into the sets of equal elements and then each half of the list is sorted by using merge sort. The sorted list is combined again to form an elementary sorted array.                                                                                            |

