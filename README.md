# csc382-lab-3-average-case-solved
**TO GET THIS SOLUTION VISIT:** [CSC382 Lab 3-Average Case Solved](https://www.ankitcodinghub.com/product/csc382-lab-3-average-case-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94054&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC382 Lab 3-Average Case Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Average Case

In this project we will try to match the Average Case of algorithm A10 as we derived in class and the “Real Average” of the algorithm using Monte Carlo approach.

A10: void Insertion (int A[ ], int n) // in reality the elements to be sorted are indexed from // index 1 to index n

{

int i,j, temp;

A[0]=-32768; //smallest possible integer using 2 bytes integer representation for (i=1; i&lt;=n, i++) {

j=i;

(1) while ( A[j] &lt; A[j-1]) { // swap

temp=A[j]; A[j]=A[j-1]; A[j-1]=temp; j–;

First you must modify A10 to return the number of steps executed. Please note that we consider only basic operations, which are the “comparisons” only. Call this subroutine

</div>
</div>
<div class="layoutArea">
<div class="column">
} }

}

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Insertion-Mod( ).

1) (CalculatedAverage) Let n = 100.

Calculate the Average-case A(n) as we derived in class. Let bound be an integer (choose a large number).

Let tot-number-steps = 0 (accumulates total number of

Generate a sequence of n integers (positive and negative as well) using a random number generator where the numbers of the sequence are between 0 and bound. Call Insertion-Mod ( ) using this sequence and add the number of steps returned by this algorithm to tot-number-steps.

Repeat steps e 100,000 times (i.e., generate 100,000 random sequences and update tot-number-steps).

Calculate the real average of algorithm A10 and let this number be A2(n).

Repeat steps a)-thru g) for the following values of n, n= {100, 500, 1000, 2500, 3000, 3500}.

</div>
</div>
<div class="layoutArea">
<div class="column">
You final output should look like:

</div>
</div>
<div class="layoutArea">
<div class="column">
Input size 100

500

</div>
<div class="column">
Calculated Average XX

XX

</div>
<div class="column">
Real Average XX

XX

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
.. .. .. 3500 XX XX

Please explain the outcome of the experiments.

</div>
</div>
</div>
</div>
