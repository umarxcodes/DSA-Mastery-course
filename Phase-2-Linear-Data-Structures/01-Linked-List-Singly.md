# Singly Linked List - Complete Mastery

## Chapter Metadata

| Field          | Value                                                                          |
| -------------- | ------------------------------------------------------------------------------ |
| Phase          | Phase 2 - Linear Data Structures                                               |
| Chapter        | 6 of 37                                                                        |
| Difficulty     | Intermediate                                                                   |
| Time to Master | 8-10 hours                                                                     |
| Prerequisites  | JavaScript fundamentals, functions, arrays, objects, and basic problem solving |

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

- Node structure, head pointer, tail null, and pointer-based storage
- SinglyLinkedList class: push, pop, shift, unshift, get, set, insert, remove, reverse
- Reversal dry run with prev/current/next pointers
- Slow-fast pointers, cycle detection, merge patterns, nth-from-end pattern
- Reverse list, detect cycle, merge sorted lists, palindrome list, intersection

## Deep Teaching Notes

### 1. Node structure, head pointer, tail null, and pointer-based storage

**Beginner explanation:** This is one of the core ideas for Singly Linked List - Complete Mastery. Start by saying it in plain language before reaching for code. A beginner should understand what problem this idea solves, what input it expects, and what output it creates.

**Why it matters:** In a FAANG interview, this point shows whether you understand the shape of the problem. Interviewers care less about memorized syntax and more about whether your choices match the constraints.

**How to reason about it:** Ask what must be remembered while the algorithm runs. If you need fast lookup, think HashMap or Set. If you need ordered movement, think pointers. If you need all possibilities, think recursion or backtracking. If you need best/count/possible over repeated subproblems, think dynamic programming.

**What to say out loud:** "I am choosing this approach because it matches the constraint: the expensive operation is repeated work, so I want a structure or pattern that removes that repetition."

**Implementation angle in JavaScript:** Prefer clear names, explicit loops when teaching, and built-ins only when you can explain their complexity. JavaScript gives you Array, Map, Set, and flexible objects, but every helper method still has a cost.

**Edge checks:** Confirm behavior for empty input, one item, duplicate values, already-ordered input, reverse-ordered input, and values at the smallest or largest allowed constraints.

### 2. SinglyLinkedList class: push, pop, shift, unshift, get, set, insert, remove, reverse

**Beginner explanation:** This is one of the core ideas for Singly Linked List - Complete Mastery. Start by saying it in plain language before reaching for code. A beginner should understand what problem this idea solves, what input it expects, and what output it creates.

**Why it matters:** In a FAANG interview, this point shows whether you understand the shape of the problem. Interviewers care less about memorized syntax and more about whether your choices match the constraints.

**How to reason about it:** Ask what must be remembered while the algorithm runs. If you need fast lookup, think HashMap or Set. If you need ordered movement, think pointers. If you need all possibilities, think recursion or backtracking. If you need best/count/possible over repeated subproblems, think dynamic programming.

**What to say out loud:** "I am choosing this approach because it matches the constraint: the expensive operation is repeated work, so I want a structure or pattern that removes that repetition."

**Implementation angle in JavaScript:** Prefer clear names, explicit loops when teaching, and built-ins only when you can explain their complexity. JavaScript gives you Array, Map, Set, and flexible objects, but every helper method still has a cost.

**Edge checks:** Confirm behavior for empty input, one item, duplicate values, already-ordered input, reverse-ordered input, and values at the smallest or largest allowed constraints.

### 3. Reversal dry run with prev/current/next pointers

**Beginner explanation:** This is one of the core ideas for Singly Linked List - Complete Mastery. Start by saying it in plain language before reaching for code. A beginner should understand what problem this idea solves, what input it expects, and what output it creates.

**Why it matters:** In a FAANG interview, this point shows whether you understand the shape of the problem. Interviewers care less about memorized syntax and more about whether your choices match the constraints.

**How to reason about it:** Ask what must be remembered while the algorithm runs. If you need fast lookup, think HashMap or Set. If you need ordered movement, think pointers. If you need all possibilities, think recursion or backtracking. If you need best/count/possible over repeated subproblems, think dynamic programming.

