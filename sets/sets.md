---
marp: true
theme: uncover
class: invert
math: mathjax
style: |
    .columns {
       display: grid;
       grid-template-columns: repeat(2, minmax(0, 1fr));
       gap: 1rem;
     }
---

## What is a set ?

A set is a collection of objects

---

## History of Set Theory

The founders of set theory are Georg Cantor, Bertrand Russell,
Ernst Zermelo, Abraham Fraenkel

![bg right height:500px](cantor.jpg)

---

## Russel's Paradox

$$let \ R = \{x | x \notin x\}$$

In other words: a set that contains sets that dont contain themselves causes paradox

---

# Axioms of Set Theory

---

## 1. Axiom of extensionality

$$\forall x \forall y [\forall z(z\in x \iff z \in y) \implies x = y ]$$

---

## 2. Axiom of regularity

$$\forall x [\exists a (a \in x) \implies \exists y]$$

---

## 3. Axiom of subsets

$$\forall z \forall w_1 \forall w_2 \dots \forall w_n \exists y \forall x [x \in y \iff ((x \in z) \land \varphi (x, w_1, w_2, \dots, w_n, z))]$$

---

## 4. Axiom of pairing

$$\forall x \forall y \exists z ((x \in z) \land (y \in z))$$

---

## 5. Axiom of union

$$\forall F \exists A \forall Y \forall x [(x \in Y \land Y \in F) \implies x \in A]$$

---

## 6. Axiom schema of replacement

$$\forall A \forall w_1 \forall w_2 \dots \forall w_n[\forall x(x \in A \implies \exists! y \varphi) \implies \exists B \forall x (x \in A \implies \exists y (y \in B \land \varphi))]$$

---

## 7. Axiom of infinity

$$\exists X[\exists e (\forall z \lnot(z \in e) \land e \in X) \land \forall y (y \in X \implies S(y) \in X)]$$
$$where \ S(w) = w \cup \{w\}$$

---

## 8. Axiom of power set

$$\forall x \exists y (z \subset x \implies z \in y)$$

---

## 9. Axiom of choice

$$\forall X \exists R \ (R well-orders X)$$

---

## Applications of Set theory

---
