# 🚀 The Accelerated 1-Year Roadmap (DSA Proficient → CF Candidate Master & FAANG Ready)

*A personalized 12-month plan starting from August 10, 2025.*

**Starting Point:** Comfortable with C++/STL, familiarity with all DSA topics on a standard sheet (like Striver's A2Z).
**Target (August 2026):** 2000+ Codeforces/AtCoder Rating, confident in solving LeetCode Hards, fully prepared for elite technical interviews.

---

### **🛠️ Phase 0: Calibration & Setup (1 Week)**

This phase ensures your environment is optimized for speed and you understand the CP landscape.

1.  **Environment Optimization:**
    * **IDE:** Use VS Code or CLion. Set up debugging capabilities (learn to use the debugger, it's faster than `cout`).
    * **Template:** Use a robust C++ template. The [KACTL library](https://github.com/kth-competitive-programming/kactl) is a great source, or build your own with fast I/O, common headers, macros for loops, and typedefs (`ll` for `long long`).
    * **Compiler Flags:** Use flags like `-std=c++17 -O2 -Wall` for optimization and warnings. Add `-D_GLIBCXX_DEBUG` for local testing to catch out-of-bounds errors.

2.  **Platform Familiarization:**
    * **Main Hubs:** [Codeforces](https://codeforces.com/) (for contests), [AtCoder](https://atcoder.jp/) (for high-quality math/constructive problems), [CSES](https://cses.fi/problemset/) (for foundational practice).
    * **Interview Hub:** [LeetCode](https://leetcode.com/) (for interview patterns).
    * **Tracking:** Set up [StopStalk](https://www.stopstalk.com/) to track your progress across platforms.

3.  **Mindset & Strategy:**
    * **The Golden Rule:** Your mantra is **Contest → Upsolve → Learn → Repeat**.
    * **Mistake Log:** Create a physical notebook or a digital one (Notion/Excel). For every problem you fail, write down: 1) The core idea you were missing, 2) The bug in your code, 3) The data structure or algorithm you should have used. Review this weekly.

---

### **📅 Phase 1: Bridging DSA to CP (Months 1-2 | Target: 1400 - "Specialist")**

**Goal:** You know DSA. Now, learn to apply it under pressure. This phase is about speed, implementation accuracy, and mastering common CP patterns that aren't just "implement a linked list."

#### **Topics to Master (Application, not just theory):**
* **Speed:** Binary Search (on answer), Two Pointers, Sliding Window.
* **Ad-hoc/Greedy:** Learn to prove greedy choices informally. Practice problems where the solution is a simple, clever observation.
* **Number Theory:** Modular Arithmetic (inverse, exponentiation), Sieve of Eratosthenes, Prime Factorization.
* **Data Structures in Action:** Using `map`, `set`, `priority_queue` for complex state management, not just storage.
* **Graph Traversal:** Applying DFS/BFS to grids, finding connected components, cycle detection, and Bipartite Checking.

#### **Practice & Contest Strategy:**
* **Practice Core:** The [**CSES Problem Set**](https://cses.fi/problemset/) is your primary tool. Complete the "Sorting and Searching", "Graph Algorithms", and "Dynamic Programming" sections. These solidify foundational applications.
* **Problem Source:** Solve Codeforces problems rated **1100-1500**.
* **Contests:** Participate in **every** Codeforces Div. 2 and AtCoder Beginner/Regular Contest.
    * **Your Goal:** Solve Div. 2 (A, B) within the first 20 minutes. Solve C within the first hour. Spend the remaining time seriously attempting D.
    * **Upsolving:** **Mandatory.** After each contest, you must solve at least one problem above your contest performance. If you solved up to C, you must solve D.

#### **Checkpoint:**
* You're on track if you can consistently solve 3 problems in Div. 2 contests by the end of month 2.

---

### **📅 Phase 2: Core CP Algorithms (Months 3-5 | Target: 1600-1700 - "Expert" Boundary)**

**Goal:** Master the algorithms that are the bread-and-butter of "Specialist" to "Expert" level problems. This is where you build a significant competitive advantage.

#### **Topics to Master:**
* **Data Structures:** **Segment Tree** & **Fenwick Tree (BIT)** are non-negotiable. Learn range updates and point queries, and vice-versa. **Disjoint Set Union (DSU)** with path compression and union by size/rank.
* **Advanced Graphs:** Dijkstra, Floyd-Warshall, Minimum Spanning Tree (Kruskal's/Prim's), Topological Sort, and finding Strongly Connected Components (SCCs).
* **Dynamic Programming (DP):** This is a major focus.
    * Patterns: Knapsack (0/1, unbounded), Longest Common Subsequence, Digit DP, basic DP on Trees.
    * Technique: Master state definition, transitions, and memoization vs. tabulation.
* **Combinatorics:** Basic counting, nCr mod p, Binomial Theorem, Principle of Inclusion-Exclusion.

#### **Practice & Contest Strategy:**
* **Learning:** Use [CP-Algorithms](https://cp-algorithms.com/) as your textbook. When you learn a topic (e.g., Segment Tree), read the article, then solve 10-15 problems on that specific tag on Codeforces.
* **Problem Source:** Focus on problems rated **1500-1800**.
* **Contests:**
    * **Your Goal:** Consistently solve Div. 2 (A, B, C, D). Problem E should be within reach. Your rating should start climbing steadily.
    * **Virtual Contests:** Once a week, do a virtual contest of a past CF round. This builds stamina and strategy without rating pressure.

#### **Checkpoint:**
* You're on track if Div. 2 D problems feel challenging but very solvable.

---

### **📅 Phase 3: Advanced Techniques & Fluency (Months 6-9 | Target: 1900+ - "Expert")**

**Goal:** Transition from knowing algorithms to true problem-solving. You'll learn to deconstruct hard problems and identify which combination of techniques is needed.

#### **Topics to Master:**
* **Trees:** Binary Lifting for Lowest Common Ancestor (LCA), Heavy-Light Decomposition (HLD).
* **String Algorithms:** Hashing (Rabin-Karp), Knuth-Morris-Pratt (KMP), Z-Algorithm, Tries.
* **Advanced DP:** DP with Bitmasking, DP on Profiles/Broken Profiles, introduction to Convex Hull Trick (CHT) DP.
* **Game Theory:** Basic Nim game, Sprague-Grundy Theorem.
* **Data Structures:** Sqrt Decomposition, Mo's Algorithm for offline queries.

#### **Practice & Contest Strategy:**
* **Problem Source:** Grind problems rated **1800-2100**. These problems rarely have a single-algorithm solution.
* **Mixed Practice:** Your practice should now be mostly mixed. Don't look at tags. Pick a hard problem and attack it. This builds problem-solving muscles.
* **AtCoder:** Spend more time on AtCoder Regular Contests (ARCs). Their problems are highly educational for developing mathematical and algorithmic creativity.
* **Contests:**
    * **Your Goal:** Aim for consistent Expert-level performance in Div. 2 rounds. This means solving up to E or even F. You might start qualifying for Div. 1 rounds.
    * **Div. 1:** Participate in Div. 1 rounds whenever possible. Don't be afraid to fail spectacularly. The exposure to harder, more creative problems is invaluable.

#### **Checkpoint:**
* You're on track if you start solving Div. 1 A and occasionally Div. 1 B during up-solving.

---

### **📅 Phase 4: The Final Push to Candidate Master (Months 10-12 | Target: 2000+)**

**Goal:** Polish your skills, master niche topics, and achieve the consistency required for a 2000+ rating. This phase is about optimization, speed, and mental fortitude.

#### **Topics to Master:**
* **DP Optimizations:** Convex Hull Trick, Divide and Conquer DP.
* **Flows & Matching:** Max-Flow Min-Cut, Min-Cost Max-Flow.
* **Polynomials & Convolutions:** Fast Fourier Transform (FFT) / Number Theoretic Transform (NTT).
* **Advanced Geometry:** Convex Hull, Rotating Calipers.
* **Persistent Data Structures:** Persistent Segment Tree/Trie.

#### **Practice & Contest Strategy:**
* **Problem Source:** Focus on problems rated **2000-2400**.
* **Team Contests:** If possible, participate in team contests like ICPC regionals. They teach communication and problem allocation.
* **Deep Analysis:** Your Mistake Log is now your best friend. Analyze why you get problems wrong—is it a gap in knowledge, a bug, or a failure to see the core idea?
* **Contests:**
    * **Your Goal:** Achieve a stable Expert rating and make pushes for Candidate Master. This requires near-perfect performance on problems you know how to solve and at least one solid solve on a problem that requires deep insight.

---

### **🎯 Parallel Track: Ongoing Interview Preparation**

Do not neglect this. CP skills help, but interviews are a different format.

* **Months 1-5:** After your CP practice, solve **1-2 LeetCode problems** per day. Follow the [**NeetCode 150**](https://neetcode.io/practice) or a similar structured list to cover all interview patterns.
* **Months 6-9:** Start doing **LeetCode Weekly/Biweekly contests**. Begin studying **System Design**. Read "**Grokking the System Design Interview**" and watch channels like [**Gaurav Sen**](https://www.youtube.com/c/GauravSensei).
* **Months 10-12:** Dedicate 30-40% of your time here. Do **mock interviews** on platforms like [**Pramp**](https://www.pramp.com/) and [**Interviewing.io**](https://interviewing.io/). Practice explaining your thought process clearly.

---

### **📚 The Ultimate Resource Repository**

* **Learning Hubs:**
    * [**CP-Algorithms**](https://cp-algorithms.com/) (Your Bible)
    * [**USACO Guide**](https://usaco.guide/) (Excellent explanations)
    * [**GeeksforGeeks (Algorithms)**](https://www.geeksforgeeks.org/fundamentals-of-algorithms/) (For reference)
* **Problem Sets & Sheets:**
    * [**CSES Problem Set**](https://cses.fi/problemset/)
    * [**Striver's A2Z & SDE Sheets**](https://takeuforward.org/strivers-a2z-dsa-course/)
    * [**NeetCode 150**](https://neetcode.io/practice)
    * [**A2OJ Ladders (Archived)**](https://a2oj.netlify.app/)
* **YouTube Masters:**
    * [**Errichto**](https://www.youtube.com/c/Errichto) - For general CP wisdom and tutorials.
    * [**SecondThread**](https://www.youtube.com/c/SecondThread) - For deep dives into advanced topics.
    * [**William Lin**](https://www.youtube.com/c/WilliamLin168) - To see how a top competitor thinks and competes.
    * [**Priyansh Agarwal**](https://www.youtube.com/c/PriyanshAgarwal) - Excellent, structured tutorials on advanced topics like DP and graphs.
    * [**Colin Galen (galen_colin)**](https://www.youtube.com/c/galencolin) - High-quality streams and educational content.
    * [**NeetCode**](https://www.youtube.com/c/NeetCode) - The best for interview-specific patterns.
* **Blogs & Codebases:**
    * The blogs on **Codeforces** are a goldmine. Search for tutorials on specific topics.
    * [**KACTL**](https://github.com/kth-competitive-programming/kactl) & [**Stanford's ICPC Notebook**](https://cs.stanford.edu/group/acm/Notebook/notebook.pdf) - For correct, optimized implementations of standard algorithms.
* **Books (for deep, theoretical understanding):**
    * [*Competitive Programmer's Handbook*](https://cses.fi/book/book.pdf) by Antti Laaksonen (free PDF).
    * [*Introduction to Algorithms (CLRS)*](https://mitpress.mit.edu/books/introduction-algorithms-third-edition) - For reference, not for reading cover-to-cover.

---

> This is your battle plan. The goal is audacious, but your foundation is strong. The key differentiators will be your consistency and the rigor of your upsolving. Good luck.
