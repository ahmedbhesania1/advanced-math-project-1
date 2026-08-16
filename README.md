# Probability & Statistics Student Analysis Project

> 🎥 **Project Explanation Video:** [Watch the Project Explanation Video](https://drive.google.com/file/d/1C6Sgz9Hkp-hhejKDX2NlVLwOfYDkOikb/view?usp=sharing)

## 📌 Project Overview

This project applies fundamental **probability and statistics concepts** to a dataset of **200 students**.

The dataset contains information about:

- Study hours per week
- Attendance percentage
- Group discussion participation
- Previous test score
- Final exam result

The main goal of this project is to understand how probability concepts can be applied to real-world student data and how different events and variables can be analyzed.

---

## 📊 Dataset

The dataset contains **200 student records** with the following columns:

| Column | Description |
|---|---|
| `study_hours` | Number of hours a student studied per week |
| `attendance` | Percentage attendance in lectures |
| `group_discussion` | Participation in group discussions (`Yes`/`No`) |
| `previous_test_score` | Marks out of 100 from the previous internal test |
| `final_exam_pass` | Final exam result (`Pass`/`Fail`) |

---

## 🎯 Topics Covered

- Probability
- Random experiment
- Outcome
- Sample space
- Events
- Random variables
- Probability distributions
- PMF
- Expected value
- Mean
- Variance
- Venn diagrams
- Contingency tables
- Joint probability
- Marginal probability
- Conditional probability
- Independent events
- Dependent events
- Mutually exclusive events
- Bayes' Theorem

---

## 🎲 Random Variable

A random variable was defined as:

> **Number of students passing the final exam out of 3 randomly selected students.**

Therefore, the possible values of the random variable are:

\[
X = \{0,1,2,3\}
\]

Where:

- `X = 0` → No student passes
- `X = 1` → 1 student passes
- `X = 2` → 2 students pass
- `X = 3` → All 3 students pass

### Probability Distribution

| X | P(X = x) |
|---:|---:|
| 0 | 0.2724 |
| 1 | 0.4469 |
| 2 | 0.2390 |
| 3 | 0.0417 |

The probabilities add up to approximately **1**, so this is a valid probability distribution.

---

## 📈 Expected Value

The expected value of a discrete random variable is calculated using:

\[
E(X) = \sum xP(X=x)
\]

For the above distribution:

\[
E(X)
=
0(0.2724)
+
1(0.4469)
+
2(0.2390)
+
3(0.0417)
\]

\[
E(X) \approx 1.05
\]

### Interpretation

If groups of 3 students are repeatedly selected, the average number of students passing per group will be approximately **1.05**.

---

## 📐 Variance

Variance measures how spread out the values of a random variable are around its expected value.

The formula used is:

\[
Var(X) = E[(X-E(X))^2]
\]

Using the probability distribution, the variance is approximately:

\[
\boxed{0.68}
\]

---

## 🔵 Venn Diagram

A Venn diagram was created for the following two events:

- **A:** Students who study more than 10 hours per week
- **B:** Students who attend more than 80% of classes

The overlap represents students who satisfy **both conditions**:

\[
A \cap B
\]

For the 200-student dataset:

- Study > 10 hours only: **85 students**
- Attendance > 80% only: **17 students**
- Both conditions: **79 students**
- Neither condition: **19 students**

---

## 📋 Contingency Table

A contingency table was created for:

- `group_discussion`
- `final_exam_pass`

### Contingency Table

| Group Discussion | Pass | Fail | Total |
|---|---:|---:|---:|
| Yes | 40 | 68 | 108 |
| No | 30 | 62 | 92 |
| **Total** | **70** | **130** | **200** |

This table was used to calculate joint, marginal, and conditional probabilities.

---

## 🔗 Joint Probability

The joint probability of:

> Participating in group discussion **AND** passing the exam

is:

\[
P(Discussion \cap Pass)
=
\frac{40}{200}
\]

\[
=0.20
\]

Therefore:

\[
\boxed{20\%}
\]

---

## 📌 Marginal Probability

The marginal probability of passing the exam is:

\[
P(Pass)
=
\frac{70}{200}
\]

\[
=0.35
\]

Therefore:

\[
\boxed{35\%}
\]

---

## 🔍 Conditional Probability

The probability of passing the exam **given that the student participated in group discussion** is:

\[
P(Pass|Discussion)
=
\frac{40}{108}
\]

\[
\approx0.3704
\]

Therefore:

\[
\boxed{37.04\%}
\]

---

## ⚖️ Independent, Dependent, or Mutually Exclusive?

The project checked whether:

> Participating in group discussions and passing the exam

are independent, dependent, or mutually exclusive events.

### Mutually Exclusive?

No.

Mutually exclusive events cannot happen at the same time.

However, **40 students both participated in group discussion and passed the exam**.

Therefore:

\[
\boxed{\text{They are not mutually exclusive}}
\]

### Independent or Dependent?

The overall probability of passing is:

\[
P(Pass)=35\%
\]

The probability of passing given participation in group discussion is:

\[
P(Pass|Discussion)=37.04\%
\]

Since:

\[
35\% \neq 37.04\%
\]

the events are considered **dependent**.

Therefore:

\[
\boxed{\text{The events are dependent}}
\]

---

## 🧮 Bayes' Theorem

Historical data was used to apply Bayes' Theorem.

Given:

- 70% of students who pass have high attendance
- 40% of students who fail have high attendance
- 60% of all students have high attendance

Let:

- `P` = Student passes
- `F` = Student fails
- `H` = Student has high attendance

Given:

\[
P(H|P)=0.70
\]

\[
P(H|F)=0.40
\]

\[
P(H)=0.60
\]

### Step 1: Find P(P)

First, we find the overall probability of passing:

\[
P(P)
=
\frac{0.60-0.40}{0.70-0.40}
\]

\[
P(P)
=
\frac{0.20}{0.30}
\]

\[
P(P)=0.6667
\]

Therefore:

\[
\boxed{P(P)=66.67\%}
\]

### Step 2: Apply Bayes' Theorem

\[
P(P|H)
=
\frac{P(H|P)P(P)}{P(H)}
\]

Substituting the values:

\[
P(P|H)
=
\frac{0.70(0.6667)}{0.60}
\]

\[
P(P|H)\approx0.7778
\]

Therefore:

\[
\boxed{P(P|H)=77.78\%}
\]

### Interpretation

A student with **high attendance (>80%)** has an estimated **77.78% probability of passing**, based on the given historical probabilities.

---

## 🛠️ Tools Used

- Python
- Pandas
- Probability and Statistics
- Venn diagrams
- Contingency tables
- GitHub
- Markdown

---

## 📚 Learning Outcomes

Through this project, I practiced:

- Calculating and interpreting probability
- Defining random variables
- Creating probability distributions
- Calculating expected value
- Calculating variance
- Understanding PMF
- Creating and interpreting Venn diagrams
- Creating contingency tables
- Calculating joint probability
- Calculating marginal probability
- Calculating conditional probability
- Identifying dependent events
- Identifying mutually exclusive events
- Applying Bayes' Theorem
- Applying probability concepts to real-world student data

---

## 📝 Conclusion

This project demonstrates how probability and statistics can be applied to real-world student data.

It combines theoretical probability concepts with practical calculations to analyze student performance, attendance, study habits, and group discussion participation.

The project helped build a practical understanding of **probability distributions, random variables, expected value, variance, conditional probability, contingency tables, and Bayes' Theorem**.

---

## 👤 Author

**Author:- Ahmed Bhesania**
