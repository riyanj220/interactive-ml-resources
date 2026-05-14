# 🧠 ML Math Roadmap: From Fundamentals to Algorithms

> A structured, curated roadmap for university students and self-taught
> developers who want to **understand the math behind Machine Learning** —
> not just call `.fit()` and hope for the best.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: CC0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](LICENSE)
[![Last Updated](https://img.shields.io/github/last-commit/riyanj220/interactive-ml-resources)](https://github.com/riyanj220/interactive-ml-resources/commits/main)

Most ML roadmaps hand you a library list and call it a day.
This one is different. Every resource here either **shows the math running**,
**visualises what the equations mean geometrically**, or **lets you work
through calculations manually** — because the only way to truly understand
an algorithm is to execute it yourself, by hand, at least once.

This roadmap is structured as a learning path, not a link dump.
Work through it top to bottom and you will go from shaky algebra
to confidently implementing and explaining ML algorithms from scratch.

---

## 📋 Table of Contents

- [How to Use This Roadmap](#-how-to-use-this-roadmap)
- [Stage 1 — Linear Algebra](#-stage-1--linear-algebra)
- [Stage 2 — Calculus & Optimisation](#-stage-2--calculus--optimisation)
- [Stage 3 — Probability & Statistics](#-stage-3--probability--statistics)
- [Stage 4 — Core ML Algorithms](#-stage-4--core-ml-algorithms)
- [Interactive Intuition Tools](#-interactive-intuition-tools)
- [Visual Algorithm Explainers](#-visual-algorithm-explainers)
- [Practice Datasets](#-practice-datasets)
- [Cheatsheets & Quick References](#-cheatsheets--quick-references)
- [Contributing](#contributing)

---

## 🗺 How to Use This Roadmap

This is not a "collect them all" resource list.
It is a **sequential curriculum**. Each stage unlocks the next.

Linear Algebra → Calculus → Probability → Algorithms → Build Things

└───────── Loop back when something breaks ──────────┘

**If you are a complete beginner:** Start at Stage 1. Do not skip it.
The reason most developers hit a wall with ML is not the code — it is
that they never built a working mental model of matrix operations
and vector spaces.

**If you have some background:** Use the Table of Contents to jump
to your weakest stage. Be honest with yourself about which stage that is.

**For exam preparation specifically:** Jump directly to the
[Interactive Intuition Tools](#-interactive-intuition-tools) section —
those resources are built for manually executing algorithms the way
a university exam requires.

---

## 📐 Stage 1 — Linear Algebra

> *The language of ML. If you cannot multiply matrices in your head,
> you cannot reason about what a neural network is doing.*

**What you need to be able to do before moving on:**
Perform matrix multiplication by hand. Understand what a dot product
measures geometrically. Explain eigenvectors without using the word
"eigenvectors." Apply these to understand why PCA works.

### Core Resources

- **[3Blue1Brown: Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)**
  — The single best starting point for anyone who has "done" linear algebra
  but never *understood* it. Each chapter reframes an abstract operation as
  a geometric transformation. Watch chapters 1–9 before touching any
  other resource. Free, 15 hours total, no prerequisites.

- **[Immersive Math — Interactive Linear Algebra](https://immersivemath.com/ila/)**
  — A peer-reviewed, fully interactive linear algebra textbook.
  Every figure is a manipulable simulation. When 3B1B explains the concept,
  this is where you go to poke at it. Covers dot products, matrix
  transformations, eigenvalues, SVD.

- **[MIT 18.06 — Gilbert Strang's Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)**
  — The canonical university course, free on MIT OpenCourseWare.
  Strang's lectures are unusually clear for a pure mathematics course.
  Use this alongside 3B1B once you want formal rigour alongside intuition.
  Problem sets are included.

- **[Khan Academy: Linear Algebra](https://www.khanacademy.org/math/linear-algebra)**
  — The safest on-ramp if MIT 18.06 feels too steep initially.
  Covers vectors, matrix operations, transformations, and inverses
  in a self-paced, fully free format.

- **[Computational Linear Algebra — fast.ai](https://github.com/fastai/numerical-linear-algebra)**
  — A practical, code-first companion to the theoretical material above.
  Implements the same concepts in Python/NumPy. Use after the
  theoretical resources, not before.

---

## 📐 Math Foundations

*For when your linear algebra or calculus needs shoring up.*

- **[Khan Academy: Linear Algebra](https://www.khanacademy.org/math/linear-algebra)** —
  Complete, free, self-paced. Covers dot products, matrix multiplication,
  eigenvectors — the building blocks of PCA, SVM, and neural networks.

- **[Immersive Math](https://immersivemath.com/ila/)** — A linear algebra
  textbook with fully interactive figures. Widely considered the best
  free visual resource for the subject.

---

## 📦 Practice Datasets

*Small, clean datasets for practicing manual calculations — not the massive
real-world sets used for training models.*

- **[UCI ML Repository](https://archive.ics.uci.edu/)** — The definitive
  source for small, clean classification and regression datasets ideal
  for working through algorithms by hand (Iris, Car Evaluation, etc.).

- **[Kaggle Datasets](https://www.kaggle.com/datasets)** — Filter by
  file size < 1MB to find datasets appropriate for manual practice.

---

## 📝 Cheatsheets & References

- **[Stanford CS229 Cheatsheets](https://stanford.edu/~shervine/teaching/cs-229/)** —
  Shervine Amidi's legendary summary sheets for the Stanford ML course.
  Dense, accurate, and used by students worldwide.

- **[aml-cheat-sheet](https://github.com/remicnrd/aml-cheatsheet)** —
  A visual, printable cheatsheet for Applied Machine Learning covering
  the most-tested algorithms in university courses.

---

## Contributing

Contributions are welcome and encouraged.

This list has a **strict quality bar**: a resource must be free, primarily
visual or interactive, and genuinely help a student understand *how* an
algorithm works — not just *that* it works.

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a PR.
Check that your suggestion is not already listed or pending in open issues.

---

<sub>Maintained by the open-source community.
Not affiliated with any of the listed projects.
Inspired by the <a href="https://github.com/sindresorhus/awesome">Awesome</a> project.</sub>