**What to say out loud:** "I am choosing this approach because it matches the constraint: the expensive operation is repeated work, so I want a structure or pattern that removes that repetition."

**Implementation angle in JavaScript:** Prefer clear names, explicit loops when teaching, and built-ins only when you can explain their complexity. JavaScript gives you Array, Map, Set, and flexible objects, but every helper method still has a cost.

**Edge checks:** Confirm behavior for empty input, one item, duplicate values, already-ordered input, reverse-ordered input, and values at the smallest or largest allowed constraints.

### 4. Slow-fast pointers, cycle detection, merge patterns, nth-from-end pattern

**Beginner explanation:** This is one of the core ideas for Singly Linked List - Complete Mastery. Start by saying it in plain language before reaching for code. A beginner should understand what problem this idea solves, what input it expects, and what output it creates.

**Why it matters:** In a FAANG interview, this point shows whether you understand the shape of the problem. Interviewers care less about memorized syntax and more about whether your choices match the constraints.

**How to reason about it:** Ask what must be remembered while the algorithm runs. If you need fast lookup, think HashMap or Set. If you need ordered movement, think pointers. If you need all possibilities, think recursion or backtracking. If you need best/count/possible over repeated subproblems, think dynamic programming.

**What to say out loud:** "I am choosing this approach because it matches the constraint: the expensive operation is repeated work, so I want a structure or pattern that removes that repetition."

**Implementation angle in JavaScript:** Prefer clear names, explicit loops when teaching, and built-ins only when you can explain their complexity. JavaScript gives you Array, Map, Set, and flexible objects, but every helper method still has a cost.

**Edge checks:** Confirm behavior for empty input, one item, duplicate values, already-ordered input, reverse-ordered input, and values at the smallest or largest allowed constraints.

### 5. Reverse list, detect cycle, merge sorted lists, palindrome list, intersection

**Beginner explanation:** This is one of the core ideas for Singly Linked List - Complete Mastery. Start by saying it in plain language before reaching for code. A beginner should understand what problem this idea solves, what input it expects, and what output it creates.

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
  const result = []

  for (const item of input) {
    result.push(item)
  }

  return result
}

console.log(solveWithPattern([1, 2, 3]))
```

## Step-by-Step Dry Run

Use this dry-run discipline for every implementation in this chapter.

| Step               | Variable State                                                        | Why It Matters                                       |
| ------------------ | --------------------------------------------------------------------- | ---------------------------------------------------- |
| Input              | Receive sample input                                                  | Confirm expected output and constraints              |
| Initialize         | Create pointers, maps, arrays, heap, stack, queue, or recursion state | A wrong initial state usually causes off-by-one bugs |
| First iteration    | Process the first meaningful item                                     | Check whether the invariant becomes true             |
| Middle iteration   | Update state without losing previous useful information               | Most logic bugs happen here                          |
| Boundary iteration | Process final item or final recursive return                          | Confirms loop termination                            |
| Return             | Return answer in exact requested format                               | Correct value with wrong shape still fails           |

### Dry Run Example Mindset

Pick a small input where the answer is not obvious. Walk one line at a time. After each line, write down pointer positions, map contents, stack contents, queue contents, or recursive call state. If you cannot explain the state, the code is too magical for an interview.

> 🔴 **Common Mistake:** Candidates often dry-run only the happy path. Always include empty input, one item, duplicate values, and boundary values.

## Time & Space Complexity Analysis

| Operation                |             Time |        Space | Why                                       |
| ------------------------ | ---------------: | -----------: | ----------------------------------------- |
| Brute force scan         |           O(n^2) |         O(1) | Checks many pairs or repeated work        |
| Optimized lookup/pattern | O(n) or O(log n) | O(n) or O(1) | Uses structure, ordering, or cached state |
| Sorting-based approach   |       O(n log n) | O(1) to O(n) | Sorting dominates the runtime             |
| Recursive approach       |  Depends on tree |     O(depth) | Call stack counts as space                |

Always explain the dominant term. If one loop runs after another, add their costs. If one loop is inside another, multiply. If recursion branches, draw the recursion tree.

## All Operations / Variations

| Variation             | When To Use                                            | Interview Signal                      |
| --------------------- | ------------------------------------------------------ | ------------------------------------- |
| Brute force           | First explanation, tiny input, baseline correctness    | You can decompose the problem         |
| HashMap / Set         | Need fast membership, counts, grouping, or complements | You know memory-time trade-offs       |
| Two pointers          | Sorted arrays, palindromes, pair constraints           | You can use order to reduce work      |
| Sliding window        | Contiguous subarray or substring with a condition      | You can maintain state incrementally  |
| Recursion / DFS       | Trees, graphs, combinations, divide and conquer        | You can express subproblems cleanly   |
| Heap / Priority Queue | Top-K, streaming min/max, merging sorted sources       | You can retrieve priority efficiently |
| Dynamic Programming   | Counting, optimization, overlapping subproblems        | You can define state and recurrence   |

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
  if (input == null) return null
  return input
}
```

