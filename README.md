# cs550-exercises-2-solved
**TO GET THIS SOLUTION VISIT:** [CS550 Exercises 2 Solved](https://www.ankitcodinghub.com/product/cs550-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118153&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS550 Exercises 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Exercises 2

a¯i denotes inputs in step i.

a¯0 a¯1 a¯j

s¯0 ··· sj s¯j+1

where Ri is our transition formula, with variables renamed:

1. In this system (which has n Boolean variables), give a simple upper bound on the longest trace from the initial state that does not contain any repeated states.

Let the set of error states be SE = {v¯ | [¯s → v¯] |= E}.

2. Use Tj and similar formulas to find quantified Boolean formulas F (QBF, with quantification only over propositional variables) whose free variables are s1,…,sn and such that the set

{v¯ | [¯v 7→ s¯] |= F}

is one of the following (write the form of the formula for each of the sets):

states that can be reached in exactly k steps, (¯rk)[Init] states that can be reached in at most k steps, ( all reachable states (

states that can reach error state in k steps, (¯r−1)k[SE] states that can reach error state in at most k steps, ( all stuck states in the system, {v¯ | ¬∃v¯′.(¯v,v¯′) ∈ r¯}

3. Write QBF formulas without free variables that express the following:

no error state is reachable from the initial state no stuck state is reachable from the initial state every state in the system is reachable in k or fewer steps

there exists an infinite trace of the system (for some behavior of the environment given by the values of ¯a in every step).

Exercise 2 (Tseytin Transformation). The Tseytin transformation of a propositional formula ϕ is a formula in Conjunctive Normal Form (CNF) produced the following way: Recursively for each subformula ϕk of ϕ looking like xi ◦ xj, create a new variable yk and a new assignement yk ↔ xi ◦ xj (for ◦ ∈ {∨,∧,→} and similarly for negation). Replace ϕk by yk in ϕ and continue until ϕ is reduced to a single variable. Take the conjunction of that variable with all created assignements. For example,

¬(a ∧ b) → c

becomes

(y1 ↔ (a ∧ b)) ∧ (y2 ↔ ¬y1) ∧ (y3 ↔ y2 → c) ∧ y3

Any expression of the type yk ↔ xi ◦ xj can then also be equivalently expressed in CNF.

1. Compute the Tseytin transformation of ¬(((a∨¬b)∧¬(b → c)) → a).

2. Prove that on all inputs, a formula and its Tseytin transform are always equisatisfiable (one is satisfiable if and only if the other is), but not necessarily equivalent.

3. Prove that if Tseytin’s transform of ¬F is unsatisfiable, then F is a valid formula.

4. given n the size of an original formula, give the assymptotic size of its Tseytin transformation, in ”Big O” notation.

Exercise 3 (SAT solving). Prove the validity of the formula

((a ∨ ¬b) ∧ ¬(b → c)) → a

by first using the Tseytin’s transformation you have computed in the first question of Exercise 2, and then following by a resolution proof on clauses to obtain an empty clause.

Exercise 4 (First-order structures). Consider a first-order language (signature) L = {L,B,T} with one relation symbol, L, of arity two, and constants, B,T. Consider the following formulas in the language L:

Min : ∀x.L(B,x)

Max : ∀x.L(x,T)

Tot : ∀x.∀y.(L(x,y) ∨ L(y,x))

Tra : ∀x.∀y.∀z. ((L(x,y) ∧ L(y,z)) → L(x,z))

Let S = {Min,Max,Tot,Tra}.

1. Let D = {b,u,t} be a set of three elements. List all possible FOL structures (D,α) of language L in which the set of formulas S is true and where α(B) = b and α(T) = t. For each structure, show the two-dimensional table of the form:

L b u t

b u t

filled with 0 and 1 where 1 indicates the relation holds and 0 that it does not hold. Explain why these are the only structures with the required property. For each structure, indicate whether L satisfies the axioms of a partial order (reflexivity, symmetry, transitivity).

2. Now consider an extended language L′ = L∪{E} where E is a binary relation symbol. We will define a new structure α′ that also defines E. In each of the structures identified in Q1, give a table for E such additionally the following formula is true:

Both : ∀x.∀y.(E(x,y) ↔ (L(x,y) ∧ L(y,x)))

In each case, check whether the relation given by α′(E) is an equivalence relation (i.e., it is reflexive, symmetric, and transitive). Let S′ = S ∪ {Both}.

3. Does there exist a structure α′ (with arbitrary domain) that makes S′ true such that the relation α′(E) is not an equivalence relation?

4. (Intentionally open ended) Can you use structure α′ with any domain D that satisfies S′ to define a new structure α1 that also satisfies S′, that has a possibly different domain D1 but with size no larger than D, and where α1(L) is a partial order relation?
