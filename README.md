# Probability & Statistics Student Analysis Project {#probability--statistics-student-analysis-project}

> 🎥 **Project Explanation Video:** [Watch the Project Explanation
> Video](https://drive.google.com/file/d/1C6Sgz9Hkp-hhejKDX2NlVLwOfYDkOikb/view?usp=sharing)

## 📌 Project Overview {#pushpin-project-overview}

This project applies fundamental **probability and statistics concepts**
to a dataset of **200 students**. The dataset contains study hours,
attendance, group discussion participation, previous test scores, and
final exam results.

The project focuses on applying probability concepts to real student
data and interpreting the results.

## 📊 Dataset {#bar_chart-dataset}

  Column                  Description
  ----------------------- --------------------------------------------------
  `study_hours`           Number of hours a student studied per week
  `attendance`            Percentage attendance in lectures
  `group_discussion`      Participation in group discussions (`Yes`/`No`)
  `previous_test_score`   Marks out of 100 from the previous internal test
  `final_exam_pass`       Final exam result (`Pass`/`Fail`)

## 🎯 Topics Covered {#dart-topics-covered}

-   Probability and probability terminology
-   Random experiments, outcomes, sample spaces, and events
-   Random variables
-   Probability distributions
-   PMF
-   Expected value / mean
-   Variance
-   Venn diagrams
-   Contingency tables
-   Joint probability
-   Marginal probability
-   Conditional probability
-   Independent and dependent events
-   Mutually exclusive events
-   Bayes\' Theorem

## 🎲 Random Variable {#game_die-random-variable}

A random variable was defined as:

> **Number of students passing the final exam out of 3 randomly selected
> students.**

Therefore:

\[ X = {0,1,2,3} \]

where `X` represents the number of students who pass.

### Probability Distribution

    X   P(X = x)
  --- ----------
    0     0.2724
    1     0.4469
    2     0.2390
    3     0.0417

The probabilities add up to approximately **1**, so this is a valid
probability distribution.

## 📈 Expected Value {#chart_with_upwards_trend-expected-value}

The expected value is calculated using:

\[ E(X)=\\sum xP(X=x) \]

For this distribution:

\[ E(X)=0(0.2724)+1(0.4469)+2(0.2390)+3(0.0417) \]

\[ E(X) pprox1.05 \]

**Interpretation:** In repeated groups of 3 randomly selected students,
the average number of students passing would be approximately **1.05**.

## 📐 Variance {#triangular_ruler-variance}

Variance measures how spread out the random variable is around its
expected value.

\[ Var(X)=E\[(X-E(X))\^2\] \]

Using the probability distribution, the variance is approximately:

\[ oxed{0.68} \]

## 🔵 Venn Diagram {#large_blue_circle-venn-diagram}

A Venn diagram was created for:

-   **A:** Students who study more than 10 hours per week
-   **B:** Students who attend more than 80% of classes

The overlap represents students satisfying **both conditions**:

\[ A\\cap B \]

For the 200-student dataset:

-   Study \> 10 hours only: **85**
-   Attendance \> 80% only: **17**
-   Both conditions: **79**
-   Neither condition: **19**

## 📋 Contingency Table {#clipboard-contingency-table}

A contingency table was created for `group_discussion` vs
`final_exam_pass`.

  Group Discussion       Pass      Fail     Total
  ------------------ -------- --------- ---------
  Yes                      40        68       108
  No                       30        62        92
  **Total**            **70**   **130**   **200**

### Joint Probability

Probability that a student **participates in group discussion AND
passes**:

\[ P(Discussion\\cap Pass)=rac{40}{200}=0.20 \]

\[ oxed{20%} \]

### Marginal Probability

Probability that a randomly selected student **passes**:

\[ P(Pass)=rac{70}{200}=0.35 \]

\[ oxed{35%} \]

### Conditional Probability

Probability that a student **passes given that they participated in
group discussion**:

\[ P(Pass\|Discussion)=rac{40}{108} pprox0.3704 \]

\[ oxed{37.04%} \]

## ⚖️ Independent, Dependent, or Mutually Exclusive? {#balance_scale-independent-dependent-or-mutually-exclusive}

The events **participating in group discussion** and **passing the
exam** are:

### Not mutually exclusive

They can happen at the same time because **40 students both participated
and passed**.

### Dependent

\[ P(Pass)=35% \]

while:

\[ P(Pass\|Discussion)=37.04% \]

Since:

\[ 35% eq37.04% \]

the events are considered **dependent**.

## 🧮 Bayes\' Theorem {#abacus-bayes-theorem}

Historical probabilities were used to find the probability of passing
given high attendance.

Given:

\[ P(H\|P)=0.70 \]

\[ P(H\|F)=0.40 \]

\[ P(H)=0.60 \]

First:

\[ P(P)=rac{0.60-0.40}{0.70-0.40}=0.6667 \]

Then:

\[ P(P\|H)=rac{P(H\|P)P(P)}{P(H)} \]

\[ =rac{0.70(0.6667)}{0.60} \]

\[ oxed{P(P\|H) pprox0.7778=77.78%} \]

**Interpretation:** Given high attendance (\>80%), the probability of
passing is approximately **77.78%** under the stated historical
assumptions.

## 🛠️ Tools Used {#hammer_and_wrench-tools-used}

-   Python
-   Pandas
-   Probability and Statistics
-   Venn diagrams
-   Contingency tables
-   GitHub / Markdown

## 📚 Learning Outcomes {#books-learning-outcomes}

This project provided practical experience with:

-   Calculating and interpreting probability
-   Defining random variables
-   Creating probability distributions
-   Calculating expected value and variance
-   Understanding PMF
-   Using Venn diagrams
-   Creating contingency tables
-   Calculating joint, marginal, and conditional probabilities
-   Identifying dependent and mutually exclusive events
-   Applying Bayes\' Theorem
-   Connecting statistical theory with real-world student data

## 📝 Conclusion {#pencil-conclusion}

This project demonstrates how probability and statistics can be applied
to real-world student data. It combines theoretical concepts with
practical calculations to analyze student performance, attendance, study
habits, and group discussion participation.

The project builds a practical understanding of probability
distributions, expected value, variance, conditional probability,
contingency tables, and Bayes\' Theorem.

------------------------------------------------------------------------

## 👤 Author {#bust_in_silhouette-author}

**Author:- Ahmed Bhesania**