### Problem 2: Solve the canonical interview problem

Focus on the invariant. The invariant is the rule that remains true after every loop or recursive call.

```javascript
/**
 * Use this to practice writing an invariant before implementation.
 */
function solveProblemTwo(input) {
  const state = Array.isArray(input) ? [...input] : input
  return state
}
```

### Problem 3: Explain the complexity out loud

Dry-run the smallest non-trivial input. If that works, test the edge cases.

```javascript
/**
 * Always test the smallest non-trivial case.
 */
function solveProblemThree(input) {
  return input
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

|   # | Problem                                                  | Difficulty |
| --: | -------------------------------------------------------- | ---------- |
|   1 | Explain the concept to a beginner in two sentences       | Easy       |
|   2 | Write the brute force approach for the canonical problem | Easy       |
|   3 | Optimize it using the main pattern                       | Medium     |
|   4 | Dry-run the optimized code on three inputs               | Medium     |
|   5 | Explain time and space complexity out loud               | Medium     |

## Chapter Summary Table

| Topic               | Must Remember                      |
| ------------------- | ---------------------------------- |
| Definition          | Know the simplest explanation      |
| Analogy             | Use it to reason about trade-offs  |
| Implementation      | Write clean JavaScript with tests  |
| Complexity          | Explain why, not just what         |
| Edge cases          | Test before declaring done         |
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

- `DSA JS/src/data-structures/linked-list/singly-linked-list/notes.md`
- `DSA JS/src/data-structures/linked-list/singly-linked-list/implementation.js`
- `DSA JS/src/data-structures/linked-list/singly-linked-list/practice.md`

### Imported Notes: `DSA JS/src/data-structures/linked-list/singly-linked-list/notes.md`

# 🔗 Singly Linked List (DSA) — Complete Notes (.md)

> **Prepared for Beginner → Professional → Interview Level**

---

## 📘 What is a Singly Linked List?

A **Singly Linked List** is a **linear data structure** where each element (called a **node**) contains:

1. **Data** – the value
2. **Next** – reference (address) of the next node

```
[data | next] → [data | next] → [data | null]
```

The list is accessed using a pointer called **HEAD**.

---

## 🧠 Why Linked List?

| Problem with Array        | Linked List Solution         |
| ------------------------- | ---------------------------- |
| Fixed size                | Dynamic size                 |
| Costly insertion/deletion | Efficient insertion/deletion |
| Memory contiguous         | Memory non-contiguous        |

---

## 🧩 Basic Structure

### Node Structure

```js
class Node {
  constructor(data) {
    this.data = data
    this.next = null
  }
}
```

### Linked List Structure

```js
class LinkedList {
  constructor() {
    this.head = null
  }
}
```

---

## 📌 Types of Linked List

1. Singly Linked List ✅ (this topic)
2. Doubly Linked List
3. Circular Linked List
4. Circular Doubly Linked List

---

## 1️⃣ Insert Operations

### 🔹 Insert at Head (Beginning)

**Steps:**

1. Create new node
2. Point newNode.next → head
3. Move head → newNode

```js
insertAtHead(data)
```

**Time Complexity:** `O(1)`

---

### 🔹 Insert at Tail (End)

**Steps:**

1. Traverse till last node
2. last.next → newNode

```js
insertAtTail(data)
```

**Time Complexity:** `O(n)`

---

### 🔹 Insert at Position

**Steps:**

1. Traverse till (position - 1)
2. Update links carefully

```js
insertAtPosition(data, pos)
```

⚠️ Order of pointer updates is very important

---

## 2️⃣ Delete Operations

### 🔸 Delete Head

```js
deleteHead()
```

**Logic:**

```
head = head.next
```

**Time:** `O(1)`

---

### 🔸 Delete Tail

**Steps:**

1. Traverse till second last node
2. temp.next = null

**Time:** `O(n)`

---

### 🔸 Delete by Value

**Steps:**

1. Find previous node
2. Skip target node

```js
temp.next = temp.next.next
```

---

## 3️⃣ Traversal / Printing

```js
print()
```

```
10 → 20 → 30 → null
```

**Time:** `O(n)`

---

## 4️⃣ Reverse Linked List ⭐ (VERY IMPORTANT)

### Approach: Iterative (Best)

**Pointers Used:**

- prev
- curr
- next

**Core Idea:**
Reverse direction of `next` pointers

**Time:** `O(n)`
**Space:** `O(1)`

📌 Most asked interview question

---

## 5️⃣ Find Middle Node (Slow & Fast Pointer)

**Logic:**

- Slow moves 1 step
- Fast moves 2 steps

When fast reaches end → slow is at middle

**Time:** `O(n)`

---

## 6️⃣ Detect Cycle (Loop Detection)

### Floyd’s Cycle Detection Algorithm

**Pointers:**

- Slow
- Fast

If slow == fast → cycle exists

**Time:** `O(n)`
**Space:** `O(1)`

---

## 7️⃣ Length of Linked List

Traverse and count nodes

```js
length()
```

---

## 8️⃣ Search in Linked List

Linear search

```js
search(value)
```

**Time:** `O(n)`

---

## 📊 Time Complexity Summary

| Operation   | Time |
| ----------- | ---- |
| Insert Head | O(1) |
| Insert Tail | O(n) |
| Delete Head | O(1) |
| Delete Tail | O(n) |
| Search      | O(n) |
| Reverse     | O(n) |

---

## ❌ Common Mistakes (Interview Killers)

- Forgetting base case when list is empty
- Losing reference during pointer update
- Not handling single-node list
- Wrong loop condition (`temp.next.next`)

---

## 🎯 Interview-Level Questions

1. Reverse linked list
2. Find middle node
3. Detect loop
4. Remove Nth node from end
5. Merge two sorted linked lists
6. Check palindrome linked list

---

## 🧠 When to Use Linked List?

✔ Frequent insertions/deletions
✔ Unknown size data
❌ Random access needed

---

## 🆚 Linked List vs Array

| Feature       | Array      | Linked List    |
| ------------- | ---------- | -------------- |
| Access        | O(1)       | O(n)           |
| Insert/Delete | O(n)       | O(1)           |
| Memory        | Contiguous | Non-contiguous |

---

## 🏁 Final Summary

- Linked List uses **nodes + pointers**
- No indexing
- Pointer handling is key
- Very important for **DSA & Interviews**

---

🔥 **Next Recommended Topics**

- Doubly Linked List
- Circular Linked List
- Linked List Interview Problems (LeetCode)
- Recursion on Linked List

---

✍️ _Prepared for DSA, FAANG & Google-level interviews_

// ===============================
// Node Class (Har dabba / node)
// ================================
class Node {
constructor(data) {
this.data = data; // value
this.next = null; // next node ka address
}
}

// ==================================
// LinkedList Class (Poori chain)
// ==================================
class LinkedList {
constructor() {
this.head = null; // pehla node
}

// ----------------------------
// Insert at Head (Start)
// ----------------------------
insertAtHead(data) {
let newNode = new Node(data);
newNode.next = this.head;
this.head = newNode;
}

// ----------------------------
// Insert at Tail (End)
// ----------------------------
insertAtTail(data) {
let newNode = new Node(data);

    if (this.head === null) {
      this.head = newNode;
      return;
    }

    let temp = this.head;
    while (temp.next !== null) {
      temp = temp.next;
    }
    temp.next = newNode;

}

// ----------------------------
// Insert at Position (Index)
// ----------------------------

insertAtPosition(data, pos) {
if (pos === 0) {
this.insertAtHead(data);
return;
}

    let newNode = new Node(data);
    let temp = this.head;

    for (let i = 0; i < pos - 1 && temp !== null; i++) {
      temp = temp.next;
    }

    if (temp === null) {
      console.log("Position invalid");
      return;
    }

    newNode.next = temp.next;
    temp.next = newNode;

}

// ----------------------------
// Delete Head
// ----------------------------
deleteHead() {
if (this.head === null) return;
this.head = this.head.next;
}

// ----------------------------
// Delete Tail
// ----------------------------
deleteTail() {
if (this.head === null || this.head.next === null) {
this.head = null;
return;
}

    let temp = this.head;
    while (temp.next.next !== null) {
      temp = temp.next;
    }
    temp.next = null;

}

// ----------------------------
// Delete by Value
// ----------------------------
deleteByValue(value) {
if (this.head === null) return;

    if (this.head.data === value) {
      this.head = this.head.next;
      return;
    }

    let temp = this.head;
    while (temp.next !== null && temp.next.data !== value) {
      temp = temp.next;
    }

    if (temp.next !== null) {
      temp.next = temp.next.next;
    }

}

// ----------------------------
// Print Linked List
// ----------------------------
print() {
let temp = this.head;
let result = "";

    while (temp !== null) {
      result += temp.data + " → ";
      temp = temp.next;
    }
    console.log(result + "null");

}

// ----------------------------
// Reverse Linked List
// ----------------------------
reverse() {
let prev = null;
let curr = this.head;

    while (curr !== null) {
      let next = curr.next;
      curr.next = prev;
      prev = curr;
      curr = next;
    }

    this.head = prev;
                                                                                                                                                                                                                                                                                                                                                                     }

// ----------------------------
// Find Middle Node
// ----------------------------
findMiddle() {
let slow = this.head;
let fast = this.head;

    while (fast !== null && fast.next !== null) {
      slow = slow.next;
      fast = fast.next.next;
    }
    return slow ? slow.data : null;

}

// ----------------------------
// Detect Cycle (Loop)
// ----------------------------

Using ==> Floyd's Tortoise and Hare Algorithm

hasCycle() {
let slow = this.head;
let fast = this.head;

    while (fast && fast.next) {
      slow = slow.next;
      fast = fast.next.next;

      if (slow === fast) return true;
    }
    return false;

}
}

### Imported Implementation: `DSA JS/src/data-structures/linked-list/singly-linked-list/implementation.js`

```javascript
class linkList {
  constructor() {
    this.head = null
  }
}

class Node {
  constructor(data) {
    this.data = data
    this.next = null
  }

  insertAtHead(data) {
    let newNode = new Node(data)
    newNode.next = this.head
    this.head = newNode
  }
}
```

### Imported Notes: `DSA JS/src/data-structures/linked-list/singly-linked-list/practice.md`

Reverse Linked List

Middle of the Linked List

Linked List Cycle

Remove Linked List Elements

Merge Two Sorted Lists

🟡 Medium (Google standard)

Linked List Cycle II

Intersection of Two Linked Lists

Remove Nth Node From End of List

Palindrome Linked List

Add Two Numbers

🔴 Advanced (Google favorites)

Reverse Nodes in k-Group 🔥

Copy List with Random Pointer 🔥

Sort List

Reorder List

Flatten a Multilevel Doubly Linked List

<!-- DSA-JS-MERGE:END -->

---

**Previous:** [Recursion - The Foundation of All Advanced Algorithms](../Phase-1-Foundations/05-Recursion-Complete-Mastery.md) | **Next:** [Doubly Linked List and Circular Linked List](../Phase-2-Linear-Data-Structures/02-Linked-List-Doubly-Circular.md)
