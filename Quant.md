# 🚀 The Ultimate Quant Prep Roadmap (Easy to Hard)

This guide provides a structured path to prepare for the technical interviews and tests at elite quantitative trading firms. It is organized by topic, with resources listed in a suggested order of completion to build your knowledge progressively.

---

### **The Grand Strategy: A Phased Approach**

Your preparation will follow a clear, three-phase sequence.

* **Phase 1: Foundational Theory (The Bedrock)**
    * First, build a solid, intuitive understanding of the core mathematical and algorithmic theory. This provides the tools for everything that follows.

* **Phase 2: Parallelized Practice & Application (The Grind)**
    * This is where you will spend the majority of your time. You will tackle Math Puzzles, Competitive Programming, Mental Math, and Market Making in parallel, as skills in one area will reinforce the others.

* **Phase 3: Specializations (The Optional Edge)**
    * Lastly, and only if required by your background or specific role, you will cover Machine Learning and Finance.

---

## Detailed Topic Breakdown

Here are the key subjects, organized from foundational to advanced.

### **1. Mathematical Theory Fundamentals**

**Goal:** Develop a robust, first-principles understanding of probability and linear algebra. Do not just memorize formulas; know *why* they work.

#### **A. Probability & Statistics**
* **Foundational (Building Intuition):**
    * **Resource:** [**Harvard Stat 110 Lectures by Joe Blitzstein**](https://www.google.com/search?q=https://www.youtube.com/%40galencolin) (on YouTube)
        * **Why:** The single best resource for building a deep, intuitive understanding of probability from the ground up.
* **Core Textbook (Building Rigor):**
    * **Resource:** **"A First Course in Probability" by Sheldon Ross** or the recommended IITD textbook for MTL106.
        * **Why:** A standard university textbook that will give you a formal, rigorous understanding of the subject. Key chapters to cover include:
            * Combinatorial Analysis
            * Axioms of Probability (including Bayes' Theorem)
            * Discrete & Continuous Random Variables
            * Expectation & Variance
            * Important Distributions (Binomial, Poisson, Uniform, Normal, Exponential)
            * Markov Chains & Stochastic Processes

#### **B. Linear Algebra**
* **Foundational (Building Intuition):**
    * **Resource:** [**3Blue1Brown's "Essence of Linear Algebra"**](https://www.youtube.com/c/DanielNaroditsky0) (on YouTube)
        * **Why:** Watch this *before* opening any textbook. It provides the geometric intuition behind the operations.
* **Core Textbook (Building Rigor):**
    * **Resource:** **"Introduction to Linear Algebra" by Gilbert Strang** (and his accompanying [**MIT OCW Lectures**](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)).
        * **Why:** The standard text for a reason. Focus on understanding vector spaces, subspaces, linear independence, and everything related to **eigenvalues and eigenvectors**.

### **2. Algorithms Fundamentals**

**Goal:** Learn the standard library of algorithms and data structures used in problem-solving. Develop an intuition for time and space complexity.

* **Core Textbook:**
    * **Resource:** [**"Competitive Programmer's Handbook"**](https://cses.fi/book/book.pdf) by Antti Laaksonen
        * **Why:** A concise and modern guide to all relevant topics for competitive programming and technical interviews. For fundamentals, cover these sections first:
            * **Part I (Basic Techniques):** Chapters 1-11. This covers Time Complexity, Sorting, Data Structures (STL), Greedy Algorithms, and Dynamic Programming.
            * **Part II (Graph Algorithms):** Chapters 12-16. This covers BFS, DFS, Dijkstra, Bellman-Ford, Floyd-Warshall, and MSTs.
* **Implementation Reference:**
    * **Resource:** [**CP-Algorithms**](https://cp-algorithms.com/)
        * **Why:** An excellent, detailed reference for a wide variety of algorithms with clean implementations. Use this when the handbook feels too brief on a specific topic.

---

*You have now completed Phase 1. Proceed to the following topics in parallel.*

---

### **3. Math & Logic Problems**

**Goal:** This is the most important section. Your aim is to become a fluent and creative problem-solver, capable of tackling unfamiliar puzzles under pressure.

* **Tier 1: Warming Up & Building Confidence**
    * **Resource:** [**"Can You Solve This Riddle?" Playlist by Ted-Ed**](https://www.google.com/search?q=https://www.youtube.com/c/BotezLive9) (on YouTube)
        * **Why:** These are fun, animated, and teach you to think outside the box. An excellent way to start your daily practice.
    * **Resource:** [**CSE Blog Puzzles**](https://gurmeet.net/puzzles/)
        * **Why:** A great collection of classic and modern puzzles to build your logical reasoning muscles.
* **Tier 2: The Core Interview Grind**
    * **Resource:** [**Brainstellar**](https://brainstellar.com/)
        * **Why:** An essential resource. It contains a large collection of classic quant interview puzzles with detailed, high-quality explanations. Work through this site methodically.
    * **Resource:** **"A Practical Guide to Quantitative Finance Interviews"** by Xinfeng Zhou
        * **Why:** Considered the modern bible for quant interview prep. Covers probability, logic, stochastic calculus, and more. Solve every problem.
    * **Resource:** **"Heard On The Street"** by Timothy Falcon Crack
        * **Why:** The classic quant interview prep book. Focus on the brain teaser and probability sections.
* **Tier 3: Achieving Mastery & Depth**
    * **Resource:** **"Fifty Challenging Problems in Probability"** by Frederick Mosteller
        * **Why:** A legendary book. Solving these problems demonstrates a true mastery of probabilistic thinking.
    * **Resource:** [**QuantGuide**](https://www.quantguide.io/)
        * **Why:** A modern platform with hard, company-tagged problems. The free problems are challenging and sufficient.
    * **Resource:** **"Twenty problems in probability"** by various authors.
        * **Why:** Another famous list of challenging problems that tests deep understanding.
* **Tier 4: Elite / For the Truly Passionate**
    * **Resource:** **"Mathematical Puzzles: A Connoisseur’s Collection"** by Peter Winkler
    * **Resource:** **"Olympiad Combinatorics"** by Pranav Sriram
        * **Why:** These are extremely difficult and go beyond standard interview scope, but working through them will make you an exceptionally strong problem solver.

#### **Classic Papers & Problems to Study:**
These are individual concepts whose understanding pays huge dividends.
* [Induction Puzzles (Blue-eyed islanders problem)](https://en.wikipedia.org/wiki/Cheryl%27s_Birthday)
* [The Josephus Problem and Powers of Two](https://www.youtube.com/watch?v=uCsD3ZGzMgE)
* [Penney's Game](https://en.wikipedia.org/wiki/Penney%27s_game)
* [The Stick Breaking Problem](https://math.stackexchange.com/questions/21539/what-is-the-expected-length-of-the-shortest-piece-when-a-stick-is-broken-into-n)
* [Bertrand's Ballot Theorem](https://en.wikipedia.org/wiki/Bertrand%27s_ballot_theorem)
* [Random Walks (MIT 6.042J Chapter 20)](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-fall-2010/pages/readings/)

### **4. Competitive Programming**

**Goal:** Develop speed and accuracy in implementing algorithmic solutions. For quant roles, a solid Codeforces "Specialist" to "Expert" level is a strong signal.

* **If you are a beginner:**
    * **Resource:** [**InterviewBit Programming Course**](https://www.interviewbit.com/courses/programming/)
    * **Resource:** [**NeetCode 150 / LeetCode Grind 169**](https://neetcode.io/practice)
        * **Why:** These provide a structured path to learn the most common programming patterns.
* **If you are experienced:**
    * **Resource:** Complete the **"Competitive Programmer's Handbook"** and implement the algorithms.
    * **Resource:** Actively participate in contests on [**Codeforces**](https://codeforces.com/) and [**AtCoder**](https://atcoder.jp/).
    * **Key Strategy:** **Upsolve!** Always solve at least one problem you couldn't solve during the contest.

### **5. Mental Math**

**Goal:** Achieve speed and comfort with numbers. In an interview, you won't have a calculator. Approximation is key.

* **Platforms for Practice:**
    * **Resource:** [**Arithmetic Game (Zetamac)**](https://arithmetic.zetamac.com/)
        * **Why:** The standard for high-speed, high-pressure arithmetic drills. A score of 60+ is excellent.
    * **Resource:** [**Tradermath**](https://tradermath.org/)
        * **Why:** Simulates the numerical tests given by some trading firms.
* **Techniques:**
    * Practice approximation (e.g., 98/7 ≈ 100/7 ≈ 14.3).
    * Learn quick squaring and square root estimation techniques.

### **6. Market Making / Trading Games**

**Goal:** Develop intuition for expected value, risk, and pricing. This is critical for firms like Optiver, Akuna, and IMC.

* **Simulator:**
    * **Resource:** [**Optiver's Market Making Game Simulator**](https://www.optiver.com/trading-careers/market-making-game/) (or similar simulators online).
        * **Why:** Provides a basic, accessible way to understand the mechanics of making a market.
* **The Best Practice:**
    * Find peers and play live trading games. This is irreplaceable. Your university's finance or trading club is the best place to find people.

### **7. Machine Learning (Optional)**

**Goal:** Understand the fundamentals of supervised learning and be able to implement basic models. Only required for specific roles or if you have it on your resume.

* **Topics:** Linear & Logistic Regression, Gradient Descent, Decision Trees, Random Forests.
* **Resources:**
    * **Resource:** [**Andrew Ng's Machine Learning Coursera Course**](https://www.coursera.org/specializations/machine-learning-introduction)
        * **Why:** The classic, best introduction to the field.
    * **Practical Skills:** Be comfortable using `scikit-learn` in Python within a Jupyter Notebook.

### **8. Finance (Optional)**

**Goal:** Understand basic financial instruments. This is **only required if you claim prior finance experience**.

* **Topics:** Options, Futures, ETFs, Swaps. For options, know the Greeks (Delta, Gamma, Vega, Theta) and the basics of the Black-Scholes model.
* **Resources:**
    * **Resource:** **"Options Volatility and Pricing"** by Sheldon Natenberg
        * **Why:** The trader's bible for options.
    * **Resource:** **Chapter 6 of Xinfeng Zhou's book.**
        * **Why:** A concise overview of the finance needed for interviews.

---
This roadmap provides the "what" and "where." The "how" is up to your discipline and consistency. Good luck.
