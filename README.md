# comp5361-assignment-3-theory-of-computation-solved
**TO GET THIS SOLUTION VISIT:** [COMP5361 Assignment 3-Theory of Computation Solved](https://www.ankitcodinghub.com/product/comp5361-assignment-3-theory-of-computation-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100014&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP5361 Assignment 3-Theory of Computation Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="layoutArea">
<div class="column">
<ol>
<li>Use the PySimpleAutomata-software to write a program that takes as input a transition table for a DFA or NFA A, and outputs the transition diagram for A. For example, the input could be the automaton A = ({q0, q1, q2}, {0, 1}, δ, q0, {q2}) that has transition table
δ01

→ q0 {q0,q1} {q0} q1 ∅ {q2}

⋆q2 ∅ ∅ The automaton A as a transition diagram:

0,1

Start q0 0 q1 1 q2
</li>
<li>Write a Python program that takes as input the transition table for an NFA A (no ε-transitions), such as the one above, and outputs the transition table and diagram for a DFA B, such that L(A) = L(B). For example, the NFA above should result in output</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
01

∅∅∅

</div>
</div>
<div class="layoutArea">
<div class="column">
and

</div>
</div>
<div class="layoutArea">
<div class="column">
→{q0} {q1 } ⋆{q2 } {q0, q1} ⋆{q0 , q2 } ⋆{q1 , q2 } ⋆{q0, q1, q2}

</div>
<div class="column">
{q0, q1} ∅

∅

{q0, q1} {q0, q1} ∅

{q0, q1}

</div>
<div class="column">
{q0 } {q2 }

∅

{q0, q2} {q0 } {q2 } {q0, q2}

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
10

</div>
</div>
<div class="layoutArea">
<div class="column">
Start {q0} 0 {q0, q1} 1 {q0, q2} 0

1

</div>
</div>
<div class="layoutArea">
<div class="column">
Input/Output format

</div>
</div>
<div class="layoutArea">
<div class="column">
The input/output format is up to the student. You may take and show the information in any format you want. The input/output streams is up to the student as well. For example, you may read from sys.stdin or from a file.

Use of libraries and some built-in python functions

• Any other function, whether built-in or not, that directly simplifies the assignment is not allowed.

What to submit

Using the Moodle system, submit a .zip file that includes:

1. Source code.

2. A .pdf file, explaining your format and how to run your code in few lines.

The format to be followed for submission file is :

&lt;yourname&gt; passign3 &lt;student-id&gt;.zip

&nbsp;

</div>
</div>
</div>
