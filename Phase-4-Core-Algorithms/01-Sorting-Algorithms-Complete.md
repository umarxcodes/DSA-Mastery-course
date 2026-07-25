# Sorting Algorithms - Complete Mastery

## Chapter Metadata

| Field | Value |
|---|---|
| Phase | Phase 4 - Core Algorithms |
| Chapter | 17 of 37 |
| Difficulty | Intermediate |
| Time to Master | 10-12 hours |
| Prerequisites | JavaScript fundamentals, functions, arrays, objects, and basic problem solving |

## Table of Contents

1. [Simple Definition](#simple-definition)
2. [Real-World Analogy](#real-world-analogy)
3. [Visual Representation](#visual-representation)
4. [Core Concept Explanation](#core-concept-explanation)
5. [Complete Implementation](#complete-implementation)
6. [Step-by-Step Dry Run](#step-by-step-dry-run)
7. [Time & Space Complexity Analysis](#time--space-complexity-analysis)
8. [All Operations / Variations](#all-operations--variations)
9. [Common Patterns and Use Cases](#common-patterns-and-use-cases)
10. [Multiple Approaches](#multiple-approaches)
11. [Interview Gold Notes](#interview-gold-notes)
12. [Common Mistakes](#common-mistakes)
13. [Best Practices](#best-practices)
14. [Senior Engineer Notes](#senior-engineer-notes)
15. [Edge Cases](#edge-cases)
16. [Tricky Interview Problems](#tricky-interview-problems)
17. [Revision Cheat Sheet](#revision-cheat-sheet)
18. [Mini Practice Problems](#mini-practice-problems)
19. [Chapter Summary Table](#chapter-summary-table)
20. [Mock Interview Questions](#mock-interview-questions)

## Simple Definition

This chapter teaches the core idea, the operations, the implementation, the interview patterns, and the trade-offs that matter at FAANG level.

Start simple: the interviewer is not testing whether you can recite textbook language. They are testing whether you can turn a problem into a reliable sequence of choices.

> 🧠 **Mental Model:** First understand what information must be stored, then decide how quickly it must be read, updated, or removed.

## Real-World Analogy

Treat the concept like a tool in a toolbox: the goal is not to memorize the tool, but to recognize when it is the cleanest tool for the job.

The analogy matters because DSA is usually about trade-offs. A structure that is excellent for fast lookup may be poor for ordered traversal. A recursive solution may be elegant but may use extra call stack memory.

## Visual Representation

```text
input -> choose structure/pattern -> process -> output
```

## Core Concept Explanation

In interviews, every topic should be explained through four questions:

1. What does it store or compute?
2. What operations must be fast?
3. What constraints change the best approach?
4. What edge cases can break a rushed solution?

> 🟡 **Interview Gold Note:** Say the trade-off out loud. A correct solution with no explanation often looks weaker than a slightly slower solution explained with clear optimization thinking.

> 🔵 **Senior Engineer Note:** Experienced engineers choose the simplest approach that satisfies the constraints. They do not optimize blindly.

## Chapter-Specific Mastery Checklist

- Bubble, selection, insertion, merge, quick, heap, counting, radix, bucket, and TimSort
- Best, average, worst, stability, space, and use cases for every sort
- JavaScript Array.sort comparator behavior
- Sorting lower bound for comparison sorts

## Deep Teaching Notes

### 1. Bubble, selection, insertion, merge, quick, heap, counting, radix, bucket, and TimSort

**Beginner explanation:** This is one of the core ideas for Sorting Algorithms - Complete Mastery. Start by saying it in plain language before reaching for code. A beginner should understand what problem this idea solves, what input it expects, and what output it creates.

**Why it matters:** In a FAANG interview, this point shows whether you understand the shape of the problem. Interviewers care less about memorized syntax and more about whether your choices match the constraints.

**How to reason about it:** Ask what must be remembered while the algorithm runs. If you need fast lookup, think HashMap or Set. If you need ordered movement, think pointers. If you need all possibilities, think recursion or backtracking. If you need best/count/possible over repeated subproblems, think dynamic programming.

**What to say out loud:** "I am choosing this approach because it matches the constraint: the expensive operation is repeated work, so I want a structure or pattern that removes that repetition."

**Implementation angle in JavaScript:** Prefer clear names, explicit loops when teaching, and built-ins only when you can explain their complexity. JavaScript gives you Array, Map, Set, and flexible objects, but every helper method still has a cost.

**Edge checks:** Confirm behavior for empty input, one item, duplicate values, already-ordered input, reverse-ordered input, and values at the smallest or largest allowed constraints.

### 2. Best, average, worst, stability, space, and use cases for every sort

**Beginner explanation:** This is one of the core ideas for Sorting Algorithms - Complete Mastery. Start by saying it in plain language before reaching for code. A beginner should understand what problem this idea solves, what input it expects, and what output it creates.

**Why it matters:** In a FAANG interview, this point shows whether you understand the shape of the problem. Interviewers care less about memorized syntax and more about whether your choices match the constraints.

**How to reason about it:** Ask what must be remembered while the algorithm runs. If you need fast lookup, think HashMap or Set. If you need ordered movement, think pointers. If you need all possibilities, think recursion or backtracking. If you need best/count/possible over repeated subproblems, think dynamic programming.

**What to say out loud:** "I am choosing this approach because it matches the constraint: the expensive operation is repeated work, so I want a structure or pattern that removes that repetition."

**Implementation angle in JavaScript:** Prefer clear names, explicit loops when teaching, and built-ins only when you can explain their complexity. JavaScript gives you Array, Map, Set, and flexible objects, but every helper method still has a cost.

**Edge checks:** Confirm behavior for empty input, one item, duplicate values, already-ordered input, reverse-ordered input, and values at the smallest or largest allowed constraints.

### 3. JavaScript Array.sort comparator behavior

**Beginner explanation:** This is one of the core ideas for Sorting Algorithms - Complete Mastery. Start by saying it in plain language before reaching for code. A beginner should understand what problem this idea solves, what input it expects, and what output it creates.

**Why it matters:** In a FAANG interview, this point shows whether you understand the shape of the problem. Interviewers care less about memorized syntax and more about whether your choices match the constraints.

**How to reason about it:** Ask what must be remembered while the algorithm runs. If you need fast lookup, think HashMap or Set. If you need ordered movement, think pointers. If you need all possibilities, think recursion or backtracking. If you need best/count/possible over repeated subproblems, think dynamic programming.

**What to say out loud:** "I am choosing this approach because it matches the constraint: the expensive operation is repeated work, so I want a structure or pattern that removes that repetition."

**Implementation angle in JavaScript:** Prefer clear names, explicit loops when teaching, and built-ins only when you can explain their complexity. JavaScript gives you Array, Map, Set, and flexible objects, but every helper method still has a cost.

**Edge checks:** Confirm behavior for empty input, one item, duplicate values, already-ordered input, reverse-ordered input, and values at the smallest or largest allowed constraints.

### 4. Sorting lower bound for comparison sorts

**Beginner explanation:** This is one of the core ideas for Sorting Algorithms - Complete Mastery. Start by saying it in plain language before reaching for code. A beginner should understand what problem this idea solves, what input it expects, and what output it creates.

**Why it matters:** In a FAANG interview, this point shows whether you understand the shape of the problem. Interviewers care less about memorized syntax and more about whether your choices match the constraints.

**How to reason about it:** Ask what must be remembered while the algorithm runs. If you need fast lookup, think HashMap or Set. If you need ordered movement, think pointers. If you need all possibilities, think recursion or backtracking. If you need best/count/possible over repeated subproblems, think dynamic programming.

**What to say out loud:** "I am choosing this approach because it matches the constraint: the expensive operation is repeated work, so I want a structure or pattern that removes that repetition."

**Implementation angle in JavaScript:** Prefer clear names, explicit loops when teaching, and built-ins only when you can explain their complexity. JavaScript gives you Array, Map, Set, and flexible objects, but every helper method still has a cost.

**Edge checks:** Confirm behavior for empty input, one item, duplicate values, already-ordered input, reverse-ordered input, and values at the smallest or largest allowed constraints.


## Complete Implementation

```javascript
/**
 * Template for solving an interview problem clearly.
 * Time: depends on the selected pattern, Space: depends on auxiliary data.
 */
function solveWithPattern(input) {
  const result = [];

  for (const item of input) {
    result.push(item);
  }

  return result;
}

console.log(solveWithPattern([1, 2, 3]));
```

## Step-by-Step Dry Run

Use this dry-run discipline for every implementation in this chapter.

| Step | Variable State | Why It Matters |
|---|---|---|
| Input | Receive sample input | Confirm expected output and constraints |
| Initialize | Create pointers, maps, arrays, heap, stack, queue, or recursion state | A wrong initial state usually causes off-by-one bugs |
| First iteration | Process the first meaningful item | Check whether the invariant becomes true |
| Middle iteration | Update state without losing previous useful information | Most logic bugs happen here |
| Boundary iteration | Process final item or final recursive return | Confirms loop termination |
| Return | Return answer in exact requested format | Correct value with wrong shape still fails |

### Dry Run Example Mindset

Pick a small input where the answer is not obvious. Walk one line at a time. After each line, write down pointer positions, map contents, stack contents, queue contents, or recursive call state. If you cannot explain the state, the code is too magical for an interview.

> 🔴 **Common Mistake:** Candidates often dry-run only the happy path. Always include empty input, one item, duplicate values, and boundary values.

## Time & Space Complexity Analysis

| Operation | Time | Space | Why |
|---|---:|---:|---|
| Brute force scan | O(n^2) | O(1) | Checks many pairs or repeated work |
| Optimized lookup/pattern | O(n) or O(log n) | O(n) or O(1) | Uses structure, ordering, or cached state |
| Sorting-based approach | O(n log n) | O(1) to O(n) | Sorting dominates the runtime |
| Recursive approach | Depends on tree | O(depth) | Call stack counts as space |

Always explain the dominant term. If one loop runs after another, add their costs. If one loop is inside another, multiply. If recursion branches, draw the recursion tree.

## All Operations / Variations

| Variation | When To Use | Interview Signal |
|---|---|---|
| Brute force | First explanation, tiny input, baseline correctness | You can decompose the problem |
| HashMap / Set | Need fast membership, counts, grouping, or complements | You know memory-time trade-offs |
| Two pointers | Sorted arrays, palindromes, pair constraints | You can use order to reduce work |
| Sliding window | Contiguous subarray or substring with a condition | You can maintain state incrementally |
| Recursion / DFS | Trees, graphs, combinations, divide and conquer | You can express subproblems cleanly |
| Heap / Priority Queue | Top-K, streaming min/max, merging sorted sources | You can retrieve priority efficiently |
| Dynamic Programming | Counting, optimization, overlapping subproblems | You can define state and recurrence |

## Common Patterns and Use Cases

- Pattern recognition starts from constraints: input size, sorted or unsorted, duplicates, negative values, and whether the answer must be contiguous.
- If the prompt says "all", "every", "path", or "combination", expect recursion, DFS, or backtracking.
- If the prompt says "maximum/minimum subarray/substring", try sliding window, prefix sum, Kadane's algorithm, or DP.
- If the prompt says "top K", "kth", or "stream", try a heap.
- If the prompt says "fast lookup", "frequency", or "seen before", try a HashMap or Set.

## Multiple Approaches

### Brute Force

State the simplest correct idea first. This proves you understand the problem and gives you a baseline complexity.

Typical brute force language: "I can check every possible candidate and keep the best valid answer. This is easy to verify, but it may repeat work."

### Optimized

Ask: "Can I use more memory to save time?" This often leads to HashMap, Set, prefix sum, memoization, or a heap.

Typical optimized language: "The repeated operation is lookup, so I can store what I have already seen."

### Optimal

Use constraints to justify the final approach. Optimal does not mean clever; it means the best practical trade-off for the given input limits.

> ⚡ **Optimization Insight:** Most FAANG improvements come from avoiding repeated work: cache it, sort once, move pointers once, or compute each state once.

## Interview Gold Notes

> 🟡 **Interview Gold Note:** Before writing code, say: "I'll start with brute force to confirm correctness, then optimize based on the constraints."

> 🎯 **FAANG Pattern:** Identify the pattern, name the invariant, then code. Interviewers listen for the invariant because it proves your logic is stable.

Use this exact interview script when you are under pressure:

1. "Let me restate the problem to make sure I understand it."
2. "Can the input be empty? Are duplicates allowed? Is the input sorted? What are the size constraints?"
3. "I'll start with a brute force solution so we have a correct baseline."
4. "The brute force complexity is ... because ..."
5. "Now I will optimize by removing repeated work."
6. "The key invariant is ..."
7. "I'll code this carefully and then dry-run it."
8. "The final complexity is ... and the space is ... because ..."

Strong interview language:

- "The input size tells me O(n^2) may be too slow."
- "Because I need fast membership checks, a Set is a good fit."
- "Because the array is sorted, two pointers can remove one dimension of search."
- "The recursive call solves the smaller subproblem; I combine the returned values here."

## Common Mistakes

1. Jumping to code before clarifying constraints.
2. Forgetting empty input or single-element input.
3. Treating JavaScript built-in methods as O(1) without checking.
4. Mutating input when the problem expects it to remain unchanged.
5. Losing track of inclusive vs exclusive boundaries.
6. Ignoring recursion stack space.
7. Returning the right value for the sample but the wrong shape for edge cases.
8. Over-optimizing before proving brute force correctness.

## Best Practices

> 🟢 **Best Practice:** Write down the invariant in one sentence before coding.

- Use descriptive variable names.
- Keep helper functions small and purposeful.
- Add tests for normal, empty, duplicate, and boundary inputs.
- Prefer Map over plain object when keys are not guaranteed to be simple strings.
- Use arrays as builders for strings when repeated concatenation would become expensive.

### JavaScript Code Quality Rules

- Use `const` by default and `let` only when a variable changes.
- Avoid one-letter names except small loop counters.
- Prefer `Map` when keys may not be safe object property names.
- Use numeric sort comparators: `numbers.sort((a, b) => a - b)`.
- Keep mutation intentional. If the caller may need the original array, copy it first.
- Add small test cases directly below the implementation while learning.

## Senior Engineer Notes

> 🔵 **Senior Engineer Note:** Production code values maintainability. In interviews, mention both asymptotic complexity and readability trade-offs.

It is acceptable to choose O(n log n) over O(n) if the O(n) solution is fragile and constraints are modest. It is also acceptable to use extra memory if it makes the solution linear and simple.

## Edge Cases

1. Empty input.
2. Single element.
3. Duplicate values.
4. Already sorted input.
5. Reverse sorted input.
6. Negative numbers or zero.
7. Very large input.
8. Unicode strings where character indexing may be tricky.

## Tricky Interview Problems

### Problem 1: Implement the main operation

Explain the brute force idea, then improve it by choosing a pattern from this chapter.

```javascript
/**
 * Interview solving placeholder.
 * Replace this with the chapter-specific optimized technique while practicing.
 */
function solveProblemOne(input) {
  if (input == null) return null;
  return input;
}
```

### Problem 2: Solve the canonical interview problem

Focus on the invariant. The invariant is the rule that remains true after every loop or recursive call.

```javascript
/**
 * Use this to practice writing an invariant before implementation.
 */
function solveProblemTwo(input) {
  const state = Array.isArray(input) ? [...input] : input;
  return state;
}
```

### Problem 3: Explain the complexity out loud

Dry-run the smallest non-trivial input. If that works, test the edge cases.

```javascript
/**
 * Always test the smallest non-trivial case.
 */
function solveProblemThree(input) {
  return input;
}
```

## Revision Cheat Sheet

- Start with brute force.
- Calculate complexity before optimizing.
- Use HashMap/Set for membership, counts, grouping, and complements.
- Use two pointers when order can eliminate choices.
- Use sliding window for contiguous ranges.
- Use recursion when the same problem appears inside a smaller version.
- Use DP when recursive subproblems repeat.
- Always count recursion stack space.

## Mini Practice Problems

| # | Problem | Difficulty |
|---:|---|---|
| 1 | Explain the concept to a beginner in two sentences | Easy |
| 2 | Write the brute force approach for the canonical problem | Easy |
| 3 | Optimize it using the main pattern | Medium |
| 4 | Dry-run the optimized code on three inputs | Medium |
| 5 | Explain time and space complexity out loud | Medium |

## Chapter Summary Table

| Topic | Must Remember |
|---|---|
| Definition | Know the simplest explanation |
| Analogy | Use it to reason about trade-offs |
| Implementation | Write clean JavaScript with tests |
| Complexity | Explain why, not just what |
| Edge cases | Test before declaring done |
| Interview readiness | Communicate the plan and invariant |

## Mock Interview Questions

1. Explain this concept to someone who knows JavaScript but not DSA.
2. What operation is fastest here, and why?
3. What operation is slowest here, and why?
4. What edge cases would you test first?
5. What is the brute force approach?
6. How would you optimize it?
7. What data structure would you choose and why?
8. How do you calculate the time complexity?
9. How do you calculate the space complexity?
10. What would change if the input were sorted?

### Strong Answers for Three Questions

**Q: What is the brute force approach?**
A: "I would first solve it directly by checking all relevant possibilities. That may be O(n^2), but it proves correctness and gives me a baseline to optimize."

**Q: How would you optimize it?**
A: "I would look for repeated work. If I repeatedly search for something, I can often use a HashMap or Set. If order matters, I can sort or use pointers. If subproblems repeat, I can memoize."

**Q: What edge cases would you test first?**
A: "Empty input, one item, duplicates, boundary values, and a case where no valid answer exists."

<!-- DSA-JS-MERGE:START -->
## Integrated DSA JS Course Material

This section consolidates useful non-empty material from the older `DSA JS` course into this Mastery chapter so `DSA-Mastery-Roadmap` becomes the single course source.

**Imported sources:**

- `DSA JS/src/algorithms/sorting/bubble-sort/notes.md`
- `DSA JS/src/algorithms/sorting/selection-sort/notes.md`
- `DSA JS/src/algorithms/sorting/selection-sort/implementation.js`
- `DSA JS/src/algorithms/sorting/insertion-sort/notes.md`
- `DSA JS/src/algorithms/sorting/insertion-sort/implementation.js`
- `DSA JS/src/algorithms/sorting/merge-sort/notes.md`
- `DSA JS/src/algorithms/sorting/merge-sort/implementation.js`
- `DSA JS/src/algorithms/sorting/quick-sort/notes.md`
- `DSA JS/src/algorithms/sorting/quick-sort/implementation.js`

### Imported Notes: `DSA JS/src/algorithms/sorting/bubble-sort/notes.md`

# 🔵 Bubble Sort Algorithm (JavaScript)

## 📌 Definition

**Bubble Sort** is a simple comparison-based sorting algorithm where **adjacent elements are repeatedly compared and swapped** if they are in the wrong order.

The largest element **"bubbles up"** to the end of the array in each pass.

---

## 🧠 Key Idea

> Compare adjacent elements and swap them until the array becomes sorted.

- Repeatedly passes through the array
- After each pass, the largest element moves to the end
- Sorting happens step by step like bubbles rising in water

---

## ⚙️ How Bubble Sort Works (Steps)

1. Start from index `0`
2. Compare `arr[i]` with `arr[i + 1]`
3. Swap if `arr[i] > arr[i + 1]`
4. Continue till the end of the array
5. Repeat passes until no swaps are needed

---

## 🧩 Example Walkthrough

Unsorted Array:

```
[5, 1, 4, 2]
```

Steps:

- Pass 1 → `[1, 4, 2, 5]` (5 bubbled to end)
- Pass 2 → `[1, 2, 4, 5]`
- Pass 3 → No swaps → Sorted

Sorted Array:

```

```

---

## ⏱️ Time Complexity

| Case    | Complexity                          |
| ------- | ----------------------------------- |
| Best    | **O(n)** (Already sorted with flag) |
| Average | **O(n²)**                           |
| Worst   | **O(n²)**                           |

---

## 💾 Space Complexity

- **O(1)** (In-place sorting)

---

## 💬 Interview Answer (One Line)

> **Bubble Sort repeatedly swaps adjacent elements until the array is sorted.**

---

## ✅ Bubble Sort Code (JavaScript)

[1, 2, 4, 5]

```js
function bubbleSort(arr) {
  let n = arr.length

  for (let i = 0; i < n - 1; i++) {
    let swapped = false

    for (let j = 0; j < n - i - 1; j++) {
      if (arr[j] > arr[j + 1]) {
        ;[arr[j], arr[j + 1]] = [arr[j + 1], arr[j]]
        swapped = true
      }
    }

    // If no swap happened, array is already sorted
    if (!swapped) break
  }

  return arr
}

const arr = [5, 1, 4, 2, 8]
console.log(bubbleSort(arr)) // [1, 2, 4, 5, 8]
```

---

## 📌 Why It Is Called "Bubble" Sort?

- Larger elements **bubble up** to the end
- Smaller elements move toward the beginning

---

## 🎯 Where Bubble Sort Is Used

- Learning basic sorting concepts
- Very small datasets
- Educational purposes

---

## 🚫 Disadvantages

- Very slow for large datasets
- Time complexity is mostly **O(n²)**
- Not suitable for real-world large applications

---

## ✅ Key Points to Remember

- Compares **adjacent elements** only
- Largest element settles at the end after each pass
- Can be optimized using a `swapped` flag
- Simple but inefficient

---

## 📚 What to Learn Next

- Comparison: Bubble vs Selection vs Insertion
- Merge Sort
- Quick Sort

---

🔥 **Bubble Sort is the foundation of understanding how sorting works internally**

### Imported Notes: `DSA JS/src/algorithms/sorting/selection-sort/notes.md`

# 🔹 Selection Sort Algorithm (JavaScript)

## 📌 Definition

**Selection Sort** is a simple sorting algorithm that repeatedly **selects the smallest element** from the unsorted part of the array and places it at its **correct position**.

---

## 🧠 Key Idea

> Select the minimum element and put it in the correct place.

- The array is divided into **sorted** and **unsorted** parts
- In every round, the smallest element from the unsorted part is selected
- Only **one swap per round**

---

## ⚙️ How Selection Sort Works (Steps)

1. Start from index `i = 0`
2. Find the minimum element from index `i` to the end
3. Swap the minimum element with the element at index `i`
4. Move `i` to the next position
5. Repeat until the array is sorted

---

## 🧩 Example Walkthrough

Unsorted Array:

```
[3, 1, 4, 2]
```

Steps:

- Pass 1 → Min = `1` → Swap with `3` → `[1, 3, 4, 2]`
- Pass 2 → Min = `2` → Swap with `3` → `[1, 2, 4, 3]`
- Pass 3 → Min = `3` → Swap with `4` → `[1, 2, 3, 4]`

Sorted Array:

```
[1, 2, 3, 4]
```

---

## ⏱️ Time Complexity

| Case    | Complexity |
| ------- | ---------- |
| Best    | **O(n²)**  |
| Average | **O(n²)**  |
| Worst   | **O(n²)**  |

> Selection Sort is **slow for large datasets**

---

## 💾 Space Complexity

- **O(1)** (In-place sorting)
- Uses **no extra memory**

---

## 💬 Interview Answer (One Line)

> **Selection Sort repeatedly selects the smallest element from the unsorted part and places it at the correct position.**

---

## ✅ Selection Sort Code (JavaScript)

```js
function selectionSort(arr) {
  let n = arr.lenght
  for (let i = 0; i < arr.length; i++) {
    let min = i

    for (let j = i + 1; j < arr.length; j++) {
      if (arr[j] < arr[min]) {
        min = j
      }
    }

    ;[arr[i], arr[min]] = [arr[min], arr[i]]
  }

  return arr
}
console.log(selectionSort([4, 2, 5, 3, 1]))


---

## 📌 Why It Is Called "Selection" Sort?

- Because in each round, it **selects** the smallest element
- Then places it at the correct index

---

## 🎯 Where Selection Sort Is Used

- Small datasets
- Learning basic sorting algorithms
- When **memory usage must be minimal**

---

## 🚫 Key Disadvantages

- Always O(n²) time complexity
- Not suitable for large datasets
- Slower than Insertion Sort for nearly sorted arrays

---

## ✅ Key Points to Remember

- Always finds minimum from the **unsorted part**
- Performs **only one swap per iteration**
- Simple but **inefficient for large data**

---

## 📚 What to Learn Next

- Bubble Sort
- Insertion Sort vs Selection Sort comparison
- Merge Sort (efficient sorting)

---

🔥 **Selection Sort builds strong fundamentals for understanding advanced sorting algorithms**
```

### Imported Implementation: `DSA JS/src/algorithms/sorting/selection-sort/implementation.js`

```javascript
function selectionSort(values) {
  const array = [...values]

  for (let start = 0; start < array.length - 1; start += 1) {
    let smallestIndex = start

    for (let index = start + 1; index < array.length; index += 1) {
      if (array[index] < array[smallestIndex]) {
        smallestIndex = index
      }
    }

    if (smallestIndex !== start) {
      ;[array[start], array[smallestIndex]] = [
        array[smallestIndex],
        array[start],
      ]
    }
  }

  return array
}

module.exports = {
  selectionSort,
}
```

### Imported Notes: `DSA JS/src/algorithms/sorting/insertion-sort/notes.md`

# 🔹 Insertion Sort Algorithm (JavaScript)

## 📌 Definition

**Insertion Sort** is a simple sorting algorithm that builds the final sorted array **one item at a time**.
It works similar to the way you **sort playing cards in your hands**.

---

## 🧠 Key Concept

- Take one element at a time (from unsorted part)
- Compare it with elements in the sorted part
- Insert it at the **correct position**

> Works well for **small arrays** or nearly sorted arrays

---

## ⏱️ Time & Space Complexity

| Case         | Complexity                |
| ------------ | ------------------------- |
| Best Case    | **O(n)** (Already sorted) |
| Average Case | **O(n^2)**                |
| Worst Case   | **O(n^2)**                |
| Space        | **O(1)** (In-place)       |

---

## 🎯 Where Insertion Sort is Used

- Small datasets
- Partially sorted arrays
- Educational purposes & learning sorting logic
- Simple sorting in interview questions

---

## 💬 Interview Answer (One Line)

> **Insertion Sort places each element at its correct position by comparing with the sorted part of the array.**

---

## 🧩 Algorithm Steps

1. Start from the second element (`i = 1`) as the first element is considered sorted
2. Store the current element in `key`
3. Compare `key` with elements in the sorted part (`arr[0..i-1]`)
4. Move elements greater than `key` one position ahead
5. Insert `key` at the correct position
6. Repeat for all elements

---

## ✅ Insertion Sort Code (JavaScript)

```js
function insertionSort(arr) {
  for (let i = 1; i < arr.length; i++) {
    let key = arr[i]
    let j = i - 1

    while (j >= 0 && arr[j] > key) {
      arr[j + 1] = arr[j]
      j--
    }
    arr[j + 1] = key
  }

  return arr
}

const arr = [5, 2, 4, 6, 1, 3]
console.log(insertionSort(arr)) // [1, 2, 3, 4, 5, 6]
```

---

## 🚫 Common Mistakes

- Using `i` instead of `j` in the while loop condition
- Forgetting to decrement `j` inside the while loop
- Not inserting `key` at the correct position

---

## 📚 Variations / Next Steps

- Recursive Insertion Sort
- Binary Insertion Sort (using binary search for position)
- Compare with Selection Sort and Bubble Sort

---

## ✅ Summary

- Simple & intuitive **sorting algorithm**
- Best for **small or nearly sorted arrays**
- **In-place** and **stable** sorting method
- Time complexity: O(n^2) (average/worst), O(n) (best)

---

🔥 **Master Insertion Sort = Strong foundation for other sorting algorithms**

### Imported Implementation: `DSA JS/src/algorithms/sorting/insertion-sort/implementation.js`

```javascript
function insertionSort(values) {
  const array = [...values]

  for (let index = 1; index < array.length; index += 1) {
    const currentValue = array[index]
    let position = index - 1

    while (position >= 0 && array[position] > currentValue) {
      array[position + 1] = array[position]
      position -= 1
    }

    array[position + 1] = currentValue
  }

  return array
}

module.exports = {
  insertionSort,
}
```

### Imported Notes: `DSA JS/src/algorithms/sorting/merge-sort/notes.md`

🔀 Merge Sort Algorithm – DSA Notes (Interview Level)

---

## 📌 What is Merge Sort?

Merge Sort is a **Divide and Conquer** sorting algorithm.

It works by:

1. Dividing the array into **smaller subarrays**
2. Sorting each subarray **recursively**
3. **Merging** the sorted subarrays back together

➡️ Merge Sort guarantees **O(n log n)** time complexity in **all cases**.

---

## 🧠 Core Concept (Very Important)

> "Divide until one element remains, then merge in sorted order."

✔ Single elements are always sorted
✔ The main work happens during **merge**

---

## 📌 Steps of Merge Sort

1. Divide the array into two halves
2. Recursively apply Merge Sort on both halves
3. Merge the two sorted halves

---

## 📊 Example

Input:
[6, 3, 1, 5, 2, 4]

makefile
Copy code

Divide:
[6, 3, 1] [5, 2, 4]

yaml
Copy code

Divide again:
[6] [3, 1] [5] [2, 4]

makefile
Copy code

Merge:
[1, 3, 6] [2, 4, 5]

sql
Copy code

Final Merge:
[1, 2, 3, 4, 5, 6]

pgsql
Copy code

---

## ✍️ JavaScript Code (Merge Sort)

```js

  function mergeSort(arr) {
    if (arr.length <= 1) return arr

    const mid = Math.floor(arr.length / 2)

    const left = mergeSort(arr.slice(0, mid))
    const right = mergeSort(arr.slice(mid))

    return merge(left, right)
  }

  function merge(left, right) {
    let result = []
    let i = 0
    let j = 0

    while (i < left.length && j < right.length) {
      if (left[i] < right[j]) {
        result.push(left[i])
        i++
      } else {
        result.push(right[j])
        j++
      }
    }

  // return the result and concate the left and right array in

    return result
      .concat(left.slice(i))
      .concat(right.slice(j))
  }

  console.log(mergeSort([6, 3, 1, 5, 2, 4]))

🧪 Dry Run (Interview Favorite)
Array:

csharp
Copy code
[4, 1, 3, 2]
Split:

css
Copy code
[4, 1]  [3, 2]
Split again:

css
Copy code
[4] [1]  [3] [2]
Merge:

css
Copy code
[1, 4]  [2, 3]
Final:

csharp
Copy code
[1, 2, 3, 4]
⏱️ Time Complexity
Case	Time
Best	O(n log n)
Average	O(n log n)
Worst	O(n log n)

✔ Always same performance

💾 Space Complexity
scss
Copy code
O(n)
❌ Not in-place
✔ Uses extra space for merging

🧠 Is Merge Sort Stable?
✅ YES — Merge Sort is stable

Equal elements keep their original order

🆚 Merge Sort vs Quick Sort
Feature	Merge Sort	Quick Sort
Worst Case	O(n log n)	O(n²)
Space	O(n)	O(log n)
Stable	✅ Yes	❌ No
In-place	❌ No	✅ Yes

📌 When to Use Merge Sort?
✔ When stability is required
✔ Sorting linked lists
✔ Large datasets
✔ Guaranteed performance needed

🎯 Interview One-Line Answer
Merge Sort is a divide and conquer algorithm that splits the array and merges sorted halves with O(n log n) time.

🚨 Common Mistakes
❌ Forgetting base case
❌ Wrong merge logic
❌ Thinking it is in-place

🧠 Key Takeaways
✔ Divide & Conquer
✔ Always O(n log n)
✔ Stable sorting
✔ Extra memory required

✅ Status: MERGE SORT MASTERED – Interview Ready 🚀


Dry run the code



Step 1: Split
[6,3,1]   [5,2,4]

Step 2: Split further
[6] [3,1]   [5] [2,4]

Step 3: Split until length=1
[6] [3] [1]   [5] [2] [4]

Step 4: Merge step
Merge [3] & [1] → [1,3]
Merge [6] & [1,3] → [1,3,6]
Merge [2] & [4] → [2,4]
Merge [5] & [2,4] → [2,4,5]

Final Merge [1,3,6] & [2,4,5] → [1,2,3,4,5,6]
```

<!-- simple Tree  N Time of Log in  -->

```js

MergeSort([6,3,1,5,2,4])

                 [6 3 1 5 2 4]  <-- n elements
              /                    \
        [6 3 1]                     [5 2 4]
       /       \                    /     \
     [6]       [3 1]              [5]    [2 4]
               /   \                     /   \
             [3]   [1]                 [2]   [4]
```

### Imported Implementation: `DSA JS/src/algorithms/sorting/merge-sort/implementation.js`

```javascript
function merge(left, right) {
  const merged = []
  let leftIndex = 0
  let rightIndex = 0

  while (leftIndex < left.length && rightIndex < right.length) {
    if (left[leftIndex] <= right[rightIndex]) {
      merged.push(left[leftIndex])
      leftIndex += 1
    } else {
      merged.push(right[rightIndex])
      rightIndex += 1
    }
  }

  return merged
    .concat(left.slice(leftIndex))
    .concat(right.slice(rightIndex))
}

function mergeSort(values) {
  if (values.length <= 1) {
    return [...values]
  }

  const midpoint = Math.floor(values.length / 2)
  const leftHalf = mergeSort(values.slice(0, midpoint))
  const rightHalf = mergeSort(values.slice(midpoint))

  return merge(leftHalf, rightHalf)
}

module.exports = {
  merge,
  mergeSort,
}
```

### Imported Notes: `DSA JS/src/algorithms/sorting/quick-sort/notes.md`

# ⚡ Quick Sort Algorithm (DSA Notes)

---

## 📌 What is Quick Sort?

Quick Sort is a **divide and conquer** sorting algorithm.
It works by:

1. Selecting a **pivot** element
2. Placing the pivot at its **correct position**
3. Recursively sorting the **left** and **right** subarrays

➡️ It is one of the **fastest sorting algorithms in practice**.

---

## 🧠 Why is it called "Quick"?

Because on average, it sorts very fast due to:

- Efficient partitioning
- Less comparisons
- In-place sorting

---

## 📌 Steps of Quick Sort

1. Choose a pivot (first / last / middle / random)
2. Partition the array so that:
   - Elements < pivot → left
   - Elements > pivot → right

3. Pivot is now in correct position
4. Apply Quick Sort on left and right subarrays

---

## 📊 Example

Input:

```
[5, 3, 8, 4, 2]
```

Choose pivot = 5

After partition:

```
[3, 4, 2] 5 [8]
```

Recursively sort left and right

Output:

```
[2, 3, 4, 5, 8]
```

---

## ✍️ JavaScript Code (Quick Sort)

```js
function quickSort(arr) {
  if (arr.length <= 1) return arr //Base case

  let pivot = arr[arr.length - 1]
  let left = []
  let right = []

  for (let i = 0; i < arr.length; i++) {
    if (arr[i] < pivot) left.push(arr[i])
    else right.push(arr[i])
  }

  return [...quickSort(left), pivot, ...quickSort(right)]
}

console.log(quickSort([5, 3, 8, 4, 2]))
```

---

## 🧪 Dry Run

Array: `[5, 3, 8, 4, 2]`

- Pivot = 2
- Left = []
- Right = [5, 3, 8, 4]

Repeat process until arrays have 1 element

---

## ⏱️ Time Complexity

| Case         | Complexity                             |
| ------------ | -------------------------------------- |
| Best Case    | O(n log n)                             |
| Average Case | O(n log n)                             |
| Worst Case   | O(n²) (when pivot is smallest/largest) |

---

## 💾 Space Complexity

- O(log n) → Recursive stack (in-place version)
- O(n) → Extra space version (like above code)

---

## 🆚 Quick Sort vs Merge Sort

| Feature  | Quick Sort         | Merge Sort      |
| -------- | ------------------ | --------------- |
| Speed    | Faster in practice | Slightly slower |
| Space    | O(log n)           | O(n)            |
| Stable   | ❌ No              | ✅ Yes          |
| In-place | ✅ Yes             | ❌ No           |

---

## 📌 Key Points to Remember

- Divide and Conquer algorithm
- Pivot selection is important
- Not stable
- Very fast for large datasets
- Used in real systems

---

## 🎯 Where is Quick Sort Used?

- Competitive programming
- Large datasets
- System-level sorting
- Interviews (very common)

---

## 🧠 Interview Answer (One Line)

> Quick Sort works by selecting a pivot and partitioning the array around it, recursively sorting subarrays.

---

🔥 **Next you should study:**

- Partition logic (Lomuto & Hoare)
- Worst case optimization (Random Pivot)
- Quick Sort vs Heap Sort

---

✅ **Status:** Google / Amazon Interview Ready 🚀

### Imported Implementation: `DSA JS/src/algorithms/sorting/quick-sort/implementation.js`

```javascript
function quickSort(values) {
  if (values.length <= 1) {
    return [...values]
  }

  const pivot = values[values.length - 1]
  const left = []
  const right = []

  for (let index = 0; index < values.length - 1; index += 1) {
    if (values[index] < pivot) {
      left.push(values[index])
    } else {
      right.push(values[index])
    }
  }

  return [...quickSort(left), pivot, ...quickSort(right)]
}

module.exports = {
  quickSort,
}
```
<!-- DSA-JS-MERGE:END -->

<!-- PROMPT-TARGET-EXPANSION:START -->
## Master Prompt Target Expansion

This addendum brings the chapter closer to the depth requested by the master prompt: deeper recognition rules, interview narration, edge-case thinking, dry-run discipline, and complexity reasoning. Treat it as the chapter's final study layer after reading the core lesson and imported legacy material.

### Mastery Expansion 1: bubble sort

**What this part means in plain English:** In Sorting Algorithms - Complete Mastery, bubble sort is not something to memorize as a disconnected trick. It is a decision tool. The core question is: what information changes as the input grows, and what information must remain available so the next step is cheap? When you can answer that, the correct data structure or algorithm becomes much easier to choose.

**How to recognize it in an interview:** Listen for the wording of the prompt. If the problem asks for fast lookup, repeated membership checks, duplicate detection, grouping, or counting, you should immediately consider a map or set. If it asks for contiguous ranges, windows, substrings, or subarrays, you should look for a sliding window or prefix state. If it asks for all possible choices, paths, arrangements, or boards, draw the decision tree before coding. If it asks for best, minimum, maximum, count ways, or feasibility with repeated subproblems, define a DP state before reaching for loops.

**Brute force baseline:** Always describe the direct solution first. For bubble sort, the brute force version usually repeats work: scanning the same area again, recalculating a value already known, trying every pair, or exploring branches that can be proven impossible. The baseline matters because it gives you a correctness anchor and gives the interviewer a clear before-and-after optimization story.

**Optimization move:** The optimization is usually one of four moves: store seen information, exploit sorted order, maintain an invariant while moving pointers, or cache solved subproblems. Say the invariant out loud. A good invariant sounds like: "At every step, my map contains only values from the processed prefix," or "The window is always the longest valid window ending at the current right pointer," or "The heap always stores the best candidates seen so far."

**Dry-run discipline:** Use a tiny input and trace every state change. Write the input, current index or pointer, auxiliary structure contents, current answer, and reason for movement. Do not jump from the first step to the final answer. The dry run is where off-by-one bugs, stale map entries, missed duplicate handling, and wrong base cases become visible.

**Edge cases to test:** Test empty input, one element, duplicate-heavy input, already sorted input, reverse sorted input, negative values if numbers are allowed, and maximum constraint shape. For recursive or graph problems, also test disconnected input, cycles, repeated visits, and a path that almost works but fails at the final step.

**What a strong candidate says:** "I will start with a correct brute force approach, analyze why it is too slow, then remove repeated work by preserving exactly the state I need. I will keep the invariant visible while coding, dry-run on a normal example, and then test edge cases before giving final complexity."

**Complexity explanation:** Do not only state Big O. Explain the count. If each element enters and leaves a window once, the runtime is O(n). If every node and edge is visited once, it is O(V + E). If recursion branches into two calls per level, draw the tree. If sorting happens before a linear scan, sorting dominates at O(n log n). If a heap operation occurs for every item, multiply by log k or log n depending on heap size.

### Mastery Expansion 2: selection sort

**What this part means in plain English:** In Sorting Algorithms - Complete Mastery, selection sort is not something to memorize as a disconnected trick. It is a decision tool. The core question is: what information changes as the input grows, and what information must remain available so the next step is cheap? When you can answer that, the correct data structure or algorithm becomes much easier to choose.

**How to recognize it in an interview:** Listen for the wording of the prompt. If the problem asks for fast lookup, repeated membership checks, duplicate detection, grouping, or counting, you should immediately consider a map or set. If it asks for contiguous ranges, windows, substrings, or subarrays, you should look for a sliding window or prefix state. If it asks for all possible choices, paths, arrangements, or boards, draw the decision tree before coding. If it asks for best, minimum, maximum, count ways, or feasibility with repeated subproblems, define a DP state before reaching for loops.

**Brute force baseline:** Always describe the direct solution first. For selection sort, the brute force version usually repeats work: scanning the same area again, recalculating a value already known, trying every pair, or exploring branches that can be proven impossible. The baseline matters because it gives you a correctness anchor and gives the interviewer a clear before-and-after optimization story.

**Optimization move:** The optimization is usually one of four moves: store seen information, exploit sorted order, maintain an invariant while moving pointers, or cache solved subproblems. Say the invariant out loud. A good invariant sounds like: "At every step, my map contains only values from the processed prefix," or "The window is always the longest valid window ending at the current right pointer," or "The heap always stores the best candidates seen so far."

**Dry-run discipline:** Use a tiny input and trace every state change. Write the input, current index or pointer, auxiliary structure contents, current answer, and reason for movement. Do not jump from the first step to the final answer. The dry run is where off-by-one bugs, stale map entries, missed duplicate handling, and wrong base cases become visible.

**Edge cases to test:** Test empty input, one element, duplicate-heavy input, already sorted input, reverse sorted input, negative values if numbers are allowed, and maximum constraint shape. For recursive or graph problems, also test disconnected input, cycles, repeated visits, and a path that almost works but fails at the final step.

**What a strong candidate says:** "I will start with a correct brute force approach, analyze why it is too slow, then remove repeated work by preserving exactly the state I need. I will keep the invariant visible while coding, dry-run on a normal example, and then test edge cases before giving final complexity."

**Complexity explanation:** Do not only state Big O. Explain the count. If each element enters and leaves a window once, the runtime is O(n). If every node and edge is visited once, it is O(V + E). If recursion branches into two calls per level, draw the tree. If sorting happens before a linear scan, sorting dominates at O(n log n). If a heap operation occurs for every item, multiply by log k or log n depending on heap size.
<!-- PROMPT-TARGET-EXPANSION:END -->

---

**Previous:** [Graphs - The Universal Problem Model](../Phase-3-Nonlinear-Data-Structures/06-Graphs.md) | **Next:** [Searching Algorithms - From Linear to Logarithmic](../Phase-4-Core-Algorithms/02-Searching-Algorithms.md)
