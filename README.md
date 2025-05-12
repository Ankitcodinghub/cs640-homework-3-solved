# cs640-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [CS640 Homework 3 Solved](https://www.ankitcodinghub.com/product/cs640-homework-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91397&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS640 Homework 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1 Adversarial Search

Consider an adversarial game with two players acting independently and the winner is unique. Suppose we have an AI agent using the min-max algorithm to play this game and it has produced a search tree shown in the figure above. In this search tree,

<ul>
<li>the first level (node 0) is the maximizing level;</li>
<li>the second level (node 1 and 2) is the minimizing level;</li>
<li>the third level (node 3, 4, 5, and 6) is the maximizing level;</li>
<li>the fourth level (node 7 to 14) is the minimizing level;</li>
<li>the fifth level (node 15 to 30) is the leaf level and the number beneath each node is the static evaluator score of the corresponding game state.
Your tasks are the following:

<ol>
<li>Apply the min-max algorithm without pruning. Show the returned value for each non-leaf node (node 0 to 14).
node 0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 value
</li>
<li>Indicate the optimal path as a linked list of nodes (e.g., 0 – 1 – 3 – 7 – 15) the agent will choose.</li>
<li>Apply the min-max algorithm with alpha-beta pruning. List all of the nodes in ascending order that will be pruned.
1
</li>
</ol>
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2 Constraint Satisfaction Problem

A degree program has the following nine courses: C1, C2, C3, C4, C5, C6, C7, C8 and C9. These courses fall into the following area of knowledge: A student is required to complete at least one course from each of the areas to obtain the

Area Courses

1 C1, C2, C3, C4, C6 2 C3,C4,C5

3 C6,C7,C8

4 C3,C9

degree. Further, there are five restriction on choosing the courses:

<ol>
<li>For A1 only, the courses must be taken in pair specified as follows: (C1, C2), (C1, C3), and (C4, C6).</li>
<li>A student can only choose one from C3, C4, C9.</li>
<li>A student can only choose one between C1 and C7.</li>
<li>A student can only choose one between C6 and C8.</li>
<li>A course can only be used to count in one area and can only be taken at most once. For example, if a student takes C3 for A1, then they cannot use it or retake it for A2 or A4.</li>
</ol>
Please answer the following questions.

<ol>
<li>Model the situation as a CSP. Specifically,
• define variables (hint: use the area of knowledge requirements),

• list their domains, and

• listtheconstraints(justforconvention,useR1,R2,…todenotethem).
</li>
<li>Use DFS with backtracking to find a solution to complete the degree while obeying all of the restrictions. When exploring, select variable/value based on the index order (e.g., Ci goes before Ci+1). If backtracking occurs, specify the constraint that is violated. Please show your work in a figure.</li>
<li>Suppose a student has already taken C8 for area 3 and C9 for area 4, what courses should they take for the remaining areas in order to obtain the degree?</li>
</ol>
</div>
</div>
</div>
