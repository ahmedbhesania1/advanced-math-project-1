# Probability & Statistics Student Analysis Project

> 🎥 **Project Explanation Video:** [Watch the Project Explanation Video](https://drive.google.com/file/d/1C6Sgz9Hkp-hhejKDX2NlVLwOfYDkOikb/view?usp=sharing)

## 📌 Project Overview

This project applies fundamental **Probability and Statistics concepts** to a dataset of **200 students**.

The dataset contains information about:

* Study hours per week
* Attendance percentage
* Group discussion participation
* Previous test score
* Final exam result

The main goal of this project is to understand how probability concepts can be applied to real-world student data and how different events and variables can be analyzed.

---

## 📊 Dataset

The dataset contains **200 student records** with the following columns:

| Column              | Description                                      |
| ------------------- | ------------------------------------------------ |
| study_hours         | Number of hours a student studied per week       |
| attendance          | Percentage attendance in lectures                |
| group_discussion    | Participation in group discussions (Yes/No)      |
| previous_test_score | Marks out of 100 from the previous internal test |
| final_exam_pass     | Final exam result (Pass/Fail)                    |

---

## 🎯 Topics Covered

* Probability
* Random Experiment
* Outcome
* Sample Space
* Events
* Random Variables
* Probability Distributions
* PMF (Probability Mass Function)
* Expected Value
* Mean
* Variance
* Venn Diagrams
* Contingency Tables
* Joint Probability
* Marginal Probability
* Conditional Probability
* Independent Events
* Dependent Events
* Mutually Exclusive Events
* Bayes' Theorem

---

## 🎲 Random Variable

A random variable was defined as:

**Number of students passing the final exam out of 3 randomly selected students.**

Possible values of X:

* X = 0 → No student passes
* X = 1 → One student passes
* X = 2 → Two students pass
* X = 3 → Three students pass

### Probability Distribution

| X | P(X=x) |
| - | ------ |
| 0 | 0.2724 |
| 1 | 0.4469 |
| 2 | 0.2390 |
| 3 | 0.0417 |

The probabilities add up to approximately **1**, so this is a valid probability distribution.

---

## 📈 Expected Value

Expected Value is calculated using:

Expected Value = Σ [x × P(X=x)]

Calculation:

Expected Value

= (0 × 0.2724)

* (1 × 0.4469)

* (2 × 0.2390)

* (3 × 0.0417)

= 1.05

### Interpretation

If groups of 3 students are repeatedly selected, the average number of students passing per group will be approximately **1.05**.

---

## 📐 Variance

Variance measures how spread out the values of a random variable are around its expected value.

Using the probability distribution:

Variance = 0.68

### Interpretation

A variance of 0.68 indicates that the number of students passing in groups of 3 varies moderately around the expected value.

---

## 🔵 Venn Diagram

A Venn diagram was created for the following two events:

* A = Students who study more than 10 hours per week
* B = Students who attend more than 80% of classes

The overlap represents students who satisfy both conditions.

### Student Distribution

| Condition             | Number of Students |
| --------------------- | ------------------ |
| Study > 10 hours only | 85                 |
| Attendance > 80% only | 17                 |
| Both conditions       | 79                 |
| Neither condition     | 19                 |

---

## 📋 Contingency Table

A contingency table was created for:

* Group Discussion Participation
* Final Exam Result

### Contingency Table

| Group Discussion | Pass | Fail | Total |
| ---------------- | ---- | ---- | ----- |
| Yes              | 40   | 68   | 108   |
| No               | 30   | 62   | 92    |
| Total            | 70   | 130  | 200   |

This table was used to calculate joint, marginal, and conditional probabilities.

---

## 🔗 Joint Probability

The joint probability of:

**Participating in Group Discussion AND Passing the Exam**

Calculation:

Joint Probability

= 40 / 200

= 0.20

= 20%

### Interpretation

There is a 20% probability that a randomly selected student both participated in group discussions and passed the final exam.

---

## 📌 Marginal Probability

The marginal probability of passing the exam is:

Marginal Probability

= 70 / 200

= 0.35

= 35%

### Interpretation

There is a 35% chance that a randomly selected student passes the final exam.

---

## 🔍 Conditional Probability

The probability of passing the exam given that the student participated in group discussion.

Calculation:

Conditional Probability

= 40 / 108

= 0.3704

= 37.04%

### Interpretation

Among students who participated in group discussions, approximately 37.04% passed the final exam.

---

## ⚖️ Independent, Dependent, or Mutually Exclusive?

The project checked whether:

**Participating in Group Discussions and Passing the Exam**

are independent, dependent, or mutually exclusive events.

### Mutually Exclusive?

No.

Mutually exclusive events cannot happen at the same time.

However, 40 students both participated in group discussions and passed the exam.

Therefore:

**The events are not mutually exclusive.**

### Independent or Dependent?

Overall probability of passing:

35%

Probability of passing given participation in group discussions:

37.04%

Since:

35% ≠ 37.04%

The events are considered dependent.

Therefore:

**Participating in group discussions and passing the exam are dependent events.**

---

## 🧮 Bayes' Theorem

Historical data was used to apply Bayes' Theorem.

Given:

* Probability of High Attendance given Pass = 0.70
* Probability of High Attendance given Fail = 0.40
* Probability of High Attendance = 0.60

Let:

* P = Student Passes
* F = Student Fails
* H = Student has High Attendance

### Step 1: Find Probability of Passing

Calculation:

Probability(Pass)

= (0.60 - 0.40)

÷ (0.70 - 0.40)

= 0.20 ÷ 0.30

= 0.6667

= 66.67%

### Step 2: Apply Bayes' Theorem

Probability(Pass | High Attendance)

= (0.70 × 0.6667)

÷ 0.60

= 0.7778

= 77.78%

### Result

**Probability(Pass | High Attendance) = 77.78%**

### Interpretation

A student with high attendance (greater than 80%) has an estimated **77.78% probability of passing** based on the given historical probabilities.

---

## 🛠️ Tools Used

* Python
* Pandas
* Probability and Statistics
* Venn Diagrams
* Contingency Tables
* GitHub
* Markdown

---

## 📚 Learning Outcomes

Through this project, I practiced:

* Calculating and interpreting probability
* Defining random variables
* Creating probability distributions
* Calculating expected value
* Calculating variance
* Understanding PMF
* Creating and interpreting Venn diagrams
* Creating contingency tables
* Calculating joint probability
* Calculating marginal probability
* Calculating conditional probability
* Identifying dependent events
* Identifying mutually exclusive events
* Applying Bayes' Theorem
* Applying probability concepts to real-world student data

---

## 📝 Conclusion

This project demonstrates how probability and statistics can be applied to real-world student data.

It combines theoretical probability concepts with practical calculations to analyze student performance, attendance, study habits, and group discussion participation.

The project helped build a practical understanding of:

* Probability Distributions
* Random Variables
* Expected Value
* Variance
* Conditional Probability
* Contingency Tables
* Joint Probability
* Marginal Probability
* Bayes' Theorem

and their application in real-world educational datasets.

---

## 👤 Author

**Ahmed Bhesania**
