---
title: "Coupling Angular Momenta I: Mathematical Background"
date: 2020-09-05T11:39:31-04:00
draft: false
---
We will deal with  &ldquo;sets&rdquo; and their elements; axiomatically, a set $A$ is a  &ldquo;collection&rdquo; of objects. We denote that an object $a$ is a member or element of $A$ by writing $a \in A$. (E.g., the set of natural numbers $\mathbb{N}$ contains the integer 1, but not 0, i.e. $1 \in \mathbb{N}$ but $0 \notin \mathbb{N}$.) Some very important sets are called <b>fields</b>, which are sets that obey certain algebraic properties; for our purposes, the two fields we shall consider are the real and complex numbers denoted $\mathbb{R}$ and $\mathbb{C}$, respectively. Given two sets, $A$ and $B$, we can define a correspondence or mapping of elements $a \in A$ to elements $b \in B$, such that each element $a$ is mapped uniquely to an element $b$. Such a map is called a <b>function</b>, and is denoted $f:A \to B$. We also write for $a \in A$, $a \mapsto f(a)$ for $f(a) \in B$ to denote that the element $a$ is mapped to $f(a)$ under the action of $f$.

An important concept, which is developed further next time, is how sets can be used to construct new sets. One straightforward way to do this is, given two sets $A$ and $B$, to define a new set composed of all ordered pairs $(a,b)$ of elements $a \in A$ and $b \in B$. This new set is called the <b>Cartesian</b> or <b>direct product</b> and is denoted,

  $\begin{equation}
    A \times B \equiv \{(a,b)\mid a \in A \text{ and } b\in B\}
  \end{equation}$

The familiar example is the construction of the Euclidean plane by taking the direct product of the real numbers with itself, $\mathbb{R}^2 \equiv \mathbb{R}\times\mathbb{R}$.
