# 📘 Chapter 3 – Probability

Probability is a measure of the likelihood of an event occurring.

Its value ranges between **0 and 1**:
- 0 → Impossible
- 1 → Certain  
Values like 0.5 or 0.6 represent varying degrees of likelihood.

---

## 🎯 Goal of This Chapter

After completing this chapter, I can:

- Understand basic probability concepts  
- Identify sample space and events  
- Work with joint, disjoint, dependent and independent events  
- Apply conditional probability  
- Use Bayes’ Theorem for real-world problems  

---

## 📌 Sample Space

Sample Space is the set of all possible outcomes of a random experiment.

### Examples

- Tossing a coin  
  `S = {T, H}`  

- Tossing two coins  
  `S = {TT, TH, HT, HH}`  

- Rolling a die  
  `S = {1,2,3,4,5,6}`  

- Rolling two dice  
  Total outcomes = **36**

---

## 📌 Event

An event is a subset of the sample space representing specific outcomes.

### Example

Rolling a die:

- Sample space:  
  `S = {1,2,3,4,5,6}`  

- Event A (even numbers):  
  `A = {2,4,6}`  

- Event B (prime numbers):  
  `B = {2,3,5}`  

---

## 📌 Probability Function

Probability assigns a value to each event:
P(Event) = Number of favourable outcomes / Total outcomes


### Examples

- Getting a head:
`P(H) = 1/2`


- Getting even number on dice:
`P = 3/6 = 1/2 = 0.5`


---

## 📌 Complement of an Event

Complement of A is written as `Aᶜ` or `A'`.

It contains outcomes NOT in A.

Formula:
`P(Aᶜ) = 1 − P(A)`

Example:
`S = {1,2,3,4,5,6}
A = {2,4,6}
Aᶜ = {1,3,5}`


---

## 📌 Types of Events

### 1️⃣ Joint Event (Non-Disjoint)

Events having common outcomes.

Formulas:
`P(A ∩ B)
P(A ∪ B) = P(A) + P(B) − P(A ∩ B)`


---

### 2️⃣ Disjoint Event (Mutually Exclusive)

No common outcomes.
`P(A ∩ B) = 0
P(A ∪ B) = P(A) + P(B)`


---

### 3️⃣ Dependent Event

One event affects another.

Example: Drawing cards without replacement.

Formula:
`P(A ∩ B) = P(A) × P(B|A)`


---

### 4️⃣ Independent Event

Events do NOT affect each other.

Example: Tossing two coins.
`P(A ∩ B) = P(A) × P(B)`

---

## 📌 Conditional Probability
Probability of A given B already occurred:
`P(A|B) = P(A ∩ B) / P(B)`


Used when previous event impacts next event.

---

## 📌 Bayes’ Theorem

Used to update probability based on new evidence.

Formula:
`P(A|B) = (P(B|A) × P(A)) / P(B)`


Where:

- P(A) → Prior  
- P(B|A) → Likelihood  
- P(B) → Marginal  
- P(A|B) → Posterior  

---

## 📌 Use Cases of Bayes’ Theorem

- Medical Diagnosis  
- Spam Classification  
- Recommendation Systems  
- Fraud Detection  

---

## 🧠 Key Example

Finding probability of King given face card:
`P(King|Face) = (P(Face|King) × P(King)) / P(Face)`
Result:`1/3`


---

## ✅ Outcome

After completing this chapter, I can:

- Define probability mathematically  
- Work with sample spaces and events  
- Distinguish joint, disjoint, dependent & independent events  
- Apply conditional probability  
- Solve problems using Bayes’ Theorem  
- Understand probability in real-world scenarios  

---







