# 605-202-31-lab-4-solved
**TO GET THIS SOLUTION VISIT:** [605.202.31 LAB 4 Solved](https://www.ankitcodinghub.com/product/605-202-31-data-structures-lab-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;126591&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;605.202.31    LAB 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
This lab assignment requires you to compare the performance of two distinct sorting algorithms to obtain some appreciation for the parameters to be considered in selecting an appropriate sort.

&nbsp;

Write a <strong>HeapSort </strong>and a <strong>Shell Sort</strong>. They should both be recursive or both be iterative, so that the overhead of recursion will not be a factor in your comparisons. In this case, iteration is recommended. <strong>Be sure to justify your choice. Also, consider how your code would have differed if you had made the other choice.&nbsp; </strong>

&nbsp;

The strategy behind a <strong>Shell Sort </strong>is to create a more nearly optimal environment for a simple, relatively inefficient sort technique, namely Simple Insertion Sort. This optimal environment allows the simple strategy to be efficient. Use the following sets of increments

&nbsp;

1, 4, 13, 40, 121, 364, 1093, 3280, 9841, 29524 (Knuth’s sequence)

1, 5, 17, 53, 149, 373, 1123, 3371, 10111, 30341

1, 10, 30, 60, 120, 360, 1080, 3240, 9720, 29160&nbsp; One or more sets of increments of your choice.

&nbsp;

&nbsp;

You will have four different Shell sorts to run.

&nbsp;

&nbsp;

<strong>Heap Sort </strong>is a practical sort to know and is based on the concept of a heap. It has two phases: Build the heap and extract the elements in sorted order from the heap. Altogether, you will have five sorts: 1 Heap and 4 Shell.

&nbsp;

Create input files of four sizes: 25,50, 200, 500 integers. For each size file, make three versions. On the first, use a randomly ordered data set. On the second, use the integers in reverse order. On the third, use the integers in normal ascending order. (You may use a random number generator or shuffle function to create the randomly ordered file. It is important to avoid too many duplicates. Keep them to about 1%).

&nbsp;

&nbsp;

Your program should access the system clock to get some time values for the different runs. The call to the clock should be placed as close as possible to the beginning and the end of each sort. If other code is included, it may have a large, fixed, cost, which would tend to drown out the differences between the runs, if any. Why take a chance! <strong>If you get too many zero time data values or any negative time values then you must fix the problem. </strong>One way to do this is to use larger files than those specified. Another solution is to perform the sorting in a loop, N times, and calculates an average value. You would need to be careful to start over with unsorted data, each time through the loop.

&nbsp;

Turn in a analysis comparing the two sorts and their performance. Be sure to comment on the relative runtimes of the various runs, the effect of the order of the data, the effect of different size files, and the effect of different increment sizes for the Shell Sort. Which factor has the most effect on the efficiency? Be sure to consider both time and space efficiency. Be sure to justify your data structures. As time permits consider implementing a Straight Insertion Sort to compare with Shell Sort. Also, consider files of size 10,000 or additional random files – perhaps with 15-20% duplicates. Your write-up must include a table of the times obtained.

&nbsp;

The source code you turn in needs to print out the sorted values
