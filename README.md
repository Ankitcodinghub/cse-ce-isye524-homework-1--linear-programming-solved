# cse-ce-isye524-homework-1--linear-programming-solved
**TO GET THIS SOLUTION VISIT:** [CSE-CE-ISyE524 Homework 1- Linear Programming Solved](https://www.ankitcodinghub.com/product/cse-ce-isye524-homework-1-linear-programming-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120376&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE-CE-ISyE524 Homework 1- Linear Programming Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
A few reminders:

• You are encouraged to discuss homework problems with classmates and even work in groups.

• However, the work you turn in must be your own. You must not communicate files containing code or answers to homework questions to each other.

• Please submit the answers in the same order as in the assignment.

• Please denote the start of each question in your Julia workbook using a LARGEFONT. • Submit a pdf file with the contents of your notebook, showing the output obtained by running your code cells. To obtain a version suitable for submission, choose File-&gt;Print Preview to obtain a nice version in a new tab, then print the contents of this tab to a pdf file.

1. [2 points] Warm-up. Model the following problem in JuMP.

maximize 5×1− x2 + 15×3 x1,x2,x3

subject to: 2×1 ≥ x2 + x3

0 ≤ xj ≤ 3, j ∈{1,2,3}

(a) Write Julia code to solve this problem using Clp, ECOS, and SCS solvers. Do all give the same result?

(b) Which solver is fastest (use the @time macro in front of the optimize!() statement to check)? Can you say why?

(c) Consider changing the first constraint to 2×1 ≥ x2 +x3 +α, where α is some real number. For all values of α larger than a certain threshold value, the problem with become infeasible. (In Julia, the solver will terminate with status INFEASIBLE.) What is this threshold value of α? Can you explain by examining the constraints why this value makes the problem infeasible?

2. [2 points] Standard Form Recall that in class we defined the “standard form” of a linear program to be

min cTx subject to Ax ≤ b, x ≥ 0.

Consider the following linear program which is NOT in standard form:

min 3z1 + 2z2− z3

subject to 2z1− z2 + 3z3 = 10,

0 ≤ z2 ≤ 5, −5 ≤ z3 ≤ 20.

(a) Transform the given LP into our standard form. How are the components of x related to the components of z = (z1,z2,z3)? Write out explicity the quantities A, b, c.

(b) Solve both versions of the LP using JuMP and show that you can recover the optimal z and objective value by solving your transformed version of the LP.

1 of 2

3. [2 points] Polyhedron modeling. We saw that the set of x such that Ax ≤ b where A ∈ Rm×n and b ∈ Rm describes a polyhedron. Find A and b such that Ax ≤ b describes the diamond-shaped polyhedron in three dimensions (that is, x ∈R3) that is defined by the following six vertices:

(1,1,0), (1,−1,0), (−1,−1,0), (−1,1,0), (0,0,1), (0,0,−1).

(It might help to sketch this figure!)

4. [3 points] Manufacturing transistors. Silicon Valley Corporation (Silvco) manufactures transistors. An important aspect of the manufacturing process is the melting of the element germanium in a furnace. Unfortunately, the melting process yields germanium of highly variable quality. The results of the process can be classified into five grades: “grade A”, “grade B”, “grade C”, “grade D”, and “defective”. Two methods can be used for the melting. Method 1 costs $50 per transistor, and Method 2 costs $70 per transistor. The qualities of germanium produced by the melting are shown in the following table (as percentage yields).

Method 1 Method 2

defective 30 20

grade D 30 20

grade C 20 25

grade B 15 20

grade A 5 15

Silvco can refire melted germanium in an attempt to improve its quality. It costs $25 to refire the melted germanium for one transistor. The results of the refiring process are shown in the table below. For example, if grade B germanium is refired, 50% of the resulting germanium will still be grade B and 50% will be grade A.

defective grade D grade C grade B grade A

defective 30 25 15 20 10

grade D 30 30 20 20

grade C 40 30 30

grade B 50 50

Silvco has sufficient furnace capacity to melt or refire germanium for at most 20,000 transistors per month. Silvco’s monthly demands are for 1000 grade A transistors, 2000 grade B transistors, 3000 grade C transistors, and 3000 grade D transistors.

Assuming that just one stage of refiring is allowed, model the melting/refiring process and determine the minimum cost of germanium processing required to meet the demands.

Hint: Remember to start by asking: What are the decision variables? Then work through how the decision variables relate to the data in the tables and the text. In particular, you will need to define how the objective (total cost) is related to the decision variables.

2 of 2
